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
loadstring(game:HttpGet('https://raw.githubusercontent.com/Front-Evill/devlyx/refs/heads/main/webhook.luau'))()
```

# Devlyx ESP Hub
---
* Enable ESP — Starts or stops the ESP system.
* Team Check — Hides ESP on players who are on your team.
* Wall Check — Only highlights players who are actually visible, instead of always showing through walls.
---
* Show Names — Adds the player's name to the tag shown above their head.
* Show Health — Adds current/max health to the tag.
* Show Distance — Adds the distance in studs to the tag.
---
* ESP Color — Sets the highlight and outline color from a preset list.
* Max Distance — Sets how far away a player's tag stays visible.
* Fill Transparency — Controls how see-through the highlight's inner fill is.
* Outline Transparency — Controls how see-through the highlight's outer outline is.
---
* Refresh ESP — Rebuilds ESP on every player using the current settings.
* Reset to Default — Restores every setting back to its original value.
* Save Settings — Saves the current configuration to a profile.
* Load Settings — Loads a previously saved configuration.
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/Front-Evill/devlyx/refs/heads/main/esp.lua'))()
```
