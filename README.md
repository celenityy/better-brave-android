# better-brave-android

My recommendations for the ultimate configuration of the Brave Browser on Android :)

**NOTE**: This is specifically tailored for Brave on Android. For Desktop, see [here](https://codeberg.org/Magnesium1062/better-brave).

# Brave Shields & privacy

**Block trackers & ads** -> `Block trackers & ads (Aggressive)`

**Auto-redirect AMP pages** -> ✅

**Auto-redirect tracking URLs** -> ✅

**Upgrade connections to HTTPS** -> `Require all connections to use HTTPS (strict)`

**Block Scripts** -> ✅ *(This **will** cause breakage, but it heavily improves privacy & security, so I'd recommend enabling it if possible and if you're willing to re-enable scripts on sites that need it)*

**Block Cookies** -> `Block third-party cookies` *(Should be default)*

**Block Fingerprinting** -> `Fingerprinting blocked (strict, may break sites)`

**Prevent fingerprinting via language settings** -> ✅

**Content Filtering**:

`EasyList Cookie` -> ✅

`Fanboy's Annoyances + uBO Annoyances` -> ✅

`Fanboy's Social` -> ✅

`Fanboy's Anti-Newsletter` -> ✅

`Fanboy's Mobile Notifications` -> ✅

`Fanboy's Anti-chat Apps` -> ✅


**Forget me when I close this site** -> ✅ *(This feature drastically improves privacy, I would highly recommend using it and just setting exceptions for sites you need to stay logged in to)*

**Allow Google login buttons on third party sites** -> ❌

**Allow Facebook logins and embedded posts** -> ❌

**Allow Twitter embedded tweets** -> ❌

**Allow LinkedIn embedded posts** -> ❌

**Allow app links to open in apps outside of Brave** -> ❌

**WebRTC IP handling policy** -> `Disable non-proxied UDP` *(Don't set this if you have to call on the web through services like Discord & Zoom)*

**Safe Browsing** -> `No protection (not recommended)` ❌ *(On Android, Safe Browsing requires Google Play Services and as such is proprietary and questionable. As long as you have other protection in place (See `secure DNS` & `Additional recommendations` below), then I don't think its worth using here)*

**Allow sites to check if you have payment methods saved** -> ❌

Unstoppable Domains -> **Resolve Method** -> `Disabled`

Ethereum Name Service -> **Resolve Method** -> `Disabled`

Ethereum Name Service -> **ENS offchain lookup** -> `Disabled`

Solana Name Service -> **Resolve Method** -> `Disabled`

**IPFS Gateway** -> ❌

**Use secure DNS** -> ✅

Use secure DNS -> **Choose another provider** -> Pick a private, secure, & reputable DNS provider of your choice, I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to (See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings), otherwise I would recommend [Quad9](https://quad9.net/): `https://dns.quad9.net/dns-query` *(Even if you have a private/secure DNS provider set on your OS/network level, make sure to still set it here too like this, so that you can take advantage of [Encrypted Client Hello](https://blog.cloudflare.com/announcing-encrypted-client-hello))*

**Block cookie consent notices** -> ✅

**Block `Switch to App` Notices** -> ✅

**Close tabs on exit** -> ✅

**Allow privacy-preserving product analytics (P3A)** -> ❌

**Automatically send diagnostic reports** -> ❌

**Automatically send daily usage ping to Brave** -> ❌

**Show autocomplete in address bar** -> ❌

**Improve search suggestions** -> ❌

**Show top sites in autocomplete** -> ❌

# Brave Wallet

**Default Ethereum wallet** -> `None`

**Default Solana wallet** -> `None`

**Display Web3 notifications** -> ❌

**Enable NFT discovery** -> ❌

# Search engines

**Standard Tab** -> `Brave`

**Private Tab** -> `Brave`

# Password Manager

**Save passwords** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Auto Sign-in** -> ❌

# Notifications

**All "Brave Ads" notifications** -> ❌

**Browser** -> ❌

**Active downloads** -> ✅

**Private** -> ✅

**Playing media** -> ✅

**Brave Browser** -> ❌

# Site settings

**Location** -> `Blocked` ❌ 

**Camera** -> `Blocked` ❌ *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed*)

**Microphone** -> `Blocked` ❌ *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed*)

**Notifications** -> `Blocked` ❌

**Motion sensors** -> `Blocked` ❌

**USB** -> `Blocked` ❌

**Clipboard** -> `Blocked from reading clipboard` ❌

**Virtual reality** -> `Blocked` ❌

**Augmented reality** -> `Blocked` ❌

**Pop-ups and redirects** -> `Blocked` ❌ *(Should be default)*

**Protected content** -> `Blocked` ❌ - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

**Autoplay** -> `Blocked` ❌

**Google Sign-In** -> `Blocked` ❌

# Downloads

**Ask where to save files (if SD card is detected)** -> ✅

**Automatically open when possible** -> ❌

**Show download progress notifications** -> ✅

# Media

**Widevine DRM** -> ❌ - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

**Background play** -> ✅

# Appearance

**Brave Rewards icon** -> ❌

**Brave Ads** -> ❌

**Disable Sharing Hub** -> ✅

# New Tab Page

**Show Sponsored Images** -> ❌

**Show Top Sites** -> ❌

# Accessibility

**Force enable zoom** -> ✅

**Simplified view for web pages** -> ✅

# Payment methods

**Save and fill payment methods** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Manually verify every time you pay using autofill** -> ✅

# Addresses and more

**Save and fill addresses** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

# Autofill in private tabs

**Autofill in private tabs** -> ❌

# brave://flags


`#android-open-pdf-inline` -> `Enabled`

`#brave-adblock-default-1p-blocking` -> `Enabled`

`#brave-block-screen-fingerprinting` -> `Enabled`

`#brave-extension-network-blocking` -> `Enabled`

`#brave-ipfs` -> `Disabled`

`#brave-rewards-vbat-notice` -> `Disabled`

`#brave-safe-browsing` -> `Disabled` *(On Android, Safe Browsing requires Google Play Services and as such is proprietary and questionable. As long as you have other protection in place (see following sections), then I don't think its worth using here)*

`#brave-speedreader` -> `Enabled`

`#brave-wallet-bitcoin` -> `Disabled`

`#enable-site-per-process` -> `Enabled`

`#native-brave-wallet` -> `Disabled`

`#sanitizer-api` -> `Enabled`

`#strict-origin-isolation` -> `Enabled`

# Additional recommendations

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).

* Use a (reputable) anti-virus if possible. On Android, you can use [Hypatia](https://f-droid.org/packages/us.spotco.malwarescanner/), and on Linux, you can use [ClamAV](https://www.clamav.net/). NOTE: You should install Hypatia through the [DivestOS Official Repo](https://divestos.org/fdroid/official/?fingerprint=E4BE8D6ABFA4D9D4FEEF03CDDA7FF62A73FD64B75566F6DD4E5E577550BE8467) instead of F-Droid's main repo, as it will allow you to receive quicker updates directly from the developer. It's also recommended to use [F-Droid Basic](https://f-droid.org/en/packages/org.fdroid.basic/) as your F-Droid client of choice.