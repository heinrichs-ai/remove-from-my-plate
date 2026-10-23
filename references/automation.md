# Make useful work repeatable

For a morning brief, resolve the calendars, weekdays, local time, IANA time zone, and exact Slack destination.
Include useful preparation notes and source links. Keep private calendar details within the approved audience.
Reuse an agent where it fits. Check its connections and delivery path, then test its report.
Use get_schema with kind trigger. Create or update the trigger through MCP after the person authorizes its concrete settings.
Explicitly set enabled. An unapproved schedule must not become active through a schema default.
Use versioned updates to enable a paused trigger after approval and testing.
The internal builder's propose_trigger is not an MCP tool. Approval here occurs in the connected app's conversation.
For incoming work, prefer a supported event over repeatedly checking an app.
Use only source recipes, events, filters, and parameters returned by find_connections. Never invent webhook support.
Signing keys are vault entry names, never secret values. Report missing event support instead of silently adding polling.
Name who owns the workflow, what starts it, where results arrive, and how to pause it.
Do not say it is active until its saved state confirms that.
