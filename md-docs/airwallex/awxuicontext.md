<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/AWXUIContext",
  "metadataVersion" : "0.1.0",
  "role" : "Class",
  "symbol" : {
    "kind" : "Class",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:@M@Airwallex@objc(cs)AWXUIContext"
  },
  "title" : "AWXUIContext"
}
-->

# AWXUIContext

The main UI context for Airwallex payment flows.

```
@MainActor @objc class AWXUIContext
```

## Overview

`AWXUIContext` provides a high-level interface for launching pre-built payment flows.
It handles the presentation of payment forms, user interactions, and payment processing
with minimal integration effort.

## Usage

```swift
let context = AWXUIContext()
context.launchPayment(
    from: viewController,
    session: session
)
```

## Classes

[`AWXUIContext.Configuration`](/documentation/airwallex/awxuicontext/configuration)

## Type Properties

[`shared`](/documentation/airwallex/awxuicontext/shared)

## Type Methods

[`launchCardPayment(from:session:paymentResultDelegate:supportedBrands:launchStyle:)`](/documentation/airwallex/awxuicontext/launchcardpayment(from:session:paymentresultdelegate:supportedbrands:launchstyle:))

[`launchCardPayment(from:session:supportedBrands:launchStyle:)`](/documentation/airwallex/awxuicontext/launchcardpayment(from:session:supportedbrands:launchstyle:))

[`launchPayment(from:session:configuration:)`](/documentation/airwallex/awxuicontext/launchpayment(from:session:configuration:))

[`launchPayment(from:session:filterBy:launchStyle:layout:)`](/documentation/airwallex/awxuicontext/launchpayment(from:session:filterby:launchstyle:layout:))

[`launchPayment(from:session:paymentResultDelegate:configuration:)`](/documentation/airwallex/awxuicontext/launchpayment(from:session:paymentresultdelegate:configuration:))

[`launchPayment(from:session:paymentResultDelegate:filterBy:launchStyle:layout:)`](/documentation/airwallex/awxuicontext/launchpayment(from:session:paymentresultdelegate:filterby:launchstyle:layout:))

[`launchPayment(name:from:session:paymentResultDelegate:supportedBrands:launchStyle:)`](/documentation/airwallex/awxuicontext/launchpayment(name:from:session:paymentresultdelegate:supportedbrands:launchstyle:))

## Enumerations

[`AWXUIContext.ElementType`](/documentation/airwallex/awxuicontext/elementtype)

[`AWXUIContext.LaunchError`](/documentation/airwallex/awxuicontext/launcherror)

[`AWXUIContext.LaunchStyle`](/documentation/airwallex/awxuicontext/launchstyle)

[`AWXUIContext.PaymentLayout`](/documentation/airwallex/awxuicontext/paymentlayout)
