# MQTT Leaflet App

Welcome to the MQTT Leaflet App repository! This repository contains an HTML file (`index.html`) and a JavaScript file (`app.js`) for a web application that integrates MQTT (Message Queuing Telemetry Transport) messaging with Leaflet maps.

## Overview

The MQTT Leaflet App allows users to connect to an MQTT broker, send and receive messages, and visualize real-time data on a Leaflet map. It provides a user-friendly interface for interacting with MQTT topics and displaying geospatial data.

## Features

- **Connect to MQTT Broker**: Users can specify the MQTT server and port to connect to.
- **Send Messages**: Users can send messages to MQTT topics.
- **Receive Messages**: Messages received from subscribed topics are displayed in real-time.
- **Visualize Data on Map**: GeoJSON data received from MQTT topics is visualized on a Leaflet map.

## Usage

1. **Connect to MQTT Broker**:
   - Enter the MQTT server and port in the provided form fields.
   - Click the "Connect" button to establish a connection.

2. **Send Messages**:
   - Enter a message and topic in the provided form fields.
   - Click the "Submit" button to send the message to the specified topic.

3. **Receive Messages**:
   - Messages received from subscribed topics are displayed below the form fields.

4. **Share Location**:
   - Click the "Share my Status" button to share your current location.
   - Your latitude and longitude coordinates will be displayed on the page.

5. **Visualize Data on Map**:
   - GeoJSON data containing temperature information is visualized on the Leaflet map.
   - Temperature data is updated in real-time as messages are received.

## Setup

To run the MQTT Leaflet App locally, follow these steps:

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.

## Dependencies

- [Bootstrap](https://getbootstrap.com/): Front-end framework for styling.
- [Leaflet](https://leafletjs.com/): JavaScript library for interactive maps.
- [Leaflet MarkerCluster](https://github.com/Leaflet/Leaflet.markercluster): Plugin for clustering markers on Leaflet maps.
- [Paho MQTT](https://www.eclipse.org/paho/clients/js/): JavaScript library for MQTT messaging.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the developers of Bootstrap, Leaflet, and Paho MQTT for their excellent libraries and tools.

