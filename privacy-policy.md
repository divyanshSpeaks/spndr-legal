# SPNDR — Privacy Policy

**Last updated:** 4 August 2026

SPNDR is a local-first expense tracker. Your expenses live on your device, not on our servers. This policy explains exactly what data exists, where it lives, and who can see it.

SPNDR is provided by **DIVYANSH BHARDWAJ** ("we", "us"). Questions: **hello.spndr@gmail.com**.

---

## 1. Short version

- Your expenses, categories, budgets and receipt images are stored **only on your device**.
- We do **not** run cloud sync, and we do **not** upload your financial data anywhere.
- We use **no analytics, no advertising, and no third-party trackers**.
- An account (email + password) is **optional** and is used only to sign in.
- Receipt scanning runs **on your device**; receipt images are not sent to us or to any OCR service.

---



## 2. Data stored on your device

The following is written to a private database inside the app's own storage area and never leaves your device unless you choose to export or share it:

- Expenses (amount, date, note, merchant, category)
- Categories and budgets
- Currency preference and cached exchange rates
- Theme and reminder preferences
- Receipt images, **only if** you save a scanned receipt with an expense
- A cached copy of your subscription tier and signed-in email address, so the app works offline

Deleting the app removes all of this data from your device. We cannot recover it for you.

## 3. Account data (optional)

You can use SPNDR fully as a guest. If you choose to create an account, authentication is handled by **Supabase**, which stores:

- Your email address
- A securely hashed password (we never see or store your password)
- An account identifier and account timestamps

Your login session token is stored in the device keychain (iOS Secure Store). Your expenses are **not** attached to this account and are **not** uploaded.

**Deleting your account:** the app includes an in-app **Delete account** option (Account screen). This permanently deletes your login from our authentication provider. Expenses stored on your device are kept, and you can continue using SPNDR as a guest.

## 4. Camera, photos, and receipt scanning

If you use receipt scanning, SPNDR requests access to your camera and/or photo library. The image is processed by **on-device text recognition** (Apple Vision / Google ML Kit) to pre-fill an expense.

- The image and recognized text are **not sent to us or to any third-party OCR service**.
- If you do not save the receipt with the expense, the image is discarded.
- If you do save it, the image is stored in the app's private storage on your device and is deleted when you delete that expense.



## 5. Purchases

SPNDR Pro is sold through the **Apple App Store**, and subscription status is managed using **RevenueCat**.

- Payment is processed by Apple. We never receive your card details.
- RevenueCat receives your purchase receipt and an app user identifier (your account ID when signed in, otherwise an anonymous ID) so your Pro access can be restored on your devices.
- We do not receive your name, billing address or payment method from Apple.



## 6. Network connections

SPNDR is offline-first. It makes network requests only for:

- **Authentication**, if you sign in or create an account (Supabase)
- **Purchases and entitlement checks** (Apple, RevenueCat)
- **Currency exchange rates**, fetched from a public rates API. This request contains no personal or financial data; as with any web request, the provider can see your IP address.



## 7. Notifications

The optional daily reminder is a **local notification scheduled on your device**. SPNDR does not use push notification servers and does not send your device token anywhere.

## 8. Analytics, advertising and tracking

SPNDR contains **no analytics SDK, no advertising SDK, and no cross-app or cross-site tracking**. We do not sell or share personal data, and we do not build user profiles.

## 9. Exporting your data

CSV export uses the iOS share sheet. Where the exported file goes is entirely your choice; once shared, that copy is outside SPNDR's control and this policy no longer governs it.

## 10. Data retention

- Device data is retained until you delete the expense, the receipt, or the app.
- Account data is retained until you delete your account in the app.



## 11. Children

SPNDR is not directed at children under 13, and we do not knowingly collect personal information from them.

## 12. Your rights

Because your financial data stays on your device, you control it directly: edit or delete any entry in the app, export it as CSV, or delete the app to erase it. For account data, you can delete your account in-app at any time, or contact us at **hello.spndr@gmail.com** with a request regarding access, correction, or deletion.

## 13. Changes to this policy

If this policy changes materially, we will update the "Last updated" date above and, where appropriate, note the change in the app or on the store listing.

## 14. Contact

**DIVYANSH BHARDWAJ** — **hello.spndr@gmail.com**