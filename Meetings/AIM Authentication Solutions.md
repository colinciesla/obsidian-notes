# AIM Authentication Solutions
---
# Firebase
Google's backend-as-a-service platform
![Image|300](https://miro.medium.com/v2/resize:fit:300/1*R4c8lHBHuH5qyqOtZb3h-w.png)
---
## Features
- Drop-in UI library for easy authentication with Firebase Auth's supported sign-in methods

- Firebase SDK allows for more extensive control over the sign-in experience

- Multiple sign-in methods:
	1. Email/password
	2. Phone number
	3. Email link

- Allows custom claims for role-based authentication

- Social sign-in providers (Google, Apple, Microsoft, etc.)

- Admin SDK allows for user management, user bulk import, MFA, sessions, cookies, tokens
---
## Pricing
Spark Plan (Free Tier) - 50k monthly active users, 50 monthly active users for SAML/OIDC

Blaze Plan (Pay as you go) - After above limits, reverts to Google Cloud pricing:
- For Tier 1 providers (email, phone, social), price per monthly active user (MAU) is less than a cent and gets lower as MAUs increase
- For Tier 2 providers (OIDC and SAML), price after 50 MAUs is $0.015 per MAU
- For phone auth and MFA, price per SMS sent is $0.01
---
Pros: 
- Can use free tier currently, scaling is quite cheap and is pay-as-you-go
- Drop-in UI library
- Ease of use

Cons:
- Vendor lock-in
- Not as many auth features as other providers (custom emails, UI for managing roles/groups)
- Query performance isn't that great
- Chance that Google abandons Firebase at some point
---
# Supabase
Open-source Firebase alternative
![Image](https://d2eip9sf3oo6c2.cloudfront.net/tags/images/000/001/299/square_480/supabase-logo-icon_1.png)
---
## Features
- Everything works on top of a PostgreSQL database
- Management UI
- Auto-generated APIs for database connectivity
- Auth rules are built with Postgres Row Level Security policies using SQL
- MFA
- Has all the social providers needed
- Support for SAML
---
## Pricing

---
## Auth0
---
