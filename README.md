# OpenNebula Frontend Graylog Content Pack
This Content Pack enables you to parse the logs which are generated  by OpenNebula Frontend and system logs provided systemd-journal. 

The logs are parsed to enable dashboards, streams and structured search queries. 
<br />Tested with NXLog CE 2.11.2190 and Graylog 4.1.3

This content pack provides useful dashboards for auditing logs:
* OpenNebula  logs from  `/var/log/one`
* Operation system logs from systemd-journal


## Includes
* Dashboard
* NXLog configuration
* Grok patterns
* Pipelines
* Pipelines rules
* Streams
* Lookup tables


## Requirements

* NXLog _You can use ansible role [Graylog-Collector](https://github.com/dganic/Ansible-Role-Graylog-Collector) to install on Ubuntu or Debian_
* Gelf TCP Input


## Screenshots

![Dashboard](https://github.com/dganic/Graylog-ContentPack-OpenNebula/blob/main/screenshots/dashboard-graylog-opennebula.png?raw=true)
