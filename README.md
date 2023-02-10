# DiREpeK
## Disaster Recovery Epesi Kit

Image based on https://github.com/jtylek/RasPiEsi
with added Chrome configured in kiosk mode to run Recovery Wizard.

Allow upload/download compressed, for example Softaculous zipped, backup file and:
- uncompress the backup
- scan for /data/ and especially /data/config.php file
- recreate a database and user in MariaDB from recovered /config.php
- recreate /Epesi/ directory structure including /Premium/ /Custom/ modules
- start Recovered Epesi

Additional tool: Forgotten admin password reset.
