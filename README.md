Table of Contents

- [Requirements](#requirements)
  * [Operating systems](#operating-systems)
  * [Zabbix Versions](#zabbix-versions)
    + [Zabbix 3.4](#zabbix-34)
  * [Installation](#installation)
  * [Main Variables](#main-variables)
    + [Overall Variables](#overall-variables)
- [Dependencies](#dependencies)
- [Contributors](#contributors)
- [License](#license)
- [Author Information](#author-information)

# Requirements

## Operating systems

This role will work on the following operating system:

 * Red Hat

## Zabbix Versions

The foloowing list of supported operating systems for Zabbix releases

### Zabbix 3.4

* RedHat 7.x
* CentOS 7.x

# Installation

Installing this role:

This role does not install a Zabbix Server and presumes an already operational zabbix system.  

# Main Variables

## Overall Variables

* `zabbix_trap_log_directory`: The directory location to store traps received by hosts
* `zabbix_trap_log_file`: The file location to store traps received by hosts
* `zabbix_trap_community`: Private snmp trap community name 
* `zabbix_trap_snmptt_files`: List of snmptt trap files snmptt will use to process traps
* `zabbix_trap_logrotate_size`: Max log file size before roetating file
* `zabbix_trap_logrotate_number`: Max number of archived log files to store  

# Dependencies

This role requires the installation of a Zabbix server already be installed and operational.  

# Contributors

The following have contributed to this Ansible role (List of Fame):

  * 

# License

GPLv3

# Author Information

This is my first github repository.  If you identify corrections, please send suggestions or pull requests.  

This project has been forked from [average-joe](https://github.com/average-joe/ansible-zabbix-trap).
