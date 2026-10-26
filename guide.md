---
title: User guide — Askwell Q&A for Confluence
---

# User guide

## Where to find Q&A

| Place | How to open it | What it does |
|---|---|---|
| Q&A page | Confluence top bar → **Apps** → **Q&A** | All questions: search, sort (Active, Newest, Top, Unanswered, Mine) and filter by topic |
| Page button | **Q&A** in the byline at the top of any page or blog post | Questions asked about that page, and **Ask about this page** |
| Macro | Edit a page → type `/Q&A questions` | A list of questions for a topic, the current space or the current page, with an **Ask a question** button |
| Settings | **Confluence administration → Askwell Q&A** (admins only) | Who can ask and answer, moderators, topic rules, usage numbers |

## Asking a good question

1. Write the title as a question someone could search for.
2. Add details: what you tried, links, error messages. Markdown works: bold with double asterisks, italic with underscores, inline code with backticks, code blocks between lines of three backticks, `- lists`, `1. numbered lists`, `> quotes` and `[links](https://example.com)`.
3. Add up to five topics, separated by commas.
4. Before posting, check the **Similar questions already asked** box that appears after you type the title.

## Answering, voting and accepting

- Anyone allowed to answer can post an answer below the question.
- Vote questions and answers up or down. You cannot vote on your own posts.
- The person who asked, or a moderator, selects **Accept answer** on the answer that solved it. Accepted answers are shown first and the question is marked **Solved**.
- Authors can edit and delete their own posts; moderators can edit and delete any post.

## Questions about restricted pages

A question asked from a page's Q&A button or from a macro on a page is linked to that page. Askwell only shows such a question to people who can see the page, in every list and in search. Questions asked from the Q&A page are visible to everyone who can use the app.

## Askwell in Rovo

If your site has Rovo, open Rovo chat and pick the **Askwell Q&A** agent, or ask any agent that has the **Search team Q&A** action. It searches your site's questions, quotes the accepted (or best-voted) answer, links the thread, and tells you where to ask when nobody has. It follows the same rule as the app: questions about pages you cannot see are never returned.

## Settings (Confluence admins)

- **Who can ask questions / Who can answer:** everyone, or only members of selected groups. Moderators can always ask and answer.
- **Moderators:** people who can edit, delete and accept on any question.
- **Topics:** free topics, or a fixed list people must choose from.

## Macro options

| Option | Values |
|---|---|
| Heading | Any text; defaults to the topic or "Questions & answers" |
| Topic | Show only questions with this topic |
| Show questions from | Whole site, This space, This page |
| Order | Recently active, Newest, Top voted, Unanswered |
| How many | 1–30 |
