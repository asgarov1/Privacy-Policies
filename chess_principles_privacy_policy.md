# Privacy Policy — Chess Principles

**Effective date:** November 23, 2026

**Developer:** Javid Asgarov

Chess Principles is an educational iOS app with guided chess explanations and
practice exercises. Lessons through Bishop pair are free; later lessons require
an active Premium subscription.

## Information stored on your device

The app stores the identifiers of completed principles on your device so it can
remember your progress and unlock the next step. Practice selections and hints are
held in memory for the current session. No account is required.

A password-protected developer override can enable Premium on this device. The
app stores only its enabled setting locally in UserDefaults, so it persists across
launches until disabled. The entered password is held temporarily in memory and
is not saved, logged, or transmitted. This feature does not check your iCloud
identity, contact a server, or create a purchase. Disabling it preserves lesson
progress and any active paid subscription.

The app also keeps up to 300 diagnostic log entries in memory for the current app
session. These include timestamps, the app version, lesson identifiers, practice
moves and their outcomes, and progress events. Logs are not saved to disk, included
in backups, or sent automatically. You can view or clear them under Information →
Logs. They are discarded when the app process ends. If you choose Share logs, the
system share sheet sends the displayed log text to the destination you select;
that destination's own privacy practices apply.

The developer does not receive or sell your learning progress. Computer evaluation
sends practice positions to a third-party service as described below. The app has no advertising,
analytics, tracking, or third-party SDKs. It does not request access to
contacts, location, microphone, camera, or photos.

## Computer evaluation

When a practice board is displayed or a move changes its position, the app sends
that position in FEN notation to **chess-api.com** over HTTPS to request a computer
evaluation. FEN describes the pieces, side to move, castling rights, en passant
square, and move counters. Requests also specify analysis settings. They do not
include your saved completion history, diagnostic logs, language preference,
subscription status, name, email, or a persistent app-generated identifier.

Like any internet service, chess-api.com receives your IP address and normal
connection metadata when handling requests. The service operates independently;
its handling and retention of server-side data are outside the developer's
control. See [chess-api.com](https://chess-api.com/) for service information.

The app uses an ephemeral network session without stored cookies, credentials or
a disk response cache. Successful evaluations are cached only in memory, with a
limit of 200 positions. The app does not send evaluations or positions to a
developer-operated server. Evaluation is informational and never determines
whether an exercise is passed. If the service is unavailable, times out or returns
an unusable response, the evaluation disappears and practice continues normally.
Evaluation requires internet access; the lessons and authored moves work without it.

## Subscriptions and Apple

Optional auto-renewable monthly, quarterly (three-month), and yearly subscriptions
are sold and managed by Apple through the App Store and StoreKit. Apple processes
your purchase and payment information under its own privacy policy. The developer
does not receive your payment-card details.

The app requests subscription products and prices from Apple and reads verified
StoreKit transactions to determine whether Premium access is active. StoreKit
may cache transaction information on your device. The app does not send your
transaction identifiers, receipts, subscription status, or learning progress to
a developer-operated server, and does not store a separate purchase history.
An internet connection may be needed to load plans, buy or restore purchases,
and update subscription status. Restore purchases contacts Apple only when you
choose that action. Manage subscription opens Apple's subscription settings.

## Device backups and external links

Locally saved progress and the developer override setting may be included in
device backups according to your Apple settings. Apple operates those services
under its own privacy policy. The developer
cannot access your backups. Opening the privacy-policy link uses your browser and
visits GitHub, whose own privacy policy applies to that visit. Opening Terms of
Use visits Apple; Apple’s privacy practices apply there.

The “See our other apps” page displays a bundled catalog and artwork without
network requests. Choosing an app opens its App Store page; Apple’s privacy
practices apply to that visit. No learning progress or diagnostic logs are sent
with these links.

## Your choices

Free lessons are available without an internet connection. Premium lessons are
available while StoreKit confirms an active entitlement, including cached access
when available offline, or while the local developer override is enabled. You
can disable the override by holding the journey’s knight for three seconds and
choosing Disable premium mode. You can restore purchases or manage/cancel a
subscription from the Premium screen. Deleting the app does not cancel an Apple
subscription.

Subscription expiry does not erase your completed-principle progress. Deleting the
app removes its local progress, subject to your device and backup settings. There
is no developer-held account or personal dataset to delete or export.

## Children

No account, advertising or analytics is provided for any user, including children.
Computer-evaluation requests use the same third-party service described above.

## Changes and contact

This policy will be updated if the app's data handling changes.
For questions, contact **office@asgarovsoftware.com**.
