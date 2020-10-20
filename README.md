# magento2.4-setup

step 1
''
php bin/magento setup:install --base-url="https://magento2.xploringtech.com/" --db-host="localhost" --db-name="magento2" --db-user="magento2" --db-password="password" --admin-firstname="admin" --admin-lastname="admin" --admin-email="admin@admin.com" --admin-user="admin" --admin-password="admin123" --language="en_US" --currency="INR" --timezone="America/Chicago" --use-rewrites="1" --backend-frontname="admin"
''

step 2
''
php bin/magento module:disable {Magento_Elasticsearch,Magento_InventoryElasticsearch,Magento_Elasticsearch6,Magento_Elasticsearch7}

''
