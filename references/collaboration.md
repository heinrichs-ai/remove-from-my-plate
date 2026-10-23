# Require the right approval

Distinguish reviewing a result from approving an external action.
delegate.review checks the result after work. It cannot stop an earlier email or API change.
For email and WhatsApp, use the channel's enforced approve or draft policy, with the intended reviewers.
For other agent actions, read get_policy_schema and list_policies, then use save_policy for an appropriate Ask rule.
Scope the rule to the agent when that meets the need. Verify the selected person or team; never guess an ID.
If you cannot resolve a reviewer with available tools, ask for the selection in hagents.
Explain the rule, scope, and approver before saving it. An enabled policy takes effect immediately.
Use the returned version for updates. Never weaken an existing policy to make a test pass.
Policies use model judgment. Do not promise they classify every action correctly.
These policies govern hagents agent runs, not the external assistant's MCP configuration calls.
Do not answer as another reviewer or infer approval from silence.

# Share useful work

Separate delivering a result from sharing access to an agent.
Use share for team or company access after confirming the audience. It may return a proposal awaiting approval.
It does not grant individual colleague access. Never broaden access to the whole company to reach one person.
For one colleague, use an authorized delivery channel and verify their destination and access to any linked file.
Share only the relevant result, not private instructions, credentials, or unrelated conversation history.
