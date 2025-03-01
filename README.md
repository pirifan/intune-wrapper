# iOS Microsoft Intune Wrapper
This repository is a selective mirror of the following Microsoft Intune Github repositories:

- https://github.com/AzureAD/microsoft-authentication-library-for-objc
- https://github.com/msintuneappsdk/ms-intune-app-sdk-ios
  
The purpose of this repository is to store the XCFrameworks that we (AlphaSense) need to integrate with and have them available as downloadable zip archives so that we can use them as a .binaryTarget() in a Swift Package. See the downloads folder for available versions.

Please observe that we will remove zip archives in the downloads folder on a case-by-case basis and that you shouldn't rely on this repository for your applications. Hopefully Microsoft will update their ms-intune-app-sdk-ios repository to provide zip archives for their respective relases in the future. That update will make this repository deprecated and no longer necessary.
