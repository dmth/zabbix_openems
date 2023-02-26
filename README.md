# zabbix_openems
A template to import data from OpenEMS into Zabbix

First draft, currently no automation. The Template has roughly 100 seperate values which are queried from the OpenEMS API individually.

## List of possible improvements:
- Use the wildcard-uri of OpenEMS instead of seperate calls, `http://[Edge-IP]/rest/channel/_sum/.*` and model the data as [dependent item](https://www.zabbix.com/documentation/current/en/manual/config/items/itemtypes/dependent_items) in Zabbix 
- Generate Items with Zabbix LowLevel-Dicovery

## Links
- OpenEMS Community-Forum thread: https://community.openems.io/t/a-zabbix-template-for-openems/1291
