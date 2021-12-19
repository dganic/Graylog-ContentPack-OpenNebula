# OpenNebula Frontend Graylog Content Pack
This Content Pack enables you to parse the logs which are generated  by OpenNebula Frontend  and system logs provided systemd-journal. 
The logs are parsed to enable dashboards, streams and structured search queries."
Tested with NXLog CE 2.11.2190 and Graylog 4.1.3

This content pack provides useful dashboards for auditing logs:
* OpenNebula  logs from /var/log/one
* Operation system logs form systemd-journal


## Includes
* Dashboard
* NXLog configuration
* Grok patterns
* Pipelines
* Pipelines rules
* Streams
* Lookup tables


## Requirements

* NXLog 
* Gelf TCP Input


## Screenshots

![Dashboard]()
