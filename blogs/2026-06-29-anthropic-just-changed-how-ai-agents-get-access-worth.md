---
title: "Anthropic just changed how AI agents get access. Worth understanding why it matters."
url: "https://www.hush.security/blog/anthropic-just-changed-how-ai-agents-get-access-worth-understanding-why-it-matters/"
date: "2026-06-29"
author: "Adi Chemoul"
feed_url: "https://www.hush.security/feed/"
---
Claude Tag (their new Slack-native agent) introduces a different authorization model. Instead of the agent acting as the user who invoked it, the agent gets its own identity — scoped per channel, with its own credentials and permissions. What changes: Old model: “What can this user do?” → agent inherits the requester’s permissions.
