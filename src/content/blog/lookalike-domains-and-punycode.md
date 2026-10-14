---
title: "Look-alike domains and punycode: when 'paypal' is not PayPal"
description: "Scammers register domains that look almost identical to real brands. Here is how to spot swapped letters, extra words and disguised characters."
date: 2026-10-07
category: "Link Safety"
---
A look-alike domain is a web address that resembles a trusted brand closely enough to fool a quick glance. They are one of the most common tools in phishing.

## Common tricks

- **Swapped or doubled letters:** `arnazon.com` instead of `amazon.com`. Two letters, "rn", can pass for "m".
- **Extra words:** `paypal-support-help.com` or `amazon-orders-verify.net`. The brand name is in there, but the domain belongs to someone else.
- **Different endings:** the same name on `.top`, `.xyz` or `.click` instead of `.com`.
- **Brand as a subdomain:** `paypal.com.secure-login.top`. The real domain is `secure-login.top`.
- **Hyphens and numbers:** `micros0ft-login.com`.

## Punycode and disguised characters

Domain names can include non-Latin letters. Some of these look identical to Latin letters. For example, the Cyrillic "а" looks just like the Latin "a". Browsers handle these by showing the underlying form, called punycode, which starts with `xn--`. A link that contains `xn--` in the domain is not automatically malicious, but it is worth a hard look, especially when it is meant to look like a well-known brand.

## How to read a link safely

1. Find the first single slash after `https://`. Everything before it is the host.
2. Read the host from right to left. The last two parts, such as `secure-login.top`, are the domain that actually matters.
3. Ask: does this match the real company's domain exactly?
4. If you are unsure, type the company's address yourself instead.

## Extra checks that help

- **Domain age:** a "bank" site registered last week is suspicious.
- **Certificate:** a valid HTTPS padlock does not prove safety, but a missing or invalid one is a clear warning.
- **Reputation:** known phishing domains appear in threat databases.

## Let LinkGuard do the comparison

LinkGuard checks for disguised characters and look-alike brand names as part of its 15 checks, and Deep Site Scan can show how old a domain is. Paste a suspect link and see what it finds.
