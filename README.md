Zabbix template for monitoring ASUSTOR devices over SNMP v2.

Requirements:

	ASUSTOR NAS with ADM 2.4.0 or later
	Zabbix Server 4.2 (not tested for older versions)

Main features:
	
	1. LLD for Physical Disks
	2. LLD for Logical Volumes
	3. LLD for Network Connections
	4. Created items for monitoring connected UPS (without triggers)
	5. Use {$SNMP_COMUNITY} to connect to NAS

Installation:

	Import template to your Zabbix server. Link it to your ASUSTOR device via SNMP interface. 

Warning: 
	
	This template was created by document "NAS_271_ASUSTOR_NAS_MIB_Guide.pdf", so if some items will not work with your hardware don't blame me )).
	Created and tested with ASUSTOR AS1002T.

I NEED YOUR HELP with testing this template with other ASUSTOR products.