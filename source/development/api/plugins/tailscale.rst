Tailscale
~~~~~~~~~

.. csv-table:: Service (AuthenticationController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","tailscale","authentication","get",""
    "``POST``","tailscale","authentication","set",""

    "``<<uses>>``", "", "", "", "*model* `Authentication.xml <https://github.com/yetitecnologia/plugins/blob/master/security/tailscale/src/opnsense/mvc/app/models/OPNsense/Tailscale/Authentication.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","tailscale","service","reconfigure",""
    "``POST``","tailscale","service","restart",""
    "``POST``","tailscale","service","start",""
    "``GET``","tailscale","service","status",""
    "``POST``","tailscale","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `Settings.xml <https://github.com/yetitecnologia/plugins/blob/master/security/tailscale/src/opnsense/mvc/app/models/OPNsense/Tailscale/Settings.xml>`__"

.. csv-table:: Resources (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","tailscale","settings","addSubnet",""
    "``POST``","tailscale","settings","delSubnet","$uuid"
    "``GET``","tailscale","settings","get",""
    "``GET``","tailscale","settings","getSubnet","$uuid=null"
    "``GET``","tailscale","settings","reload",""
    "``*``","tailscale","settings","searchSubnet",""
    "``POST``","tailscale","settings","set",""
    "``POST``","tailscale","settings","setSubnet","$uuid"

    "``<<uses>>``", "", "", "", "*model* `Settings.xml <https://github.com/yetitecnologia/plugins/blob/master/security/tailscale/src/opnsense/mvc/app/models/OPNsense/Tailscale/Settings.xml>`__"

.. csv-table:: Service (StatusController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","tailscale","status","get",""
    "``GET``","tailscale","status","ip",""
    "``GET``","tailscale","status","net",""
    "``POST``","tailscale","status","set",""
    "``GET``","tailscale","status","status",""

    "``<<uses>>``", "", "", "", "*model* `Status.xml <https://github.com/yetitecnologia/plugins/blob/master/security/tailscale/src/opnsense/mvc/app/models/OPNsense/Tailscale/Status.xml>`__"
