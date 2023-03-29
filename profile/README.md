
# Grayl - A PHP E-commerce Framework

Grayl is as a lightweight modular set of packages to handle several e-commerce website tasks. It is an excellent example of my use of fully object oriented programming, interfaces, abstract classes (see the gateway-common package for precise examples), name spaces, and code coverage with unit tests.

It can be installed using the Composer package manager which will also install its dependencies. The highlight is a hand written database Query Builder class that can be used to build SQL queries from objects and classes, and then run them safely using prepared statements to prevent SQl injections. There are also tons of packages that provide API integration with popular services like MailChimp, MinFraud, Paypal and AuthorizeDotNet (for both on-site and off-site credit card processing), ZendDesk, and ZohoCRM. It includes unit tests you can review as well.

## Highlights:

- The [gateway-common](https://github.com/grayl-php/gateway-common) package is a set of interfaces and abstract classes that all the other API based packages in Grayl are built on.
- The [database-query](https://github.com/grayl-php/database-query) package builds SQL queries from objects. So you can assemble a full SELECT statement, or even insert data, using classes and methods. It also sanitizes data and implements prepared statements to protect against things like SQL injections.
- The [omnipay-paypal](https://github.com/grayl-php/omnipay-paypal) library handles connecting to Paypal's APIs to handle processing payments on Paypal's website.
- The [omnipay-authorizenet](https://github.com/grayl-php/omnipay-authorizenet) handles processing actual credit card payments on-site using AuthorizeDotNet as a merchant provider.
- The [gateway-mailchimp](https://github.com/grayl-php/gateway-mailchimp) library uses APIs to create users and mailing lists on your MailChimp service.
    
## Written by

[Scott Richardson](https://github.com/scottyrichardson)

## License

MIT
