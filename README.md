How to publish an app
============

# Common requirements

* logotype
* tagline
* AppStore and Google Play description; [AppStore previewer](http://bjango.com/articles/appstoredescriptionpreviewer/)
* AppStore (100 characters max) and Google Play keywords
* screenshots for AppStore (iPhone 3.5in Retina, iPhone 4in Retina, iPad Retina) and Google Play (smartphone, tablet)
* __icons__
  - AppStore [guides](https://developer.apple.com/library/ios/documentation/userexperience/conceptual/mobilehig/IconMatrix.html)
    - 29x29, 29x29@2x
    - 40x40, 40x40@2x
    - 50x50, 50x50@2x
    - 57x57, 57x57@2x
    - 60x60, 60x60@2x
    - 72x72, 72x72@2x
    - 76x76, 76x76@2x
    - 512x512, 512x512@2x (Artwork)
  - Google Play [guides](https://support.google.com/googleplay/android-developer/answer/1078870?hl=en)
    - 36x36
    - 48x48
    - 72x72
    - 96x96
    - 512x512 (ArtWork)
    - 1024x512 (optional, for recommendations)
    - 180х120 (optional, for ads)
* (optional) splash screens


# iOS

* __Apple Developer account__
* iOS Dev Center
  * create developer certificate
  * create an app (App ID)
  * create provisioning profile (for distribution in AppStore) for an App ID
* [iTunes Connect](https://itunesconnect.apple.com/)
  * create an app and fill in description, screenshots, etc
  * prepare for binary (Xcode archive) upload
* Xcode
  * add icons and (optional) splash screens
  * check deployment targets, devices, app version (numbers and dots only)
  * select provisioning profile (for distribution in AppStore) and code signing identity
  * Scheme: iOS Device
  * Product > Archive
  * Organizer > [app] > [archive] > Distribute
