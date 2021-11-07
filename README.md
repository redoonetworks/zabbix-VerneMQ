# Zabbix VerneMQ Template
Template to monitor VerneMQ from Zabbix  

**Currently in development and will be extended, after proof of concept was sucessfully and script is convert all metrix to xml.**

Template use Prometheus metrics, generated from VerneMQ server.  
It use the IP and Port 8888 from Zabbix Host to read metrics. So you need to make add a secure way to pull values and prevent access from public.

## Compatibility

Tested with following zabbix versions: 
  - 5.4
  
## Installation
   - Download template XML
   - Import XML into templates
