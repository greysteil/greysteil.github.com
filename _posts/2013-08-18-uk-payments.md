---
layout: post
title: Fixing UK payments
---

{{ page.title }}
================

The Treasury are currently looking at ways to
[increase competition](https://www.gov.uk/government/consultations/opening-up-uk-payments)
in the UK's payment space. Their ideal outcome is a world where many payment
networks can co-exist and compete. Here's how it could work:

![Theory for new networks](/assets/images/theory.png)

The above provides a viable model for innovation at the payment network level:

-	A link with the UK's payment infrastructure is provided in a secure,
well-defined way. Customers are protected by their bank, and new networks are
only given access to a payer's account when the payer agrees
-	Assuming the requirements of this link are met, the innovator is free to
build on top of it and expose their own, new payment network

[GoCardless](https://gocardless.com) operates similarly to the above, with
Direct Debit as the link with the banking system:

![How it works at GoCardless](/assets/images/practice.png)

The above works well for GoCardless, where we deal with payments that don't
need to be instant (typically invoice payments).

Unfortunately, Direct Debit isn't a good enough link with the UK's payment
infrastructure to allow new instant payment networks, which could be used in
e-commerce. For the innovator's new network to be instant, their underlying
link must also be instant, and Direct Debit payments aren't (they take at
least 2 days). What's needed to create competition in the e-commerce payments
market, and beyond, is a new, instant bare-bones network backed by the UK's
faster payments infrastructure.

Fix the underlying link with the UK's payment infrastructure, and anyone would
be able to safely innovate on top of it. You'd have a safe but competitive
market at the payment network level.