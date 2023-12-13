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
![Image|400](https://d2eip9sf3oo6c2.cloudfront.net/tags/images/000/001/299/square_480/supabase-logo-icon_1.png)
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
- We would likely use the Pro tier, which is $25/month. Includes 100,000 MAUs along with generous storage and bandwidth limits.
- Next tier, the Team tier, is $599/month and adds SOC2 compliance, SSO for the Supabase Dashboard, and priority support and SLAs.
- SSO/SAML requires the Enterprise tier which is likely much more expensive.
---
Pros:
- Open-source
- PostgreSQL database means lots of customization and control using SQL
- Nice management UI
Cons: 
- Steep learning curve if you aren't a SQL guru. Need to understand RLS and policies fairly well
- Documentation is spotty
- C# library is community-supported, not officially-supported by Supabase
- If we need anything outside of the Pro tier the cost increases dramatically
---
# Auth0
Premiere identity access management provider
![Image|400](https://miro.medium.com/v2/resize:fit:2400/1*kofg5S-_kcyij3HL-uCnZA.png)
---
## Features
- Pretty much every auth feature you can think of (MFA, password-less auth, SSO, universal login, all the social logins, etc.)
- Management UI for most features
- Drop-in libraries for auth process
- JWT middleware for ASP.NET
---
## Pricing
- We would likely use the B2C - Professional tier which is $240/month for 500 users. Includes admin roles, external databases, MFA, unlimited social connections.
- Pricing scales up quite dramatically based on MAUs. Professional tier would cost $1600/month at 10,000 MAUs; after 10,000 you have to contact Auth0 for a custom plan.
---
Pros:
- Probably the best feature set out of the major auth providers
- Easy to use, and has a slick management UI

Cons:
- Vendor lock-in
- Exorbitantly expensive as you scale up. If AdPredictive ever reached the Enterprise tier the costs would increase dramatically. Costs aren't public but reportedly start at $2500/month.
---
# ASP.NET Core Identity
ASP.NET Core's native authentication provider
![Image|300](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/.NET_Core_Logo.svg/2048px-.NET_Core_Logo.svg.png)
---
