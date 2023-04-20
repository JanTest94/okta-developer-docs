<ApiLifecycle access="ea" />
<ApiLifecycle access="ie" />

This guide explains how to implement a direct authentication MFA out-of-band (OOB) flow for your app in Okta.

---

**Learning outcomes**

* Understand the OAuth 2.0 direct authentication MFA OOB flow.
* Set up your app with the MFA OOB grant type.
* Implement the MFA OOB flow in Okta.

**What you need**

* [Okta Developer Edition organization](https://developer.okta.com/signup)
* An app that you want to implement OAuth 2.0 direct authentication MFA OOB with Okta
* A test user in your org enrolled in Okta Verify <!-- Need to update this after the entire feature is rolled out and not limited to Okta Verify>
* The Direct Authentication feature enabled for your org. From the left navigation pane in the Admin Console, go to **Settings** > **Features**, locate the Direct Authentication feature and slide to enable.

<ApiAmProdWarning />