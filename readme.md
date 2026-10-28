# FieldProof Desktop

Windows desktop app for [FieldProof](https://your-frontend-url.vercel.app).

This app opens the FieldProof web platform in a dedicated desktop window (Electron).

## Download

1. Open the latest **Release** on this repository.
2. Download **FieldProof Setup** (`.exe`).
3. Run the installer and open **FieldProof** from the Start Menu.

> Windows may show **Unknown publisher** because the app is not code-signed.  
> Click **More info** → **Run anyway** if you trust this build.

## Requirements

- Windows 10 or Windows 11 (64-bit)
- Internet connection (app loads the live FieldProof website)
- A FieldProof account (worker, manager, or admin)

## How it works

- The desktop app is a lightweight window around the FieldProof website.
- Login, tasks, GPS check-in, and all features use the same backend as the web app.
- When the website is updated, the desktop app shows the new UI automatically (no new install required for small web updates).

## For developers

```bash
cd desktop
npm install
