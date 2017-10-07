# magento2-currency-conversion-bug
### This Module fixes an issue where the price is incorrectly converted when viewed in non-base currency in the product view block

 ## How to install
  
  ### Composer method
  Install the module via composer.
  
  **Install Extension**:
  
  ```
  composer require subrata/core-bug-currency-conversion:*
  php bin/magento cache:clean
  php bin/magento setup:static-content:deploy en_US
  php bin/magento indexer:reindex
  php bin/magento cache:clean
  php bin/magento cache:flush
  
  ```
  
  
  **Update Extension**:
  
  ```
  composer update subrata/core-bug-currency-conversion:*
  php bin/magento cache:clean
  php bin/magento setup:static-content:deploy en_US
  php bin/magento indexer:reindex
  php bin/magento cache:clean
  php bin/magento cache:flush
  
  ```
  
  #### Authentication required (Optional)
  
  ![Authentication required](https://i.imgur.com/dmryiPk.png)
  
  If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)
  
