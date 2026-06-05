<!--
{
  "availability" : [

  ],
  "documentType" : "symbol",
  "framework" : "Airwallex",
  "identifier" : "/documentation/Airwallex",
  "metadataVersion" : "0.1.0",
  "role" : "Framework",
  "symbol" : {
    "kind" : "Framework",
    "modules" : [
      "Airwallex"
    ],
    "preciseIdentifier" : "Airwallex"
  },
  "title" : "Airwallex"
}
-->

# Airwallex

## Overview

The Airwallex iOS SDK is a flexible tool that enables you to integrate payment methods into your iOS app. It provides native UI screens to facilitate payment functions on top of your existing purchase flow. You can also choose to build your own custom UI using API integration.

- [Installation](https://github.com/airwallex/airwallex-payment-ios?tab=readme-ov-file#installation)
- [Required Setup](https://github.com/airwallex/airwallex-payment-ios?tab=readme-ov-file#required-setup)
- [UI Integration - Hosted Payment Page](https://github.com/airwallex/airwallex-payment-ios?tab=readme-ov-file#ui-integration---hosted-payment-page-hpp)
- [UI Integration - Embedded Element](https://github.com/airwallex/airwallex-payment-ios?tab=readme-ov-file#ui-integration---embedded)
- [API Integration](https://github.com/airwallex/airwallex-payment-ios?tab=readme-ov-file#low-level-api-integration)

## Topics

### Preparation

[`AWXPaymentIntent`](/documentation/Airwallex/AWXPaymentIntent)

`AWXPaymentIntent` includes the information of payment intent.

[`Session`](/documentation/Airwallex/Session)

`Session` is a specialized subclass of `AWXSession`

[`PaymentConsentOptions`](/documentation/Airwallex/PaymentConsentOptions)

Options for payment consents

[`AWXApplePayOptions`](/documentation/Airwallex/AWXApplePayOptions)

Object used to construct PKPaymentRequest for Apple Pay.

[`AWXAPIClientConfiguration`](/documentation/Airwallex/AWXAPIClientConfiguration)

`AWXAPIClientConfiguration` contains the base configuration the API client needs.

### UI Integration - Hosted Payment Page

[`AWXUIContext`](/documentation/Airwallex/AWXUIContext)

The main UI context for Airwallex payment flows.

### UI Integration - Embedded Element

[`AWXPaymentElement`](/documentation/Airwallex/AWXPaymentElement)

An embeddable payment element that can be added to any view hierarchy.

### API Integration

[`PaymentSessionHandler`](/documentation/Airwallex/PaymentSessionHandler)

A low-level API handler for managing Airwallex payment sessions.

[`AWXPaymentConsent`](/documentation/Airwallex/AWXPaymentConsent)

`AWXPaymentConsent` includes the info of payment consent.

### Customization

[`AWXTheme`](/documentation/Airwallex/AWXTheme)

`AWXTheme` manages text styles.

### Payment Result

[`AWXPaymentResultDelegate`](/documentation/Airwallex/AWXPaymentResultDelegate)

## Preparation

[`AWXPaymentIntent`](/documentation/airwallex/awxpaymentintent)

[`Session`](/documentation/airwallex/session)

[`PaymentConsentOptions`](/documentation/airwallex/paymentconsentoptions)

[`AWXApplePayOptions`](/documentation/airwallex/awxapplepayoptions)

[`AWXAPIClientConfiguration`](/documentation/airwallex/awxapiclientconfiguration)

## UI Integration - Hosted Payment Page

[`AWXUIContext`](/documentation/airwallex/awxuicontext)

## UI Integration - Embedded Element

[`AWXPaymentElement`](/documentation/airwallex/awxpaymentelement)

## API Integration

[`PaymentSessionHandler`](/documentation/airwallex/paymentsessionhandler)

[`AWXPaymentConsent`](/documentation/airwallex/awxpaymentconsent)

## Customization

[`AWXTheme`](/documentation/airwallex/awxtheme)

## Payment Result

[`AWXPaymentResultDelegate`](/documentation/airwallex/awxpaymentresultdelegate)

## Classes

[`AWXAPIClient`](/documentation/airwallex/awxapiclient)

[`AWXAPIErrorResponse`](/documentation/airwallex/awxapierrorresponse)

[`AWXAddress`](/documentation/airwallex/awxaddress)

[`AWXApplePayProvider`](/documentation/airwallex/awxapplepayprovider)

[`AWXAuthenticationData`](/documentation/airwallex/awxauthenticationdata)

[`AWXBank`](/documentation/airwallex/awxbank)

[`AWXBrand`](/documentation/airwallex/awxbrand)

[`AWXCandidate`](/documentation/airwallex/awxcandidate)

[`AWXCard`](/documentation/airwallex/awxcard)

[`AWXCardCVCViewController`](/documentation/airwallex/awxcardcvcviewcontroller)

[`AWXCardOptions`](/documentation/airwallex/awxcardoptions)

[`AWXCardProvider`](/documentation/airwallex/awxcardprovider)

[`AWXCardScheme`](/documentation/airwallex/awxcardscheme)

[`AWXCardValidator`](/documentation/airwallex/awxcardvalidator)

[`AWXConfirmPaymentIntentRequest`](/documentation/airwallex/awxconfirmpaymentintentrequest)

[`AWXConfirmPaymentIntentResponse`](/documentation/airwallex/awxconfirmpaymentintentresponse)

[`AWXConfirmPaymentNextAction`](/documentation/airwallex/awxconfirmpaymentnextaction)

[`AWXConfirmThreeDSRequest`](/documentation/airwallex/awxconfirmthreedsrequest)

[`AWXCountry`](/documentation/airwallex/awxcountry)

[`AWXCreatePaymentConsentRequest`](/documentation/airwallex/awxcreatepaymentconsentrequest)

[`AWXCreatePaymentConsentResponse`](/documentation/airwallex/awxcreatepaymentconsentresponse)

[`AWXCreatePaymentMethodRequest`](/documentation/airwallex/awxcreatepaymentmethodrequest)

[`AWXCreatePaymentMethodResponse`](/documentation/airwallex/awxcreatepaymentmethodresponse)

[`AWXDefaultActionProvider`](/documentation/airwallex/awxdefaultactionprovider)

[`AWXDefaultProvider`](/documentation/airwallex/awxdefaultprovider)

[`AWXDevice`](/documentation/airwallex/awxdevice)

[`AWXDisablePaymentConsentRequest`](/documentation/airwallex/awxdisablepaymentconsentrequest)

[`AWXDisablePaymentConsentResponse`](/documentation/airwallex/awxdisablepaymentconsentresponse)

[`AWXField`](/documentation/airwallex/awxfield)

[`AWXFieldValidation`](/documentation/airwallex/awxfieldvalidation)

[`AWXForm`](/documentation/airwallex/awxform)

[`AWXFormMapping`](/documentation/airwallex/awxformmapping)

[`AWXGetAvailableBanksRequest`](/documentation/airwallex/awxgetavailablebanksrequest)

[`AWXGetAvailableBanksResponse`](/documentation/airwallex/awxgetavailablebanksresponse)

[`AWXGetPaResRequest`](/documentation/airwallex/awxgetparesrequest)

[`AWXGetPaResResponse`](/documentation/airwallex/awxgetparesresponse)

[`AWXGetPaymentConsentsRequest`](/documentation/airwallex/awxgetpaymentconsentsrequest)

[`AWXGetPaymentConsentsResponse`](/documentation/airwallex/awxgetpaymentconsentsresponse)

[`AWXGetPaymentIntentResponse`](/documentation/airwallex/awxgetpaymentintentresponse)

[`AWXGetPaymentMethodTypeRequest`](/documentation/airwallex/awxgetpaymentmethodtyperequest)

[`AWXGetPaymentMethodTypeResponse`](/documentation/airwallex/awxgetpaymentmethodtyperesponse)

[`AWXGetPaymentMethodTypesRequest`](/documentation/airwallex/awxgetpaymentmethodtypesrequest)

[`AWXGetPaymentMethodTypesResponse`](/documentation/airwallex/awxgetpaymentmethodtypesresponse)

[`AWXGetPaymentMethodsRequest`](/documentation/airwallex/awxgetpaymentmethodsrequest)

[`AWXGetPaymentMethodsResponse`](/documentation/airwallex/awxgetpaymentmethodsresponse)

[`AWXNextActionHandler`](/documentation/airwallex/awxnextactionhandler)

[`AWXOneOffSession`](/documentation/airwallex/awxoneoffsession)

[`AWXPaymentAttempt`](/documentation/airwallex/awxpaymentattempt)

[`AWXPaymentMethod`](/documentation/airwallex/awxpaymentmethod)

[`AWXPaymentMethodOptions`](/documentation/airwallex/awxpaymentmethodoptions)

[`AWXPaymentMethodType`](/documentation/airwallex/awxpaymentmethodtype)

[`AWXPlaceDetails`](/documentation/airwallex/awxplacedetails)

[`AWXRecurringSession`](/documentation/airwallex/awxrecurringsession)

[`AWXRecurringWithIntentSession`](/documentation/airwallex/awxrecurringwithintentsession)

[`AWXRedirectActionProvider`](/documentation/airwallex/awxredirectactionprovider)

[`AWXRequest`](/documentation/airwallex/awxrequest)

[`AWXResources`](/documentation/airwallex/awxresources)

[`AWXResponse`](/documentation/airwallex/awxresponse)

[`AWXRetrievePaymentConsentRequest`](/documentation/airwallex/awxretrievepaymentconsentrequest)

[`AWXRetrievePaymentIntentRequest`](/documentation/airwallex/awxretrievepaymentintentrequest)

[`AWXSchema`](/documentation/airwallex/awxschema)

[`AWXSession`](/documentation/airwallex/awxsession)

[`AWXShippingViewController`](/documentation/airwallex/awxshippingviewcontroller)

[`AWXThreeDs`](/documentation/airwallex/awxthreeds)

[`AWXVerifyPaymentConsentRequest`](/documentation/airwallex/awxverifypaymentconsentrequest)

[`AWXVerifyPaymentConsentResponse`](/documentation/airwallex/awxverifypaymentconsentresponse)

[`AWXViewController`](/documentation/airwallex/awxviewcontroller)

[`AWXWeChatPayActionProvider`](/documentation/airwallex/awxwechatpayactionprovider)

[`AWXWeChatPaySDKResponse`](/documentation/airwallex/awxwechatpaysdkresponse)

[`Airwallex`](/documentation/airwallex/airwallex)

[`AnalyticsLogger`](/documentation/airwallex/analyticslogger)

[`ImageLoader`](/documentation/airwallex/imageloader)

[`PaymentSchedule`](/documentation/airwallex/paymentschedule)

[`TermsOfUse`](/documentation/airwallex/termsofuse)

## Protocols

[`AWXJSONDecodable`](/documentation/airwallex/awxjsondecodable)

[`AWXJSONEncodable`](/documentation/airwallex/awxjsonencodable)

[`AWXPage`](/documentation/airwallex/awxpage)

[`AWXPageViewTrackable`](/documentation/airwallex/awxpageviewtrackable)

[`AWXPaymentElementDelegate`](/documentation/airwallex/awxpaymentelementdelegate)

[`AWXProviderDelegate`](/documentation/airwallex/awxproviderdelegate)

[`AWXShippingViewControllerDelegate`](/documentation/airwallex/awxshippingviewcontrollerdelegate)

[`ErrorLoggable`](/documentation/airwallex/errorloggable)

[`PaymentIntentProvider`](/documentation/airwallex/paymentintentprovider)

## Structures

[`AWXCardBrand`](/documentation/airwallex/awxcardbrand)

[`AWXHTTPMethod`](/documentation/airwallex/awxhttpmethod)

[`AWXPaymentMethodFlow`](/documentation/airwallex/awxpaymentmethodflow)

[`Palette`](/documentation/airwallex/palette)

[`RequiredBillingContactFields`](/documentation/airwallex/requiredbillingcontactfields)

## Variables

[`AIRWALLEX_API_VERSION`](/documentation/airwallex/airwallex_api_version)

[`AIRWALLEX_VERSION`](/documentation/airwallex/airwallex_version)

[`AWXApplePayKey`](/documentation/airwallex/awxapplepaykey)

[`AWXCardKey`](/documentation/airwallex/awxcardkey)

[`AWXCybsURL`](/documentation/airwallex/awxcybsurl)

[`AWXHTTPMethodGET`](/documentation/airwallex/awxhttpmethodget)

[`AWXHTTPMethodPOST`](/documentation/airwallex/awxhttpmethodpost)

[`AWXPaymentTransactionModeOneOff`](/documentation/airwallex/awxpaymenttransactionmodeoneoff)

[`AWXPaymentTransactionModeRecurring`](/documentation/airwallex/awxpaymenttransactionmoderecurring)

[`AWXSDKErrorDomain`](/documentation/airwallex/awxsdkerrordomain)

[`AWXThreatMatrixFingerprintServer`](/documentation/airwallex/awxthreatmatrixfingerprintserver)

[`AWXThreatMatrixOrganizationID`](/documentation/airwallex/awxthreatmatrixorganizationid)

[`AWXThreeDSCheckEnrollment`](/documentation/airwallex/awxthreedscheckenrollment)

[`AWXThreeDSContinue`](/documentation/airwallex/awxthreedscontinue)

[`AWXThreeDSReturnURL`](/documentation/airwallex/awxthreedsreturnurl)

[`AWXThreeDSValidate`](/documentation/airwallex/awxthreedsvalidate)

[`AWXThreeDSWaitingUserInfoInput`](/documentation/airwallex/awxthreedswaitinguserinfoinput)

[`AWXThreeDSWatingDeviceDataCollection`](/documentation/airwallex/awxthreedswatingdevicedatacollection)

[`AWXWeChatPayKey`](/documentation/airwallex/awxwechatpaykey)

[`AirwallexCoreVersionNumber`](/documentation/airwallex/airwallexcoreversionnumber)

[`AirwallexCoreVersionString`](/documentation/airwallex/airwallexcoreversionstring)

[`AirwallexWeChatPayVersionNumber`](/documentation/airwallex/airwallexwechatpayversionnumber)

[`AirwallexWeChatPayVersionString`](/documentation/airwallex/airwallexwechatpayversionstring)

[`PaymentVersionNumber`](/documentation/airwallex/paymentversionnumber)

[`PaymentVersionString`](/documentation/airwallex/paymentversionstring)

## Functions

[`AWXApplePaySupportedNetworks()`](/documentation/airwallex/awxapplepaysupportednetworks())

[`ClassToHandleFlowForPaymentMethodType(_:)`](/documentation/airwallex/classtohandleflowforpaymentmethodtype(_:))

[`ClassToHandleNextActionForType(_:)`](/documentation/airwallex/classtohandlenextactionfortype(_:))

[`FormatAirwallexSDKMode(_:)`](/documentation/airwallex/formatairwallexsdkmode(_:))

[`FormatMerchantTriggerReason(_:)`](/documentation/airwallex/formatmerchanttriggerreason(_:))

[`FormatNextTriggerByType(_:)`](/documentation/airwallex/formatnexttriggerbytype(_:))

[`GetTextFieldTypeByUIType(_:)`](/documentation/airwallex/gettextfieldtypebyuitype(_:))

## Type Aliases

[`AWXRequestHandler`](/documentation/airwallex/awxrequesthandler)

## Enumerations

[`AWXBrandType`](/documentation/airwallex/awxbrandtype)

[`AWXFormType`](/documentation/airwallex/awxformtype)

[`AWXSDKErrorCode`](/documentation/airwallex/awxsdkerrorcode)

[`AWXTextFieldType`](/documentation/airwallex/awxtextfieldtype)

[`AirwallexMerchantTriggerReason`](/documentation/airwallex/airwallexmerchanttriggerreason)

[`AirwallexNextTriggerByType`](/documentation/airwallex/airwallexnexttriggerbytype)

[`AirwallexPaymentStatus`](/documentation/airwallex/airwallexpaymentstatus)

[`AirwallexSDKMode`](/documentation/airwallex/airwallexsdkmode)

[`PaymentAmountType`](/documentation/airwallex/paymentamounttype)

[`PeriodUnit`](/documentation/airwallex/periodunit)

## Extended Modules

[`CoreGraphics`](/documentation/airwallex/coregraphics)

[`Foundation`](/documentation/airwallex/foundation)

[`ObjectiveC`](/documentation/airwallex/objectivec)

[`PassKit`](/documentation/airwallex/passkit)

[`UIKit`](/documentation/airwallex/uikit)
