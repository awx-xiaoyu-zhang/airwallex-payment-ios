<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/AWXProviderDelegate",
  "metadataVersion" : "0.1.0",
  "role" : "Protocol",
  "symbol" : {
    "kind" : "Protocol",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:objc(pl)AWXProviderDelegate"
  },
  "title" : "AWXProviderDelegate"
}
-->

# AWXProviderDelegate

A delegate which handles checkout results.

```
@MainActor protocol AWXProviderDelegate : NSObjectProtocol
```

## Instance Methods

[`hostViewController()`](/documentation/airwallex/awxproviderdelegate/hostviewcontroller())

[`provider(_:didCompleteWith:error:)`](/documentation/airwallex/awxproviderdelegate/provider(_:didcompletewith:error:))

[`provider(_:didCompleteWithPaymentConsentId:)`](/documentation/airwallex/awxproviderdelegate/provider(_:didcompletewithpaymentconsentid:))

[`provider(_:didInitializePaymentIntentId:)`](/documentation/airwallex/awxproviderdelegate/provider(_:didinitializepaymentintentid:))

[`provider(_:shouldHandle:)`](/documentation/airwallex/awxproviderdelegate/provider(_:shouldhandle:))

[`provider(_:shouldInsert:)`](/documentation/airwallex/awxproviderdelegate/provider(_:shouldinsert:))

[`provider(_:shouldPresent:forceToDismiss:withAnimation:)`](/documentation/airwallex/awxproviderdelegate/provider(_:shouldpresent:forcetodismiss:withanimation:))

[`providerDidEndRequest(_:)`](/documentation/airwallex/awxproviderdelegate/providerdidendrequest(_:))

[`providerDidStartRequest(_:)`](/documentation/airwallex/awxproviderdelegate/providerdidstartrequest(_:))
