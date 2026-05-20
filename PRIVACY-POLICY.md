# Privacy Policy – Garden Fleet

_Last updated: 20. Mai 2026_

Garden Fleet is an independent iOS application that helps you manage one or more GARDENA smart system installations across multiple households or properties. We take your privacy seriously: by design, Garden Fleet **does not collect any personal data on its own servers** — in fact, we operate no servers at all.

## What data Garden Fleet uses

Garden Fleet stores and processes the following data **only on your device**:

- **Your Husqvarna Application Key and Application Secret**, entered during onboarding or in Settings. Stored in the iOS Keychain.
- **OAuth tokens** issued by the Husqvarna Authentication API for each GARDENA account you connect. Stored in the iOS Keychain.
- **Account metadata** (display name, color, identifier) and app preferences. Stored in iOS UserDefaults.
- **Optional custom header image** that you may set. Stored in the app's Documents folder.

None of this data is transmitted to any server operated by the developer. All API traffic flows **directly between your device and the official Husqvarna/GARDENA Cloud**.

## What data Garden Fleet does NOT collect

- No analytics, telemetry, or usage statistics
- No crash reporting service
- No advertising or third-party tracking SDKs
- No personal data is sent to the developer
- No advertising identifiers are read

## Third-party services

When you connect a GARDENA account, Garden Fleet communicates with the official **Husqvarna Group Developer API** (`api.authentication.husqvarnagroup.dev` and `api.smart.gardena.dev`). Your GARDENA credentials are never entered into Garden Fleet — login happens via the secure OAuth 2.0 flow against Husqvarna's own login page.

Please refer to the [Husqvarna Group Privacy Statement](https://www.husqvarnagroup.com/en/privacy-notice) for details on how Husqvarna processes data you submit to their service.

## Your rights and how to delete your data

Because Garden Fleet stores nothing outside your device, you have full control:

- **Reset Setup** in Settings → "Zurücksetzen" deletes all stored Application Keys, secrets, OAuth tokens and accounts from your device.
- **Deleting the app** removes all locally stored data.

You may also revoke the access of the Garden Fleet application in your GARDENA account at any time via the [Husqvarna Developer Portal](https://developer.husqvarnagroup.cloud/).

## Children's privacy

Garden Fleet is not directed to children under 13. We do not knowingly collect any data from anyone.

## Changes to this policy

If we update this policy, the new version will be published at the same URL with an updated revision date.

## Contact

For questions about this policy, contact:

**Garden Fleet Team**
**gardenfleet@icloud.com**

---

_Garden Fleet is an independent product and is not affiliated with, endorsed by, or sponsored by Husqvarna AB or the GARDENA brand. "GARDENA" is a trademark of Husqvarna AB._
