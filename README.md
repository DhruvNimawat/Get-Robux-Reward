🎮 Get Robux Reward – Android Quiz Platform
Get Robux Reward is a professionally engineered Android engagement and monetization platform designed as an interactive gaming trivia application. Featuring a modern lavender aesthetic, this repository showcases a production-ready architectural pipeline combining a synchronized UI frontend with a robust, cloud-controlled backend.
✨ Key Features
🕹️ Core Gameplay & UX
The 18-Level S-Curve Ladder: A mathematically synchronized progression path. Interactive nodes and background vector paths align dynamically across all device aspect ratios.
Smart Quiz Engine: Each level hosts a 5-question gaming trivia set featuring dynamic answer-shuffling to prevent pattern memorization.
Premium Animations: Custom 6-second simulated loading transitions with native progress indicators to maximize user engagement.
💰 Cloud-Controlled Monetization
100% Server-Driven Ads: All Google Ad Manager logic is decoupled from the client code. The app fetches a remote config.json on launch.
Instant Over-the-Air Updates: Toggle ad visibility, switch ad placement frequencies, or update Ad Unit IDs instantly without pushing store updates.
Hybrid Ad Placement: Programmed for optimal UX with persistent bottom banners and incentivized rewarded video triggers.
⚙️ Production Architecture
Firebase Firestore: Real-time synchronization of user profiles, advertising IDs, and virtual balances.
Firebase Cloud Messaging (FCM): Fully integrated push notification architecture for targeted user re-engagement.
Dual-Layer Caching: Utilizes SharedPreferences as a high-speed local cache layer to ensure offline functionality and instant state restoration.
🛠️ Tech Stack
Layer	Technology
Frontend	Native Android SDK (Kotlin/Java), XML, Custom Canvas
Database	Firebase Firestore
Remote Configuration	Cloud-hosted JSON Architecture
Monetization	Google Ad Manager SDK (Banner & Rewarded)
Analytics & Notifications	Firebase Analytics, Firebase Cloud Messaging (FCM)
