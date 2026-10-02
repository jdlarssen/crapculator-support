# Crapculator privacy policy

**Effective date: 2 October 2026**

Crapculator has no app accounts or ads. Build 8 and earlier have no in-app analytics service and do not send gameplay or settings to a developer-operated server. Later versions that include PERSONNEL → PLAY DATA offer optional play statistics, disabled by default, as described below.

## On your device

Your game progress, earned dispensations and display settings are stored locally. Crapculator does not provide its own cloud-save service. Deleting the app removes its local data; restoring a purchase does not restore your game progress. Device backups are managed separately by your operating system.

## Purchases and Apple services

The optional one-time purchase, The Raise, uses Apple's in-app purchase system. Looking up the offer, purchasing and restoring purchases can connect to Apple's services. The app checks Apple's verified purchase information on your device to decide whether paid rounds are unlocked. We do not receive your payment-card details or Apple Account password.

Apple processes purchases and may provide the developer with sales, usage or diagnostic reports according to its services and your sharing settings. TestFlight also provides testing information and any feedback you choose to submit. These services are separate from in-app tracking. See [Apple's privacy information](https://www.apple.com/legal/privacy/).

## Optional play statistics (versions that include PLAY DATA)

Crapculator can share optional play statistics to help us understand which rounds
people play, where progress slows, whether they return, and how the unlock screen
is used. Sharing is off by default. You can choose ENABLE when invited after the
first round, or change your choice in PERSONNEL → PLAY DATA. Declining does not
change the game, your progress, purchases, or access.

If you enable sharing, the app creates a random identifier used only for these
statistics. It sends play-session starts; round starts, completions and pauses;
round number, grade, aggregate calculation count and elapsed foreground time;
unlock-screen visits, purchase/restore button actions and access-opening events;
and the app build, platform and event time. Access opening is not proof of a new
purchase. We do not send individual keys, calculations, purchase receipts,
transaction identifiers, your name, email, advertising identifier, or saved game
identifier. We do not record your screen.

We use PostHog's EU service to process these statistics. Network connections
necessarily expose an IP address to the receiving infrastructure. Our project
is configured to discard IP addresses from analytics events and disables
location enrichment and person profiles. The random identifier lets us link
voluntarily shared activity from the same app installation. These records are
pseudonymous; we do not describe them as irreversibly anonymous.

You can turn sharing off at any time in PERSONNEL → PLAY DATA. This immediately
stops new collection and sending, and clears the app's queued statistics and
local analytics identifier. A request already delivered cannot be recalled.
Previously received statistics remain with PostHog under its retention settings;
turning sharing off does not delete historical records. Re-enabling generates a
new identifier. The app does not upload play history collected before consent.

We use the data for product improvement, not advertising or tracking across other
companies' apps or websites. The current free service retains analytics data for
up to its one-year retention window; this is not a promise that consent withdrawal
triggers immediate erasure from all provider storage or backups. For privacy
questions, use the contact details in this policy.

## Sharing and support

If you choose the game's share action, the selected result text is passed to the destination you choose through the system share sheet. That destination's privacy practices apply.

If you [open a support issue](https://github.com/jdlarssen/crapculator-support/issues), your GitHub username and what you post are visible publicly. We use that information to respond to your request. Please do not post passwords, payment information or other private details. GitHub handles information on its service under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Questions about this policy can be raised through the same support page. If the policy changes, the updated version and effective date will be published here.
