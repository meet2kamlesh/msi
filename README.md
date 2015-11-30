DESCRIPTION:
-----------------
Simple module alter the System Site Information form and Add an extra field with name siteapikey and update the Save
configuration button text. You can add your site apikey to get json output of your page(Page Content Type).


INSTALLATION:
------------------
* Install as usual, see https://www.drupal.org/documentation/install/modules-themes/modules-7 for further information.
* Or put folder to the directory modules, then go to "admin/modules" and enable 
module: "Modify Site Information". 

You also can use drush: "drush en msi"


CONFIGURATION:
------------------
* Go to Site > admin > config > system > site-information
* See Site API Key at bottom
* Insert the siteApi key into Text box and click to Update Configuration.

USAGE:
------------------
* Access your web page Like: http://www.example.com/page_json/SITEAPIKEY/5
* If your APIKEY will match with key in url (like arg(1)), then you will get the json response otherwise access denied page
will display.

CONTACT:
------------------
call2kamlesh@gmail.com
