---
layout: default
title: "&ast;TXT"
description: Quick Notes — Capture Anything, Anywhere
---

# Privacy Policy

**Last Updated: November 1, 2026**

*TXT ("asterisk text") is a notes app that keeps your notes as plain text files in your own storage. It does not require an account and does not collect your personal information on servers operated by the developer. This Privacy Policy explains how information is handled when you use *TXT on iPhone, iPad, Mac, and Apple Watch.

## Information We Collect

*TXT does not require you to create an account and does not collect, transmit, sell, or share your personal information with the developer.

### Your Notes

Your notes are ordinary text files (.txt, containing Markdown) together with their attachments, such as images, PDFs, and voice memos. They are stored in one of two places:

* **iCloud Drive**, when you are signed in to iCloud: in the *TXT folder ("asteriskTXT") in your own iCloud Drive, where they sync to your other devices through Apple's iCloud service.
* **On your device**, when iCloud is not available: in the app's folder, which you can see in the Files app (On My iPhone or iPad) or in Finder on the Mac.

Because they are regular files in your own storage, you can open, copy, move, back up, or delete them with any app, at any time. The developer has no access to them.

*TXT also keeps some information alongside your notes in the same storage, so it is the same on all your devices: the tags you use, your favorites, notes in Recently Deleted, your templates, a list of files that could not be imported, with the reason, and **Recovered Changes** — versions of a note that could not be saved to it (for example, when the note changed on another device at the same time), kept as separate notes so nothing is lost, with the reason each was kept. When a note changes on two devices at once and *TXT combines the two sets of changes, it keeps a copy of both versions for 30 days in a hidden folder in the same storage, so the combined note can be checked or corrected. A copy of each note's attachments and a search index are kept in the app's private storage on each device, and edits made before your library has finished opening are held there briefly (**Pending Changes**) until they are saved to your notes. Each device also keeps, in its private storage, the recent versions of the notes it saved (used to combine edits made on two devices), and previews of your attachments so notes open quickly. These never leave the device.

### Encrypted Notes

You can encrypt any note except your pinned note. Its text and attachments are encrypted on your device before they are saved (with AES-GCM and a 256-bit key of its own for each note), so they can't be read in Files, Finder, iCloud Drive, or any other app. The note's **title** (its first line) and its file name are not encrypted, and stay readable wherever the file is.

* **Your notes key**, which the key for each note is made from, is kept in your device's keychain. When iCloud Keychain is on, Apple syncs it, end-to-end encrypted, to your other devices, so they can open your encrypted notes too.
* **Your notes password** is never stored. A copy of your notes key, locked with your password, is kept in a hidden file in your library, so a device without the key can open encrypted notes once you type the password. The developer cannot see or recover your notes password, and cannot open your encrypted notes.
* **While a note is unlocked**, its text is decrypted only in the app's memory, and its attachments are decrypted into the app's private cache on that device so they can be shown. Those copies are deleted when the note locks. No previews of an encrypted note's attachments are kept.
* **When you encrypt a note**, *TXT deletes its unencrypted attachments from your library (they don't go to Recently Deleted) and the older saved versions of its file. Each of your devices also deletes the recent versions of the note it kept, the next time *TXT there reads your notes. Copies made before the note was encrypted aren't changed: a backup, a copy in another app, a recovered version in **Recovered Changes**, or a combined note's earlier versions (removed after 30 days).
* **Encrypted notes are left out** of Spotlight, widgets, Siri and Shortcuts, and the share sheet's list of notes. Search in *TXT finds them by title only, or not at all if you turn off **Show Titles** in **Settings → Encrypted Notes**.

Turning encryption off saves the note and its attachments unencrypted again.

### Face ID and Touch ID

*TXT can unlock encrypted notes with Face ID, Touch ID, or your device passcode. Apple's operating system handles this: *TXT is told only whether it succeeded, and never receives your face, fingerprint, or passcode data. Optional — turn off **Use Face ID** (or **Use Touch ID**) in **Settings → Encrypted Notes** to use your notes password instead.

### Microphone and Speech Recognition

*TXT asks for access to your microphone for two optional features:

* **Dictation** types what you say into a note. The microphone listens only while you are dictating, and the audio is not saved.
* **Voice memos** record audio that you choose to attach to a note. The recording is saved as an audio file with that note, like any other attachment.

Apple's speech recognition turns your words into text, both for dictation and when you choose **Audio + Transcript** or **Add Transcript Below** for a voice memo. Depending on your device and settings, Apple may process the audio on your device or on Apple's servers; *TXT asks for on-device recognition wherever it is available. Optional — controlled in Settings.

### Camera and Photos

*TXT asks for access to your camera so you can take a photo, scan a document, or scan text straight into a note. Photos from your library are chosen through Apple's photo picker, which shares only the items you select — *TXT cannot browse your library and does not ask for photo library access. Pictures and scans you add are saved as attachments with the note. Optional — controlled in Settings.

### Text Recognition

When you use **Extract Text**, or import a photo or scanned PDF, *TXT reads the text in the image using Apple's Vision framework, on your device. Nothing is sent anywhere for this.

### Importing Files

You can bring in files by choosing them in the app, by placing them in the *TXT folder in Files or Finder, or from other apps. *TXT reads only the files you give it. It keeps an untouched copy of each imported file in the **Originals** folder of your storage, and files it cannot read are moved to the **Not Imported** folder. Importing never fetches anything from the internet: pictures that a web page links to online stay as links.

### Content from Other Apps

When you share text, links, images, or recordings to *TXT from another app's share sheet, *TXT receives only what you share. Until the app adds it to a note, it is held in storage that only *TXT and its extensions can use on that device; it is then saved like any other note.

### Currency Conversions

If a note uses calculations (#calc) and converts between currencies, *TXT downloads the European Central Bank's public daily exchange rates, at most about once a day. The request contains no information about you or your notes, and the rates are kept on your device.

Depending on when you use it, the rates may not be the most up to date. The European Central Bank publishes its reference rates once per working day (not on weekends or its holidays), *TXT checks for new rates only after its copy is about a day old, and when you're offline it uses the last rates it downloaded. Tapping a currency answer shows the date of the rates it used. The rates are for information only and are not suitable for financial transactions. *TXT is not affiliated with or endorsed by the European Central Bank, and cannot guarantee that the rates will be available, complete, or accurate.

### Links and Note Previews

*TXT does not load anything from the internet when you view a note. Web links in a note are opened in your browser only when you tap them, and note previews and exports never fetch remote images or other content.

### Spotlight Search

*TXT adds your notes to Apple's on-device Spotlight index so you can find them from your device's search. Encrypted notes are never added. The index is maintained by the operating system on that device and stays on it. To keep *TXT's notes out of search, turn off *TXT in your device's search settings (on iPhone and iPad, Settings ▸ Apps ▸ *TXT ▸ Search).

### Widgets, Controls, and Siri

Widgets and Control Center controls can show your note titles and the beginning of your notes. To make this possible, *TXT keeps a small summary of your notes in storage shared between the app and its widgets on the same device. This stays on your device and is visible wherever you have chosen to show a widget, including the Lock Screen. Encrypted notes are never included.

Siri and Shortcuts can create, find, and add to notes when you ask them to. Anything Siri or a shortcut passes to *TXT is saved as a note in your storage. They can't find or read encrypted notes, and anything sent to one is saved as a new note instead.

### Apple Watch

Your iPhone sends the Watch your pinned note and the settings it needs, such as your accent color and where new notes go, over their direct connection. Notes you dictate or type on the Watch, and checklist items you tick there, are sent to your iPhone the same way; when your iPhone isn't nearby, watchOS holds them on the Watch until it is. Nothing from the Watch goes through the developer.

### Mac

On the Mac, *TXT can open at login, add an item to the menu bar, and show its window with a keyboard shortcut you choose. These are optional settings stored on your Mac.

### Analytics and Crash Reports

Apple may collect diagnostic, usage, and crash information as part of its operating systems and services, depending on the privacy and analytics settings you have selected on your device. *TXT does not use any third-party analytics, advertising, or tracking service. The developer may receive diagnostic or analytics information made available by Apple to identify problems, improve reliability, and improve the app.

## How We Use Information

Because *TXT does not collect personal information on developer-operated servers, we do not use your personal information for advertising, profiling, or marketing.

Diagnostic and analytics information made available by Apple may be used to diagnose crashes, fix bugs, improve performance, and improve *TXT.

## Data Sharing and Sale

*TXT does not sell your personal information and does not share your notes or other personal information with advertisers, data brokers, or other third parties.

## Data Retention and Deletion

Your notes stay in your storage until you delete them. Deleted notes move to **Recently Deleted** for 30 days so you can restore them, and are then removed automatically. Notes in **Recovered Changes** stay until you delete them or add them back to a note. Copies of the versions behind a combined note are removed automatically after 30 days, and so are the recent versions each device keeps (the oldest go sooner once they take more than 50 MB). Attachment previews on a device are removed when the attachment is deleted, or when they take more than about 150 MB, and the system may also clear them to free space. Imported originals in the **Originals** folder and files in **Not Imported** stay until you delete them yourself. You can also delete any of these files directly in Files or Finder.

Data stored in iCloud Drive can be removed through the controls Apple provides, such as your Apple account's iCloud storage settings. Deleting the app may remove data stored on the device, but does not remove your notes from iCloud Drive.

## Security

*TXT is designed to minimize the collection and transmission of personal information. Your notes are protected by the security of your device and, in iCloud Drive, by Apple's iCloud encryption. If you turn on Advanced Data Protection for your Apple account, iCloud Drive is end-to-end encrypted. Notes you encrypt in *TXT are also encrypted by the app itself (see **Encrypted Notes**). If you forget your notes password and your notes key isn't in your iCloud Keychain, your encrypted notes can't be opened, and the developer can't recover them. No method of electronic storage or transmission can be guaranteed to be completely secure.

## Children's Privacy

*TXT does not collect personal information from children or maintain user accounts or developer-operated databases containing children's personal information.

## Your Privacy Rights

Because *TXT does not maintain a developer-operated database of users' personal information, the developer generally does not possess personal information that can be accessed, corrected, exported, or deleted on a user's behalf — this includes rights described under laws such as the EU/UK General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA). Your notes are files in your own storage, which you can view, export, or delete at any time.

If you have questions about privacy or believe information has been collected by *TXT unexpectedly, you may contact us using the information below.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes to *TXT, applicable laws, or the services the app uses. Any changes will be posted on this page, and the "Last Updated" date at the top of this policy will be revised accordingly.

## Contact Us

If you have questions about this Privacy Policy, contact us at [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com?subject=%2ATXT). Please include **\*TXT** in the subject line, since this address is shared with our other app, Due Something. The email link fills it in for you.
