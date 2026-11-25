---
title: "SYNC: Nexus Control - Privacy Policy"
---

# SYNC: Nexus Control — Privacy Policy

Last updated: 24 November 2026

SYNC: Nexus Control ("SYNC", "the game", Android package `com.levver.sync`) is made by
Lev Albrant ("we", "us"). This page explains what the game stores about you, why, and
how to delete it.

**Short version:** we store only what the game needs to run accounts, matches, ratings
and the leaderboard. No ads, no analytics or tracking, and we never sell or share your
data.

## 1. What we store

### Your account
- **Email and password** (email accounts only). Handled by Firebase Authentication; we
  never see your password.
- **Guest ID** (guests only). An anonymous ID from Firebase Authentication, not linked to
  any name, email or phone number.
- **Callsign.** The name other players see. You choose it, or you get a random one like
  `PLAYER-7KQ2`. It is never taken from your email.
- **Rating and stats.** Your rating (with its deviation and volatility), games played and
  games won. Guest games are never rated.

### When you play online
- **Match records.** Both players' IDs and callsigns, every card bid, the prize order,
  round and game scores, clock times, the result, rating changes and timestamps.
- **Presence.** During a match, whether you're connected and when you were last seen
  (`lastSeen`). It decides disconnects.
- **Current match.** A pointer to the match you're in, so you can rejoin after the app
  closes.
- **Matchmaking entry.** While you search: your ID, callsign, rating, guest status and
  when you joined. It is deleted when you're matched, cancel, or stop responding.

### Technical data
Google's servers process your **IP address** and connection details to deliver the
service and protect it from abuse. Server logs may also record your player ID. They are
kept for a limited time (see §5).

### On your device only
Your sign-in token and email, so you stay signed in (deleted when you sign out), and
your sound settings.

### What we don't collect
No location, contacts, photos, microphone, advertising ID or browsing data. No ads, no
analytics, no crash reporting, no tracking.

Practice against the bot without signing in sends nothing to us.

## 2. Why

| data | used for |
|---|---|
| email, password, guest ID | signing you in |
| callsign | showing who you're playing; the leaderboard |
| rating and stats | matchmaking by skill; the leaderboard; your profile |
| match records | deciding results fairly on the server; ratings; investigating cheating |
| presence, current match | disconnect rules; rejoining a match |
| matchmaking entry | finding you an opponent |
| IP address, logs | running the service; security |

Legal basis (where GDPR applies): running the game you asked to use (contract), and our
legitimate interest in fair play and security.

## 3. Who can see it

- **Your opponents** see your callsign, rating and moves in the matches you play with
  them.
- **Signed-in players** can see the callsign, rating, games played and games won of every
  registered player who has played a rated match. The leaderboard shows the top 10.
  Guests never appear there.
- **Google (Firebase)** stores and processes the data for us as our service provider,
  under the Firebase data processing terms. The database and server code run in Google's
  `europe-west1` region (Belgium). Sign-in data (Firebase Authentication) is handled by
  Google globally, including in the United States.
- **Nobody else.** We don't sell, rent or share your data, and we don't use it for
  advertising. We disclose data only if the law requires it.

## 4. Shared account with the SYNC web game

Your account also works in the SYNC web game. Deleting it here deletes your web-game
profile and leaderboard entry too (see §6 for what stays).

## 5. How long we keep it

- **Account, stats and match records:** until you delete your account.
- **Guest data:** deleted automatically after **12 months** without opening the game,
  or at once when you delete it.
- **Matchmaking entries:** until you're matched or cancel.
- **Server logs:** 30 days, then deleted by Google.

## 6. Deleting your data

- **In the app:** Settings → Account → **Delete account** (or **Delete guest data**).
  It works when you're not in a live match, and takes effect at once.
- **Without the app:** follow
  https://levver.github.io/goofspiel-legal/delete-account/ or email
  levalbrant@gmail.com from your account's address. We complete it within 30 days.

**What is deleted:** your sign-in, callsign, rating, stats, leaderboard entry, current
match and matchmaking entry, any waiting private game you created, and your profile
and leaderboard entry in the SYNC web game.

**What stays:** in matches you played, your ID and callsign are replaced with
"deleted". Your opponent keeps the result, so their history and rating stay correct,
but nothing links it to you. When both players have deleted their accounts, the match
is removed. Matches you played in the SYNC web game keep the result too, but not your name.

## 7. Your rights

Depending on where you live, you can ask us to access, correct, export or delete your
data, or object to how we use it. Email levalbrant@gmail.com. You can also complain to
your local data protection authority.

## 8. Children

The game is for ages 13 and up. We don't knowingly collect data from children under 13.
If you think a child has given us an email address, contact us and we'll delete it.

## 9. Security

All traffic is encrypted (HTTPS). Database rules let each player read only their own
account and the matches they play in. Results, bids and ratings are decided on the
server, never on your device.

## 10. Changes

When this policy changes, we update this page and its date.

## 11. Contact

Lev Albrant, levalbrant@gmail.com
