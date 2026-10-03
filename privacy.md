# YES Audio privacy policy

Updated 3 October 2026. YES Audio is an audio app by Chris Frost. This policy covers listening and downloads, optional Apple accounts and listening research in account-enabled builds, demo memberships, purchases where enabled, and our support services. Features available in your build are shown in the app.

## Listening and local storage

You can listen without creating an account. YES Audio stores your favorites, playback positions and completed-session history on your device so you can resume a session and see your listening summary. It does not upload that existing local history. If you separately choose to share listening research, the app collects new usage summaries as described below. The app does not request access to your microphone, camera, contacts, precise device location or health records.

Audio streams over HTTPS when you play a session that has not been downloaded. Streaming and downloading use your internet connection and may use mobile data. You can choose to download sessions to the app's local storage for later offline listening, and remove those downloads in the app. Downloads are saved only after you request them and are checked for completeness before being made available offline. A fresh installation does not include the audio files. Temporary playback buffers are different from a completed offline download.

The app supplies the current track title, artwork and playback state to iOS for the lock screen and system audio controls. It does not include an advertising SDK. Purchase information is processed as described below.

## Optional Apple account

In account-enabled builds, you can use Sign in with Apple from **Account & privacy**. Signing in creates a YES Audio account; it does not enable listening research. Apple authenticates you and provides an app-specific account identifier. We do not request Apple's name or email scopes or receive your Apple password. Apple and our authentication provider, Supabase, process identity, session and security information to operate sign-in; Apple may include an email address or relay address in identity information it makes available. We do not use that information for advertising or infer your gender from it.

YES account records and research data are stored in a dedicated Supabase project. The app keeps account session credentials in the iOS Keychain. Your account identifier, sign-in/session records, research choice and policy/consent records support account access and your privacy choices. Account and consent records remain until you delete the account, except for the research deletions described below. This account feature does not sync your favorites or playback positions between devices.

## Optional listening research

**Share listening research** is off unless you choose to enable and save it in **Account & privacy**. Listening, signing in and using a membership do not require research participation. With your choice enabled, we receive your account identifier, app-session and listening-session identifiers, session start times, track identifiers, cumulative time actually heard, qualifying completion and days you use the app. We summarize this information by month to understand popular tracks, repeat listening and how usage changes over time, and to improve YES Audio. These are account-linked product-usage records, not anonymous records or a clinical study. We do not collect microphone recordings or send your listening research to RevenueCat.

You may also select a gender answer, including **Prefer not to say**, or leave it unanswered. This is optional and separate from your ability to listen. We use volunteered answers to examine usage patterns among participating listeners, not to infer characteristics of other users. We do not report gender comparison groups with fewer than ten responding accounts. We do not sell this research data, share it with data brokers, or use it for cross-app advertising tracking.

While offline, the app can hold an account-specific queue of unsent research summaries, bounded to 512 entries and 30 days, for upload when connected. The queue is excluded from device backups. Research begins with your choice; the app does not backfill earlier listening. Scheduled daily cleanup removes detailed uploaded session records older than 90 days. Monthly summaries cover the current UTC month and 23 preceding months; daily activity dates are kept for 24 months. Provider security logs and backups have separate retention, as explained below.

Turning research sharing off immediately stops collection on that device and clears its unsent research queue. When connected, the app clears your shared gender answer and deletes your detailed research sessions, monthly summaries and activity dates from the active database. A minimal disabled preference record remains so your choice is respected. If you are offline, the app shows that withdrawal still needs to sync. Other devices may learn of the change when they reconnect; the server rejects uploads made under an earlier consent once withdrawal is received. Re-enabling starts a new consent period.

## Demo membership beta

A build labelled **Demo membership** previews the monthly and annual plans and can unlock demo access on that device. It does not create an Apple purchase, start a real trial, charge you or create an auto-renewing subscription. In this demo mode the app does not contact StoreKit or RevenueCat for purchases; demo membership state is stored locally. Apple sign-in and any listening research you explicitly enable still use the account services described above. A future build that uses actual Apple purchases is identified separately in its checkout.

## Apple purchases, where enabled

In builds with purchases enabled, Apple processes payments for monthly or annual YES Audio memberships. The annual plan offers a seven-day introductory free trial to eligible subscribers, followed by annual billing; the monthly plan bills monthly. The purchase screen shows the localized price, billing period and any eligible trial before confirmation. We do not receive your payment-card details.

In these purchase-enabled builds, RevenueCat receives an app-specific identifier, transaction and purchase history, subscription status, and related technical information to validate purchases, restore access, recognize renewals, expirations and refunds, and provide purchase reporting. If you sign in, our server provides a random purchase identifier mapped to your YES account so membership can be connected to it. This is necessary account processing and does not depend on optional research consent. Guest purchase access uses a separate app-specific purchase identifier. Your favorites and listening research are not sent to RevenueCat. We do not send your Apple account identifier, name or email as RevenueCat purchase identifiers or use purchases for cross-app advertising. See [RevenueCat’s privacy policy](https://www.revenuecat.com/privacy/).

Restore purchases uses the Apple Account used for the original purchase. Verified purchase information is cached on the device for offline access. Existing permanent Starter Collection purchases retain access to their purchased recordings without a membership. Membership expiration does not remove those permanent rights. An expired membership or refunded purchase can remove its corresponding access after purchase information is refreshed.

Subscriptions renew automatically unless cancelled through Apple. Use [Manage Apple subscriptions](https://apps.apple.com/account/subscriptions), or open Settings, tap your name and select Subscriptions. Cancel at least 24 hours before your trial ends to avoid its annual charge. Cancelling stops future renewal and does not automatically refund a payment; [refund requests are handled by Apple](https://support.apple.com/en-us/118223). Deleting the app or your YES account does not cancel an Apple subscription. Account deletion removes our account-to-purchase-identifier mapping but does not automatically erase Apple's transaction records or RevenueCat's purchase records. Those records may remain for purchase administration, fraud prevention and applicable recordkeeping requirements. Contact us for privacy requests.

## Hosted audio and connection information

Audio is delivered through Supabase Storage and its content-delivery infrastructure. To deliver a stream or download, these services receive connection and request information, such as your IP address, the requested audio URL, request time, platform or browser headers, byte-range requests, response status and response timing. Request paths can identify which session was requested. The hosting infrastructure also records approximate city and country information derived from an IP address.

Hosting and authentication providers retain operational and security logs beyond the immediate request. These records support delivery, troubleshooting and protecting the service; streaming and sign-in are not anonymous or entirely on-device operations. Turning off optional listening research does not stop the operational processing needed for services you continue to use. Our local favorites and completion records are separate from these service logs. Provider log and backup retention depends on the service configuration and providers' applicable policies; the research cleanup periods above do not promise immediate deletion from backups or operational logs. Backups may retain deleted records until they expire, and restored data must have account deletions and research withdrawals reapplied before normal access resumes. See [Supabase's privacy policy](https://supabase.com/privacy).

Apple, Supabase, RevenueCat where enabled, GitHub and support providers may process information in countries other than your own. Their privacy notices describe their processing and applicable transfer safeguards.

## Your controls

You can remove saved audio using the app's download controls. Use **Clear listening history** in **Your rhythm** to clear completed-session history and saved playback positions. Favorites remain until you remove them individually. Clearing local data does not erase hosting logs or support correspondence.

In **Account & privacy**, you can change or withdraw research choices, sign out, export your YES account profile and shared listening records as a JSON file, or delete your account and research data. Exporting does not automatically send the file to anyone: you choose whether and where to save or share it. The export is of YES account/research records, not Apple's billing records or every provider's operational logs. Contact us if you need help with access, correction, deletion or another privacy request.

**Delete account and research data** removes your dedicated YES authentication account, app profile, consented research records and any account-to-purchase-identifier mapping from the active database, and revokes its YES sessions. The app can ask you to sign in with Apple again to revoke Apple's separate authorization. If Apple is unavailable or automatic revocation cannot complete, YES data deletion can still finish and the app explains how to disconnect YES Audio in your Apple account settings. Signing out, disconnecting Apple and deleting your YES account are different actions; signing out alone does not erase server data. Completed local downloads, favorites and local listening history have their own controls. Copies you previously exported or shared remain wherever you saved them.

Deleting the app removes its local app data from that device. Offloading an app may preserve data. Completed audio downloads are marked as excluded from device and iCloud backups. Other local preferences and history may be governed by your Apple backup settings; YES Audio does not provide its own cloud sync. When you have a completed offline download, playing that local copy does not require fetching that session's audio again.

## TestFlight, website and support

For beta installations, Apple automatically collects TestFlight crash and usage information and shares it with the app provider. Feedback you submit is shared too, and may include your name or email depending on the invitation method. We use beta reports to investigate problems with YES Audio. See [Apple's TestFlight privacy information](https://www.apple.com/legal/privacy/data/en/test-flight/).

Our support and privacy pages are hosted on GitHub Pages. Opening those pages sends a web request to GitHub and its delivery providers, which may process connection and usage information under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

If you email us, we receive the address, message and attachments you choose to send. Email and support providers process that correspondence to deliver and manage your request. Please do not send sensitive information that is unnecessary for resolving your issue. A fixed automatic deletion schedule for support correspondence or exported beta reports has not been established.

## Contact and changes

For support, privacy questions, or requests concerning information you have sent us, contact [soundpaw@hotmail.com](mailto:soundpaw@hotmail.com). Please describe your request without sending passwords or payment information. We will explain what information we can locate and what action is available, subject to applicable requirements.

We will update this policy when the app's data practices change. The date above identifies the current policy text.
