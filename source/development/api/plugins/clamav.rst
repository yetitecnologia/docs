Clamav
~~~~~~

.. csv-table:: Service (GeneralController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","clamav","general","get",""
    "``POST``","clamav","general","set",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/security/clamav/src/opnsense/mvc/app/models/OPNsense/ClamAV/General.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","clamav","service","freshclam",""
    "``POST``","clamav","service","reconfigure",""
    "``POST``","clamav","service","restart",""
    "``POST``","clamav","service","start",""
    "``GET``","clamav","service","status",""
    "``POST``","clamav","service","stop",""
    "``GET``","clamav","service","version",""

    "``<<uses>>``", "", "", "", "*model* `General.xml <https://github.com/yetitecnologia/plugins/blob/master/security/clamav/src/opnsense/mvc/app/models/OPNsense/ClamAV/General.xml>`__"

.. csv-table:: Resources (UrlController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","clamav","url","addUrl",""
    "``POST``","clamav","url","delUrl","$uuid"
    "``GET``","clamav","url","get",""
    "``GET``","clamav","url","getUrl","$uuid=null"
    "``*``","clamav","url","searchUrl",""
    "``POST``","clamav","url","set",""
    "``POST``","clamav","url","setUrl","$uuid"
    "``POST``","clamav","url","toggleUrl","$uuid"

    "``<<uses>>``", "", "", "", "*model* `Url.xml <https://github.com/yetitecnologia/plugins/blob/master/security/clamav/src/opnsense/mvc/app/models/OPNsense/ClamAV/Url.xml>`__"
