# Microsoft Entra ID Lab: Conditional Access, MFA, and SSO

This lab demonstrates practical hands-on skills in configuring core identity protection and authentication features using **Microsoft Entra ID** (formerly Azure AD). The tasks include setting up **Conditional Access Policies**, enabling **Multi-Factor Authentication (MFA)**, and configuring **Single Sign-On (SSO)** for enterprise applications.

---

## 🔍 Objective

To secure organizational identities and applications by:
- Enforcing MFA using both per-user settings and Conditional Access.
- Applying Conditional Access policies for selected users and apps.
- Enabling Single Sign-On (SSO) for third-party apps using Microsoft Entra Enterprise Applications.

---

## 🛠️ Tools & Technologies

- Microsoft Entra Admin Center
- Azure AD Conditional Access
- Microsoft Authenticator App
- Enterprise Applications (SSO integration)

---

## ✅ Tasks Performed

### 1. Multi-Factor Authentication (MFA)
- Enabled per-user MFA in Entra.
- Allowed trusted devices for 31-day persistence.
- Configured Microsoft Authenticator as the preferred MFA method.
- Verified successful MFA using Authenticator app.

### 2. Conditional Access
- Created a Conditional Access policy named `MFA policy`.
- Assigned the policy to specific users (e.g., `jammy`).
- Configured the policy to **require MFA** to access selected resources.

### 3. Single Sign-On (SSO)
- Navigated to Enterprise Applications.
- Assigned users to SSO-enabled apps like Microsoft Graph and Oracle Access Manager.
- Configured group/user assignments under the SSO app.
- Verified that users are assigned correctly and SSO is enabled.

---

## 📸 Screenshots

Each step is documented in the PDF file included in this repo:
📄 [Download the full walkthrough with screenshots](./Entra_ID_Conditional_Access_MFA_SSO_Project.pdf)

---

## 📚 Outcome

Successfully implemented identity protection and streamlined access management using Microsoft Entra. This project demonstrates readiness for roles involving **IT Support**, **System Administration**, and **Identity & Access Management**.

---

## 🧠 Keywords

`Microsoft Entra ID` `Azure AD` `Conditional Access` `MFA` `SSO` `Enterprise Applications` `Authenticator` `IT Support Project` `Security Best Practices`
