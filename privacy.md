---
title: Privacy Policy — Askwell Q&A for Confluence
---

# Privacy Policy

**App:** Askwell — Questions & Answers for Confluence
**Publisher:** Atesen Software (independent developer, Türkiye)
**Contact:** sametatesen2@gmail.com
**Last updated:** 26 October 2026

## 1. What the app stores

The app runs inside your Atlassian Cloud site on the Atlassian Forge platform. To provide a Q&A knowledge base it stores, in Forge hosted storage:

- **Questions:** title, text written by the author, topics, the Atlassian account ID of the author, created/updated times, vote score, answer count, the accepted answer, and — when asked from a page — the page ID and space key.
- **Answers:** text written by the author, the author's Atlassian account ID, times and vote score.
- **Votes:** the voter's Atlassian account ID, the question or answer voted on, the vote (+1/−1) and its time.
- **Settings:** who may ask and answer (group IDs), moderators (account IDs) and the topic list.

The app does not store names, email addresses, avatars or page content. Names and avatars are displayed by Atlassian's own components from the account ID. Page titles are looked up live, with the viewer's permissions, and are not stored.

## 2. Where data is stored and where it goes

All processing and storage happen on Atlassian's Forge platform, inside Atlassian's cloud infrastructure (Forge SQL and Forge key-value storage). The app has no servers of its own and **makes no requests outside Atlassian**. There are no analytics services, advertising networks or sub-processors, and **no data is sent to Atesen Software**.

## 3. How long data is kept

Questions, answers and votes are kept while the app is installed, because they are your team's knowledge base; authors and moderators can delete them at any time. Once a week the app reports the stored account IDs to Atlassian's personal data reporting service. When Atlassian reports that an account has been closed, the app removes that account ID from every question and answer (the post is then shown as written by a "Former user"), deletes that account's votes and removes it from the moderator list. Uninstalling the app deletes the app's storage according to Atlassian's Forge data retention policies.

## 4. Logs

Application logs contain event names, handler names, counts and HTTP status codes. **They never contain question or answer text, page titles or account IDs.** Forge logs are stored by Atlassian and are visible to the publisher only through Atlassian's developer tooling, with Atlassian's own retention limits.

## 5. Roles

For data processed by this app on your site, your organization is the controller and Atesen Software acts as a processor to the limited extent described here. Atlassian is the infrastructure provider; see Atlassian's privacy policy for how they process data in your cloud site.

## 6. Your requests

To ask about data handled by this app, or to request deletion of data on your site, write to sametatesen2@gmail.com. Authors can delete their own questions and answers, and moderators can delete any of them, directly in the app.

## 7. Security

Questions linked to a page are shown only to people Confluence lets see that page: the app checks visibility with Confluence search run as the viewing user. Group-based permissions are checked on every request on the server, never in the browser. Settings can only be changed from the Confluence administration screen.

## 8. Changes

Material changes to this policy are announced in the release notes on the app's Atlassian Marketplace listing.
