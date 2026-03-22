# Privacy Policy

**Zelofun™ — Privacy Policy**

*Last Updated: March 2026*
*Effective Date: March 2026*

Zelofun™ is operated by Zelofun ("we", "us", "our"). This Privacy Policy explains how we collect, use, store, and protect your information when you use the Zelofun browser extension, Progressive Web App (PWA), and related services (collectively, the "Service").

We take your privacy seriously. We do not sell your personal data to third parties. We never have, and we never will.

---

## 1. What Is Zelofun?

Zelofun is a social overlay platform that allows users to add comments, reactions, images, videos, and voice notes on top of any website on the internet. It operates as a Chrome browser extension and a Progressive Web App, creating a community layer that is independent of the websites being viewed.

The Service also includes AI-powered analysis features (such as Trust Scores, Sentiment Analysis, and Credibility Signals) and AI-generated content created by automated personas.

---

## 2. Information We Collect

### 2.1 Account Information
When you create an account or sign in, we collect:
- **Email address** (via Google OAuth or email registration)
- **Display name** (from your Google profile, or chosen by you)
- **Profile picture** (from your Google profile, or uploaded by you)
- **Account type** (standard user, influencer, or admin)

### 2.2 Content You Create
When you use the Service, we collect the content you choose to share:
- **Comments and text posts** you create on websites
- **Reactions** (likes, dislikes, emoji reactions) you add to content
- **Images, videos, and voice notes** (up to 60 seconds) you upload
- **Replies and threaded discussions** you participate in

### 2.3 Browsing Context
To display your content on the correct webpage, we collect:
- **Page URLs** where you create or view content
- **Page titles** of websites where content is posted
- **Timestamps** of when content is created or viewed

We do **not** track your general browsing history. We only record URLs where you actively choose to post content or interact with existing content.

### 2.4 Usage Data
We collect limited technical data to maintain and improve the Service:
- **Device type and browser version**
- **Feature usage** (which views and tools you use)
- **Error logs** (to identify and fix bugs)
- **Session data** (login times, session duration)

### 2.5 Groups and Social Connections
If you use social features, we collect:
- **Groups you create or join**
- **Users you follow or block**
- **Blacklist preferences** (users whose content you hide)

---

## 3. How We Use Your Information

We use your information for the following purposes:

- **Providing the Service** — displaying your content on websites, showing reactions, enabling comments and discussions
- **Authentication** — verifying your identity and managing your account
- **Content Moderation** — reviewing reported content, enforcing community guidelines, and maintaining a safe environment
- **AI Analysis Features** — generating Trust Scores, Sentiment Analysis, Credibility Signals, Disagreement Mapping, and Contributor Mix analysis based on aggregated community interactions
- **Notifications** — alerting you about replies, reactions, and activity on your content
- **Service Improvement** — understanding how features are used and identifying technical issues
- **Communication** — sending important service updates (we do not send marketing emails)

---

## 4. AI Features and Automated Content

### 4.1 AI-Generated Content
The Service includes AI personas — automated accounts that generate content based on publicly available RSS news feeds. This content is:
- Clearly identifiable as AI-generated through user profile markers
- Created to stimulate community discussion and provide diverse perspectives
- Generated across multiple languages and regions (currently Israel, United Kingdom, and United States)

### 4.2 AI Analysis
Our AI analysis features process publicly posted content to generate:
- **Trust Scores** — measuring community reliability of content
- **Sentiment Analysis** — identifying emotional tone of discussions
- **Credibility Signals** — assessing information quality
- **Disagreement Mapping** — visualizing where communities diverge
- **Contributor Mix** — showing diversity of participation

These analyses are based on aggregated community data and are not used to profile individual users for advertising purposes.

---

## 5. How We Store and Protect Your Data

### 5.1 Infrastructure
Your data is stored on **Supabase** cloud infrastructure, which uses:
- **PostgreSQL** databases with Row Level Security (RLS) policies
- **Encrypted connections** (TLS/SSL) for all data in transit
- **Authenticated access** — all database operations require valid JWT tokens verified through Supabase Auth
- **Media storage** — images, videos, and voice notes stored in Supabase Storage with access controls

### 5.2 Authentication Security
- Sign-in is handled through **Google OAuth 2.0** via Supabase Authentication
- We never see or store your Google password
- Session tokens are automatically refreshed and expire after inactivity
- All write operations require authenticated sessions verified at the database level

### 5.3 Row Level Security
Every database operation is protected by Row Level Security policies. This means:
- Users can only edit or delete their own content
- Private content is only visible to its creator
- Group content is only visible to group members
- Admin actions are restricted to verified administrators

---

## 6. Data Sharing

### 6.1 We Do NOT
- Sell your personal data to anyone
- Share your data with advertisers
- Use your data for targeted advertising
- Provide your data to data brokers
- Share your private content with other users

### 6.2 We May Share Data When
- **You make it public** — content you post as "public" is visible to all Zelofun users on that webpage
- **Legal requirements** — if required by law, court order, or governmental authority
- **Service providers** — with infrastructure providers (Supabase, Cloudflare) who process data on our behalf under strict data protection agreements
- **Safety** — to protect against fraud, abuse, or threats to safety

---

## 7. Your Rights and Choices

### 7.1 All Users
You have the right to:
- **Access** your data — view all content you have posted
- **Edit** your content — modify your comments, reactions, and profile information
- **Delete** your content — remove any content you have posted
- **Delete your account** — request complete account deletion
- **Block users** — hide content from specific users
- **Report content** — flag content that violates community guidelines
- **Control visibility** — choose whether your content is public, private, or limited to groups

### 7.2 GDPR Rights (EU/UK Users)
If you are located in the European Union or United Kingdom, you additionally have the right to:
- **Data portability** — receive your data in a structured, machine-readable format
- **Rectification** — correct inaccurate personal data
- **Erasure** ("Right to be Forgotten") — request deletion of your personal data
- **Restrict processing** — limit how we use your data
- **Object to processing** — object to certain uses of your data
- **Withdraw consent** — withdraw any consent you have previously given

To exercise any of these rights, contact us at privacy@zelofun.com.

### 7.3 Account Deletion
You may delete your account at any time. When you delete your account:
- Your profile information is permanently removed
- Your content may be anonymized or deleted (depending on whether others have replied to it)
- Media files you uploaded are deleted from storage
- This process is irreversible

---

## 8. Cookies and Local Storage

The Zelofun browser extension uses **Chrome local storage** (not cookies) to store:
- Your authentication session
- Your display preferences (view mode, language, dark mode)
- Your blacklist preferences
- Cached data for performance

The Zelofun website (zelofun.com) may use standard cookies for:
- Analytics (anonymized usage statistics)
- Session management

We do not use advertising cookies or third-party tracking cookies.

---

## 9. Children's Privacy

The Service is not intended for children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us at privacy@zelofun.com and we will delete such information.

---

## 10. Data Retention

- **Active accounts** — data is retained for as long as your account is active
- **Deleted accounts** — personal data is deleted within 30 days of account deletion request
- **Content on active threads** — may be anonymized rather than deleted if other users have replied
- **Error logs** — retained for up to 90 days for debugging purposes
- **Aggregated analytics** — may be retained indefinitely in anonymized form

---

## 11. International Data Transfers

Our infrastructure providers may process data in locations outside your country of residence. When your data is transferred internationally, it is protected by:
- Standard contractual clauses (for EU/UK transfers)
- Encryption in transit and at rest
- Data processing agreements with all service providers

---

## 12. Third-Party Websites

Zelofun operates as an overlay on third-party websites. We are not responsible for the privacy practices of the websites you visit while using our Service. Our overlay does not modify, access, or collect data from the underlying websites — it only displays and manages Zelofun community content.

---

## 13. Changes to This Policy

We may update this Privacy Policy from time to time. When we make significant changes, we will:
- Update the "Last Updated" date at the top of this page
- Notify active users through the extension (for significant changes)
- Post a notice on zelofun.com

Your continued use of the Service after changes are posted constitutes acceptance of the updated policy.

---

## 14. Contact Us

For privacy-related inquiries, data access requests, or concerns:

**Email:** privacy@zelofun.com
**Website:** https://zelofun.com

For GDPR-related requests, please include "GDPR Request" in your email subject line. We will respond within 30 days.

---

*Zelofun™ — Your voice on any website*
*© 2024-2026 Zelofun. All rights reserved.*
