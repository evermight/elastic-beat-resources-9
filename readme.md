Used by:

https://evermight.com//install-elasticsearch-kibana-9/

Useful commands:

Test output and Config

```
/usr/share/filebeat/bin/filebeat test config -c /etc/filebeat/filebeat.yml --path.data /var/lib/filebeat --path.home /usr/share/filebeat
/usr/share/filebeat/bin/filebeat test output -c /etc/filebeat/filebeat.yml --path.data /var/lib/filebeat --path.home /usr/share/filebeat
```

Setup

```
/usr/share/filebeat/bin/filebeat setup -c /etc/filebeat/filebeat.yml --path.data /var/lib/filebeat --path.home /usr/share/filebeat
```
