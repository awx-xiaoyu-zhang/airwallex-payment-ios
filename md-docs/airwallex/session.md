<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/Session",
  "metadataVersion" : "0.1.0",
  "role" : "Class",
  "symbol" : {
    "kind" : "Class",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:@M@Airwallex@objc(cs)Session"
  },
  "title" : "Session"
}
-->

# Session

`Session` is a specialized subclass of `AWXSession`

```
@objc final class Session
```

## Overview

This class provides a unified interface for working with the simplified consent flow,
abstracting away the complexity of different payment scenarios (one-off and recurring payments).
It handles both standard payment intents and recurring payment configurations through a
consistent API, making it easier to implement payment processing in your application.

> SeeAlso: `AWXSession`, `PaymentConsentOptions`

## Initializers

[`init(paymentIntent:countryCode:applePayOptions:autoCapture:autoSaveCardForFuturePayments:billing:hidePaymentConsents:lang:paymentMethods:paymentConsentOptions:requiredBillingContactFields:returnURL:)`](/documentation/airwallex/session/init(paymentintent:countrycode:applepayoptions:autocapture:autosavecardforfuturepayments:billing:hidepaymentconsents:lang:paymentmethods:paymentconsentoptions:requiredbillingcontactfields:returnurl:))

[`init(paymentIntentProvider:countryCode:applePayOptions:autoCapture:autoSaveCardForFuturePayments:billing:hidePaymentConsents:lang:paymentMethods:paymentConsentOptions:requiredBillingContactFields:returnURL:)`](/documentation/airwallex/session/init(paymentintentprovider:countrycode:applepayoptions:autocapture:autosavecardforfuturepayments:billing:hidepaymentconsents:lang:paymentmethods:paymentconsentoptions:requiredbillingcontactfields:returnurl:))

## Instance Properties

[`autoCapture`](/documentation/airwallex/session/autocapture)

[`autoSaveCardForFuturePayments`](/documentation/airwallex/session/autosavecardforfuturepayments)

[`paymentConsentOptions`](/documentation/airwallex/session/paymentconsentoptions)

[`paymentIntent`](/documentation/airwallex/session/paymentintent)

[`paymentIntentProvider`](/documentation/airwallex/session/paymentintentprovider)

## Instance Methods

[`amount()`](/documentation/airwallex/session/amount())

[`currency()`](/documentation/airwallex/session/currency())

[`customerId()`](/documentation/airwallex/session/customerid())

[`paymentIntentId()`](/documentation/airwallex/session/paymentintentid())

[`transactionMode()`](/documentation/airwallex/session/transactionmode())
