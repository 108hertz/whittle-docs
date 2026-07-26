# Privacy Policy — Whittle: AI App Maker

**Effective date:** July 26, 2026

Whittle ("the app", "we") is designed around a simple principle: **your data stays on your device.** Whittle has no user accounts, no analytics, no advertising, and no backend servers operated by us.

## What we collect

**Nothing.** We do not collect, store, transmit, or sell any personal data. There is no sign-up, no login, and no telemetry.

## Where your data lives

Everything you create in Whittle — the apps you build, their code (HTML, CSS, JavaScript), any data those apps save, and your settings — is stored **locally on your device** in the app's private storage. We never see it.

Because your data lives only on your device:

- Deleting the app deletes your apps and their data.
- We cannot recover your data for you, because we never had it.
- To move your work to another device, export or share it yourself.

## Network access

Whittle uses your device's network connection for exactly two purposes:

1. **Downloading the on-device AI model (optional).** If you enable the built-in AI assistant, the app downloads a language model file (approximately 1 GB) directly from [Hugging Face](https://huggingface.co). This is a plain file download; no personal data is sent. Hugging Face's own [privacy policy](https://huggingface.co/privacy) applies to that connection, as it would to any download.
2. **A local-only preview server.** The apps you build are served to the app's built-in viewer from a server that runs *inside the app on your device* (localhost). It is not reachable from the internet and sends nothing anywhere.

Once the AI model is downloaded, the built-in assistant runs **entirely on your device, offline**. Your prompts and your code are never sent to us or to any cloud AI service by the built-in assistant.

## Using external AI assistants (optional)

Whittle can hand off an app-building prompt to a third-party AI chat assistant of your choice (for example ChatGPT, Claude, or Gemini) and let you paste the result back. If you choose this workflow:

- The prompt and any code you share are sent to that third-party service **by you, through their app or website**, under **their** terms of service and privacy policy.
- We do not operate, control, or receive anything from those services.

If you prefer to keep everything on-device, use the built-in assistant instead.

## Notifications

Apps you build in Whittle can schedule **local reminders/notifications** on your device, only if you grant the notification permission. These are scheduled and delivered by your device's operating system — no push-notification servers are involved, and nothing leaves your device. You can revoke the permission at any time in system settings.

## Children's privacy

Whittle does not collect personal data from anyone, including children. The apps you build and the AI content you generate stay on your device.

## Third-party services summary

| Service | When it's used | What it receives |
|---|---|---|
| Hugging Face | Only if you download the on-device AI model | A standard file-download request (no personal data from us) |
| External AI assistants (ChatGPT, Claude, etc.) | Only if you choose the external-assistant workflow | Whatever you yourself paste or share with them |
| App stores (Google Play / Apple App Store) | Installing and updating the app | Governed by Google's / Apple's own policies |

## Changes to this policy

If Whittle's behavior ever changes in a way that affects your privacy (for example, if a future version adds a cloud feature), we will update this policy and change the effective date above before the change ships.

## Contact

Questions about this policy: **arakelyan.movses.1@gmail.com**

Or open an issue via our [Support page](SUPPORT.md).
