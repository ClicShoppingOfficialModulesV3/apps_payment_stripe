# apps_payment_stripe

The Stripe payment plugin module allows you to connect your Stripe account to your online store.
The payment gateway is operated by Stripe,<br /><br />
https://www.stripe.com

Important Note :
You have installed composer on your server
You must have an account to Stripe.
You site must have a valid ssl certificate
A help section is including inside the apps to help you to configure your account and Apps

Pack
Language : English - french
licence  : GPL 2 - MIT

Install :
https://monsite/myAdmin/index.php?A&Payment\Stripe
or via the Menu/Configuration/Payment

Activate the module in Payment
Copy the apps_payment_stripe.json into ClicShopping/Work/Cache/Github (manual installation)

Important note :
- To use this apps, you must install composer on your local server or your server (apt-get install composer for linux).
- The exec function must be authorised by your hoster else the auto installation will not work (for the libray but the apps will be installed).
- To install manually the library
Inside the shop directory (where there is composer.json file)

composer require stripe/stripe-php ==> installation
composer update stripe/stripe-php ==> update
composer remove stripe/stripe-php ==> remove

Once this installaton is made, you can set the apps.


See Marketplace for all informations
link to marketplace : https://www.clicshopping.org/forum/files/file/173-stripe/


All informations about the ClicShopping

Community : https://www.clicshopping.org
Software : https://github.com/ClicShopping
Official add on : https://github.com/ClicShoppingOfficialModulesV3
Community add on : https://github.com/ClicShoppingV3Community
trademark License info : https://www.clicshopping.org/forum/trademark/ 

![image](https://github.com/ClicShoppingOfficialModulesV3/apps_payment_stripe/blob/master/ModuleInfosJson/image.png)
