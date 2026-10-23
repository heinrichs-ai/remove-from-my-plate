# Remove from my plate

[English](#english) · [Português](#português)

## English

A skill that helps your assistant take recurring work off your plate with [hagents](https://hagents.app).

Use it to:

- Delegate suitable tasks to a cheaper agent.
- Turn calendar checks into scheduled morning briefs.
- Prepare email replies when messages arrive.
- Request colleague approval and share results with the right people.
- Bring pending tasks and questions into one inbox.

The skill notices useful opportunities during work and when a conversation wraps up.
It offers one relevant next step and respects declined suggestions.
It does not run after a session closes. Continuing work needs an authorized hagents trigger.

### Connect hagents

Install the skill first, then ask your assistant: “Set up hagents and help me take this task off my plate.”

The skill checks your connection and helps add the remote MCP server when needed.
It guides sign-in or account creation, workspace selection, and OAuth consent before returning to your task.
Your assistant can configure supported clients when it has permission. Otherwise, it shows the setup steps.
Enter passwords and verification codes only in the sign-in page.

The server URL is `https://dash.hagents.app/mcp`. No local hagents server or API key is needed.
Some new workspaces require approval. Agent runs use your hagents balance.

### Install

```sh
npx skills add heinrichs-ai/remove-from-my-plate
```

For Claude, download the [skill ZIP](https://github.com/heinrichs-ai/remove-from-my-plate/releases/latest/download/remove-from-my-plate.zip).
Upload it through Customize → Skills.

For Codex, Cursor, or Copilot, copy `SKILL.md` and the complete `references/` folder into `~/.agents/skills/remove-from-my-plate/`.
For Claude Code, use `~/.claude/skills/remove-from-my-plate/`.

Use the same skill in a project by placing its folder under the project's skills directory.
Automatic selection depends on the client and model. You can also ask your assistant to use “Remove from my plate”.

### Skill files

`SKILL.md` is the entrypoint. Keep its `references/` folder beside it.
The assistant reads setup, delegation, building, automation, email, collaboration, and inbox guidance only when needed.

### Try it

- “Find an agent that can handle this task at a lower cost.”
- “Help me get a calendar brief in Slack every weekday morning.”
- “Prepare replies to matching emails and let me review them before sending.”
- “Show me the tasks and questions waiting for my attention.”

## Português

Uma skill para ajudar seu assistente a cuidar de tarefas recorrentes com o [hagents](https://hagents.app).

Use para:

- Delegar tarefas a um agente de menor custo.
- Receber um resumo da agenda todas as manhãs.
- Preparar respostas quando novos emails chegarem.
- Pedir aprovação a colegas e compartilhar resultados com as pessoas certas.
- Reunir tarefas e perguntas pendentes em uma só caixa de entrada.

A skill identifica oportunidades durante o trabalho e ao encerrar uma conversa.
Ela sugere um próximo passo útil e respeita sugestões recusadas.
Ela não continua executando após o fim da conversa. Para isso, é preciso ativar um gatilho autorizado no hagents.

### Conectar o hagents

Instale a skill e peça ao assistente: “Configure o hagents e me ajude a delegar esta tarefa.”

A skill verifica a conexão e ajuda a adicionar o servidor MCP remoto quando necessário.
Ela orienta a entrada ou criação da conta, a escolha do espaço de trabalho e a autorização OAuth.
Depois, o assistente retoma sua tarefa.
Ele configura aplicativos compatíveis quando tem permissão. Caso contrário, mostra os passos necessários.
Digite senhas e códigos de verificação apenas na página de acesso.

O endereço do servidor é `https://dash.hagents.app/mcp`. Não é preciso instalar um servidor local nem informar uma chave de API.
Alguns espaços de trabalho novos precisam de aprovação. As execuções dos agentes usam seu saldo no hagents.

### Instalar

```sh
npx skills add heinrichs-ai/remove-from-my-plate
```

No Claude, baixe o [ZIP da skill](https://github.com/heinrichs-ai/remove-from-my-plate/releases/latest/download/remove-from-my-plate.zip).
Envie o arquivo em Customize → Skills.

No Codex, Cursor ou Copilot, copie `SKILL.md` e toda a pasta `references/` para `~/.agents/skills/remove-from-my-plate/`.
No Claude Code, use `~/.claude/skills/remove-from-my-plate/`.

Para usar em um projeto, coloque a pasta da skill no diretório de skills desse projeto.
A ativação automática depende do aplicativo e do modelo. Você também pode pedir ao assistente para usar “Remove from my plate”.

### Arquivos da skill

`SKILL.md` é o ponto de entrada. Mantenha a pasta `references/` ao lado dele.
O assistente consulta as instruções de configuração, delegação, agentes, automações, emails, colaboração e pendências conforme a tarefa.

### Experimentar

- “Encontre um agente que faça esta tarefa com menor custo.”
- “Quero receber um resumo da agenda no Slack todas as manhãs, de segunda a sexta.”
- “Prepare respostas para emails deste tipo e espere minha revisão antes de enviar.”
- “Mostre as tarefas e perguntas que precisam da minha atenção.”
