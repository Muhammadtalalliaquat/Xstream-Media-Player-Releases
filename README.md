# Xstream Media Player

Downloads for Xstream Media Player on macOS and Windows.

**[Download the latest version](https://github.com/Muhammadtalalliaquat/Xstream-Media-Player-Releases/releases/latest)**, then choose your file from the **Assets** list at the bottom of the release.

| Your computer | Download this file |
|---|---|
| Mac with Apple silicon (M1 or newer), macOS 11 or later | `Xstream-Media-Player-<version>-mac-arm64.dmg` |
| Windows 10 or later, 64-bit (recommended) | `Xstream-Media-Player-Setup-<version>-x64.exe` |
| Windows, no installation | `Xstream-Media-Player-Portable-<version>-x64.exe` |

Intel Macs are not supported at the moment.

> Only download the app from this page. The app isn't signed with paid Apple or Microsoft developer certificates yet, so your computer will warn you the first time you open it. The steps below explain what to do.

---

## Install on macOS

1. Open the `.dmg` file.
2. Drag **Xstream Media Player** into the **Applications** folder. If you're asked, choose **Replace**.
3. Open the app from **Applications**.

### "Apple could not verify" message

1. Click **Done**.
2. Open **System Settings → Privacy & Security**.
3. Scroll down to **Security** and click **Open Anyway** next to Xstream Media Player.
4. Confirm with your password or Touch ID.

You only need to do this once.

### "Xstream Media Player is damaged and can't be opened" message

Your download is not broken. macOS shows this message for some downloaded apps that aren't signed by a registered developer.

1. Click **Eject Disk Image**, and quit Xstream Media Player if it's open.
2. Open the **Terminal** app, paste this command, and press Return:

   ```bash
   xattr -d com.apple.quarantine ~/Downloads/Xstream-Media-Player-*-mac-arm64.dmg
   ```

   If you see `No such file`, check that the `.dmg` is in your **Downloads** folder and that its name has no extra text, such as `(1)`.

3. Open the `.dmg` again, drag the app to **Applications**, and choose **Replace**.
4. Open the app.

If you still see the message, paste this into Terminal, press Return, and open the app again:

```bash
xattr -cr "/Applications/Xstream Media Player.app"
```

---

## Install on Windows

### Installer (recommended)

1. Open `Xstream-Media-Player-Setup-<version>-x64.exe`.
2. If you see **Windows protected your PC**, click **More info**, then **Run anyway**.
3. Follow the steps in the installer.
4. Open **Xstream Media Player** from the desktop shortcut or Start menu.

### Portable

1. Move `Xstream-Media-Player-Portable-<version>-x64.exe` to any folder you like.
2. Open it. If you see **Windows protected your PC**, click **More info**, then **Run anyway**.

The Portable version doesn't install itself or update automatically. Download the new file from this page when you want a newer version.

### If your browser blocks the download

Browsers may warn that the file isn't commonly downloaded. Open your browser's **Downloads** list and choose the option to keep the file.

---

## Updates

The app checks for updates when it starts and every few hours. When a new version is ready, it shows you what's new and lets you choose when to update. You can also check from **Settings → Application updates**.

- **Windows installer:** click **Update now**, then **Restart & install**.
- **macOS:** click **Download update**, then **Open installer**. Drag the app to **Applications** and choose **Replace**.
- **Windows Portable:** click **Open download page** and download the new file.

### "Couldn't check for updates"

Older versions of the app look for updates in a location that's no longer available. Install the latest version from this page once, using the steps above, and updates will work from then on.
