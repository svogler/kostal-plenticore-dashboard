# kostal-modbus

Grafana Dashboard to visualize PV Kostal Plenticore information retrieved via Modbus.
All is run on a Raspberry 3b+

Data are retrieved via Telegraf / Modbus and stored in InfluxDB. Grafana is used for visualization.
Docker is used as container for Telegraf. 
JSON for the Grafana dashboard is part of the repo, Grafana itself is not part of the Docker container (in my case Grafana is installed locally)


## Screenshot

![Dashboard Example](/doc/dashboard_example.jpg)


