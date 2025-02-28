Cron
~~~~

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","cron","service","reconfigure",""

.. csv-table:: Resources (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","cron","settings","addJob",""
    "``POST``","cron","settings","delJob","$uuid"
    "``GET``","cron","settings","get",""
    "``GET``","cron","settings","getJob","$uuid=null"
    "``*``","cron","settings","searchJobs",""
    "``POST``","cron","settings","set",""
    "``POST``","cron","settings","setJob","$uuid"
    "``POST``","cron","settings","toggleJob","$uuid,$enabled=null"

    "``<<uses>>``", "", "", "", "*model* `Cron.xml <https://github.com/yetitecnologia/core/blob/master/src/opnsense/mvc/app/models/OPNsense/Cron/Cron.xml>`__"
