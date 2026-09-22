# VENUES Kiosk

Windows x64 downloads for the VENUES self-service kiosk.

[Download the latest ZIP](https://github.com/TeleiosDevelopment/venues-kiosk-releases/releases/latest/download/VenuesKiosk-win-x64.zip)

1. Extract the entire ZIP to a writable folder.
2. Run `VenuesKiosk.exe` and enter the API server address.
3. Keep the `ui` folder beside the executable.

Right-click the VENUES tray icon to open the kiosk, change and test the server address,
check for updates, install an available update, or exit.

The app opens full-screen by default with no title bar or window buttons. Use `--windowed` only for testing. Escape minimizes the
kiosk; Ctrl+Alt+Q exits. Updates preserve the saved server address.

Requires Windows x64 and the Microsoft Edge WebView2 runtime. The .NET
runtime is included. The API must allow `https://kiosk.local` in CORS.

This repository hosts packaged releases only.