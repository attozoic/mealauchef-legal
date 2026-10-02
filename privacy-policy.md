# Privacy Policy — Meal au Chef

**Effective date:** 2026-10-02
**Last updated:** 2026-10-02

This policy explains what personal data Meal au Chef ("the app", "we", "us")
collects, how we use it, and the choices you have. It applies to the mobile
app on iOS and Android and any related services.

## 1. Who we are

**Data controller:** attozoic, based in Serbia.
**Contact:** support@attozoic.dev

You can reach us at that address for any privacy question, data-access
request, or deletion request.

## 2. Data we collect

We collect only what the app needs to function.

**Account data** (created when you sign up):
- Email address
- Password (never stored in plain text — hashed by our auth provider,
  Supabase)
- Account creation and last-sign-in timestamps

**Content you create in the app:**
- Recipes (title, description, ingredients, steps, servings, meal type,
  prep time)
- Images attached to recipes (either provided by you or automatically
  downloaded from the source URL when you extract a recipe)
- Source URL for extracted recipes (e.g. the Instagram post you saved from)
- Meal plans (7-day plans referencing your recipes)
- Shopping lists (auto-generated from meal plans or manual)
- User preferences (language, measurement system, default servings, theme)

**Usage data (minimal):**
- Monthly count of AI recipe extractions you've made this calendar month
  (used solely to enforce the free-tier quota)

**Subscription data:**
- Current tier (free or premium)
- Subscription source (Apple App Store or Google Play)
- Trial status and expiration date
- The store product identifier you subscribed to (e.g. "monthly", "yearly")

## 3. Data we do NOT collect

We do not collect any of the following:

- Analytics or behavioural tracking (no Google Analytics, no Firebase
  Analytics, no Mixpanel, no third-party tracking SDKs)
- Crash reports (no Sentry, no Firebase Crashlytics)
- Advertising identifiers (no IDFA, no AAID)
- Location data
- Contacts, calendar, or other device data
- Payment card details (Apple and Google handle payments; we never see
  card numbers)

## 4. How we use your data

- To authenticate you and keep you signed in
- To store and display your recipes, meal plans, and shopping lists
- To enforce the free-tier quota on AI recipe extractions (5 per calendar
  month)
- To determine whether you have access to premium features
- To respond to support requests you send us

We do not sell your data. We do not share your data with advertisers. We
do not profile you.

## 5. Third-party services

The app depends on a small set of processors, each with a specific role.

| Service | Role | Data shared | Region |
|---|---|---|---|
| **Supabase** | Authentication, database, storage | All account and content data | EU (Ireland) |
| **OpenAI** | AI-powered recipe extraction | The recipe text or web page content you're extracting | US |
| **RevenueCat** | Subscription management | Your user ID (same as your Supabase account ID), subscription events | US |
| **Apple App Store** | iOS payments + IAP | Your Apple ID (handled by Apple directly, we don't see it) | Apple's regions |
| **Google Play** | Android payments + IAP | Your Google account (handled by Google directly) | Google's regions |
| **Recipe source websites** (Instagram, blogs, etc.) | Fetching the page you're extracting | The URL is loaded via a headless browser in the app; the source site sees a normal page view | N/A |

Supabase, OpenAI, RevenueCat, Apple, and Google each have their own privacy
policies governing how they handle data they receive.

**About OpenAI specifically:** the recipe text you're extracting is sent to
OpenAI's API for parsing. OpenAI's API terms state they do not train their
models on data sent through the API. We do not send your account ID or any
identifying information along with the extraction request.

## 6. Where your data is stored

- **Primary storage:** Supabase project in the West EU (Ireland) region.
  All account data, recipes, meal plans, shopping lists, and images live
  there at rest, encrypted.
- **Backups:** managed by Supabase within the same region.
- **In transit:** all connections use HTTPS/TLS.

If you access the app from outside the EU, your requests still route to
the EU data location.

## 7. How long we keep your data

- Your account and content are kept as long as your account is active.
- If you delete your account, we delete your account and all associated
  content within 30 days. Automated backups continue to hold a copy for
  up to a further 30 days before being overwritten.
- Server logs (auth logs, edge-function logs) are retained by Supabase for
  up to 30 days for debugging and security auditing.
- Subscription entitlement records are kept for the duration of your
  subscription plus 12 months after cancellation for accounting purposes.

## 8. Your rights (GDPR)

Regardless of where you live, if you are in the EU (or Serbia, whose data
protection law mirrors GDPR) you have the following rights:

- **Access** — request a copy of the personal data we hold about you
- **Rectification** — correct inaccurate data (most is editable directly
  in the app)
- **Erasure ("right to be forgotten")** — request deletion of your account
  and all data
- **Portability** — receive your data in a machine-readable format; you
  can also export individual recipes as PDF directly in the app
- **Restrict processing** — ask us to stop processing your data in
  specific ways
- **Object** — object to processing based on our legitimate interests
- **Withdraw consent** — where processing is based on consent, you can
  withdraw it at any time (this doesn't affect processing before withdrawal)
- **Lodge a complaint** — with your national data protection authority
  (in Serbia: Poverenik za informacije od javnog značaja i zaštitu
  podataka o ličnosti)

To exercise any of these, email support@attozoic.dev. We respond within 30
days.

## 9. Security

- Passwords are hashed and never stored in plain text
- All network traffic uses HTTPS/TLS 1.2 or newer
- Database access is protected by Supabase Row Level Security — you can
  only read and write your own data
- We keep the number of people with production database access to a
  minimum (just the developer)

## 10. Children

Meal au Chef is not directed at children under 13. We do not knowingly
collect data from anyone under 13. If we learn we have collected data
from a child under 13, we will delete it. Contact us at
support@attozoic.dev if you believe we may have such data.

## 11. International transfers

Data collected in the EU is stored on servers in the EU. However, some of
our processors (OpenAI, RevenueCat, Apple, Google) are US-based, so some
processing happens in the US. Those transfers rely on the processors' own
Standard Contractual Clauses and adequacy mechanisms.

## 12. Changes to this policy

We may update this policy from time to time. When we do, we will:

- Post the new version at this URL with an updated "Last updated" date
- For material changes, notify you via in-app message or email at least
  14 days before the change takes effect

## 13. Contact

For any question or request related to this policy or your data:

**attozoic**
**Email:** support@attozoic.dev

---

*This policy is written in plain language on purpose. If any clause is
unclear, please email us and we'll explain.*
