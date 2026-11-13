# TallyBridge Connector downloads

Windows connector for TallyBridge (Shopify <-> TallyPrime) by Navya Enterprises.

## TallyBridge.exe — v2.1.1 (13 Nov 2026)

- Size: 6,714,368 bytes
- SHA-256: `e3cc08685621b00c8e245530b54ffb97eb11b66a1d93a47bc62597ab582297ff`
- Download for clients: TallyBridge portal → Tally Connector → "Get key & download"

### What's in it
- Native Windows app: icon in the system tray near the clock (green / amber / red status),
  right-click menu, notifications.
- App window with Status, Tally Settings, Activity and Connection tabs (no browser).
- Installs itself to `%ProgramData%\TallyBridge`, starts with Windows, updates itself.

### Changes
- 2.1.1 — reads Tally closing stock correctly (`<CLOSINGBALANCE TYPE="Quantity">`).
- 2.1.0 — native Windows app with system tray and settings window.
- 2.0.0 — first single-exe connector (browser-based window).
