Netdata
~~~~~~~

.. csv-table:: Service (GeneralController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","netdata","general","get",""
    "``POST``","netdata","general","set",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/net-mgmt/netdata/src/opnsense/mvc/app/models/OPNsense/Netdata/General.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","netdata","service","reconfigure",""
    "``POST``","netdata","service","restart",""
    "``POST``","netdata","service","start",""
    "``GET``","netdata","service","status",""
    "``POST``","netdata","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/net-mgmt/netdata/src/opnsense/mvc/app/models/OPNsense/Netdata/General.xml>`__"
