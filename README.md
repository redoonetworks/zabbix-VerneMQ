# zabbix-verneMQ
Template to monitor VerneMQ from Zabbix  

Currently in development and will be extended, after proof of concept was sucessfully and script is convert all metrix to xml.

Template loads Prometheus metrix, generated from VerneMQ server.  
It use the IP from Zabbix Host to read Metrix. So you need to make add a secure way to pull values and prevent access from public.

## Compatibility

Tested with following zabbix versions: 
  - 5.4
  
## Installation
   - Download template XML
   - Import XML into templates
