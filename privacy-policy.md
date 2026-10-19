---
title: Notori Privacy Policy
permalink: /privacy-policy/
---

# Notori Privacy Policy

Updated 19 October 2026

## Privacy at a glance

Notori is a note-taking app with AI. Your notes are stored on your device and, if you use iCloud, in your own iCloud account; Notori has no user accounts and does not keep your notes on a server of its own. AI is part of the service: to organise your notes and answer your questions, their content is sent to Notori’s server on Cloudflare and to OpenAI. Notori does not sell data, show ads or use advertising trackers, and does not track you across apps or websites.

## 1. Controller and contact

The data controller is the developer of Notori, who publishes the app on the App Store. For any privacy question or request, email [miguelangelxramirez@gmail.com](mailto:miguelangelxramirez@gmail.com) (also the support contact linked from Notori’s App Store page).

## 2. Data stored on your device and in iCloud

Your notes, links, attached photos and files with their recognised text, edits, and derived topics and relationships are stored in Notori’s private app or App Group container. When iCloud is available, Notori syncs this database with your private iCloud (CloudKit) database, so it can appear on your other devices signed in with the same Apple Account. That copy sits in your own iCloud account under Apple’s terms; Notori does not operate an account or a server for it and cannot read it. The local search index, settings, record of your acceptance of the AI notice and its version, widget snapshot and the queue of pending AI jobs stay only on the device and are not synced. To stop syncing, turn off iCloud for Notori in your device’s system iCloud settings; copies already stored in iCloud remain until you delete them there. Apple may also include app data in device backups according to your iCloud or backup settings.

## 3. AI processing

Before using Notori you accept the AI notice once, identified by its version; you are asked again only if that version changes. From then on, Notori sends Notori’s Cloudflare Worker, which forwards to OpenAI, what each task needs: the text of your notes and their attached files; for links, the address, title and text read from the page; your questions and bounded excerpts of the notes relevant to answering them; the app language, the note’s date and time and your time zone, to interpret expressions such as “yesterday”; and random technical identifiers for the note and the request. For photos you save, a resized copy of the image is also sent with its recognised text to describe objects and scenes, not just words. The uploaded copy is generated without the original file metadata; the original photo remains stored on your device. This requires accepting the updated notice even if you previously accepted text processing. The Worker asks OpenAI for store:false, so the response is not stored, and sends it a fingerprint (SHA-256 hash) of the installation identifier as a safety identifier, which OpenAI uses to detect abuse; OpenAI does not receive your name, email address or Apple Account. OpenAI states that by default it does not use API data to train its models and that its abuse-monitoring logs may retain content for up to 30 days, unless the law requires it to keep content longer or this is needed to protect its services or third parties. For some requests (organising notes and building topics), the Worker keeps the result for up to 24 hours, linked to the installation identifier, so an interrupted request can be recovered without repeating it; it is then deleted automatically. Notori does not use OpenAI’s web search: answers are based only on what you send. There is no setting to turn AI off and no local-only mode. If you do not accept this processing, do not use Notori; you can export your notes and delete your data at any time. Do not include information you do not want these providers to process, especially health data or other special categories of data, or other people’s data.

## 4. Reading links

When you save a link, your device downloads that page directly, without cookies, to read its title and text; for TikTok videos it also requests the public preview that TikTok provides. That website receives the request as it would any visit, including your IP address, and handles it under its own policy. The text obtained is stored with the note and processed with AI as described above.

## 5. Service security

Notori creates a persistent random installation identifier, stored in this device’s keychain, and uses Apple App Attest to check that requests come from a genuine copy of the app. With this, the Worker enforces rate, size and daily-use limits and investigates abuse. Cloudflare stores in the European Union (Durable Objects with EU jurisdiction) the App Attest public key and its receipt, linked to a fingerprint of the installation identifier, and usage counters that reset every minute and every day. Cloudflare also processes your IP address to establish the connection and keeps technical request logs (time, path, result and technical identifiers, without the content of your notes) for up to 7 days. The identifier is not used for advertising or cross-app tracking.

## 6. Purchases

Apple processes payment information. RevenueCat receives an anonymous persistent app-user identifier, subscription and purchase status, and the store language and currency, so Notori can offer, restore and manage Premium access and the free trial, analyse purchase reliability and prevent fraud. Notori does not receive your full payment-card details. This data is not used for advertising tracking.

## 7. Purposes and legal bases

- Providing the service you sign up for: storing and syncing your notes, reading your links, organising them and answering your questions with AI, and managing your subscription or free trial. Legal basis: performance of the contract (Art. 6(1)(b) GDPR). Accepting the AI notice is part of accepting that contract; it is not a separate consent.
- Protecting the service: verifying the device, enforcing limits, investigating and preventing abuse and fraud, and analysing purchase reliability. Legal basis: legitimate interest in keeping the service secure and preventing fraudulent use (Art. 6(1)(f) GDPR).
- Complying with legal obligations and responding to requests from authorities. Legal basis: legal obligation (Art. 6(1)(c) GDPR).

Providing this data is a contractual requirement: it is needed to use Notori and, without it, we cannot provide the service. Notori does not make decisions based solely on automated processing that produce legal effects concerning you or similarly significantly affect you (Art. 22 GDPR): AI only organises your notes and answers your questions, and usage limits are technical security controls.

## 8. Recipients and processors

- Cloudflare, Inc. (USA), processor: hosts Notori’s Worker, its EU storage and its technical logs.
- OpenAI, processor: processes the content described above with AI.
- RevenueCat, Inc. (USA), processor: manages subscriptions.
- Apple: processes App Store payments, App Attest verification, iCloud and backups under its own terms and privacy policy. Notori includes no third-party analytics or crash-reporting tools; if you turn on sharing analytics with app developers on your device, Apple may provide the developer with crash and performance reports.
- The websites of the links you save, as explained in section 4.

Notori shares data with them only when needed to provide the service, protect it, comply with law or complete a transaction. Notori does not sell personal data.

## 9. International transfers

Cloudflare, OpenAI and RevenueCat are US companies and may process data outside the European Economic Area. Cloudflare is certified under the EU-U.S. Data Privacy Framework, which is covered by a European Commission adequacy decision (Art. 45 GDPR), and its data processing agreement also includes standard contractual clauses. OpenAI and RevenueCat are not listed under that Framework; their transfers rely on the standard contractual clauses approved by the European Commission and included in their data processing agreements (Art. 46(2)(c) GDPR). You can ask for information about these safeguards at the contact address.

## 10. Retention and deletion

Your notes are kept on your devices and in your iCloud until you delete them. Items moved to Notori’s trash remain on your devices until you restore them or remove the app data. You can permanently delete items from Trash at any time; with iCloud on, that deletion syncs to your private iCloud copy and to your other devices when they are online. “Delete all my data” in Settings deletes your notes and derived data from this device and asks iCloud to delete Notori’s private zone in your iCloud (CloudKit) database, including changes this device has not downloaded yet. It needs a connection and an iCloud account. Notori reports the data as deleted only once that has finished; if it cannot reach iCloud it tells you that only this device was erased, and you can repeat the deletion later. You can export your notes as Markdown from Settings. Exporting and deleting your data also work without a subscription. If iCloud sync is off, these deletions apply only to this device and copies already in iCloud must be deleted in your iCloud storage settings. Because notes sync through iCloud, a change or deletion made on one device is also applied to your other devices. Removing the app and its data removes the local database from that device, but not the copies already synced to iCloud, which may be downloaded again if you reinstall Notori with iCloud on; you can delete them in your iCloud storage settings. Copies may remain in Apple backups until those backups expire or you delete them. On the servers: results the Worker keeps temporarily are deleted automatically within 24 hours at most; Cloudflare’s technical logs within 7 days at most; OpenAI’s abuse-monitoring logs within the period stated in section 3. The App Attest public key and its receipt do not expire automatically: they are kept while they serve to verify that installation and do not contain the content of your notes. RevenueCat keeps the purchase history linked to the anonymous identifier for as long as Notori uses its service, unless its deletion is requested.

## 11. Your rights

You have the right to access, rectify and erase your data, to restrict its processing, to data portability and to object to processing based on legitimate interest (Arts. 15 to 21 GDPR). You can exercise most of them in the app itself: edit or delete notes, export them as Markdown and use “Delete all my data”. For anything else, email [miguelangelxramirez@gmail.com](mailto:miguelangelxramirez@gmail.com); we will reply within one month, extendable in the cases provided for in Art. 12 GDPR. Because Notori has no accounts, server-side data is linked only to random identifiers and we may need additional information to match it to your installation (Art. 11 GDPR). Subscriptions are managed in Apple’s subscription settings. If you believe your data is not being processed properly, you can lodge a complaint with the Spanish Data Protection Agency ([www.aepd.es](https://www.aepd.es)) or with the supervisory authority of your country of residence.

## 12. Children

Notori is not directed at children. Do not use Notori if you are under the minimum age your country’s law requires to accept the processing of your data yourself (14 in Spain).

## 13. Changes to this policy

If this policy changes, the date above will be updated. If the AI notice changes, the app will ask you to accept the new version before sending more content to the AI. This same policy is published at <https://miguelangelxramirez.github.io/Notori-privacy/>.
