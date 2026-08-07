# Webhook Hunter

## Hunt: 

### Status

Displays the current scanner state and the total number of detected webhooks.

### Controls

Contains the main controls for the scanner.

- **Start** — Starts or stops live scanning.
- **Protection** — Enables the firewall that blocks webhook requests before they are sent.
- **Aggressive Mode** — Blocks every outgoing request except trusted Roblox domains.
- **Auto Copy** — Automatically copies detected webhooks to the clipboard.
- **Auto-Fill Webhook Tab** — Automatically fills the last detected webhook into the Webhook tab.
- **Rescan GUI** — Scans all existing GUI elements again.
- **Clear** — Clears the detected webhook list.

### Self-Test

Used to verify that the protection system is working correctly.

- **Run Diagnostics** — Prints executor compatibility and hook information to the console.
- **Run Test** — Sends a safe test request to verify that the protection detects and blocks webhook requests.

---

## Caught

Displays every detected webhook along with its source location.

### Caught Webhooks

Shows the detected webhook URL, its full object path, and provides a button to copy it.
---
### Actions
- **Webhook URL** — Input field for a webhook URL.
- **Message** — Input field for the message content.
- **Load Last Caught** — Loads the most recently detected webhook.
- **Send** — Sends a message to the selected webhook.
- **Delete This Webhook** — Permanently deletes the selected webhook.
---
```lua
loadstring(game:HttpGet(''))()
```
