<p align="center">
  <img src="assets/logo.png" width="200" />
  <br>
  <strong>Ambient real-world social discovery.</strong>
</p>
Kami is an ambient social discovery app built around real-world proximity.

Instead of manually searching for people, swapping usernames, or scanning QR codes, Kami quietly shows nearby Instagram-connected users when they are physically nearby right now.

The goal is simple:

make real-world social discovery feel natural again.

---

# Current Features

## Nearby Discovery

Kami continuously checks for nearby users using passive location awareness and lightweight background location updates.

When two active Kami users are physically nearby, they can appear in each other’s Nearby feed in real time.

The Nearby experience is designed to feel ambient and lightweight:

* no manual check-ins
* no map tracking
* no location sharing screens
* no QR code exchange required in most situations

Nearby users only appear while they are actively nearby.

---

## Instagram Connected Profiles

Users can connect their Instagram account to import:

* profile photo
* handle
* display name
* bio

Kami uses this information to create lightweight nearby social identity cards.

---

## Nearby Notifications

Kami can send notifications when another Kami user is detected nearby.

Notifications are designed to be:

* lightweight
* infrequent
* context-aware
* proximity-based

Examples:

* “Someone nearby is on Kami”
* “[Name] is nearby”

Multiple nearby users are grouped into a single notification to reduce spam.

---

## Passive Background Location Checks

Kami uses periodic passive location updates to support nearby detection.

The app:

* sends lightweight proximity pings while active
* performs opportunistic background refreshes
* removes stale location presence automatically
* does not store persistent public movement trails

Location presence automatically expires if:

* the app becomes inactive
* background updates stop responding
* the last known presence becomes stale

---

## Ghost Mode

Ghost Mode temporarily hides a user from Nearby discovery while still allowing the app to function normally.

While Ghost Mode is active:

* the user will not appear in Nearby results
* nearby notifications are disabled
* passive location checks may still occur internally
* the user can still earn future participation/activity rewards

Ghost Mode automatically expires after 24 hours.

---

## Pause Kami

Pause Mode fully disables Nearby participation.

While paused:

* Nearby discovery stops
* nearby notifications stop
* location participation stops
* the user will not appear to others nearby

Pause Mode remains active until manually disabled.

---

## Privacy Controls

Kami is designed around nearby discovery, not public location tracking.

Kami does not provide:

* public live map sharing
* persistent public location history
* public movement trails
* exact coordinate displays

The app focuses on temporary nearby presence rather than long-term location storage.

---

# Design Philosophy

Kami is designed to feel:

* passive instead of performative
* ambient instead of addictive
* social instead of algorithmic
* real-world first

The app focuses on lightweight real-world interactions rather than feeds, follower farming, or endless content consumption.

---

# Status

Kami is currently in active development and closed beta testing.

---

# Contact

[hello@kamisocial.com](mailto:hello@kamisocial.com)
