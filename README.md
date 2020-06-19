# grafana-openwrt-influxdb
Grafana based Open-WRT network monitoring using InfluxDB

Dashboard model is in the "OpenWRT_Dashboard_Grafana_model.json" file
## Dashboard Demo:
![GitHub Logo](/Grafana_dash_Example.jpg)
## Uses the following:
Collectd, luci-app-statistics, iptmon for Open-WRT data logging (Find iptmon here: https://github.com/oofnikj/iptmon)

InfluxDB running on RaspberryPi with collectd agent enabled

Grafana with influxDB as datasource
