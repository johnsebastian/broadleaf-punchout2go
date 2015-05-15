blc-braintree
=============

Broadleaf Commerces offers an out-of-the-box Braintree solution that requires little configuration and is easily set up.
This solution implements the Transparent Redirect model offered by the Braintree API.

For instruction on how to integrate this module into your Broadleaf project, please follow our integration guide here: http://docs.broadleafcommerce.org/current/Braintree-Module.html

## Useful Links and Resources:

- https://www.braintreepayments.com/docs/java
- https://github.com/braintree/braintree_java
- https://github.com/braintree/braintree_java_examples
- Customer Support: 1 (877) 434-2894


### Example Response
For convenience, here are some example responses from the Gateway

Server to Server Authorization Request
```text
{"addOns":[],"amount":11.99,"avsPostalCodeResponseCode":"I","avsStreetAddressResponseCode":"I","billingAddress":{},"createdAt":{"year":2014,"month":5,"dayOfMonth":6,"hourOfDay":19,"minute":47,"second":25},"creditCard":{"bin":"411111","cardholderName":"Joe Test","cardType":"Visa","customerLocation":"US","expirationMonth":"04","expirationYear":"2016","isDefault":false,"isVenmoSdk":false,"isExpired":false,"imageUrl":"https://assets.braintreegateway.com/payment_method_logo/visa.png?environment\u003dsandbox\u0026merchant_id\u003dztwzspcp27xsrh8y","last4":"1111","commercial":"Unknown","debit":"Unknown","durbinRegulated":"Unknown","healthcare":"Unknown","payroll":"Unknown","prepaid":"Unknown","countryOfIssuance":"Unknown","issuingBank":"Unknown","subscriptions":[]},"currencyIsoCode":"USD","customer":{"customFields":{},"creditCards":[],"addresses":[]},"customFields":{},"cvvResponseCode":"I","disbursementDetails":{"fundsHeld":false},"descriptor":{},"discounts":[],"id":"8xn54g","merchantAccountId":"BroadleafCommerce","processorAuthorizationCode":"ZJ1Z5H","processorResponseCode":"1000","processorResponseText":"Approved","recurring":false,"refundIds":[],"shippingAddress":{},"status":"SUBMITTED_FOR_SETTLEMENT","statusHistory":[{"amount":11.99,"status":"AUTHORIZED","timestamp":{"year":2014,"month":5,"dayOfMonth":6,"hourOfDay":19,"minute":47,"second":26},"source":"API","user":"elbertbautista"},{"amount":11.99,"status":"SUBMITTED_FOR_SETTLEMENT","timestamp":{"year":2014,"month":5,"dayOfMonth":6,"hourOfDay":19,"minute":47,"second":26},"source":"API","user":"elbertbautista"}],"subscription":{"addOns":[],"discounts":[],"hasTrialPeriod":false,"neverExpires":false,"transactions":[]},"taxExempt":false,"type":"SALE","updatedAt":{"year":2014,"month":5,"dayOfMonth":6,"hourOfDay":19,"minute":47,"second":26}}
```
