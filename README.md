# Magento 2 Bash Installer Script
This script simplifies installation of Magento 2 by performing routine operations.

This script is designed to be run from directory with magento.

You can place config file to 
 - current directory ./.m2install.conf
 - home directory ~/.m2install.conf 

Example of config file
```
VERBOSE=1
HTTP_HOST=http://your-mage-host.com/
BASE_PATH=your/base/path/${CURRENT_DIR_NAME}
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=dbpassword
```
