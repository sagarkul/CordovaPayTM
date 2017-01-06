# CordovaPayTM


Installation
Methods
  staging support
  live support


cordova plugin add https://github.com/isathyam/CordovaPayTM.git --variable GENERATE_URL=<Checksum Generation URL> --variable VERIFY_URL=<Checksum Validation Url> --variable MERCHANT_ID=<MerchantID> --variable INDUSTRY_TYPE_ID=<IndustryType> --variable WEBSITE=<WAPWebsiteName>


Usage
window.plugins.paytm.startPayment(txn_id, customer_id, email, phone, amount, successCallback, failureCallback);


It ws originally created by samyam-a, and i just updated callback response, staging support(testing).
All credit should goes to samyam-a.

Feel free ask ask questions n even i love new request..


