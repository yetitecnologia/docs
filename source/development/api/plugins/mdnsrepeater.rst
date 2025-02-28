Mdnsrepeater
~~~~~~~~~~~~

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","mdnsrepeater","service","reconfigure",""
    "``POST``","mdnsrepeater","service","restart",""
    "``POST``","mdnsrepeater","service","start",""
    "``GET``","mdnsrepeater","service","status",""
    "``POST``","mdnsrepeater","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `MDNSRepeater.xml <https://github.com/yetitecnologia/plugins/blob/master/net/mdns-repeater/src/opnsense/mvc/app/models/OPNsense/MDNSRepeater/MDNSRepeater.xml>`__"

.. csv-table:: Service (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","mdnsrepeater","settings","get",""
    "``POST``","mdnsrepeater","settings","set",""

    "``<<uses>>``", "", "", "", "*model* `MDNSRepeater.xml <https://github.com/yetitecnologia/plugins/blob/master/net/mdns-repeater/src/opnsense/mvc/app/models/OPNsense/MDNSRepeater/MDNSRepeater.xml>`__"
