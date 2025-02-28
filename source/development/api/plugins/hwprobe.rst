Hwprobe
~~~~~~~

.. csv-table:: Service (GeneralController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","hwprobe","general","get",""
    "``POST``","hwprobe","general","set",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/sysutils/hw-probe/src/opnsense/mvc/app/models/OPNsense/Hwprobe/General.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","hwprobe","service","reconfigure",""
    "``GET``","hwprobe","service","report",""
    "``POST``","hwprobe","service","restart",""
    "``POST``","hwprobe","service","start",""
    "``GET``","hwprobe","service","status",""
    "``POST``","hwprobe","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/sysutils/hw-probe/src/opnsense/mvc/app/models/OPNsense/Hwprobe/General.xml>`__"
