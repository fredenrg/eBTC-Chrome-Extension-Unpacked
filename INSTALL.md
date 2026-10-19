# Installing the Eco Bitcoin Virtual Miner Stats extension (preview)

This is a preview build that you install by hand until the extension is
available on the Chrome Web Store. It takes about two minutes.

**Requirements:** Google Chrome 116 or newer, or another Chromium browser
such as Brave or Edge, on a desktop computer.

## Install

1. **Unzip** `ebtc-virtual-miner.zip` into a folder you'll keep, for
   example `Documents/ebtc-virtual-miner`. Chrome loads the extension from
   this folder every time it starts, so don't delete or move it afterwards.
2. Open a new tab and go to `chrome://extensions`.
3. Turn on **Developer mode** with the switch in the top-right corner.
4. Click **Load unpacked** and select the folder you unzipped. Select the
   folder that contains `manifest.json`, not a folder above it.
5. The extension now appears in the list. Click the puzzle-piece icon in
   the toolbar and **pin** Eco Bitcoin Virtual Miner Stats so it's always visible.

## Connect your wallet

1. Click the eBTC icon in the toolbar to open the side panel.
2. Click **Connect with Phantom / Solflare** to open
   https://ebtc.fredenergy.org in a new tab.
3. Approve the sign-in message in your wallet. This signature only proves
   that you own the address. It doesn't send a transaction or cost anything.
4. Go back to the side panel, where your miners, hash rate and the draw
   countdown are now shown.

The extension never asks for your seed phrase or private key and can't move
funds. Boosting and claiming always happen on the website, where your wallet
asks you to approve each action. To follow an address without signing
anything, paste it into the side panel and click **Watch address**.

## Updating to a new preview build

Preview builds don't update automatically. When you receive a new zip:

1. Replace the contents of your extension folder with the new files.
2. Go to `chrome://extensions` and click the reload icon on the Eco Bitcoin
   Virtual Miner Stats card.

Your saved wallets and settings are kept.

## Moving to the Chrome Web Store version

Once the extension is published, the store version is a separate install:

1. Remove the preview from `chrome://extensions`.
2. Install Eco Bitcoin Virtual Miner Stats from the Chrome Web Store.
3. Connect your wallet again.

## Troubleshooting

- **"Manifest file is missing or unreadable":** you selected the wrong
  folder. Pick the folder that contains `manifest.json`.
- **A "Disable developer mode extensions" banner appears:** Chrome shows
  this for any extension installed by hand. Click the close button, not
  "Disable".
- **"Load unpacked" is missing or greyed out:** your browser is managed by
  an organisation that blocks hand-installed extensions. Use a personal
  browser profile instead.
- **No win notifications:** check that **Notify me when one of my miners
  wins** is ticked in the side panel and that your operating system allows notifications
  from Chrome.
- **Data isn't loading:** reload the extension from `chrome://extensions`.
  If the problem continues, let us know.
