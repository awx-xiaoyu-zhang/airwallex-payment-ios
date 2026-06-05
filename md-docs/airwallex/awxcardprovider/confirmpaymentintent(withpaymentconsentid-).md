<!--
{
  "availability" : [
    "*: -"
  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/AWXCardProvider/confirmPaymentIntent(withPaymentConsentId:)",
  "metadataVersion" : "0.1.0",
  "role" : "Instance Method",
  "symbol" : {
    "kind" : "Instance Method",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:objc(cs)AWXCardProvider(im)confirmPaymentIntentWithPaymentConsentId:"
  },
  "title" : "confirmPaymentIntent(withPaymentConsentId:)"
}
-->

# confirmPaymentIntent(withPaymentConsentId:)

Confirm the payment intent with payment consent ID.

## Deprecated

Will be removed in next major version release, use AirwallexPayment.CardProvider instead

```
func confirmPaymentIntent(withPaymentConsentId paymentConsentId: String)
```

## Parameters

`paymentConsentId`

ID of the PaymentConsent.