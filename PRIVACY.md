# Privacy Policy — Asghans Live Status

*Last updated: October 2026*

This extension does not collect, store, sell or share any personal data.

**What the extension does.** Every few minutes, it asks a small server we operate (a Cloudflare Worker) whether the Twitch channel "asghans" is live. The request contains no identifier, account, cookie or browsing data. The server answers with public information only: live status, stream title, game, viewer count and the channel's profile picture.

**Our server.** The server only queries the official Twitch API (Helix) for that single channel. It does not log or store requests. Like any website, the hosting provider (Cloudflare) technically processes the IP address in order to deliver the response; see [Cloudflare's privacy policy](https://www.cloudflare.com/privacypolicy/).

**Local storage.** The extension stores the last known live status and stream details (title, category, viewer count, start time), the time of the last check, the channel's avatar URL and your theme choice in your browser's local extension storage. This data never leaves your device and is removed when you uninstall the extension.

**Permissions.** `alarms` (periodic check), `notifications` (live alert), `storage` (local state), and access to our server's domain only.

**No tracking.** No analytics, no advertising, no cookies, no third-party scripts.

Contact: open an issue on the [privacy policy repository](https://github.com/Sokenzane/Asghans-Live-Tracker-Privacy-Markdown/issues), or reach @Sokenzane.
