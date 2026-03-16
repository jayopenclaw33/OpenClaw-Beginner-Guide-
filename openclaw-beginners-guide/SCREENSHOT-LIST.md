# Screenshot List — OpenClaw Beginner's Guide
### Capture these in order. All screenshots go in: `openclaw-beginners-guide/screenshots/`

---

## 📋 Naming Convention
`##-short-description.png`  
Example: `01-install-complete.png`

---

## ✅ Screenshots to Capture

### CLI / Terminal Screenshots (macOS Terminal or iTerm2)
> Tip: Use a clean terminal — dark theme, readable font (16pt+), no clutter in the window title

| # | Filename | What to Show |
|---|----------|-------------|
| 01 | `01-install-complete.png` | Terminal after running the install script — should show download progress and a success/done message |
| 02 | `02-version-check.png` | Terminal showing `openclaw --version` output with version number |
| 03 | `03-onboard-welcome.png` | Terminal showing the first screen of `openclaw onboard --install-daemon` — the welcome banner |
| 04 | `04-wizard-provider.png` | Terminal showing the model/AI provider selection step in the wizard |
| 05 | `05-wizard-complete.png` | Terminal showing the wizard completion — "Setup complete" or similar success message |
| 06 | `06-gateway-status.png` | Terminal showing `openclaw gateway status` output — gateway running with uptime |

### Browser Screenshots (Control UI)
> Open `http://127.0.0.1:18789/` in Chrome or Safari. Use a clean browser window — no extensions visible.

| # | Filename | What to Show |
|---|----------|-------------|
| 07 | `07-controlui-empty.png` | The Control UI open in browser, empty/fresh state — shows the chat input and interface |
| 08 | `08-controlui-first-chat.png` | A conversation in the Control UI — user says "Hello!" and agent responds introducing itself |
| 09 | `09-bootstrap-conversation.png` | The bootstrap ritual — agent asking "What should I call you?" or similar first-run question |

### Workspace / Finder Screenshots
| # | Filename | What to Show |
|---|----------|-------------|
| 10 | `10-workspace-finder.png` | macOS Finder window open at `~/.openclaw/workspace` showing all the .md files (AGENTS.md, SOUL.md, USER.md, etc.) |

### Messaging App Screenshots
> These can be captured on iPhone/Android and transferred, or via Mac app

| # | Filename | What to Show |
|---|----------|-------------|
| 11 | `11-telegram-botfather.png` | Telegram app — BotFather conversation, the message showing the bot token after creating a new bot (blur/cover the actual token!) |
| 12 | `12-whatsapp-qr.png` | Terminal or app showing the WhatsApp QR code pairing screen |

### macOS App Screenshots (if using the native app)
> Capture these during a fresh install of the macOS app

| # | Filename | What to Show |
|---|----------|-------------|
| 13 | `13-macos-security-warning.png` | macOS Gatekeeper security warning when opening OpenClaw app for first time |
| 14 | `14-macos-network-permission.png` | macOS "Find local networks" permission dialog |
| 15 | `15-macos-security-notice.png` | OpenClaw app security notice / welcome screen |
| 16 | `16-macos-gateway-choice.png` | Gateway location selection screen — "This Mac (Local only)" option |
| 17 | `17-macos-permissions.png` | macOS permissions screen inside the OpenClaw app |
| 18 | `18-macos-onboarding-chat.png` | The macOS app onboarding chat — agent's first message introducing itself |

---

## 📐 Screenshot Specs

| Setting | Value |
|---------|-------|
| **Format** | PNG (preferred) or JPG |
| **Resolution** | At least 1280px wide |
| **Retina/2x** | Yes, use if available — looks sharper in guides |
| **Annotations** | Optional: add red arrows or boxes to highlight key elements |
| **Privacy** | Always blur/cover API keys, tokens, personal info before saving |

---

## 🛠️ Recommended Tool for Annotations
- **macOS built-in:** Screenshot → Markup (pencil icon)
- **CleanShot X** — best Mac screenshot tool, highly recommended
- **Skitch** — free, great for adding arrows and labels

---

## 📁 Where to Put Them
Save all screenshots to:
```
~/.openclaw/workspace/openclaw-beginners-guide/screenshots/
```

Then update `openclaw-guide.html` — each screenshot placeholder has a comment showing which image to swap in.

---

## 🔄 Priority Order
If you're short on time, capture in this order:
1. `07` — Control UI (most important visual)
2. `08` — First conversation
3. `01` — Install complete
4. `03` — Wizard welcome
5. Everything else

---

*Screenshot list by Zara ⚡ — ZaraAI.com*
