# iOS Configuration Profiles
------------
A collection of configuration profiles I have used or am currently using in my workplace.

I did not have access to a MacOS server profile configurator. All profiles were hand coded  by referencing the Apple Configuration Profile Reference help articles ([https://developer.apple.com/library/content/featuredarticles/iPhoneConfigurationProfileRef/Introduction/Introduction.html](https://developer.apple.com/library/content/featuredarticles/iPhoneConfigurationProfileRef/Introduction/Introduction.html)), a sample profile created by Apple Configurator for iOS devices and various other samples floating around on the internet.

All profiles have a Payload Removal policy. This causes the profile to require a password to be removed. If you don't need this feature delete the Profile Removal Password block from the beginning of the file. If you do need it, ensure you change the removal password. These profiles can be signed with a certificate to prevent end users from viewing the raw contents with a text editor.

The following changes will need to be made for all profiles to suit your environment:
- any passwords / SSID's present
- Payload Identifiers, Descriptions, Display Names, Organization (optional)

As with any code on the internet, don't blindly copy and paste / run what you download without reading it first. These profiles work for me, but may not for you. I am not responsible for any side effects of using these profiles, but am more than happy to help where I can.

The following profiles are provided for individual use:
1. Google Exchange Account ([google-exchange.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/iOS/google-exchange.mobileconfig "google-exchange.mobileconfig"))
2. Wireless Settings ([wifi.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/iOS/wifi.mobileconfig "wifi.mobileconfig"))