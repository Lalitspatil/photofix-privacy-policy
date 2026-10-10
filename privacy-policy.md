# PhotoFix Privacy Policy

**Effective date:** October 10, 2026  
**Developer contact:** lalitspatil1260@gmail.com

PhotoFix is an Android photo-editing app. This Privacy Policy explains how the
app handles information when you use its features.

## What PhotoFix does

PhotoFix lets you select photos and prepare edited copies using tools such as
compression, resizing, cropping, rotation, flipping, format conversion, ID
photo sizing, and batch processing.

## Photos and on-device processing

When you choose photos, PhotoFix reads the selected image files and processes
their image data on your device. PhotoFix's image-processing implementation
does not send selected photos to a PhotoFix-operated server. PhotoFix does not
currently operate its own backend or photo-processing API.

PhotoFix keeps selected and processed image data in app memory while you use
the editing workflow. The app code does not create a persistent PhotoFix
library or account for selected photos. The Android image-picker plugin and
operating system may use temporary resources while selecting media; their
exact behavior can depend on the Android version and picker implementation.

## Saving to your Gallery

If you choose **Save to gallery**, PhotoFix writes the processed image to the
device's public Pictures/Gallery media collection. The saved copy remains on
your device until you or another app remove it. PhotoFix does not currently
provide a separate in-app deletion or retention service for saved Gallery
images; manage those copies using your device's Gallery or file-management
tools.

## Sharing

If you choose **Share**, PhotoFix passes the selected processed image to the
Android sharing interface so that you can choose another app or destination.
On Android, the current sharing plugin stages a share copy in PhotoFix's
app-private cache and clears that share cache when a later share operation is
prepared. Android or the receiving app may also make its own copy.

Sharing is initiated by you. After you send an image to another app or service,
that recipient's privacy practices and handling of the file are outside
PhotoFix's control. Review the recipient's policies before sharing.

## Advertising and consent

PhotoFix includes Google Mobile Ads (AdMob) for advertising and Google's
consent-management functionality (Google User Messaging Platform, or UMP).
Where applicable, UMP may request or present advertising consent choices.
PhotoFix requests ads only when the consent SDK reports that ads may be
requested. Ads may be unavailable because of consent, network availability, or
ad-loading results; photo-editing features do not depend on ad availability.

Google Mobile Ads and UMP are third-party services. Their SDKs and services
may process information under Google's own policies and according to applicable
settings and consent choices. The exact information involved can depend on the
SDK version, Android version, Google configuration, and any later ad setup.
This policy does not make a claim about an exact list of Google data fields.
For more information, review Google's current privacy information, including
Google's Privacy Policy and Google's page on how Google uses information from
sites or apps that use its services.

The app has an in-app **Advertising privacy choices** entry when UMP indicates
that a privacy-options form is required. The app does not show that entry when
the SDK reports it is not required. The app's **Privacy policy** entry opens
this policy at
<https://lalitspatil.github.io/photofix-privacy-policy/privacy-policy.html>
in your device's browser.

## Accounts, analytics, and crash reporting

PhotoFix does not require an account or login. The current app code does not
implement a PhotoFix-owned analytics or crash-reporting service. This statement
does not cover diagnostics or information processing performed by third-party
SDKs, the Android operating system, or other apps you choose to use. Those
services may have their own data practices.

## Data retention and deletion

PhotoFix does not operate a backend for selected-photo processing and does not
retain selected photos in a server account. Selected and processed bytes are
used in the active editing workflow. A user-requested Gallery save creates a
device-visible image that the user can manage on the device.

For Android sharing, the current sharing plugin uses an app-private cache copy
and clears its share cache when it prepares a subsequent share. The app does
not configure a fixed retention period for this cache. The operating system
manages cache storage, and a recipient may retain a shared copy independently.

Because PhotoFix does not currently maintain user accounts or a PhotoFix
photo-processing backend, there is no PhotoFix account-based deletion request
or server photo store to access through the app. To remove a Gallery copy,
delete it using the device's Gallery or file-management app. For privacy
questions, contact the developer at lalitspatil1260@gmail.com.

## Children's privacy

PhotoFix does not ask users to create accounts or submit personal information
to PhotoFix. Third-party advertising services may apply their own age-related
and consent requirements. A parent or guardian with a privacy question can
contact the developer using the contact details in the Contact section below.

## Changes to this policy

This policy may be updated when PhotoFix's features, SDKs, or data practices
change. The effective date at the top of this page indicates when the current
version was published or last updated.

## Contact

For questions about this Privacy Policy or PhotoFix's privacy practices,
contact:

- **Developer:** Lalit Patil
- **Email:** lalitspatil1260@gmail.com
- **Privacy Policy URL:** https://lalitspatil.github.io/photofix-privacy-policy/privacy-policy.html

