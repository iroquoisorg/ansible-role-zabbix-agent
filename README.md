# zabbix-agent

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-zabbix-agent.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for zabbix-agent

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.zabbix-agent`

# Default settings

```

zabbix_agent_zabbix_version: 3.4
zabbix_agent_package: zabbix-agent
zabbix_agent_service: zabbix-agent
zabbixagent_server:
zabbixagent_serveractive:

zabbix_agent_pidfile: /var/run/zabbix/zabbix_agentd.pid
zabbix_agent_logfile: /var/log/zabbix/zabbix_agentd.log
zabbix_agent_custom_config: []
zabbix_agent_logfilesize: 100
zabbix_agent_debuglevel: 3
zabbix_agent_sourceip:
zabbix_agent_enableremotecommands: 0
zabbix_agent_logremotecommands: 0
zabbix_agent_listenport: 10050
zabbix_agent_listeninterface:
zabbix_agent_listenip:
zabbix_agent_startagents: 3
zabbix_agent_hostname:
zabbix_agent_hostnameitem:
zabbix_agent_hostmetadata:
zabbix_agent_hostmetadataitem:
zabbix_agent_refreshactivechecks: 120
zabbix_agent_buffersend: 5
zabbix_agent_buffersize: 100
zabbix_agent_maxlinespersecond: 100
zabbix_agent_allowroot: 0
zabbix_agent_zabbix_alias:
zabbix_agent_timeout: 3
zabbix_agent_include: /etc/zabbix/zabbix_agentd.d
zabbix_agent_unsafeuserparameters: 0
zabbix_agent_userparameter:
zabbix_agent_loadmodulepath: ${libdir}/modules
zabbix_agent_loadmodule:

```
