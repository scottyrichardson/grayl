
# Grayl - A PHP E-commerce Framework

Grayl is as a lightweight modular set of packages to handle several e-commerce website tasks. It can be installed using the Composer package manager. All packages include unit tests for high code coverage.

## Features

- Uses interfaces and abstract classes in all API gateway classes to enforce conformity.
- Includes a custom query builder. Build SQL queries from objects and run them as prepared statements to protect against SQL injections.
- Handles off-site Paypal payments using the Paypal API.
- Processes on-site credit card payments using the Paypal Payflow API and Authorize.net API.
- Reduces fraudulent charges using the MinFraud API.
- Prevents web form abuse with flood-checks and de-duplication packages.
- Comes with a full store management library including products, discounts, orders, and payments.
- Communicates with common web services like MailChimp, ZenDesk, ZohoCRM, and Mandrill.

## Packages

Each package has its own repo and individual instructions if needed.

| Package | Description |
| -- | -- |
| [grayl-config](https://github.com/grayl-php/grayl-config) | Imports configuration files into objects for use in classes. |
| [grayl-database-main](https://github.com/grayl-php/grayl-database-main) | Runs SQL queries against a PDO gateway. |
| [grayl-database-query](https://github.com/grayl-php/grayl-database-query) | Builds select, insert, update, and delete queries using objects. Supports where clauses. Converts query objects into SQL statements ready for use in prepared statements. |
| [grayl-date](https://github.com/grayl-php/grayl-date) | Handles date conversions and calculations. |
| [grayl-display-navigation](https://github.com/grayl-php/grayl-display-navigation) | Builds navigations from objects. Tracks breadcrumbs and next/prev references. |
| [grayl-file](https://github.com/grayl-php/grayl-file) | Creates, reads, and writes to file handlers. |
| [grayl-gateway-common](https://github.com/grayl-php/grayl-gateway-common) | Interfaces and abstract classes used in all Grayl gateway classes. |
| [grayl-gateway-mailchimp](https://github.com/grayl-php/grayl-gateway-mailchimp) | Connects to the MailChimp API. Creates mailing lists. Subscribes users to mailing lists. Updates user fields and information. |
| [grayl-gateway-mandrill](https://github.com/grayl-php/grayl-gateway-mandrill) | Connects to the Mandrill API. Populates an email template with fields. Sends the template as a transactional email. |
| [grayl-gateway-minfraud](https://github.com/grayl-php/grayl-gateway-minfraud) | Connects to the MinFraud API. Builds fraud check from user data and payment information. Determines if the payment is high risk. |
| [grayl-gateway-pdo](https://github.com/grayl-php/grayl-gateway-pdo) | Creates a PDO object for MySQL database queries. Executes queries on the database using prepared statements. |
| [grayl-gateway-zendesk](https://github.com/grayl-php/grayl-gateway-zendesk) | Connects to the ZenDesk API. Creates new users. Updates user fields. |
| [grayl-gateway-zohocrm](https://github.com/grayl-php/grayl-gateway-zohocrm) | Connects to the ZohoCRM API. Creates new contacts. Updates contact fields. Creates notes for contacts. |
| [grayl-image-thumbnail](https://github.com/grayl-php/grayl-image-thumbnail) | Generates different thumbnail sizes from an image. |
| [grayl-input-duplicator](https://github.com/grayl-php/grayl-input-duplicator) | Prevents duplicate web form submissions using keys. |
| [grayl-input-floodcheck](https://github.com/grayl-php/grayl-input-floodcheck) | Prevents web form abuse using time checks and keys. |
| [grayl-mixin-common](https://github.com/grayl-php/grayl-mixin-common) | Miscellaneous mixin classes used in other Grayl packages. |
| [grayl-omnipay-common](https://github.com/grayl-php/grayl-omnipay-common) | Interfaces and abstract classes used in all Grayl Omnipay gateway classes. |
| [grayl-omnipay-authorizenet](https://github.com/grayl-php/grayl-omnipay-authorizenet) | Connects to the Authorize.net API. Authorizes direct credit card payments. Captures direct credit card payments. |
| [grayl-omnipay-payflow](https://github.com/grayl-php/grayl-omnipay-payflow) | Connects to the Paypal Payflow API. Authorizes direct credit card payments. Captures direct credit card payments. |
| [grayl-omnipay-paypal](https://github.com/grayl-php/grayl-omnipay-paypal) | Connects to the Paypal API. Creates links for offsite payment. Handles payment cancellations. |
| [grayl-store-order](https://github.com/grayl-php/grayl-store-order) | Creates orders from products and sales. Tracks applied payments and status. |
| [grayl-store-product](https://github.com/grayl-php/grayl-store-product) | Handles products in the store. Calculates features, quantities, and pricing. |
| [grayl-store-sale](https://github.com/grayl-php/grayl-store-sale) | Handles product sales in the store. Calculates sale discounts. |

## Archived packages

| Package | Description |
| -- | -- |
| [grayl-display-content](https://github.com/grayl-php/grayl-display-content) | *Archived*: Reads large blocks of content from files into objects. |
| [grayl-display-template](https://github.com/grayl-php/grayl-display-template) | *Archived*: Parses template files. Swaps placeholders with values. |
| [grayl-input-form](https://github.com/grayl-php/grayl-input-form) | *Archived*: Sanitizes different types of form input. |
| [grayl-utility](https://github.com/grayl-php/grayl-utility) | *Archived*: Miscellaneous utility classes used in other Grayl packages. |

## Written by

[Scott Richardson](https://github.com/scottyrichardson)

## License

MIT
