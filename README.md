Magento 2.4.1 TrainingBoard
---

**Requirement**
    
    PHP v7.4.9
    Elasticsearch v7.9.2 (port 9200)
    MySQL v5.7.26  

**Installation**

Run command: **_composer install_**

Expand database (from dump).

Run command: **_bin/magento module:enable --all_**

Run command: **_bin/magento module:disable Magento_TwoFactorAuth_**

Create php config **_/app/etc/env.php_** and **_set settings_**.

Run command: **_bin/magento setup:upgrade_**

Run command: **_bin/magento setup:di:compile_**

Run command: **_bin/magento indexer:reindex_**

Run command: **_bin/magento cache:flush_**
