---
title: Additional detections
pcx_content_type: how-to
weight: 5
---

# Additional detections

Email Security allows you to configure the following additional detections:

- Domain age
- Blank email detection
- ACH change from free email detection
- HTML attachment email detection

To configure additional detections:

1. Log in to the [Cloudflare dashboard](https://dash.cloudflare.com/).
2. Select **Email Security**.
3. Select **Settings**.
4. On the **Settings** page, go to **Detection settings** > **Additional detections** tab, and select **Edit**.

## Configure domain age

The domain age is the time since the domain has been registered.

To configure a domain age:

1. On the **Edit additional detections** page:
   - Select **Malicious domain age**: Controls the threshold for a malicious disposition. Maximum of 100 days.
   - Select **Suspicious domain age**: Controls the threshold for a suspicious disposition. Maximum of 100 days.
2. Select **Save**.

## Configure blank email detection

Blank email detection detects emails with blank bodies and assigns a default disposition. You can choose between **Malicious** and **Suspicious** as dispositions.

To enable blank email detection:

1. On the **Edit additional detections** page, select the **Blank email detection** toggle.
2. Choose between **Malicious** and **Suspicious**.
3. Select **Save**.

## Configure ACH change from free email detection

ACH change from free email detection detects payroll inquiries or change requests from free email domains and assigns a default disposition. You can choose between malicious and suspicious as dispositions.

To enable ACH change from free email detection:

1. On the **Edit additional detections** page, enable **ACH change from free email detection**.
2. Choose between **Malicious** and **Suspicious**.
3. Select **Save**.

## Configure HTML attachment email detection

HTML attachment email detection detects HTM and HTML attachments in emails and assigns a default disposition.

To enable HTML attachment email detection:

1. On the **Edit additional detections** page, enable **HTML attachment email detection**.
2. Choose between **Malicious** and **Suspicious**.
3. Select **Save**.