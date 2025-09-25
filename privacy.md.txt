# Flight Log Scanner – Privacy Policy

**Effective date:** 25 September 2025  
**App:** Flight Log Scanner (iOS/iPadOS)  
**Owner:** Alliance Airlines (internal tool)  
**Contact:** [elima@allianceairlines.com.au]

---

## Summary (plain English)

- The app scans flight log documents to extract operational data.  
- Scanning and OCR happen **on-device**. Images and recognized text stay local unless you explicitly submit or email a report.  
- When you send a report, the app uses **Microsoft Graph** with your work account to deliver the data to approved recipients.  
- We don’t sell or share data with third parties. We use service providers strictly to deliver the app’s core functionality (e.g., Apple frameworks, Microsoft Graph).  
- Access is restricted to authorized Alliance personnel. This is a **private enterprise app**, not for consumer use.

---

## Scope

This policy covers the Flight Log Scanner mobile application and its supporting enterprise services used by Alliance Airlines personnel.

---

## Data We Process

### 1) Data you provide
- **Scanned documents & photos:** Images of flight logs or related operational paperwork captured with the device camera.
- **Manual inputs:** Tail number, flight number, sector times, duty info, comments, and any additional fields in your workflow.
- **Account identity:** Your enterprise identity used to authenticate with Microsoft Graph (email/UPN and access token *via your organization’s SSO*).

### 2) Device & app data (minimal)
- **App telemetry (diagnostics):** Crash logs or non-identifying diagnostics the OS provides if you opt in at the OS level.  
- **Device information:** Model, OS version; used only to support compatibility and troubleshooting.

We do **not** collect location, contacts, photos library, or background tracking.

---

## How Data Is Processed

### On-device by default
- **OCR & parsing:** Performed locally using Apple Vision / related frameworks.  
- **Temporary storage:** Scans and extracted text are kept locally in the app sandbox (and, if configured by you, in the app’s offline queue).  
- **No automatic uploads:** Nothing leaves the device unless you submit.

### When data leaves the device
- **Email/report submission (Microsoft Graph):**  
  If you press **Send** or submit a report, the app packages the structured fields (and, optionally, the rendered PDF/attachments) and sends via Microsoft Graph using your enterprise authentication.  
  - **Recipients:** Base-specific operational inboxes and/or a central reporting address configured by your organization.  
  - **Metadata:** Timestamps, file names, and app version may be included to support traceability.

- **Enterprise storage:**  
  Reports sent via Graph are stored in the recipients’ mailboxes or downstream systems (e.g., SharePoint, ticketing, or data pipelines) per Alliance policy.

---

## Legal Basis & Purpose

- **Legitimate interests / performance of employment duties:** Supporting operational safety, compliance, and efficiency in flight ops.  
- **Compliance:** Assisting record-keeping requirements applicable to aviation operations.

---

## Data Retention

- **On-device:** Retained until you send or delete it, or until the app purges old items per configured limits.  
- **Enterprise systems:** Retention follows Alliance policies and applicable regulatory requirements.  
- **Diagnostics (if any):** Retained per Apple/Microsoft standard practices and Alliance troubleshooting needs.

---

## Security

- **On-device isolation:** iOS/iPadOS sandbox; Face ID/Touch ID/Passcode as configured by you and enforced by MDM where applicable.  
- **In transit:** Reports sent via Microsoft Graph use TLS.  
- **Access control:** App access is limited to authorized Alliance accounts; server-side access is role-based per Alliance policies.  
- **MDM/Intune (if applicable):** Device compliance, app protection policies, and conditional access may be enforced by IT.

---

## Third Parties / Subprocessors

- **Apple frameworks:** Camera, Files, Vision/OCR, background tasks.  
- **Microsoft Graph / Entra ID:** Authentication and email delivery using your work account.  
- **Enterprise platforms:** Mail servers, SharePoint/OneDrive, ticketing or data pipelines managed by Alliance IT.

These providers process data only to deliver the app’s functionality under Alliance control.

---

## Your Choices & Rights

- **Review before sending:** You can review, edit, or delete scans before submission.  
- **Delete local data:** Remove items from the queue/history within the app.  
- **Access/Correction/Deletion (enterprise records):** Contact your manager or the privacy contact above to exercise rights available under law and company policy.

---

## Children

This app is for **authorized employees/contractors** only and is not intended for children.

---

## International Transfers

Depending on your organization’s tenancy and routing, Microsoft Graph and enterprise systems may process data in multiple regions. Alliance applies contractual and technical safeguards consistent with applicable law.

---

## Changes to This Policy

We may update this policy to reflect product or regulatory changes. The “Effective date” will be revised, and material changes will be communicated through internal channels.

---

## Contact

For questions or requests, contact: [elima@allianceairlines.com.au].
