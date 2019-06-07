Metricbeat is a lightweight shipper that you can install on your servers to periodically collect metrics from the operating system and from services running on the server. Metricbeat takes the metrics and statistics that it collects and ships them to the output that you specify, such as Elasticsearch or Logstash.

Available commands after deploy:

    sudo systemctl status metricbeat
    sudo systemctl start metricbeat
    sudo systemctl stop metricbeat
    sudo metricbeat