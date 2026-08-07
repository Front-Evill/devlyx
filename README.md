# Webhook Hunter
- **Start** — Starts or stops live scanning.
- **Protection** — Enables the firewall that blocks webhook requests before they are sent.
- **Aggressive Mode** — Blocks every outgoing request except trusted Roblox domains.
- **Auto Copy** — Automatically copies detected webhooks to the clipboard.
- **Auto-Fill Webhook Tab** — Automatically fills the last detected webhook into the Webhook tab.
- **Rescan GUI** — Scans all existing GUI elements again.
- **Clear** — Clears the detected webhook list.
---
- **Run Diagnostics** — Prints executor compatibility and hook information to the console.
- **Run Test** — Sends a safe test request to verify that the protection detects and blocks webhook requests.
---
- **Webhook URL** — Input field for a webhook URL.
- **Message** — Input field for the message content.
- **Load Last Caught** — Loads the most recently detected webhook.
- **Send** — Sends a message to the selected webhook.
- **Delete This Webhook** — Permanently deletes the selected webhook.
---
```lua
loadstring(game:HttpGet(''))()
```
