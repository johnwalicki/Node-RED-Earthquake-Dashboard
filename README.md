# Node-RED-Earthquake-Dashboard
Plot Earthquake seismic activity on a Node-RED Map Dashboard and Table

Plot a list of earthquakes from the [USGS earthquake public API](http://earthquake.usgs.gov/earthquakes) on a [Node-RED](https://nodered.org) Dashboard

This example flow and Node-RED Dashboard might be useful as part of a [Call for Code](https://developer.ibm.com/callforcode/) Natural Disaster solution.

### Prerequistes

- [Install Node-RED](https://nodered.org/docs/getting-started/) on your system or in the cloud
- [Add the following nodes](https://nodered.org/docs/user-guide/runtime/adding-nodes) to your Node-RED palette
  - [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)
  - [node-red-contrib-web-worldmap](https://flows.nodered.org/node/node-red-contrib-web-worldmap)
  - [node-red-node-ui-table](https://flows.nodered.org/node/node-red-node-ui-table)

## Node-RED flow in this repository:

- Import the [earthquakes flow](earthquakes.json)

---
### A flow that displays Earthquake Alerts on a map

- Display a Notification Alert if there is a Earthquake >= Magnitude 5
- Click on the red icon to zoom to that epicenter on the Earth.

![Earthquake Alert Dashboard](screenshots/EarthquakeAlert-dashboard.png?raw=true "Earthquake Dashboard")

![Earthquake Alert flow](screenshots/Earthquake-flow.png?raw=true "Earthquake flow")

![Earthquake Alert LosAngeles](screenshots/EarthquakeAlert-PuertoRico.png?raw=true "Earthquake Dashboard")
---

### Authors

- [John Walicki](https://github.com/johnwalicki)
___

Enjoy!  Give us [feedback](https://github.com/johnwalicki/Node-RED-Earthquake-Dashboard/issues) if you have suggestions on how to improve this tutorial.

## License

This tutorial is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).
