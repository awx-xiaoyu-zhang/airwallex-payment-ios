<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/AWXPaymentElementDelegate",
  "metadataVersion" : "0.1.0",
  "role" : "Protocol",
  "symbol" : {
    "kind" : "Protocol",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:@M@Airwallex@objc(pl)AWXPaymentElementDelegate"
  },
  "title" : "AWXPaymentElementDelegate"
}
-->

# AWXPaymentElementDelegate

Delegate protocol for receiving payment events from AWXPaymentElement.

```
@MainActor @objc protocol AWXPaymentElementDelegate
```

## Overview

This delegate replaces `AWXPaymentResultDelegate` for AWXPaymentElement,
providing payment lifecycle notifications with method information.

## Instance Methods

[`paymentElement(_:didCompleteFor:with:error:)`](/documentation/airwallex/awxpaymentelementdelegate/paymentelement(_:didcompletefor:with:error:))

[`paymentElement(_:didCompleteFor:withPaymentConsentId:)`](/documentation/airwallex/awxpaymentelementdelegate/paymentelement(_:didcompletefor:withpaymentconsentid:))

[`paymentElement(_:onProcessingStateChangedFor:isProcessing:)`](/documentation/airwallex/awxpaymentelementdelegate/paymentelement(_:onprocessingstatechangedfor:isprocessing:))

[`paymentElement(_:validationFailedFor:invalidInputView:)`](/documentation/airwallex/awxpaymentelementdelegate/paymentelement(_:validationfailedfor:invalidinputview:))
