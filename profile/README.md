
# Grayl - A PHP E-commerce Framework

Grayl is as a lightweight modular set of packages to handle several e-commerce website tasks. It can be installed using the Composer package manager. The highlight is a hand written database Query Builder class that can be used to build SQL queries from objects and classes, and then run them safely using prepared statements to prevent SQL injections. There are also lots of packages that provide API integration with popular services like MailChimp, MinFraud, Paypal, AuthorizeDotNet, ZendDesk, and ZohoCRM. All packages include unit tests for high code coverage.

## Highlights

- The [grayl-gateway-common](https://github.com/grayl-php/grayl-gateway-common) package is a set of interfaces and abstract classes that all the other API based packages in Grayl are built on.
- The [grayl-database-query](https://github.com/grayl-php/grayl-database-query) package builds SQL queries from objects. So you can assemble a full SELECT statement, or even insert data, using classes and methods. It also sanitizes data and implements prepared statements to protect against things like SQL injections.
- The [grayl-omnipay-paypal](https://github.com/grayl-php/grayl-omnipay-paypal) library handles connecting to Paypal's APIs to handle processing payments on Paypal's website.
- The [grayl-omnipay-authorizenet](https://github.com/grayl-php/grayl-omnipay-authorizenet) handles processing actual credit card payments on-site using AuthorizeDotNet as a merchant provider.
- The [grayl-gateway-mailchimp](https://github.com/grayl-php/grayl-gateway-mailchimp) library uses APIs to create users and mailing lists on your MailChimp service.

## Packages

Each package has its own repo and individual instructions if needed.

| Package | Description |
| -- | -- |
| [grayl-config](https://github.com/grayl-php/grayl-config) | Keeps track of class configurations. |
| [grayl-database-main](https://github.com/grayl-php/grayl-database-main) | Main database library that runs query builder against a database. |
| [grayl-database-query](https://github.com/grayl-php/grayl-database-query) | Object based query builder with prepared statements. |
| [grayl-date](https://github.com/grayl-php/grayl-date) | Manages and manipulates dates. |
| [grayl-display-navigation](https://github.com/grayl-php/grayl-display-navigation) | Navigation builder with breadcrumbs. |
| [grayl-file](https://github.com/grayl-php/grayl-file) | Reads and writes to files. |
| [grayl-gateway-common](https://github.com/grayl-php/grayl-gateway-common) | Main interfaces and abstract classes for all gateway packages. |
| [grayl-gateway-mailchimp](https://github.com/grayl-php/grayl-gateway-mailchimp) | Subscribes users and creates lists using the MailChimp API. |
| [grayl-gateway-mandrill](https://github.com/grayl-php/grayl-gateway-mandrill) | Sends transactional emails using the Mandrill API. |
| [grayl-gateway-minfraud](https://github.com/grayl-php/grayl-gateway-minfraud) | Scores the potential for credit card fraud using the MinFraud API. |
| [grayl-gateway-pdo](https://github.com/grayl-php/grayl-gateway-pdo) | A supporting database PDO connector. |
| [grayl-gateway-zendesk](https://github.com/grayl-php/grayl-gateway-zendesk) | Creates users using the ZenDesk API. |
| [grayl-gateway-zohocrm](https://github.com/grayl-php/grayl-gateway-zohocrm) | Creates customer records, notes, and fields using the ZohoCRM API. |
| [grayl-image-thumbnail](https://github.com/grayl-php/grayl-image-thumbnail) | Creates thumbnails from images. |
| [grayl-input-duplicator](https://github.com/grayl-php/grayl-input-duplicator) | Checks for duplicate form submissions. |
| [grayl-input-floodcheck](https://github.com/grayl-php/grayl-input-floodcheck) | Prevents click floods on web forms. |
| [grayl-mixin-common](https://github.com/grayl-php/grayl-mixin-common) | Common helper classes. |
| [grayl-omnipay-common](https://github.com/grayl-php/grayl-omnipay-common) | Interfaces and abstract classes for all Omnipay packages. |
| [grayl-omnipay-authorizenet](https://github.com/grayl-php/grayl-omnipay-authorizenet) | Authorizes, captures, and refunds credit card payments using Authorize.net API. |
| [grayl-omnipay-payflow](https://github.com/grayl-php/grayl-omnipay-payflow) | Authorizes, captures, and refunds credit card payments using Paypal Payflow API. |
| [grayl-omnipay-paypal](https://github.com/grayl-php/grayl-omnipay-paypal) | Creates orders and redirects for offsite payment using Paypal API. |
| [grayl-store-order](https://github.com/grayl-php/grayl-store-order) | The order module for the store package. |
| [grayl-store-product](https://github.com/grayl-php/grayl-store-product) | The product module for the store package. |
| [grayl-store-sale](https://github.com/grayl-php/grayl-store-sale) | The store module for the store package. |

## Archived packages

| Package | Description |
| -- | -- |
| [grayl-display-content](https://github.com/grayl-php/grayl-display-content) | Content management from files - *archived* |
| [grayl-display-template](https://github.com/grayl-php/grayl-display-template) | Parses templates using markup - *archived* |
| [grayl-input-form](https://github.com/grayl-php/grayl-input-form) | Validates and sanitizes form input - *archived* |
| [grayl-utility](https://github.com/grayl-php/grayl-utility) | Utilities and tools - *archived* |

## Written by

[Scott Richardson](https://github.com/scottyrichardson)

## License

MIT
