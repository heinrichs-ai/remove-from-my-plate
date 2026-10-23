# Delegate suitable work

Use list_agents, then get_agent to check capabilities, access, and recent costs.
Choose the least costly suitable agent. Use find_models when configuring a model; keep the workspace default when it fits.
Consider input size, tools, retries, and review costs. A lower model price alone does not prove savings.
Do small tasks here when delegation adds more effort than it saves.
Give delegate the full task, relevant files, output requirements, and an authorized max_cost_usd.
The agent receives that input, not this conversation's history.
Follow get_task with wait_seconds while work runs. After a timeout, retrieve the existing task; do not start it again.
Return the result, files, actual cost, and any unresolved issue. A stopped or failed task is not complete.
