---
name: Forum Pro Plugin Issue
about: Issue with Forum Pro.
title: "[forum-pro] Summary of the issue"
labels: forum-pro
assignees: rhukster

---

Please describe your issue with as much detail as possible. Please include versions of the product. As well as Grav, admin plugin or any other plugins involved. 

Also please provide detail steps to reproduce the issue or sample code that exhibits the issue.  The easier you make it for us to reproduce the issue, the faster we can resolve the it. 

Screenshots or short videos showing unexpected behavior can also be very helpful.

Forum Pro specifics that usually speed things up:

* Your **database engine** (SQLite, MySQL/MariaDB or PostgreSQL) and version.
* The output of `bin/plugin forum-pro status`, which covers connection, schema, background jobs and scheduler health.
* Whether the **Grav scheduler** is installed, if the issue involves email, badges, digests or retention purges.
* Which optional plugins are in play: `email`, `sync` / `sync-mercure`, `ai-pro`, `yetisearch-pro`, `codesh`, `form`.
* For layout or styling issues, the **theme** you are running and whether it publishes `--grav-*` design tokens.
