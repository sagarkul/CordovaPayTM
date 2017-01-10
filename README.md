# CordovaPayTM

---
title: Whitelist
description: Whitelist external content accessible by your app.
---

This plugin has only been tested in Cordova 3.2 or greater, and its use in previous Cordova versions is not recommended (potential conflict with keyboard customization code present in the core in previous Cordova versions).

If you do use this plugin in an older Cordova version (again, not recommended), you have to make sure the HideKeyboardFormAccessoryBar and KeyboardShrinksView preference values are always false, and only use the API functions to turn things on/off.

This plugin was based on this Apache project and has a compatible API.

Installation

Methods
  staging support
  live support

Supported Platforms

iOS
Android

cordova plugin add https://github.com/isathyam/CordovaPayTM.git --variable GENERATE_URL=<Checksum Generation URL> --variable VERIFY_URL=<Checksum Validation Url> --variable MERCHANT_ID=<MerchantID> --variable INDUSTRY_TYPE_ID=<IndustryType> --variable WEBSITE=<WAPWebsiteName>


Usage
window.plugins.paytm.startPayment(txn_id, customer_id, email, phone, amount, successCallback, failureCallback);

Methods: 
  Staging support will be added in near future
  
  Now supports live payTm service.

It was originally created by samyam-a, and i just updated callback response, staging support(testing).
All credit should goes to samyam-a.

Feel free ask ask questions n even i love new request..


