# cordova-plugin-ios-plist

iOS9 does not allow cleartext HTTP resouce load since its insecure. This plugin allows to configure temporary exceptions to allow cleartext for development purpose. Do not include this plugin for app approval otherwise your app  will be rejected.

Plugin to updates the plist  info file for key NSAppTransportSecurity with dict-key NSAllowsArbitraryLoads
