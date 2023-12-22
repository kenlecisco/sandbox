The ./grafana folder will be place to store data for grafana and will be mount to /var/lib/grafana
Docker daemon need to have permission to write to this folder
So grant the write permission: chmod 777 grafana
