# ShareTunnel CasaOS App Store

A small third-party app store for [CasaOS](https://casaos.io) with one app: **[ShareTunnel](https://github.com/Shariqtechie/Sharetunnel)**, which shares files from your self-hosted Nextcloud with anyone on the internet in one click. No domain, no port forwarding.

## Add it to CasaOS

1. Open your CasaOS dashboard and go to the **App Store**.
2. Click **Add Source** (top right, above the app list).
3. Paste this link and click **Add**:

   ```
   https://github.com/Shariqtechie/sharetunnel-casaos-store/archive/refs/heads/main.zip
   ```

4. Wait a moment, then find **ShareTunnel** in the list. Click it and install.
5. Open the app on port `9099`. The first time, ShareTunnel asks you to create a password (from a device on your home network). Then press **Start tunnel**.

## Updating

Open the ShareTunnel menu in CasaOS and choose **Update** when a new version is shown. (Updates are handled by CasaOS, so ShareTunnel's own updater is switched off in this version.)

Requires CasaOS 0.4.4 or newer, and Nextcloud running in Docker with a PostgreSQL database (for example the Nextcloud app from the CasaOS store).

## Need help?

Open an issue on the [ShareTunnel repository](https://github.com/Shariqtechie/Sharetunnel/issues).
