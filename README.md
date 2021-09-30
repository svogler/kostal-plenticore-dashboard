# Kostal Plenticore Dashboard 

Grafana Dashboard to visualize Photovoltaics information from Kostal Plenticore retrieved via Modbus.

* Data from Plenticore are retrieved via Telegraf / Modbus and stored in InfluxDB. 
* Grafana is used for visualization.
* Docker is used as container for Telegraf. 
* JSON for the Grafana dashboard is part of the repo
* Grafana itself is not part of the Docker container (in my case Grafana is installed locally)

All is run on a Raspberry 3b+, but can run on any almost any hardware.

## Screenshot

![Dashboard Example](/doc/dashboard_example.jpg)


