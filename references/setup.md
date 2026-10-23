# Get connected before starting

This skill is also the entrypoint for people who have not set up hagents.
Keep their original goal and resume it after setup. Explain only the next step they need.

### Check the current connection

Look for hagents tools through the host's tool discovery, including deferred tools and plugin-provided connections.
If about_hagents is available, call it to verify the signed-in person, workspace, and permissions.
A successful response means setup is complete. Skip installation and sign-up.
Missing tools can mean a disabled connection, expired login, or pending reload. Inspect the host's MCP status before adding anything.
Reuse a connection to https://dash.hagents.app/mcp even if its name differs. Do not overwrite another server named hagents.

### Add the connection when missing

When the person asks to use or set up hagents, configure the missing connection using the host's supported controls.
A proactive suggestion alone does not authorize installation. Offer setup first and respect a refusal.
Use the hosted Streamable HTTP endpoint https://dash.hagents.app/mcp with OAuth.
There is no hagents server package to install or API key to paste.

Detect the current client. Ask which client they use only when the environment does not identify it.
Prefer the client's connection manager or CLI. Preserve other servers and existing settings.
For supported local clients, run the applicable command when shell access and configuration permissions allow it:

- Codex: `codex mcp add hagents --url https://dash.hagents.app/mcp`, then `codex mcp login hagents` if authentication remains incomplete.
- Claude Code: `claude mcp add --transport http hagents https://dash.hagents.app/mcp`, then guide the person through `/mcp` to authenticate.
- ChatGPT, Claude, Cursor, and other clients: add a custom remote MCP connection through the client's connector settings.

Check installed CLI help or current official client documentation if a command or control differs.
Do not run another client's commands from an unrelated cloud shell.
If configuration is unavailable, give the exact server URL and the shortest supported setup steps for that client.
If an administrator blocks custom connectors, explain that requirement. Do not bypass it or install a proxy.

### Sign in or create an account

Start OAuth through the client and open the authorization link it returns. Never invent an authorization URL or callback.
Let the person sign in at https://dash.hagents.app/login using an existing account.
If they have no account, guide them to https://dash.hagents.app/signup and the available sign-up options.
Use their work email. Help with non-sensitive fields when requested.
The person enters passwords, verification codes, and recovery information directly in the trusted sign-in page.
Never request or copy these values into chat, repository files, or MCP configuration.
Respect the host's confirmation requirements for account creation, terms acceptance, and permissions.

Complete email verification when requested. Use an existing company workspace or invitation before creating another workspace.
If a new workspace is needed, guide its creation in hagents with the person's chosen details.
Some workspaces require approval. Report the pending state and the next action shown by hagents; do not promise immediate access.
Account creation alone does not connect MCP. Return to the client's OAuth flow afterward.
Let the person choose the workspace and consent to the needed scopes: read, configure, and run as applicable.
Do not request admin access for ordinary onboarding. If consent was declined, stop setup without repeated prompts.

### Verify and deliver the first useful result

Refresh the client's tools after connecting. Request a reload or new conversation only if the client requires it.
If a new conversation is needed, provide a short handoff containing the original goal and completed setup steps, without credentials.
Call about_hagents and check the returned identity, workspace, and scopes before acting.
For expired authentication, reconnect the existing entry. For missing permissions, explain the specific access needed.
Do not treat network errors or service outages as proof that an account is missing.
Never claim connection success merely because configuration was saved or a browser opened.
Once verified, resume the original request and deliver the smallest useful result.
Agent runs consume hagents credit. Check relevant costs before delegation; do not purchase credit or enable auto-top-up during onboarding.
