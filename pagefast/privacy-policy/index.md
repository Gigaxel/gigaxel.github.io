# Privacy Policy for PageFast

Last updated: November 10, 2026

PageFast: Speed Reading is an iOS reading app developed by Mehmed Bazdar. This policy explains how PageFast handles information when you read, import books, browse the free book catalog, use AI retention quizzes, or subscribe to PageFast Pro.

## Reading and Local Storage

PageFast does not require you to create an account or sign in. Core reading works offline.

Your imported books and documents, reading position, bookmarks, highlights, reading sessions, goals, statistics, and app preferences are stored locally on your device. Generated quizzes and quiz attempts are also saved locally. Your device and Apple backup settings may determine whether local app data is included in device backups.

Importing or reading a document does not upload your library to the PageFast server. An excerpt is sent only when you request an AI retention quiz, as described below.

## Anonymous Installation and Server Data

When online features are used, PageFast creates a random installation identifier and an authentication token. The app stores these credentials in the iOS Keychain; the server stores a hashed version of the token. This identifier is not your name or email address, but it links the online activity of that installation.

The PageFast server stores the installation identifier, platform, app version and build number, locale, time zone, and creation and last-use timestamps. It also stores records needed to operate quizzes, subscription access, credit balances, usage limits, and fraud prevention.

Network requests expose technical information such as your IP address to the services receiving them. PageFast and its hosting and network providers, including Hetzner and Cloudflare, process technical request information to deliver and secure the service and limit abuse.

## AI Retention Quizzes

If you request an AI retention quiz, the app sends an excerpt from the reading session, quiz preferences such as question count and difficulty, and relevant request identifiers to the PageFast server. The server forwards the excerpt and generation instructions to the AI service through OpenRouter and the model provider that processes the request.

The full imported file and the rest of your library are not sent as part of this request. Do not request a quiz from material you do not want processed by an external AI service, including confidential or sensitive personal information.

The PageFast database does not store the raw source excerpt as a separate document. It stores a fingerprint of that text, request and usage metadata, and the generated quiz. **Generated questions, explanations, and supporting quotations can contain information or short passages from the source**, and these are stored as part of the quiz. Submitted answers, scores, completion time, and attempt timestamps are also stored on the server.

OpenRouter and the AI model provider process requests under their own policies and applicable service terms. Their retention and use of data depend on the provider and its settings. This policy does not promise that those providers never retain requests or use them to improve their services. See [OpenRouter's Privacy Policy](https://openrouter.ai/privacy).

## Subscriptions and Purchases

Apple handles subscription payments. PageFast does not receive your payment card or bank account details.

PageFast uses RevenueCat to manage subscriptions, verify entitlements, and manage quiz credits. The random installation identifier is used as the RevenueCat App User ID. RevenueCat processes purchase and subscription records, entitlement and credit information, and technical app and device information needed for these services. The PageFast server uses subscription and credit records to decide whether a quiz is available.

See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/) and [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## No Advertising

PageFast does not show ads and does not include an advertising SDK. PageFast does not request Apple's App Tracking Transparency permission, does not access the advertising identifier (IDFA), and does not track you across other companies' apps or websites. PageFast does not sell your personal information or share it for targeted advertising.

## Free Book Catalog

Catalog searches and browsing requests are sent to the PageFast server. Book files and cover images are downloaded directly from Project Gutenberg, so those requests expose your IP address and the requested resource to that service. The PageFast server hosts catalog metadata, not the downloaded books. See [Project Gutenberg's Privacy Policy](https://www.gutenberg.org/policy/privacy_policy.html).

## Analytics and Support

PageFast does not currently include a separate third-party product analytics or crash-reporting service. This does not exclude the operational records or the data processed by RevenueCat described above.

If you contact the developer, your email address, message, and any information you choose to provide are used to respond and resolve your request. Avoid sending your authentication token or sensitive document contents.

## Retention and Deletion

Local reading data remains on your device until you remove it using the app's available controls or remove the app, subject to iOS and backup behavior. Keychain credentials may persist after uninstalling. Removing a book or uninstalling PageFast does not automatically delete related server records, cancel a subscription, or delete records held by service providers.

Server records currently have no automatic expiration. They are retained to provide your quizzes and access history, maintain balances, prevent duplicate transactions and abuse, and meet applicable legal obligations. To request access, correction, or deletion of information linked to your installation, email **mehmedbazdaret@gmail.com** and include the **Support ID** shown in PageFast Settings so the records can be located. We may need to verify that the request relates to your installation. Some transaction, security, or legally required records may need to be retained.

Manage or cancel subscriptions through your Apple account. Requests concerning information independently held by Apple, RevenueCat, or an AI provider may also need to be directed to that provider.

## Your Rights and International Processing

Depending on where you live, you may have rights to access, correct, delete, or obtain a copy of personal information, object to or restrict processing, and withdraw consent. You may also have the right to complain to your local data protection authority. Contact the developer to exercise applicable rights; using a privacy right will not itself result in discrimination.

Information may be processed outside your country by the developer and service providers. Where applicable, processing relies on providing the features you request, legitimate interests in operating and protecting the service, or legal obligations.

## Children's Privacy

PageFast is not directed at children under 13 and does not knowingly collect personal information from them. If you believe a child has provided personal information, contact the developer so it can be investigated and removed as appropriate.

## Security and Policy Changes

PageFast uses iOS app storage and Keychain protections, HTTPS for production service requests, and authenticated access to installation-specific server data. No storage or transmission method is completely secure.

Updates to this policy will be posted on this page with a revised "Last updated" date.

## Contact

Mehmed Bazdar, developer of PageFast

[mehmedbazdaret@gmail.com](mailto:mehmedbazdaret@gmail.com)
