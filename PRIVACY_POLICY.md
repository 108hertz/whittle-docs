# Privacy Policy

**Effective date:** July 30, 2026

Whittle ("the app", "we") is built around a simple principle: **your work stays on your device.** There are no accounts, no cloud sync, and no servers of ours that ever see the apps you build.

To keep the app working we do collect a small amount of **anonymous usage and crash data**. This policy explains exactly what that is, what it is not, and who receives it.

## The short version

| | |
|---|---|
| **Your apps, their code and their data** | Stay on your device. We never receive them. |
| **Anonymous usage & crash data** | Collected via Google Firebase, so we can see which screens are used and fix crashes. |
| **Accounts, names, email, contacts, location, ads** | Not collected. No advertising, no data selling, no user profiling. |

## What stays on your device

Everything you create in Whittle — the apps you build or import, their code (HTML, CSS, JavaScript), any data those apps save, your library, and your settings — is stored **locally, in the app's private storage**. We never see it, and it is never uploaded.

Because your work lives only on your device:

- Deleting the app deletes your apps and their data.
- We cannot recover your data for you, because we never had it.
- To move your work to another device, export or share it yourself.

The apps you install are served to Whittle's built-in viewer by a **local-only preview server running inside the app** (`127.0.0.1`). It is not reachable from the internet and sends nothing anywhere.

## What we collect

### Usage analytics (Google Analytics for Firebase)

Whittle uses Google Analytics for Firebase to understand how the app is used in aggregate — which screens people reach, and whether a release broke something. It is tied to a randomly generated **app instance ID**, not to you.

What is recorded:

- **Screen views** — the name of the screen you navigate to (for example "Library", "Create", "Settings"). Screen names only; never the contents of your apps.
- **Notification events** — when a campaign notification from us is received or opened, together with the in-app destination it points at.
- **Standard Firebase events** — first open, app updates, session starts and session length.
- **Device and app context** collected automatically by the Firebase SDK — device model, operating system version, app version, language, and an approximate country or region derived from your IP address.

We do **not** set any custom user properties, and we do not collect an advertising identifier. Whittle does not ask for App Tracking Transparency permission on iOS, does not track you across other apps or websites, and shows no ads.

### Crash reports (Firebase Crashlytics)

When Whittle crashes or hits an internal error, Crashlytics files a report so we can fix it. A report contains the stack trace, the app and OS version, device state at the time of the crash, a randomly generated Crashlytics installation ID, and Whittle's own recent warning and error log lines as breadcrumbs.

Those breadcrumbs are diagnostic messages written by Whittle, not your content. They can, however, mention the internal identifier or storage path of an app you installed, or repeat an error message produced by that app's own JavaScript. We never upload the code of the apps you build, the data they store, or the prompts you write.

### Push notifications (Firebase Cloud Messaging)

If you allow notifications, your device registers with Firebase Cloud Messaging and receives a **registration token** from Google, so we can send occasional announcements about the app. The token identifies a device installation, not a person; we do not upload it to any server of ours, and we do not build audiences from it. Campaign notifications are sent to everyone (or to a broad segment), never to an individual.

Notifications that **apps you build** schedule are a separate thing: those are local reminders delivered by your device's own operating system. No servers are involved and nothing leaves your device. You can revoke the notification permission at any time in system settings.

### Turning it off

There is currently no in-app switch to disable analytics or crash reporting. Uninstalling Whittle stops all of it. If you would like data associated with your installation deleted, [contact us](#contact) — see [Your rights](#your-rights) below for what we can and cannot do with pseudonymous data.

## What we never collect

- No name, email address, phone number, or account of any kind — there is no sign-up.
- No precise location, contacts, photos, calendar, or microphone data.
- No contents of the apps you build, the prompts you write, or the data your apps store.
- No advertising ID, no cross-app or cross-site tracking, no ad networks.
- We do not sell or share personal information, and we do not use your data to train AI models.

## Other services, and when they are used

### AI assistants you choose

Whittle can hand an app-building prompt to a third-party AI chat assistant you already have (for example ChatGPT, Claude, Gemini, Perplexity, Copilot or Poe) and let you paste the result back. If you use this workflow, the prompt and any code you share are sent to that service **by you, through their app**, under **their** terms and privacy policy. We do not operate, control, or receive anything from them.

### Feedback form

"Send feedback" opens a Google Form in your browser. Whatever you type there — including any contact details you choose to give — is submitted to us through Google Forms and governed by Google's privacy policy. Please don't include passwords or API keys.

### Apps you install

An app you build or import runs in a sandboxed web view and can make its own network requests if its code does so. Whittle does not monitor, proxy, or log that traffic — but it also cannot vouch for it. Review code from an AI or a third party before installing it.

### Summary

| Service | When it's used | What it receives |
|---|---|---|
| Google Analytics for Firebase | Always, while the app runs | Anonymous usage events, device/app context, approximate region from IP |
| Firebase Crashlytics | On a crash or internal error | Stack trace, device state, app log breadcrumbs, installation ID |
| Firebase Cloud Messaging | If you allow notifications | A device registration token |
| Google Forms | Only if you send feedback | Whatever you write in the form |
| External AI assistants | Only if you use the AI workflow | Whatever you yourself share with them |
| Google Play / Apple App Store | Installing and updating the app | Governed by Google's and Apple's own policies |

## Where the data goes, and for how long

Analytics and crash data are processed by **Google LLC** as our service provider, on Google's infrastructure, which may include servers outside your country. Google's handling is described in the [Firebase privacy documentation](https://firebase.google.com/support/privacy) and [Google's privacy policy](https://policies.google.com/privacy).

- Analytics data is retained for the period set on our Firebase project, following Google's default retention for app-instance data.
- Crash reports are retained by Crashlytics for approximately 90 days.
- Aggregated, non-identifying statistics may be kept longer.

If you are in the EEA or the UK, our legal basis for collecting anonymous usage and crash data is our **legitimate interest** in keeping Whittle stable and improving it (Art. 6(1)(f) GDPR).

## Your rights

Depending on where you live, you may have the right to access, correct, delete, or object to the processing of your personal data, and to lodge a complaint with your data-protection authority.

Please note that everything described above is **pseudonymous**: it is tied to a random installation identifier, and we have no way to connect it to you as a person, so we usually cannot locate "your" records from an email address alone. If you contact us with the details of your installation we will do what we can, and you can always stop all collection by uninstalling the app.

## Children's privacy

Whittle is not directed at children under 13 (or the equivalent minimum age where you live), and we do not knowingly collect personal data from them. If you believe a child has provided us with personal data, contact us and we will delete what we can.

## Changes to this policy

If Whittle's data practices change, we will update this policy and its effective date before the change ships. Material changes will also be noted in the app's release notes.

## Contact

Questions about this policy, or a privacy request: **1008hertz@gmail.com**, or via our [Support page](SUPPORT.html).
