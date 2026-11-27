# AI Portal — update feed

Built app-layer artifacts only (no source, no AI models). The AI Portal
app checks `latest.json` here at boot and on the update button.

An update zip carries `resources/app.asar` + `resources/backend/` —
roughly 35 MB — and applies to every distribution (small portable, FULL
bundle). Source installs pull the private production repo instead.
