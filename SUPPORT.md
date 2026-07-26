# Whittle Support

Welcome to Whittle support. Most questions are answered below — if yours isn't, [contact us](#contact-us) at the bottom of this page.

## Frequently asked questions

### The AI model download fails or takes very long

The built-in AI assistant needs a one-time download of a language model (approximately **1 GB**).

- Use a **Wi-Fi connection** — the download is large and may stall on weak mobile data.
- Make sure your device has at least **2 GB of free storage** before starting.
- If the download was interrupted, reopen the AI setup screen and start it again.
- Corporate or school networks sometimes block large downloads from huggingface.co; try a different network.

### The built-in AI assistant is slow or unavailable

The assistant runs entirely **on your device** — nothing is sent to the cloud. Performance depends on your hardware:

- Older or low-memory devices generate code noticeably slower. Shorter, more specific prompts finish faster.
- On some devices with very limited memory, the on-device assistant may be unavailable. You can still build apps using the **external assistant workflow** (share your prompt with ChatGPT, Claude, or another chat assistant, then paste the result back into Whittle).
- Closing other heavy apps frees memory and speeds up generation.

### My app preview shows a blank page or an error

Your apps are served by a small server that runs inside Whittle on your device.

1. Close the preview and open the app again from your library.
2. If that doesn't help, fully close Whittle (swipe it away from recent apps) and relaunch it.
3. If one specific app is broken, open it in the editor — a JavaScript error in `app.js` can make a page render blank. The editor highlights syntax problems.

### Reminders / notifications from my app don't fire

- Check that **notifications are allowed** for Whittle in your device's system settings (Settings → Notifications).
- Check that the **reminders capability is enabled** for that specific app inside Whittle's app settings.
- On Android, battery-saver or "app hibernation" settings can delay or block scheduled reminders; exclude Whittle from battery optimization if reminders matter to you.

### I pasted a result from ChatGPT/Claude but nothing was imported

When using an external assistant:

- Copy the **entire response**, including the full code blocks — a partial copy can't be imported.
- Return to Whittle and use the import/paste action on the screen you started from; Whittle reads the result from your clipboard.
- Some devices clear the clipboard after a short time or restrict clipboard access in the background. Paste soon after copying, and make sure Whittle is allowed to read the clipboard when you tap import.

### I reinstalled the app and my apps are gone

Whittle stores everything **only on your device** — there is no account and no cloud backup. Uninstalling the app deletes your apps and their data, and we have no way to recover them. Before uninstalling or switching devices, export or share anything you want to keep.

### Which languages does Whittle support?

The app interface is available in 30 languages and follows your device's language setting. The AI assistants understand prompts in most major languages, though results are generally strongest for English prompts.

## Contact us

Still stuck, found a bug, or have a feature request?

**→ [Report an issue / contact us (Google Form)](https://forms.gle/REPLACE_WITH_YOUR_FORM_ID)**

The form takes about a minute. Please include:

- Your device model and OS version (e.g., "Pixel 8, Android 15" or "iPhone 15, iOS 19"),
- What you were doing when the problem happened,
- What you expected vs. what actually happened,
- A screenshot, if you have one.

Prefer email? Reach us at **arakelyan.movses.1@gmail.com**.

---

See also: [Privacy Policy](PRIVACY_POLICY.md) · [Terms of Use](TERMS_OF_USE.md)
