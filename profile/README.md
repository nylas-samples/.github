<img src="./logo.png" width="96" alt="Nylas"/>

# Nylas code samples

**Open-source examples for the Nylas APIs.**
Snippets and reference apps across every official SDK — Email, Calendar,
Contacts, Scheduler, Notetaker, and Webhooks.

[Sign up](https://dashboard-v3.nylas.com/register) ·
[Docs](https://developer.nylas.com) ·
[CLI docs](https://cli.nylas.com) ·
[Main org](https://github.com/nylas) ·
[Forum](https://forums.nylas.com) ·
[Blog](https://nylas.com/blog)

## Get started

[Sign up](https://dashboard-v3.nylas.com/register) to create an app and generate an API key. Or do it from the terminal:

```bash
brew install nylas/nylas-cli/nylas
nylas init
```

Then grab a sample and run it:

```bash
git clone https://github.com/nylas-samples/nylas-code-samples-starter
cd nylas-code-samples-starter
# add NYLAS_API_KEY to .env, then follow the sample's README
```

## Featured samples

Hand-picked starting points if you're not sure where to begin.

- [**nylas-code-samples-starter**](https://github.com/nylas-samples/nylas-code-samples-starter) — the template every sample is built from.
- [**node-starter-repo**](https://github.com/nylas-samples/node-starter-repo) — start building with the Nylas Node.js SDK.
- [**node-manage-calendar-events**](https://github.com/nylas-samples/node-manage-calendar-events) — create, update, and delete calendar events.
- [**python-holidays-generator**](https://github.com/nylas-samples/python-holidays-generator) — Markdown holiday calendar in Python.
- [**streamlit_email_dashboard**](https://github.com/nylas-samples/streamlit_email_dashboard) — inbox dashboard built with Streamlit.
- [**scheduling-app**](https://github.com/nylas-samples/scheduling-app) — React frontend for the Nylas Scheduler.
- [**node-webhooks-challenge-serverless-function**](https://github.com/nylas-samples/node-webhooks-challenge-serverless-function) — Nylas webhooks on a serverless function.

## Browse the org

By product:
[Email](https://github.com/orgs/nylas-samples/repositories?q=email) ·
[Calendar](https://github.com/orgs/nylas-samples/repositories?q=calendar) ·
[Contacts](https://github.com/orgs/nylas-samples/repositories?q=contact) ·
[Scheduler](https://github.com/orgs/nylas-samples/repositories?q=scheduler) ·
[Webhooks](https://github.com/orgs/nylas-samples/repositories?q=webhook) ·
[Auth](https://github.com/orgs/nylas-samples/repositories?q=auth)

By language:
[Node.js](https://github.com/orgs/nylas-samples/repositories?q=node) ·
[Python](https://github.com/orgs/nylas-samples/repositories?q=python) ·
[Ruby](https://github.com/orgs/nylas-samples/repositories?q=ruby) ·
[Java](https://github.com/orgs/nylas-samples/repositories?q=java)

## Try it in Postman

Three collections in the [public workspace](https://www.postman.com/trynylas/nylas-api), pre-wired and ready to fork.

| Collection | Run |
|---|---|
| **Administration** | [<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" width="128" height="32">](https://god.gw.postman.com/run-collection/21157315-07346e8d-7c2c-43d4-87f6-2a8b6ebc4b30?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D21157315-07346e8d-7c2c-43d4-87f6-2a8b6ebc4b30%26entityType%3Dcollection%26workspaceId%3De36cf1fc-a749-494d-9c8c-f3c28f18c342) |
| **Email, Calendar, Contacts & Notetaker** | [<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" width="128" height="32">](https://god.gw.postman.com/run-collection/21157315-b864762a-ddbb-4e08-bcc5-e87bb51a825a?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D21157315-b864762a-ddbb-4e08-bcc5-e87bb51a825a%26entityType%3Dcollection%26workspaceId%3De36cf1fc-a749-494d-9c8c-f3c28f18c342) |
| **Scheduler** | [<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" width="128" height="32">](https://god.gw.postman.com/run-collection/21157315-91771656-d8a7-43c9-ad24-8533f43d6f35?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D21157315-91771656-d8a7-43c9-ad24-8533f43d6f35%26entityType%3Dcollection%26workspaceId%3De36cf1fc-a749-494d-9c8c-f3c28f18c342) |

---

## SDKs

- [nylas-nodejs](https://github.com/nylas/nylas-nodejs) · `npm i nylas`
- [nylas-python](https://github.com/nylas/nylas-python) · `pip install nylas`
- [nylas-ruby](https://github.com/nylas/nylas-ruby) · `gem install nylas`
- [nylas-java](https://github.com/nylas/nylas-java) · Maven / Gradle

Community: [Teamwork/nylas-go](https://github.com/Teamwork/nylas-go),
[lanlin/nylas-php](https://github.com/lanlin/nylas-php).

## API reference

- [API](https://developer.nylas.com/docs/reference/api/)
- [Notifications](https://developer.nylas.com/docs/reference/notifications/)
- [UI components](https://developer.nylas.com/docs/reference/ui/)

## AI agents

[nylas/skills](https://github.com/nylas/skills) drops Nylas into Claude Code,
Cursor, Codex, and other agents that support the skills format:

```bash
npx skills add nylas/skills
/plugin marketplace add nylas/skills   # Claude Code
```

The CLI installs an MCP server for Claude Desktop, Claude Code, Cursor,
Windsurf, or VS Code:

```bash
brew install nylas/nylas-cli/nylas
nylas mcp install
```

## Contributing

Pull requests welcome — see [CONTRIBUTING.md](https://github.com/nylas-samples/.github/blob/main/CONTRIBUTING.md). New to open source? The [starter template](https://github.com/nylas-samples/nylas-code-samples-starter) is a good place to begin.

## Connect

[Forum](https://forums.nylas.com) ·
[LinkedIn](https://www.linkedin.com/company/nylas/) ·
[X](https://twitter.com/nylas) ·
[YouTube](https://www.youtube.com/c/nylas)

---

_If you're interested in building Nylas, [come join us](https://www.nylas.com/company/jobs/)._
