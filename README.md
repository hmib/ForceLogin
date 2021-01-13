Force Login

Overview

RLTSquare Force Login restricts the user to visit the pages, checkout, and custom URLs on which the force login is applied. Users can visit the pages after login or after making registration/account. Without login, the user will redirect to the user login Page. After login of the restricted user, the user will also be redirected to the page set by the admin.

Features

	•	Admin disables the account creation on the frontend.
	•	Set the message for the user after the redirection of user.
	•	Restrict the user from accessing the pages like, product detail page, category page, checkout page, search page and custom pages.
	•	Also, restrict all search catalog pages from the configuration.
	•	Include custom pages by pasting the URL’s comma-separated.
	•	Exclude the URL’s comma-separated.
	•	After the successful login, redirect to any page by placing the custom URL.

Installation
 
Enter following commands to enable the module:
php bin/magento module:enable RLTSquare_ForceLogin
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento static:content:deploy -f
php bin/magento cache:clean
php bin/magento cache:flush

If Magento® is running in production mode, deploy static content and then clear the cache: 
php bin/magento setup:static-content:deploy
This extension for Magento® works on Magento 2.3, 2.4’s all versions. Tested on versions from 2.3.0 and above.


Go to Stores→Configuation→Force Login

1. General Configuration

2. Attach Pages/Catalog Pages.

3. Apply on Custom Pages, Exclude Custom Pages and Redirect to Pages After Login



Support
RLTSquare team assures to provide you all the support you require with fast responses for this extension. Moreover, we will also customize this extension for you to suit your specific needs. For support, contact us at  <support@rltsquare.com>
