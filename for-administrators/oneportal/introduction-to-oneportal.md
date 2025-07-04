---
description: >-
  Learn what OnePortal is, why you use it, and how it fits into the NEO
  platform.
---

# Introduction to OnePortal

AnywhereNow **NEO OnePortal** is the self‑service administration hub where you provision, configure, and monitor NEO Cloud Contact Center resources. It lets you:

* Spin up new **Unified Contact Center (UCC)** instances.
* Configure **Session Border Controllers (SBCs)** and SIP trunks.
* Manage **Dialogue Studio** deployments and other add‑ons.
* Track change requests and deployment history in one place.
* Validate configurations before they hit production.

{% hint style="info" %}
Why it matters OnePortal gives administrators full tenant control without opening support tickets—accelerating onboarding and reducing errors.
{% endhint %}

### When to use OnePortal

Use OnePortal whenever you need to create, update, or retire tenant‑level resources. Typical tasks include:

1. Creating a new UCC for a customer tenant.
2. Requesting additional capacity or feature toggles.
3. Reviewing pending change requests.
4. Downloading audit logs for compliance.

{% hint style="warning" %}
Prerequisite: You need **Administrator** rights for the target tenant. Ask your **NEO Supervisor** if you don’t see the _OnePortal_ tile in OneDashboard.&#x20;
{% endhint %}

### Key concepts

| Term                   | Description                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------- |
| **Service**            | A logical bundle of NEO components (UCC, SBC, Dialogue Studio) scoped to a tenant. |
| **Action Request**     | A tracked change submission in OnePortal, e.g., “Create UCC” or “Add SBC.”         |
| **Validation Checker** | The pre‑deployment engine that confirms prerequisites and shows fixes.             |
