# Xamarin.iOS.Intercom.V6
Xamarin package of Intercom V 6.1 for iOS

This package pulls in the "Intercom.framework" directory for Intercom from the following repo:
https://github.com/intercom/intercom-ios

This solution has a single project with the Intercom.framework added as a Native Reference.

There is also a nuget commandline to create a nuget package.  The nuget package is published in a public repo under "xamarin.iOS.V6" (xamarin.intercom was already taken).

*Note, to compile download the repo for Intercom, then copy over the Intercom.framework directory.  Then in the Xamarin.iOS.Intercom project set the Native References to the Intercom.framework folder.