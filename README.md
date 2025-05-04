# Store remover for [uBlacklist](https://github.com/iorate/ublacklist)
Meant to reduce the amount of stores shown when using common search-engines when searching for english and norwegian pages.

### Subscription URL
```
https://raw.githubusercontent.com/ogmagog/store-remover/refs/heads/ublacklist/ublacklist-store-remover-full.txt
```
<details>
<summary>
  Display filter (<a href="https://github.com/ogmagog/store-remover/blob/b67ad178ff1d78dde4d4577369962bb56f03f2ad/ublacklist-store-remover-full.txt#L1C1-L36C17">link</a>)
</summary>

```
---
name: Online store remover (full version)
creator: Ogmagog
description: Meant to remove online stores from searches
homepage: https://github.com/ogmagog/store-remover/
---
# Blanket blocking of every site with common store terms
/\S*store\S*|\S*Store\S*|\S*STORE\S*/
/\S*shop\S*|\S*Shop\S*|\S*SHOP\S*/
/\S*deal\S*|\S*Deal\S*|\S*DEAL\S*/
/\S*dx\S*|\S*Dx\S*|\S*DX\S*/
/\S*market\S*|\S*Market\S*|\S*MARKET\S*/
/\S*shopping\S*|\S*Shopping\S*|\S*SHOPPING\S*/

# Websites with heavy ad-load
*://*.amazon.com/*
*://*.ebay.com/*
*://*.aliexpress.com/*
*://*.banggood.com/*
*://*.temu.com/*
*://*.alibaba.com/*
*://*.etsy.com/*
*://*.wish.com/*
*://*.joinhoney.com/*
*://*.honey.com/*v
*://*.shein.com/*

# Blokkering av nettadresser med vanlige nettbutikktermer
/\S*butik\S*|\S*Butik\S*|\S*BUTIK\S*/
/\S*handel\S*|\S*Handel\S*|\S*HANDEL\S*/

# Blokkering av nettsteder med høy reklamebelastning
*://*.prisjakt.no/*
*://*.kelkoo.no/*
*://*.klarna.com/*
*://*.klikk.no/*
```
</details>

## Dependencies
- uBlacklist extension for your favorite [Chromium](https://chromewebstore.google.com/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe), [Firefox](https://apps.apple.com/us/app/ublacklist-for-safari/id1547912640
) or [iOS](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/) based browser
- The use of a [supported search engine](https://github.com/iorate/ublacklist?tab=readme-ov-file#supported-search-engines)

## Step-by-step installation
1. Add the uBlacklist extension to your browser
2. Head over to uBlacklist's *Options*, most often found on your browser's toolbar or extension manager

<img src="https://github.com/user-attachments/assets/d9d2cb83-cd7a-4d0f-97d2-1dc87c724a76" alt="store-options-in-toolbar" width="400">

3. Scroll down to the **Supscription** and click **Add a subscription**

<img src="https://github.com/user-attachments/assets/74625fbb-9119-48c8-8447-1c7a8159ec5f" alt="subscription-section-in-ublacklist-options" width="400">

4. Copy and paste the Subscription URL for my filter into the *URL-field* and hit **Add**
```
https://raw.githubusercontent.com/ogmagog/store-remover/refs/heads/ublacklist/ublacklist-store-remover-full.txt
```
<img src="https://github.com/user-attachments/assets/74625fbb-9119-48c8-8447-1c7a8159ec5f" alt="add-subscription-dialog-in-ublacklist-options" width="400">

Enjoy not finding this github page in your Google searches!

For more information head over to the [iorate's](https://github.com/iorate) (creator) [github](https://github.com/iorate/ublacklist) or documentation[](https://iorate.github.io/ublacklist/docs).
