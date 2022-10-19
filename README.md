# Signal K PostgSail plugin
PostgSail effortlessly logs your voyages, automatically capturing your trips, moorages, dockings and anchorages with no additional need to stop/start anything. Built for sailors, motorboats and commercial uses.

## Description
Signal K server plugin to send all self SignalK numeric data and nagigation entry to an PostgSail server.

## Features
- Automatically log your voyages without manually starting or stopping a trip.
- Automatically capture the details of your voyages (boat speed, heading, wind speed, etc).
- Timelapse video your trips!
- Add custom notes to your logs.
- Export to CSV or GPX and download your logs.
- Aggregate your trip statistics: Longest voyage, time spent at anchorages, home ports etc.
- See your moorages on a global map, with incoming and outgoing voyages from each trip.
- Monitor your boat (position, depth, wind, temperature, battery charge status, etc.) remotely.
- Notification via email or PushOver.

## Dependencies
[signalk-autostate](https://www.npmjs.com/package/@meri-imperiumi/signalk-autostate) by @meri-imperiumi. Used to determine the vessel's state based on sensor values, and updates the `navigation.state` value accordingly.

## Cloud
Optional a free account on [iot.openplotter.cloud](https://iot.openplotter.cloud/).
