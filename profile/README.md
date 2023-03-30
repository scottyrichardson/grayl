
# Grayl - A PHP E-commerce Framework

Grayl is as a lightweight modular set of packages to handle several e-commerce website tasks. It is an excellent example of my use of fully object oriented programming, interfaces, abstract classes (see the gateway-common package for precise examples), name spaces, and code coverage with unit tests.

It can be installed using the Composer package manager which will also install its dependencies. The highlight is a hand written database Query Builder class that can be used to build SQL queries from objects and classes, and then run them safely using prepared statements to prevent SQl injections. There are also tons of packages that provide API integration with popular services like MailChimp, MinFraud, Paypal and AuthorizeDotNet (for both on-site and off-site credit card processing), ZendDesk, and ZohoCRM. It includes unit tests you can review as well.

## Highlights:

- The [gateway-common](https://github.com/scottyrichardson/gateway-common) package is a set of interfaces and abstract classes that all the other API based packages in Grayl are built on.
- The [database-query](https://github.com/scottyrichardson/database-query) package builds SQL queries from objects. So you can assemble a full SELECT statement, or even insert data, using classes and methods. It also sanitizes data and implements prepared statements to protect against things like SQL injections.
- The [omnipay-paypal](https://github.com/scottyrichardson/omnipay-paypal) library handles connecting to Paypal's APIs to handle processing payments on Paypal's website.
- The [omnipay-authorizenet](https://github.com/scottyrichardson/omnipay-authorizenet) handles processing actual credit card payments on-site using AuthorizeDotNet as a merchant provider.
- The [gateway-mailchimp](https://github.com/scottyrichardson/gateway-mailchimp) library uses APIs to create users and mailing lists on your MailChimp service.

## Available modules

Each module has its own repo and individual instructions if needed.

- [grayl-config](https://github.com/scottyrichardson/grayl-config) - Keeps track of class configurations
- [grayl-database-main](https://github.com/scottyrichardson/grayl-database-main) - Main database library that runs query builder against a database
- [grayl-database-query](https://github.com/scottyrichardson/grayl-database-query) - Object based query builder with prepared statements
- [grayl-date](https://github.com/scottyrichardson/grayl-date) - Manages and manipulates dates
- [grayl-display-content](https://github.com/scottyrichardson/grayl-display-content) - Content management from files - archived
- [grayl-display-navigation](https://github.com/scottyrichardson/grayl-display-navigation) - Navigation builder with breadcrumbs
- [grayl-display-template](https://github.com/scottyrichardson/grayl-display-template) - Parses templates using markup
- [grayl-file](https://github.com/scottyrichardson/grayl-file) - Reads and writes to files
- [grayl-gateway-common](https://github.com/scottyrichardson/grayl-gateway-common) - Main interfaces and abstract classes for all gateway packages
- [grayl-gateway-mailchimp](https://github.com/scottyrichardson/grayl-gateway-mailchimp) - Subscribes users and creates lists using the MailChimp API
- [grayl-gateway-mandrill](https://github.com/scottyrichardson/grayl-gateway-mandrill) - Sends transactional emails using the Mandrill API
- [grayl-gateway-minfraud](https://github.com/scottyrichardson/grayl-gateway-minfraud) - Scores the potential for credit card fraud using the MinFraud API
- [grayl-gateway-pdo](https://github.com/scottyrichardson/grayl-gateway-pdo) - A supporting database PDO connector
- [grayl-gateway-zendesk](https://github.com/scottyrichardson/grayl-gateway-zendesk) - Creates users using the ZenDesk API
- [grayl-gateway-zohocrm](https://github.com/scottyrichardson/grayl-gateway-zohocrm) - Creates customer records, notes, and fields using the ZohoCRM API
- [grayl-image-thumbnail](https://github.com/scottyrichardson/grayl-image-thumbnail) - Creates thumbnails from images
- [grayl-input-duplicator](https://github.com/scottyrichardson/grayl-input-duplicator) - Checks for duplicate form submissions
- [grayl-input-floodcheck](https://github.com/scottyrichardson/grayl-input-floodcheck) - Prevents click floods on web forms
- [grayl-input-form](https://github.com/scottyrichardson/grayl-input-form) - Validates and sanitizes form input
- [grayl-mixin-common](https://github.com/scottyrichardson/grayl-mixin-common) - Common helper classes
- [grayl-store-order](https://github.com/scottyrichardson/grayl-store-order) - The order module for the store package
- [grayl-store-product](https://github.com/scottyrichardson/grayl-store-product) - The product module for the store package
- [grayl-store-sale](https://github.com/scottyrichardson/grayl-store-sale) - The store module for the store package
- [grayl-utility](https://github.com/scottyrichardson/grayl-utility) - Utilities and tools - archived

## Written by

[Scott Richardson](https://github.com/scottyrichardson)

## License

MIT
