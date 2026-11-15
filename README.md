# EVE Intel Map

A lightweight 2D intel map for EVE Online, with threat coloring from chat-log intel channels.

This repository holds the downloads only.

## Install

1. Download the `.exe` from the [latest release](https://github.com/Spanky-McSpank/eve_intel_map_releases/releases/latest).
   Download the .exe under Assets. Ignore 'Source code', which has no program in it.
2. Run it. When asked, enter your intel channel name and your EVE chat log folder.
   The default log folder is `%USERPROFILE%\Documents\EVE\logs\Chatlogs`.
   More channels can be added later in the app's Settings.
3. On first launch, the setup wizard asks for a license key, signs you in with EVE SSO, and downloads the EVE static data (SDE, about 600 MB).

Some security software scans a new program the first time it runs and can block its internet access for a few minutes.
If activation says it can't reach the license server, wait a few minutes and try again.

Windows 10 or 11, 64-bit.

## Windows SmartScreen

The installer is not code-signed, so Windows shows "Windows protected your PC".
Click **More info**, then **Run anyway**.

To check that your download is intact, compare its SHA-256 with the table below.
In PowerShell:

```powershell
Get-FileHash .\EVEIntelMap_Setup_v1.1.0_5d893b7.exe -Algorithm SHA256
```

| Release | File | SHA-256 |
|---|---|---|
| v1.1.0 | `EVEIntelMap_Setup_v1.1.0_5d893b7.exe` | `e0f719da976a38dc1b17678354720e090f96138d8dabe2914e7d7b519bd04d3e` |

Already installed? Run the new installer over your current version: your sign-in, license and settings are kept.

## Early access: get a license

Send **exactly 1,000,000,101 ISK** to the character **Relance Haklar**, as a normal ISK transfer.
Nothing needs to go in the Reason field.

The exact amount is how your payment is recognised. Any other amount isn't matched automatically,
so if you sent a different amount, send an in-game EVE mail to Relance Haklar.

The key is sent by in-game EVE mail after manual approval. It is not instant.
It can take a while for the payment to be picked up, so please allow time before asking.

The license is perpetual, per install (one key activates one PC), with no warranty.
This is an early-access release.

## Problems

Send an in-game EVE mail to Relance Haklar.
