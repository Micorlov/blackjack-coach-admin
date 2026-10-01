# Blackjack Coach Admin

Single-file admin panel (`admin.html`) for the Blackjack Coach app's anonymous usage stats.
Sign-in is Google, restricted to the admin account; Firestore rules (`firestore.rules`) are the real gate.

- Live: https://micorlov.github.io/blackjack-coach-admin/admin.html
- Firebase project: `blackjack-coach-stats` (Spark plan, no Cloud Functions)
- Deploy rules: `firebase deploy --only firestore`
