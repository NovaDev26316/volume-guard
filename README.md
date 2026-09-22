# Volume Guard

Volume Guard is a Chrome extension that normalizes and controls the audio of the current browser tab using the Web Audio API.

This is the official public support and documentation repository for Volume Guard. **The proprietary source code of the Volume Guard extension is not published in this repository.**

## About Volume Guard

When you enable Volume Guard, it captures the active tab's audio and processes it locally in your browser. It can make loud audio quieter and quiet audio louder without changing the audio of other tabs.

Captured tab audio is used only for real-time processing. It is not recorded, saved, uploaded, sold, or shared.

## Features

- Active-tab audio normalization with local browser processing.
- Global and per-site controls for tailoring behavior across websites.
- Free controls for normalization, output volume, site exclusions, diagnostics, and Korean / English UI.
- Pro Advanced Mixer with Mixer Master, HPF / LPF, 4-band EQ, Compressor, Gate / Expander, Limiter, Reverb, Delay, metering, reset controls, and a real-time EQ response graph.

## Links

- [Install Volume Guard from the Chrome Web Store](https://chromewebstore.google.com/detail/volume-guard/jphlbijdgpcjanmdjacfhlhidgcbogah)
- [Privacy Policy](./volume_guard_privacy_policy.html)
- [Changelog](./CHANGELOG.md)
- [Security Policy](./SECURITY.md)
- [Issues](https://github.com/NovaDev26316/volume-guard/issues)
- [Releases](https://github.com/NovaDev26316/volume-guard/releases)

## Reporting Bugs and Support

The primary support path is the in-app report form. Open the extension's **Diagnostics** tab, choose **Report problem**, review the category, title, description, optional reproduction steps, and diagnostics preview, then press **Submit report**.

Volume Guard does not automatically send bug reports, usage data, or diagnostics. A report is sent only after you explicitly submit it. You may submit anonymously or, when a valid sign-in session is available, associate the report with your account.

The form can optionally include a strict support-safe diagnostics set: extension and manifest version, browser summary and language, UI language, active state, current gain, input level, output volume, normalization strength, Night Mode state, scope, and plan. The current site hostname is a separate opt-in. Raw audio, full URLs, page titles, saved-site lists, credentials, tokens, payment identifiers, and arbitrary extension storage are not included.

If the in-app service is unavailable:

1. Use **Copy diagnostics** in the extension popup or support page and review the content.
2. Open the [issue form](https://github.com/NovaDev26316/volume-guard/issues/new/choose), describe the problem, and paste the diagnostics if they are relevant.
3. Review everything you plan to submit and remove private or sensitive information.

GitHub Issues are a public fallback. Do not post personal information, private browsing details, credentials, OTPs, tokens, payment information, or account identifiers. Do not report security vulnerabilities through GitHub; follow [SECURITY.md](./SECURITY.md).

## Permissions

Volume Guard uses these Chrome extension permissions:

| Permission | Purpose |
| --- | --- |
| `tabCapture` | Captures the audio of the active tab for local processing. |
| `offscreen` | Runs Web Audio processing in an offscreen document. |
| `activeTab` | Identifies the active tab when the user invokes the extension. |
| `storage` | Stores presets, output volume, site exclusions, language settings, and related preferences locally. |

## Privacy

Volume Guard processes active-tab audio locally in the browser. It does not record, save, upload, sell, or share captured audio. Extension preferences may be stored locally in Chrome's extension storage.

See the [Privacy Policy](./volume_guard_privacy_policy.html) for full details and the [`privacy-policies`](./privacy-policies/) directory for version-specific historical policies.

## Release Notes

Public changes are documented in the [Changelog](./CHANGELOG.md). Published packages and release notes may also be available on the [Releases](https://github.com/NovaDev26316/volume-guard/releases) page.

## Feedback

Suggestions and general feedback are welcome through the in-app **Feature request** or **General feedback** categories. GitHub's [Feature Request or General Feedback form](https://github.com/NovaDev26316/volume-guard/issues/new/choose) remains available as the public fallback.

## Security

Do not report security vulnerabilities through public GitHub Issues. Follow the private reporting instructions in [SECURITY.md](./SECURITY.md).

## About This Repository

This repository is limited to public-facing material for:

- user support;
- bug reports;
- feature requests and feedback;
- release notes and changelog history;
- privacy and security policies; and
- other public documentation.

It does not contain the proprietary extension source code, and no open-source license is granted or implied.
