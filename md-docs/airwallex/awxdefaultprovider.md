<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex/AWXDefaultProvider",
  "metadataVersion" : "0.1.0",
  "role" : "Class",
  "symbol" : {
    "kind" : "Class",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "c:objc(cs)AWXDefaultProvider"
  },
  "title" : "AWXDefaultProvider"
}
-->

# AWXDefaultProvider

A provider which handles payment business.

```
class AWXDefaultProvider
```

## Initializers

[`init(delegate:session:)`](/documentation/airwallex/awxdefaultprovider/init(delegate:session:))

[`init(delegate:session:paymentMethodType:)`](/documentation/airwallex/awxdefaultprovider/init(delegate:session:paymentmethodtype:))

## Instance Properties

[`delegate`](/documentation/airwallex/awxdefaultprovider/delegate)

[`paymentConsent`](/documentation/airwallex/awxdefaultprovider/paymentconsent)

[`paymentMethod`](/documentation/airwallex/awxdefaultprovider/paymentmethod)

[`paymentMethodType`](/documentation/airwallex/awxdefaultprovider/paymentmethodtype)

[`session`](/documentation/airwallex/awxdefaultprovider/session)

[`showPaymentDirectly`](/documentation/airwallex/awxdefaultprovider/showpaymentdirectly)

## Instance Methods

[`complete(with:error:)`](/documentation/airwallex/awxdefaultprovider/complete(with:error:))

[`confirmPaymentIntent(with:paymentConsent:)`](/documentation/airwallex/awxdefaultprovider/confirmpaymentintent(with:paymentconsent:))

[`confirmPaymentIntent(with:paymentConsent:completion:)`](/documentation/airwallex/awxdefaultprovider/confirmpaymentintent(with:paymentconsent:completion:))

[`confirmPaymentIntent(with:paymentConsent:flow:)`](/documentation/airwallex/awxdefaultprovider/confirmpaymentintent(with:paymentconsent:flow:))

[`createPaymentConsentAndConfirmIntent(with:)`](/documentation/airwallex/awxdefaultprovider/createpaymentconsentandconfirmintent(with:))

[`createPaymentConsentAndConfirmIntent(with:completion:)`](/documentation/airwallex/awxdefaultprovider/createpaymentconsentandconfirmintent(with:completion:))

[`handleFlow()`](/documentation/airwallex/awxdefaultprovider/handleflow())

## Type Methods

[`canHandle(_:paymentMethod:)`](/documentation/airwallex/awxdefaultprovider/canhandle(_:paymentmethod:))
