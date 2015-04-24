# Magento-5344-noshhpatch
Magento 1.8 > 5344 Patch. Might apply to other versions. Designed for use where no SSH access is available to run the Magento shell script.

# Installation
Copy the supplied folders into the root directory of your Magento installation and overwrite the existing files.

# Files effected
app/code/core/Mage/Admin/Model/Observer.php
app/code/core/Mage/Core/Controller/Request/Http.php
app/code/core/Mage/Oauth/controllers/Adminhtml/Oauth/AuthorizeController.php
app/code/core/Mage/XmlConnect/Model/Observer.php
lib/Varien/Db/Adapter/Pdo/Mysql.php
