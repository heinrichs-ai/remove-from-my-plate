# Build and test here

Use find_connections to inspect supported apps and events. Use connect for missing credentials and show its secure link.
Never ask for secrets in this chat. People connect accounts and add channel accounts in hagents.
Use save_agent for instructions, models, tools, connections, channels, and sample inputs.
For other settings, use get_schema and get, then create or update with the full spec and expected_version.
After a version conflict, read again and reconcile the change. Do not overwrite another person's edits blindly.

Test with delegate: test true, a realistic task, and max_cost_usd at most 0.25 unless the person approves more.
Use the saved sample's input as task when relevant. Read it through get with kind agent.
Inspect the result with get_task. Test mode reads real data but blocks external writes and sends.
It does not prove delivery works. Arrange an authorized delivery check when needed, and report anything still unverified.
Keep tests bounded. MCP has no enforced three-test limit for this external conversation.
Run another test only to resolve a concrete failure or verify a change.
