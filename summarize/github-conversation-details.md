# Executive summary instructions

From the following GitHub conversation JSON, extract only the key human-centric metadata that would help an LLM understand the intent, context, and outcome of the conversation. Exclude all redundant API URLs, avatars, and system-level metadata. Focus only on:

* PR title, body, and html_url
* Conversation state
* Author login and timestamps (created_at, merged_at)
* Assignees and reviewers (logins only)
* merged_by login
* All comment authors, bodies, and timestamps
* All review authors, bodies, states, and timestamps
* Review comments (line comments): file path, line, author login, body, and timestamp
* Diff
* Commit details
* Ignore dependebot, copilot, and other system messages, comments, and reviews

Format as structured JSON suitable for LLM ingestion and omit all unused fields. This should be as small and informative as possible while retaining the full context and human interaction.
