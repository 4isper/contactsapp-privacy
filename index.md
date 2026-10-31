# Privacy Policy for "Contacts"

**Effective Date:** October 31, 2026

**Developer:** 4isper

## 1\. Overview

"Contacts" (the "App") is an offline contacts manager for Android: it lets you
view, create, and edit the contacts already stored on your device, keep a
favorites list, organize contacts into groups, dial phone numbers, scan a QR
code to add a contact, export and import .vcf cards, receive birthday
reminders, add a birthday to your calendar, and use a home screen widget.

This Privacy Policy explains what data is processed when you use the App and
how it is protected. We follow a minimal-data approach: the App requires no
account, has no backend, and never transmits your data anywhere. Android
release builds are shipped without the `INTERNET` permission, so the App is
technically unable to send any information over the network. The App contains
no advertising SDKs and no analytics.

## 2\. Data We Process and Where It Lives

- **Your device contacts.** The App reads and writes contacts directly in the
  system Contacts Provider — the storage managed by Android and shared with
  your phone, dialer, and other apps. The App does not create or keep its own
  copy of your contacts database: names, numbers, emails, birthdays, photos,
  and other contact details always remain in the storage of your device.
- **Favorites.** Marking a contact as a favorite stores the standard "starred"
  flag in the system Contacts Provider, alongside the contact itself.
- **App settings.** Your preferences — theme, sort order, list density,
  language, reminder schedule, and similar choices — are stored **strictly
  locally** in the App's private storage. We do not transmit, upload, or store
  this data on any external server under our control.
- **App lock.** If you enable app lock, your PIN is stored only as a salted
  PBKDF2 hash, never in plain text. If you enable biometric unlock, your
  fingerprint or face data is handled entirely by the Android system; it never
  reaches the App and is not stored by it.
- The App does not request or store personal information such as your name,
  email address, location, advertising identifiers, or any unique device
  identifiers, and it collects no telemetry.

## 3\. Permissions We Request

Each permission is requested only when it is needed for the feature you are
using, and you can decline without losing the rest of the App:

- **Contacts (read and write)** — to display your contact list and to create,
  edit, and delete contacts at your request. Write access may be requested
  together with read access, so that you are not shown a second prompt the
  first time you edit or favorite a contact.
- **Phone (direct calling)** — so the call button on a contact card can dial
  the number directly. If the permission is declined, the App opens your
  dialer with the number pre-filled instead.
- **Camera** — used only while you are scanning a QR code with a contact. The
  App does not take photos or record video, and camera frames are never stored.
- **Notifications** — to show birthday reminders. Requested only when you turn
  reminders on; if you decline, no reminders are scheduled.
- **Run at startup** — to restore your reminder schedule after the device
  restarts.
- **Biometrics** — to unlock the App with your fingerprint or face, if you
  enable it in settings.

## 4\. Local Notifications

Birthday reminders are scheduled entirely on your device: there is no push
server, no messaging service, and no device token is ever created or sent.
Because a reminder may display a contact's name on your lock screen, keep this
in mind if that information is sensitive to you.

## 5. Data Sharing and Transmission

- The App cannot send your data anywhere: release builds do not include the
  `INTERNET` permission.
- **Exporting a contact.** When you choose to share a contact, the App
  prepares a temporary .vcf file and hands it to the destination app you pick
  (for example, email or messenger). From that moment the receiving app
  handles the data under its own terms — the App itself sends nothing.
- **Importing a contact.** When you open a .vcf file in the App, the file is
  processed locally and the contact is added to your device storage only.
- **Integrations with other apps.** Other apps can open the App to view,
  edit, create, or pick a contact, but only as a result of an action you take
  in that other app. The App never sends contacts to other apps on its own.
- **Handing data to other apps.** When you tap a phone number, an email
  address, or a messenger handle on a contact card, or choose "add to
  calendar" for a birthday, the App opens the corresponding app — your
  dialer, email client, messenger, or calendar — and passes only the details
  you tapped. From that moment the receiving app handles the data under its
  own terms — the App itself sends nothing.
- **Widget.** The home screen widget displays data from your contacts on your
  device's home screen. It is rendered by your launcher locally and is not
  transmitted anywhere.

## 6. System Backups

The App allows Android's system backup, so your App settings (not the contacts
themselves) may be included in your Google account device backup. Your
contacts live in the system Contacts Provider and, if backed up, are handled
by the operating system's own backup mechanisms, which are outside our
control. You can disable backups for the device in your Android settings.

## 7. Data Protection and Your Rights

- **Your contacts.** Because your contacts are stored by your device, you
  retain full control over them. You can view, edit, or delete any contact
  from the App, from your device's Contacts app, or from system Settings. You
  can also revoke the App's contacts permission at any time in system
  settings.
- **App data.** You can erase all App settings and app-lock data at any time
  by clearing the App's storage in your device settings or by uninstalling the
  App.
- **Extra protection on device.** The App offers an optional lock screen (PIN
  or biometrics) and an option to hide its content in the recent apps view.
- **EEA users.** If you are in the European Economic Area, you have the right
  to access, rectify, or erase your personal data and to object to or restrict
  its processing, as well as to lodge a complaint with a supervisory
  authority. Because the App holds no personal data on any server and creates
  no account, these rights are exercised through the controls above. If you
  need anything beyond them, contact us and we will assist.

## 8. Children's Privacy

The App is intended for a general audience and is not specifically directed at
children. It collects no personal information from anyone, children included.
If you believe information about a child has been collected, please contact us
and we will remove it.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be
posted on this page with an updated "Effective Date". We advise you to review
this page periodically.

## 10. Contact Us

If you have any questions about this Privacy Policy, please contact the
developer at: **m4isper@gmail.com**.
