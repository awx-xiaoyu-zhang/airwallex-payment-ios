<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/PaymentSessionHandler",
  "metadataVersion" : "0.1.0",
  "role" : "Class",
  "symbol" : {
    "kind" : "Class",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:@M@Airwallex@objc(cs)PaymentSessionHandler"
  },
  "title" : "PaymentSessionHandler"
}
-->

# PaymentSessionHandler

A low-level API handler for managing Airwallex payment sessions.

```
@MainActor class PaymentSessionHandler
```

## Overview

`PaymentSessionHandler` provides direct control over payment processing without pre-built UI components.
It’s designed for developers who want to implement custom payment flows while leveraging Airwallex’s
payment processing capabilities.

## Usage

```swift
let handler = PaymentSessionHandler(
    session: session,
    viewController: self,
    paymentResultDelegate: self
)

// Handle card payment
handler.startCardPayment(
    card: card,
    billing: billing,
    saveCard: true
)

// Handle Apple Pay
handler.startApplePay()
```

This class handles:

- Direct payment method processing
- Payment result callbacks
- Error handling and validation
- Custom payment flow integration

## Initializers

[`init(session:viewController:methodType:)`](/documentation/airwallex/paymentsessionhandler/init(session:viewcontroller:methodtype:))

[`init(session:viewController:paymentResultDelegate:methodType:)`](/documentation/airwallex/paymentsessionhandler/init(session:viewcontroller:paymentresultdelegate:methodtype:))

## Instance Properties

[`showIndicator`](/documentation/airwallex/paymentsessionhandler/showindicator)

## Instance Methods

[`startApplePay()`](/documentation/airwallex/paymentsessionhandler/startapplepay())

[`startCardPayment(with:billing:saveCard:)`](/documentation/airwallex/paymentsessionhandler/startcardpayment(with:billing:savecard:))

[`startConsentPayment(with:)`](/documentation/airwallex/paymentsessionhandler/startconsentpayment(with:))

[`startConsentPayment(withId:)`](/documentation/airwallex/paymentsessionhandler/startconsentpayment(withid:))

[`startConsentPayment(withId:requiresCVC:)`](/documentation/airwallex/paymentsessionhandler/startconsentpayment(withid:requirescvc:))

[`startRedirectPayment(with:additionalInfo:)`](/documentation/airwallex/paymentsessionhandler/startredirectpayment(with:additionalinfo:))

## Type Methods

[`canHandle(methodType:session:)`](/documentation/airwallex/paymentsessionhandler/canhandle(methodtype:session:))

## Default Implementations

[`AWXProviderDelegate Implementations`](/documentation/airwallex/paymentsessionhandler/awxproviderdelegate-implementations)
