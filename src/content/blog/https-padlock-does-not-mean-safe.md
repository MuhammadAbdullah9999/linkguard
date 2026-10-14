---
title: "Does the HTTPS padlock mean a website is safe? No. Here is why"
description: "Scam sites use HTTPS too. Learn what the padlock actually tells you and what to check instead."
date: 2026-10-05
category: "Security Basics"
---
For years we were told to look for the padlock. It is good advice with an important catch: the padlock means your connection to the site is encrypted. It does not mean the site is honest.

## What HTTPS actually does

HTTPS encrypts data between your browser and the website, so nobody on the network can read or change it. It also confirms you reached the site that holds the certificate for that domain.

## What HTTPS does not do

It does not tell you who owns the site, whether the owner is trustworthy, or whether the page is trying to trick you. Free certificates are easy to get. A scammer can register `my-bank-login.top`, get a certificate in minutes and display a padlock.

So a padlock on a phishing page is normal. It just means your password will be sent to the scammer securely.

## What to look at instead

- **The domain.** Is it exactly the company's real domain?
- **How you got there.** Did you type it yourself, or tap a link from a message?
- **What it asks for.** Logins, card numbers and one-time codes deserve extra caution.
- **The age of the site.** A very new domain claiming to be a long-established brand is a red flag.
- **Reputation.** Check the link against threat databases before you trust it.

## When a missing padlock matters

If a site that asks for a login or payment does not use HTTPS at all, leave. That is a real warning sign, because the details you type travel unprotected.

## What LinkGuard checks

LinkGuard's checks include whether a site uses valid, trusted TLS and secure HTTPS, but treats it as one signal among many. It also looks at threat databases, link structure and look-alike tricks. Deep Site Scan grades the TLS setup in more detail.

## The short version

Padlock present: your connection is private. Padlock missing: be careful. Neither one answers the real question, "is this site what it claims to be?"
