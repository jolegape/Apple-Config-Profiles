# MacOS Configuration Profiles
------------
A collection of configuration profiles I have used or am currently using in my workplace.

I did not have access to a MacOS server profile configurator. All profiles were hand coded  by referencing the Apple Configuration Profile Reference help articles ([https://developer.apple.com/library/content/featuredarticles/iPhoneConfigurationProfileRef/Introduction/Introduction.html](https://developer.apple.com/library/content/featuredarticles/iPhoneConfigurationProfileRef/Introduction/Introduction.html)), a sample profile created by Apple Configurator for iOS devices and various other samples floating around on the internet.

All profiles have a Payload Removal policy. This prevents the profile from being removed without the password specified in the payload. If you don't need this feature delete the Profile Removal Password payload from the beginning of each file. If you do need it, ensure you change the removal password. These profiles can be signed with a certificate to prevent end users from viewing the raw contents with a text editor.

The following changes will need to be made for all profiles to suit your environment:
- any passwords / SSID's present
- Payload Identifiers, Descriptions, Display Names, Organization (optional)

As with any code on the internet, don't blindly copy and paste / run what you download without reading it first. These profiles work for me, but may not for you. I am not responsible for any side effects of using these profiles, but am more than happy to help where I can.

The following profiles are provided for individual use:
1.  Wireless Configuration ([wifi.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/wifi.mobileconfig "wifi.mobileconfig"))
2.  Desktop Background ([desktop-background.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/desktop-background.mobileconfig "desktop-background.mobileconfig"))
3.  System Preference Panes ([system-preferences.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/system-preferences.mobileconfig "system-preferences.mobileconfig"))
4.  Dock Layout ([dock-layout.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/dock-layout.mobileconfig "dock-layout.mobileconfig"))
5. Login Items ([login-items.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/login-items.mobileconfig "login-items.mobileconfig"))
6. Login Window ([login-window.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/login-window.mobileconfig "login-window.mobileconfig"))
7. Diagnostics ([disable-diagnostics.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/disable-diagnostics.mobileconfig "disable-diagnostics.mobileconfig"))
8. Restrictions ([restrictions.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/restrictions.mobileconfig "restrictions.mobileconfig"))
9. Finder Preferences ([finder.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/finder.mobileconfig "finder.mobileconfig"))
10. Google Chrome & Autoupdate ([google-chrome.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/google-chrome.mobileconfig "google-chrome.mobileconfig"))
11. Siri ([disable-siri.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/disable-siri.mobileconfig "disable-siri.mobileconfig"))
12. GateKeeper ([disable-gatekeeper.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/disable-gatekeeper.mobileconfig "disable-gatekeeper.mobileconfig"))
13. Global Preferences ([global-preferences.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/global-preferences.mobileconfig "global-preferences.mobileconfig"))
14. Setup Assistant ([setup-assistant.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/setup-assistant.mobileconfig "setup-assistant.mobileconfig"))
15. Microsoft Office ([microsoft-office.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/microsoft-office.mobileconfig "microsoft-office.mobileconfig"))
16. VLC ([vlc.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/vlc.mobileconfig "vlc.mobileconfig"))
17. Sibelius ([sibelius.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/sibelius.mobileconfig "sibelius.mobileconfig"))
18. GarageBand ([garageband.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/garageband.mobileconfig "garageband.mobileconfig"))
19. Software Updates ([software-update.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/software-update.mobileconfig "software-update.mobileconfig"))


I have also provided the main profile I use for deployment ([MacOS-Config.mobileconfig](https://github.com/jolegape/Apple-Config-Profiles/blob/master/MacOS/MacOS-Config.mobileconfig "MacOS-Config.mobileconfig")), minus any sensitive information such as passwords.