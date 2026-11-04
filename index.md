# Privacy Policy — Koinz

**Last updated:** November 4, 2026

Kenny Lee ("we", "us") operates the mobile application **Koinz**. This page explains how we handle information when you use our app.

## Summary

Koinz is a personal finance app. You sign in with Google and your bookkeeping data syncs to our cloud database (Supabase). Free users see ads via Google AdMob; optional Koinz Plus subscriptions are processed via Google Play and RevenueCat.

## Information We Collect

### Account information

When you sign in with Google, we receive your **email address** and a unique user identifier. We use this only to authenticate you and associate your bookkeeping data with your account.

### Financial data you enter

You may store wallets, transactions, categories, split bills, projects, household memberships, assets, and related notes. This data is **created by you** in the app and stored in our cloud database (Supabase) to sync across devices.

We do **not** connect to your bank accounts. On Android, if you turn on **Auto bookkeeping**, Koinz reads payment notifications only from the apps you pick (see below).

### Payment notifications (Android, optional)

If you grant notification access and pick which apps to follow, Koinz reads payment notifications from those apps only. Each notification is read **on your device** to work out the amount, merchant and wallet. The notification text is not uploaded. Only the entries you keep, or that you set to record automatically, are saved to your account like any other entry. You can turn this off at any time in Koinz or in Android settings.

### AI suggestions (optional, off by default)

Koinz works without AI. If you turn on **AI suggestions** (Features → AI suggestions), some features send text to a third-party AI service through our server:

- **Chat entry:** what you type (e.g. "lunch 68 Octopus"), plus the names of your wallets, categories and projects, so the service can propose entries.
- **Category suggestions:** the note of one entry, plus your category and project names.
- **Finance assistant (Koinz Plus):** your question and your category names. To word the answer, it also gets figures the app already calculated from your records (e.g. a spending total). Your full transaction list is not sent.

Requests go through our server, so your email and account ID are not sent to the AI service. Each account has a daily usage limit.

AI output is only a suggestion. The app checks every value against your own data. **Nothing is saved until you confirm it**, and entries made by chat can be undone for 7 days. The AI cannot edit or delete your existing records. If AI suggestions are off, or the service is unavailable, chat entry still works using on-device parsing.

### Device and usage data

- **AdMob (Google)** may collect device identifiers (such as the advertising ID) and ad interaction data to show banner and occasional full-screen ads to free users.
- **Google Play Billing / RevenueCat** processes subscription purchases; we receive entitlement status (premium or not), not your full payment card details.
- **Supabase** hosts authentication and database services under their [privacy policy](https://supabase.com/privacy).

### Market data and exchange rates

To show prices and currency conversions, the app requests public quotes from **Yahoo Finance**, **CoinGecko**, and the **Frankfurter** exchange-rate API. These requests contain only ticker symbols or currency codes. Your account, balances, and holdings are never sent to these services.

## How We Use Information

- Provide app functionality (sync, household views, exports)
- Authenticate users
- Show ads to non-subscribers
- Validate and restore subscriptions
- Improve reliability and fix bugs

We do **not** sell your personal data.

## Data Sharing

We share data only with service providers necessary to run the app:

| Provider | Purpose |
|----------|---------|
| Supabase | Authentication & database hosting |
| Google (Sign-In, Play, AdMob) | Sign-in, subscriptions, advertising |
| RevenueCat | Subscription entitlement management |
| Yahoo Finance, CoinGecko, Frankfurter | Public price and exchange-rate lookups (ticker symbols and currency codes only) |
| Third-party AI service | Optional AI suggestions: entry text, notes, category / wallet / project names (only when you turn it on) |

Each provider processes data under their own privacy policies.

## Data Retention

Your data is kept while your account is active. You may delete your bookkeeping data or your entire account from **Settings** in the app. Deletion removes your transactions, wallets, and auth account from our systems, subject to brief backup retention by infrastructure providers.

## Security

Data is transmitted over HTTPS/TLS. Database access is protected by row-level security policies so users can only access their own data (and permitted household/project peers).

## Your Rights

Depending on your region, you may have rights to access, correct, export, or delete your data. Use in-app account deletion or email us at the contact below.

## Children's Privacy

Koinz is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy from time to time. The "Last updated" date at the top will change when we do.

## Contact

If you have questions about this privacy policy, contact us at:

**Email:** [lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com)

---

## 隱私權政策 — Koinz（繁體中文摘要）

**最後更新：** 2026 年 11 月 4 日

Koinz 為個人理財 App。以 Google 登入後，記帳資料同步至雲端（Supabase）。免費版顯示 Google AdMob 廣告；可選 Koinz Plus 訂閱透過 Google Play 與 RevenueCat 處理。

- **帳號：** Google 登入取得 email 與使用者 ID，僅用於驗證與資料關聯。
- **記帳資料：** 錢包、交易、分帳、專案標籤等由您輸入，存於 Supabase 以跨裝置同步；不連接銀行帳戶。
- **自動記帳（Android，可選）：** 只讀取你揀選嘅 App 嘅付款通知，喺手機上處理，通知內容唔會上載；只有你保留嘅記錄會同步。
- **AI 建議（可選，預設關閉）：** 開啟後，對話記帳輸入嘅文字、記錄備註、錢包／類別／專案名稱，以及理財精靈問題同已計好嘅數字，會經我哋伺服器傳去第三方 AI 服務；唔會傳送你嘅 email 或帳號 ID。AI 只提供建議，你確認之前唔會寫入任何資料，亦唔會修改或刪除現有記錄。
- **第三方：** AdMob（廣告）、RevenueCat / Google Play（訂閱）、Supabase（後端）；Yahoo Finance、CoinGecko、Frankfurter 只用於查詢公開報價與匯率，只會收到代號或幣別，不含你的帳號或資產資料。
- **刪除資料：** 可在 App「設定」刪除記帳資料或整個帳號。
- **我們不出售個人資料。**

如有疑問，請來信：**[lee.mh.kenny@gmail.com](mailto:lee.mh.kenny@gmail.com)**
