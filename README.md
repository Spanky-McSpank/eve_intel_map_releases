# EVE Intel Map

A lightweight 2D intel map for EVE Online, with threat coloring from chat-log intel channels.

This repository holds the beta downloads only.

## Install

1. Download the `.exe` from the [latest release](https://github.com/Spanky-McSpank/eve_intel_map_releases/releases).
2. Run it. When asked, enter your intel channel name and your EVE chat log folder.
   The default log folder is `%USERPROFILE%\Documents\EVE\logs\Chatlogs`.
   More channels can be added later in the app's Settings.
3. On first launch, the setup wizard asks for a license key, signs you in with EVE SSO, and downloads the EVE static data (SDE, about 600 MB).

Windows 10 or 11, 64-bit.

## Windows SmartScreen

The installer is not code-signed, so Windows shows "Windows protected your PC".
Click **More info**, then **Run anyway**.

To check that your download is intact, compare its SHA-256 with the table below.
In PowerShell:

```powershell
Get-FileHash .\EVEIntelMap_Setup_v1.0.3_900db4d.exe -Algorithm SHA256
```

| Release | File | SHA-256 |
|---|---|---|
| v1.0.3 beta 1 | `EVEIntelMap_Setup_v1.0.3_900db4d.exe` | `fb3c25b06a468831a019921279afba48f9660266a61f5899d29ea9f07974e476` |

## Early access: get a license

1. Send **1,000,000,101 ISK** to the character **Relance Haklar**, as a normal ISK transfer.
2. Put `license key` in the **Reason** field.

The key is sent by in-game EVE mail after manual approval. It is not instant.
It can take a while for the payment to be picked up, so please allow time before asking.

The license is perpetual, per install (one key activates one PC), with no warranty.
This is an early-access release.

## Problems

Send an in-game EVE mail to Relance Haklar.
