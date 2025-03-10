Haproxy
~~~~~~~

.. csv-table:: Resources (ExportController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","export","config",""
    "``GET``","haproxy","export","diff",""
    "``GET``","haproxy","export","download","$type"

.. csv-table:: Resources (MaintenanceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","maintenance","certActions",""
    "``GET``","haproxy","maintenance","certDiff",""
    "``GET``","haproxy","maintenance","certSync",""
    "``GET``","haproxy","maintenance","certSyncBulk",""
    "``POST``","haproxy","maintenance","fetchCronIntegration",""
    "``GET``","haproxy","maintenance","get",""
    "``GET``","haproxy","maintenance","searchCertificateDiff",""
    "``GET``","haproxy","maintenance","searchServer",""
    "``GET``","haproxy","maintenance","serverState",""
    "``GET``","haproxy","maintenance","serverStateBulk",""
    "``GET``","haproxy","maintenance","serverWeight",""
    "``GET``","haproxy","maintenance","serverWeightBulk",""
    "``POST``","haproxy","maintenance","set",""

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/yetitecnologia/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","service","configtest",""
    "``POST``","haproxy","service","reconfigure",""
    "``POST``","haproxy","service","restart",""
    "``POST``","haproxy","service","start",""
    "``GET``","haproxy","service","status",""
    "``POST``","haproxy","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/yetitecnologia/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Resources (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","haproxy","settings","addAcl",""
    "``POST``","haproxy","settings","addAction",""
    "``POST``","haproxy","settings","addBackend",""
    "``POST``","haproxy","settings","addCpu",""
    "``POST``","haproxy","settings","addErrorfile",""
    "``POST``","haproxy","settings","addFcgi",""
    "``POST``","haproxy","settings","addFrontend",""
    "``POST``","haproxy","settings","addGroup",""
    "``POST``","haproxy","settings","addHealthcheck",""
    "``POST``","haproxy","settings","addLua",""
    "``POST``","haproxy","settings","addMapfile",""
    "``POST``","haproxy","settings","addServer",""
    "``POST``","haproxy","settings","addUser",""
    "``POST``","haproxy","settings","addmailer",""
    "``POST``","haproxy","settings","addresolver",""
    "``POST``","haproxy","settings","delAcl","$uuid"
    "``POST``","haproxy","settings","delAction","$uuid"
    "``POST``","haproxy","settings","delBackend","$uuid"
    "``POST``","haproxy","settings","delCpu","$uuid"
    "``POST``","haproxy","settings","delErrorfile","$uuid"
    "``POST``","haproxy","settings","delFcgi","$uuid"
    "``POST``","haproxy","settings","delFrontend","$uuid"
    "``POST``","haproxy","settings","delGroup","$uuid"
    "``POST``","haproxy","settings","delHealthcheck","$uuid"
    "``POST``","haproxy","settings","delLua","$uuid"
    "``POST``","haproxy","settings","delMapfile","$uuid"
    "``POST``","haproxy","settings","delServer","$uuid"
    "``POST``","haproxy","settings","delUser","$uuid"
    "``POST``","haproxy","settings","delmailer","$uuid"
    "``POST``","haproxy","settings","delresolver","$uuid"
    "``GET``","haproxy","settings","get",""
    "``GET``","haproxy","settings","getAcl","$uuid=null"
    "``GET``","haproxy","settings","getAction","$uuid=null"
    "``GET``","haproxy","settings","getBackend","$uuid=null"
    "``GET``","haproxy","settings","getCpu","$uuid=null"
    "``GET``","haproxy","settings","getErrorfile","$uuid=null"
    "``GET``","haproxy","settings","getFcgi","$uuid=null"
    "``GET``","haproxy","settings","getFrontend","$uuid=null"
    "``GET``","haproxy","settings","getGroup","$uuid=null"
    "``GET``","haproxy","settings","getHealthcheck","$uuid=null"
    "``GET``","haproxy","settings","getLua","$uuid=null"
    "``GET``","haproxy","settings","getMapfile","$uuid=null"
    "``GET``","haproxy","settings","getServer","$uuid=null"
    "``GET``","haproxy","settings","getUser","$uuid=null"
    "``GET``","haproxy","settings","getmailer","$uuid=null"
    "``GET``","haproxy","settings","getresolver","$uuid=null"
    "``*``","haproxy","settings","searchAcls",""
    "``*``","haproxy","settings","searchActions",""
    "``*``","haproxy","settings","searchBackends",""
    "``*``","haproxy","settings","searchCpus",""
    "``*``","haproxy","settings","searchErrorfiles",""
    "``*``","haproxy","settings","searchFcgis",""
    "``*``","haproxy","settings","searchFrontends",""
    "``*``","haproxy","settings","searchGroups",""
    "``*``","haproxy","settings","searchHealthchecks",""
    "``*``","haproxy","settings","searchLuas",""
    "``*``","haproxy","settings","searchMapfiles",""
    "``*``","haproxy","settings","searchServers",""
    "``*``","haproxy","settings","searchUsers",""
    "``*``","haproxy","settings","searchmailers",""
    "``*``","haproxy","settings","searchresolvers",""
    "``POST``","haproxy","settings","set",""
    "``POST``","haproxy","settings","setAcl","$uuid"
    "``POST``","haproxy","settings","setAction","$uuid"
    "``POST``","haproxy","settings","setBackend","$uuid"
    "``POST``","haproxy","settings","setCpu","$uuid"
    "``POST``","haproxy","settings","setErrorfile","$uuid"
    "``POST``","haproxy","settings","setFcgi","$uuid"
    "``POST``","haproxy","settings","setFrontend","$uuid"
    "``POST``","haproxy","settings","setGroup","$uuid"
    "``POST``","haproxy","settings","setHealthcheck","$uuid"
    "``POST``","haproxy","settings","setLua","$uuid"
    "``POST``","haproxy","settings","setMapfile","$uuid"
    "``POST``","haproxy","settings","setServer","$uuid"
    "``POST``","haproxy","settings","setUser","$uuid"
    "``POST``","haproxy","settings","setmailer","$uuid"
    "``POST``","haproxy","settings","setresolver","$uuid"
    "``POST``","haproxy","settings","toggleBackend","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleCpu","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleFrontend","$uuid"
    "``POST``","haproxy","settings","toggleGroup","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleLua","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleServer","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleUser","$uuid,$enabled=null"
    "``POST``","haproxy","settings","togglemailer","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleresolver","$uuid,$enabled=null"

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/yetitecnologia/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Resources (StatisticsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","statistics","counters",""
    "``GET``","haproxy","statistics","info",""
    "``GET``","haproxy","statistics","tables",""
