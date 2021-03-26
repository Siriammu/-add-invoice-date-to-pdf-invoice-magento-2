# add invoice date to pdf and some othe content in it invoice magento 2
By default invoice date is not available on Magento 2 pdf invoice, this module just allow you to add invoice date beside order date

Follow the below steps to use this module for your Magento 2 setup 
Clone & Download the files.

Extract files and put inside app directory, app/code/siri/Pdf

Once you install the module, please run below command in order to make it work.

php bin/magento enable siri_Pdf 
php bin/magento setup:di:compile
php bin/magento cache:clean
php bin/magento cache:flush

OR You may run below command

php bin/magneto setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magneto cache:flush


Thank you & Regards
Siri
