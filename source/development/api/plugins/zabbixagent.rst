Zabbixagent
~~~~~~~~~~~

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","zabbixagent","service","reconfigure",""
    "``POST``","zabbixagent","service","restart",""
    "``POST``","zabbixagent","service","start",""
    "``GET``","zabbixagent","service","status",""
    "``POST``","zabbixagent","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `ZabbixAgent.xml <https://github.com/yetitecnologia/plugins/blob/master/net-mgmt/zabbix-agent/src/opnsense/mvc/app/models/OPNsense/ZabbixAgent/ZabbixAgent.xml>`__"

.. csv-table:: Resources (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","zabbixagent","settings","addAlias",""
    "``POST``","zabbixagent","settings","addUserparameter",""
    "``POST``","zabbixagent","settings","delAlias","$uuid"
    "``POST``","zabbixagent","settings","delUserparameter","$uuid"
    "``GET``","zabbixagent","settings","get",""
    "``GET``","zabbixagent","settings","getAlias","$uuid=null"
    "``GET``","zabbixagent","settings","getUserparameter","$uuid=null"
    "``*``","zabbixagent","settings","searchAliases",""
    "``*``","zabbixagent","settings","searchUserparameters",""
    "``POST``","zabbixagent","settings","set",""
    "``POST``","zabbixagent","settings","setAlias","$uuid"
    "``POST``","zabbixagent","settings","setUserparameter","$uuid"
    "``POST``","zabbixagent","settings","toggleAlias","$uuid"
    "``POST``","zabbixagent","settings","toggleUserparameter","$uuid"

    "``<<uses>>``", "", "", "", "*model* `ZabbixAgent.xml <https://github.com/yetitecnologia/plugins/blob/master/net-mgmt/zabbix-agent/src/opnsense/mvc/app/models/OPNsense/ZabbixAgent/ZabbixAgent.xml>`__"
