# 📸 QR Photo Drop

Instant, zero-cloud Phone ⇄ PC photo transfer & sharing via QR code.

## ✨ Features
- **📱 Phone → PC Instant Upload:** Scan the Room QR code on your computer screen with your phone camera to snap or select photos from your phone and beam them live to your PC.
- **📲 PC → Phone Individual Photo QR Codes:** Click **QR Share** on any photo in the gallery to generate a dedicated QR code so any phone can scan and download that photo directly.
- **✂️ Built-in Crop & Rotate:** Powered by `Cropper.js` right in the browser.
- **📦 Bulk ZIP Download & Local Persistence:** Automatically caches received photos in your browser's local `IndexedDB` and lets you download all photos as a `.zip` archive.
- **📶 Personal Hotspot Ready:** Uses a Dual-Engine tunnel (**PeerJS WebRTC** + **MQTT over WebSockets fallback**) so it works 100% reliably even when your PC is tethered to your phone's personal hotspot.
