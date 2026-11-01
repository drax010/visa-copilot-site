---
title: Visa Copilot privacy policy
---

# Visa Copilot privacy policy

*Last updated: 1 November 2026*

Visa Copilot is an Android app with visa checklists for Indian passport holders. It gives information and preparation help; it has no accounts and no sign-in. This page says what the app keeps on your phone, what leaves it, and how to turn that off.

Visa Copilot is made by Basit, an independent developer. Questions or requests: **jndoe470@gmail.com**.

## What stays on your phone

These are saved only on your phone and are never sent anywhere:

- your applications, the names you give them, and the items you tick;
- the copy of the visa rules the app downloads;
- your settings, including whether you've read the disclaimer and whether reports are on.

Uninstalling the app, or clearing its storage, deletes them.

## What the app downloads

The app downloads its visa rules from GitHub Pages (`drax010.github.io`), a static file that's the same for everyone. As with any web request, GitHub receives your phone's IP address when it serves the file. No details about you or your applications are sent.

When you tap "Open official page", the government page opens in a browser. That website's own privacy policy applies.

## Anonymous usage events (PostHog)

Unless you turn them off, the app sends a few anonymous events to PostHog, so we can see which parts of the app are used and how many people come back:

| Event | Sent when |
| --- | --- |
| App opened | The app comes to the screen |
| Application created | You save a new application |
| Item ticked | You tick an item |
| Personalised version tapped | You tap "Get the personalised version" |
| Official page opened | You open an official page |

The only detail the app adds to an event is the visa type you were using, such as "US B-1/B-2". It never adds the names you give applications, the items you ticked, or anything you type.

Each event also carries a random ID made when the app first runs, the time of the event, the app's version, and your phone's operating system and its version. The app removes the other details PostHog's software would add, such as your phone's model, screen size, language and time zone. The random ID isn't linked to your name, email, phone number or Google account. We've told PostHog to discard IP addresses and not to work out your location from them: each event carries a flag that turns PostHog's location lookup off, and the lookup is also switched off for the whole project. PostHog stores the events in the European Union.

When the app first sends an event, PostHog's software also downloads its own settings from PostHog. That request contains no details about you, your phone or your applications.

## Crash reports (Sentry)

Unless you turn them off, the app sends a report to Sentry when it hits an error, so we can fix it. A report contains the error, where in the app's code it happened, the app's version, and your phone's model and operating system version. It doesn't contain the names you give applications or anything you type. Sentry is told not to store IP addresses, and stores reports in the European Union.

## Turning reports off

Nothing is sent to PostHog or Sentry until you tap "I understand" on the first screen. After that, **Settings → "Send anonymous usage and crash reports"** turns both off at once, and the app sends nothing more to either.

## Forms (Tally)

Some buttons open forms run by Tally, in your browser: "Get the personalised version", feedback, and "Need another country?". The app sends nothing to Tally by itself. If you fill in a form, Tally receives your answers, and your email address if you give it. The "Get the personalised version" form also receives the visa type you were viewing.

We use form answers only to reply to you or to tell you when a feature is ready. Email **jndoe470@gmail.com** to have your answers deleted. Tally's own privacy policy also applies.

## What we don't do

- We don't sell data or share it for advertising.
- We don't ask for your name, passport number or documents.
- The app has no accounts, sign-in or payments.

## Who it's for

Visa Copilot is meant for adults (18 and over).

## Changes

When this policy changes, the date at the top changes too, and the old versions stay in this page's public history on GitHub.
