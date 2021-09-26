# kostal-modbus

Grafana Dashboard to visualize PV Kostal Plenticore information retrieved via Modbus.
All is run on a Raspberry 3b+

Data are retrieved via Telegraf / Modbus and stored in InfluxDB. Grafana is used for visualization.
Docker is used as container for Telegraf. Grafana is not part of the Docker config (in my case installed locally)


## Example

![Dashboard Example](/doc/dashboard_example.jpg)


