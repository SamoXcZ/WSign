# WSign

WSign is an app signer that runs on your iPhone or iPad. You import an
.ipa, sign it with your own certificate, and install it. All of it
happens inside the app, so you don't need a Mac, a PC or a cable.

## What it does

- Signs any .ipa with your .p12 and provisioning profile
- Installs the signed app straight from the Sign tab
- Has a file manager that handles big files (multi-GB IPAs are fine):
  unzip, zip, rename, duplicate, share, and edit text and plist files
- Packs a Payload folder back into an IPA
- Injects .dylib, .deb and .framework files. It ships with a built-in
  CydiaSubstrate replacement, so most tweaks load without a jailbreak
- Lets you change the bundle ID, name and version, enable file sharing,
  strip extensions or the Watch app, and set a minimum iOS version
- Stores several certificates, lets you pick a default, and shows when
  each one expires

## How to use it

1. Settings > Add Certificate. Pick your .p12, type the password, and
   choose the matching provisioning profile.
2. Import an .ipa in the Files tab.
3. Tap the .ipa and choose Import to Sign.
4. Check the details, add tweaks if you want, then sign and install.

## Install

WSign is released as an unsigned IPA. Download it from Releases, sign
it with your own certificate, and install it.

## Contact

Updates, bugs or ideas: Telegram @slidecashh, Twitter @SamoXcZ.
