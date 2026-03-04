---
title: Data Deletion Request - Taleria
---

# Data Deletion Request

**Taleria**: AI-Powered Stories for Children

---

## In-App Deletion (Recommended)

The fastest way to delete your data is directly from the app:

1. Open the Taleria app
2. Go to **Settings** > **Account**
3. Scroll to the **Danger Zone** section
4. Tap **Delete All Data**
5. Confirm the deletion in the dialog

This will **immediately** delete:
- All locally stored data (stories, profiles, avatars, settings, orders)
- All cloud data (device identity, usage quotas, story history, subscription-device mapping)

---

## Email Deletion (Fallback)

If you have already uninstalled the app and cannot use in-app deletion, send an email to:

**[joytect25@gmail.com](mailto:joytect25@gmail.com?subject=Taleria%20Data%20Deletion%20Request)**

In your email, please include:
- The subject line: **"Taleria Data Deletion Request"**
- Your **Paddle checkout email** (the email you used when purchasing a subscription), if applicable

We will process your request within **30 days** and send you a confirmation once completed.

**Note for free-tier users:** If you never purchased a subscription, your cloud data consists only of an anonymous device identifier and a monthly usage counter. This data contains no personally identifiable information and cannot be linked back to you.

---

## What Data Will Be Deleted

When you delete your data (in-app or via email), the following will be **permanently removed**:

| Data Type | Location | Action |
|-----------|----------|--------|
| Stories, chapters, images, audio | On device | Deleted |
| Child profiles | On device | Deleted |
| Custom avatars | On device | Deleted |
| Story orders | On device | Deleted |
| App settings, PIN, parental controls | On device | Reset to defaults |
| Session time tracking | On device | Deleted |
| Device identifier | Cloud (Cloudflare KV) | Deleted |
| Story usage quotas | Cloud (Cloudflare KV) | Deleted |
| Subscription-device mapping | Cloud (Cloudflare KV) | Deleted |
| Story recovery history | Cloud (Cloudflare KV) | Deleted |

---

## What Data Is Retained

| Data Type | Reason |
|-----------|--------|
| Subscription purchase records | Managed by Paddle (our payment provider). Subject to their data retention policies. |
| Cached story content (R2 storage) | Shared content cache, not linked to individual users. Contains no personal data. |

---

## On-Device Data

All locally stored data can also be deleted at any time by simply **uninstalling the app**, which removes all local data from your device.

---

## Contact

If you have any questions about data deletion, please contact us at:

**Email:** [joytect25@gmail.com](mailto:joytect25@gmail.com)

---

© 2026 Taleria. All rights reserved.
