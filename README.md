<p align="center"><img src="icon.png" width="96" alt="Mirage icon"></p>

<h1 align="center">Mirage</h1>

<p align="center">Change your iPhone's location: teleport anywhere on the map, or drive a route with real traffic lights and stop signs. Tap <b>Stop</b> and your real location comes right back.</p>

<p align="center"><a href="https://github.com/alexpeterson443/mirage/releases/latest/download/Mirage.ipa"><b>⬇️ Download Mirage.ipa</b></a></p>

---

## Before you start

- iPhone on **iOS 26 or newer**
- A **computer** (Mac or Windows) for the one-time setup
- Your **Apple ID** (a free one works)

iPhones can't install apps straight from a link unless they're on the App Store, so Mirage installs through **SideStore**. You only do this setup once.

## Setup

**1. Install SideStore.** Follow the official guide at [docs.sidestore.io](https://docs.sidestore.io). It uses the **iloader** app on your computer and your Apple ID.

**2. Add Mirage to SideStore.** On your iPhone, open SideStore → **Sources** → **+** and paste:

```
https://raw.githubusercontent.com/alexpeterson443/mirage/main/source.json
```

Then install Mirage from that source. Doing it this way means SideStore shows you updates. (Or download the `.ipa` above, then SideStore → **My Apps** → **+** → pick the file.)

**3. Install LocalDevVPN** from the App Store and turn it on. Mirage only works while LocalDevVPN is connected.

**4. Get your pairing file from Alex.** Mirage needs a pairing file made for *your* iPhone. Bring your phone to Alex's Mac with a USB cable, unlock it and tap **Trust**. Alex sends you the file. Open Mirage → ⚙️ Settings → **Pairing File** → import it.

**5. Spoof.** Tap anywhere on the map (or search), then tap **Spoof**. You'll see a green **Spoofing** timer with a red **Stop** button. Tap **Stop** to go back to your real location.

## Good to know

- **Free Apple IDs expire apps after 7 days.** Open SideStore and tap **Refresh** before then. Mirage → Settings → *Keep Mirage Installed* shows how many days are left.
- **Free Apple IDs can have 3 sideloaded apps at a time** (SideStore counts as one).
- **Stuck on a fake location?** Mirage → Settings → **Restore Real Location**.
- Your location really changes for every app, including Find My, Life360 and Snapchat, so anyone you share your location with will see the spoofed spot.
