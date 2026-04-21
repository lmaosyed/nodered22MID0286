# nodered 22MID0286

# MQTT Publish-Subscribe System (Node-RED)

## Overview
This project implements a Smart Home Monitoring system using MQTT and Node-RED.

## Architecture
- 3 Publishers:
  - Temperature
  - Humidity
  - Status
- 1 Wildcard Subscriber: `home/livingroom/#`
- MQTT Broker: Mosquitto

## Topics
- home/livingroom/temperature
- home/livingroom/humidity
- home/livingroom/status

## Features
- Publish-Subscribe model
- Wildcard subscription
- Real-time dashboard
- QoS implementation
- Retained messages


## QoS Used
- QoS 1 → Temperature & Humidity
- QoS 2 → Status

