# ERPNext Whitelabel

## Installation Steps

step 1

      bench get-app https://github.com/bibhashanand/whitelabel

step 2

      bench --site sitename install-app whitelabel

step 3

      bench migrate
      bench restart
      bench clear-cache

## to remove app

      bench --site sitename uninstall-app whitelabel

to delete from frappe

      bench remove-app whitelabel
