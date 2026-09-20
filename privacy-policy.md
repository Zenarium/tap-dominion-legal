# Tap Dominion Privacy Policy

Last updated: September 13, 2026

Tap Dominion ("we", "us", "our") values your privacy. This policy explains what information the app processes and how it is used.

## 1. Data We Process

Depending on which features you use, the app may process:

- Gameplay and app usage events (analytics), such as screens viewed, game mode, Campaign level,
  score, hits, misses, session duration, feature interactions, virtual Credits and item activity,
  ad interactions, and categorized errors. These events do not include your name, email address,
  profile photo URL, or free-text content.
- Analytics and installation identifiers, including a Firebase app-instance or installation
  identifier, a random identifier created for one app launch, and the Firebase Authentication UID
  after the App creates an anonymous identity or you sign in with Google. The App also reports the
  authentication type (none, anonymous, Google, or other).
- App, device, and network-derived information processed by our SDKs, such as app version,
  platform, device model, operating-system version, IP address, and approximate location inferred
  from the IP address.
- Crash diagnostics and device diagnostics (crash reporting), including stack traces, relevant app
  state, device metadata, and installation identifiers.
- Advertising-related identifiers and ad interaction signals (for ad delivery and measurement).
- App and device integrity information used to protect Firebase services from abuse, including app
  metadata, integrity or attestation material, licensing status, and short-lived App Check tokens.
- Optional Google sign-in and account data:
  - Firebase Authentication identifier (UID),
  - Google email address,
  - Google display name,
  - Google profile photo URL.
- Cloud profile and game-progress data when you sign in with Google:
  - display name and avatar URL,
  - the avatar you selected: your Google profile photo, no picture, or one of the avatars bundled with the app,
  - member-since year,
  - total hits, Classic and Survival best scores, daily Classic best score, and rank,
  - Campaign progress, including completed levels, stars, best level scores, reward status, and
    claimed sector milestones,
  - virtual Credits balance and whether the starting grant was claimed,
  - Booster inventory and rewarded Shield cooldown timestamp,
  - unlocked and selected cosmetic target styles,
  - a state schema version and last-updated timestamp used to synchronize this data across devices.
- Global leaderboard data:
  - your display name, leaderboard position, score for Classic, Survival, or Total Hits, and the avatar you selected may be shown to other players who use the leaderboard.
  - your Google profile photo URL is included in leaderboard entries only while you have selected that photo as your avatar. If you select one of the avatars bundled with the app, only its identifier is included; if you select no picture, no avatar data is included.
  - your email address and Firebase UID are not returned as leaderboard entries. Your email address is not included in Online Duel records; your Firebase UID is used there as the technical player identifier described below.
- Online PvP session data for matchmaking and match sync in Online Duel and Sector Duel:
  - Firebase Authentication identifier (an anonymous UID or your Google-linked UID, depending on whether you are signed in with Google),
  - display name, selected avatar identifier, and Google profile photo URL when one is available,
  - matchmaking queue state and timestamps,
  - match identifier,
  - live score updates, final score, match status, connection flags, and result timestamps,
  - for Sector Duel, per-target gameplay outcomes and aggregate hit, miss, accuracy, life-cell, turn, and round results; target positions are generated independently on each device and are not sent over the network,
  - the selected cosmetic target style used to render a player's side of a Sector Duel,
  - player connection/presence flags.
  - authenticated players can read the temporary queue for an online mode so that their devices can find an available opponent. Your matched opponent may see your display name and selected avatar during the match and on its result screen.
- Friends and friend-invitation data, available only to players signed in with Google:
  - a generated, rotatable friend code;
  - friendship relationships, incoming and outgoing friend requests, request status, and related timestamps;
  - availability and activity presence shared with accepted friends, such as online/offline status, whether you are in a menu or playing, an applicable Campaign level, and the last update time;
  - duel invitations between friends, including sender and recipient account identifiers, match type (Online Duel or Sector Duel), invitation state, expiry time, and match identifier;
  - friend-card data shown to accepted friends or involved request recipients: display name, selected avatar, and Classic best score. Your Google email address and Firebase UID are not displayed to friends as profile fields.
- Locally stored game data on your device, including settings, ratings, Campaign progress, virtual
  Credits, Booster inventory, cosmetic target styles, profile data, and ad counters.

## 2. Optional Google Account and Anonymous Play

You can play without creating a traditional account. The App does not provide a username/password registration flow.

For online PvP features, the App uses Firebase Anonymous Authentication to generate a technical identifier required to match players and synchronize online sessions.

You may optionally sign in with Google to save and synchronize your profile and game progress across devices. We do not receive or store your Google account password. Signing out clears the local signed-in state, but does not delete your cloud profile or game data.

## 3. Why We Process Data

We process data to:

- keep the app stable and fix crashes;
- measure app usage and performance, understand feature and ad-reward funnels, fix errors, and
  improve gameplay;
- run online PvP matchmaking and synchronize online match state;
- identify players to each other in Online Duel and Sector Duel using their display name and selected avatar;
- provide friend codes, friend requests, friend lists, availability indicators, and invitations to
  Online Duel or Sector Duel between accepted friends;
- authenticate optional Google accounts and synchronize profile, Campaign, virtual Credits,
  Booster, cosmetic, and game-progress data across devices;
- provide and operate the global leaderboard;
- process account-deletion requests;
- show and measure ads;
- verify that requests come from an authentic App and eligible device, protect backend services,
  and prevent abuse, cheating, and unauthorized access;
- deliver configuration such as feature availability, localized content, ad settings, and minimum
  supported app versions;
- remember local settings and progress on your device.

## 4. SDKs and Third Parties

The app uses third-party SDKs and services, including:

- Firebase Analytics;
- Firebase Crashlytics;
- Firebase Authentication (Anonymous Auth and Google sign-in);
- Cloud Firestore (signed-in profiles and game progress);
- Firebase Realtime Database (online matchmaking and online match synchronization);
- Firebase Cloud Functions (leaderboard, Friends, Sector Duel results, and account deletion);
- Firebase Remote Config (app configuration and feature availability);
- Firebase App Check, using Google Play Integrity on production Android builds and Apple App Attest
  on production iOS builds (backend protection and abuse prevention);
- reCAPTCHA Enterprise on the account-deletion website (backend protection and abuse prevention);
- Google Mobile Ads (AdMob);
- Google User Messaging Platform (UMP) for consent and privacy choices.

These services may process data under their own privacy terms:

- Google Privacy Policy: https://policies.google.com/privacy
- Firebase Privacy and Security: https://firebase.google.com/support/privacy

## 5. Consent and Privacy Choices

Where required by law, the app asks for consent for advertising/privacy choices using Google's User Messaging Platform (UMP). You can revisit privacy choices from the in-app Support / Privacy section.

On iOS, the app may request tracking authorization through Apple's App Tracking Transparency prompt.

## 6. Data Retention

- Local app data remains on your device until you clear app data or uninstall the app. Depending on
  your platform and account settings, a copy may also be included in a platform backup or a
  device-to-device transfer.
- On supported Android versions, local app data is excluded from cloud backup but may be included in
  a device-to-device transfer that you initiate while setting up another device.
- Signed-in cloud profile, game-progress, Campaign, virtual Credits, Booster, and cosmetic data
  remain in our Firebase services until you delete your Tap Dominion account, unless a longer
  retention period is required by law or necessary to resolve a security, fraud, or legal issue.
- Online PvP queue/match records are designed to be temporary and are cleaned up when matchmaking is cancelled, sessions end, or disconnections are detected. A private Sector Duel result receipt may be retained for the two participants until it is acknowledged or an associated account is deleted.
- Friend codes, friendship relationships, pending requests, invitations, and their technical mirrors remain while needed to provide the Friends feature. Removing a friend, cancelling or clearing a request or invitation, rotating a code, or deleting an account removes the relevant records; presence is temporary and is removed or marked offline when the session ends.
- App Check attestation material and tokens are retained according to the applicable attestation
  provider's and Firebase's retention rules.
- Analytics, crash, authentication, database, configuration, integrity, and advertising data
  retention is controlled by the corresponding third-party providers.

## 7. Account Deletion

You can permanently delete your Tap Dominion account from the App or at https://tapdominion.web.app/delete-account/. Deletion requires Google sign-in for the account being deleted and removes the Firebase Authentication user, cloud profile, synchronized Campaign progress, virtual Credits, Booster inventory, cosmetic target styles, stored game-progress data, friend code, friendship and request records, pending invitations, presence, Sector Duel result receipts, and active online-match records associated with that account. It does not delete your Google Account itself.

Deletion does not necessarily remove data that third-party providers retain independently, such as aggregated analytics, crash diagnostics, advertising records, or data they must retain under their own policies or legal obligations.

## 8. Children's Privacy

The app is not directed to children under the age where parental consent is required in your region.

## 9. Security

We rely on platform and third-party security controls, including encrypted transport where
applicable. We also use Firebase App Check and platform attestation services to help distinguish
authentic App requests and protect backend resources from abuse. These controls reduce risk but do
not guarantee that the App or its services will always be secure or available.

## 10. Your Rights

Depending on your region, you may have rights related to access, deletion, or objection to data processing.

For access, deletion, or other privacy requests, contact us:
- Email: support@zenarium.am

## 11. Changes to This Policy

We may update this policy from time to time. We will update the "Last updated" date when changes are made.

## 12. Contact

If you have questions about this policy:
- support@zenarium.am
