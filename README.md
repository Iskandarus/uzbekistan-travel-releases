# Uzbekistan Travel releases

Builds of Uzbekistan Travel, an offline-first travel guide to Uzbekistan. The source code lives in a private repository; this one carries nothing but the binaries and the notes that go with them.

Every release is one version built for Android and iOS, so a file is only ever missing if that build failed.

**[Latest release](../../releases/latest)**

## Which file

| Platform | File |
| --- | --- |
| Android | `UzbekistanTravel-<version>-arm64-v8a.apk`, or `-android.apk` when unsure which ABI |
| iPhone / iPad | `UzbekistanTravel-<version>-ios-unsigned.ipa` |

## What each platform asks of you

**Android.** The APKs are signed with the project's own release key, not the Play Store's. Installing one means allowing installs from unknown sources once.

**iPhone / iPad.** The .ipa is unsigned, which is as far as a build without a paid Apple Developer account can go. Install it with AltStore or Sideloadly, which sign it with your own Apple ID on the way in. An app signed that way stops launching after seven days and has to be re-signed.
