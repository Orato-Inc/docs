> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- "AI Assistant" (or "assistant") for a voice agent. Roles: Outbound, Inbound, Web Widget.
- "Lead batch" for a group of leads; "campaign" for outbound calling across a batch.
- "Workspace" for an organization account; "member" for a teammate.
- "Wallet" for the prepaid USD balance.
- Match dashboard labels exactly in bold, e.g. **Create Assistant**, **Make call**.

## Style preferences

- Do not use em dashes.
- Screenshots live in `images/app/`. Blur account details (name, avatar, balance) and real phone numbers before committing.

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document only what is visible in app.tryorato.com. Do not invent REST endpoints or webhook payloads.
