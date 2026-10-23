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

You need a hagents account and an assistant that supports skills and remote MCP connections.
Agent runs use your hagents balance. This repository contains instructions, not account access.

1. Add `https://dash.hagents.app/mcp` as a remote MCP server in your assistant.
2. Sign in through OAuth and choose your workspace and permissions.
3. Install the skill using one of the options below.

### Install

```sh
npx skills add heinrichs-ai/remove-from-my-plate
```

For Claude, download the [skill ZIP](https://github.com/heinrichs-ai/remove-from-my-plate/releases/latest/download/remove-from-my-plate.zip).
Upload it through Customize → Skills.

For Codex, Cursor, or Copilot, copy `SKILL.md` into `~/.agents/skills/remove-from-my-plate/`.
For Claude Code, use `~/.claude/skills/remove-from-my-plate/`.

Use the same skill in a project by placing its folder under the project's skills directory.
Automatic selection depends on the client and model. You can also ask your assistant to use “Remove from my plate”.

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

Você precisa de uma conta no hagents e de um assistente compatível com skills e conexões MCP remotas.
As execuções dos agentes usam seu saldo no hagents. Este repositório contém instruções, sem acesso à sua conta.

1. Adicione `https://dash.hagents.app/mcp` como servidor MCP remoto no seu assistente.
2. Entre pela conexão OAuth e escolha o espaço de trabalho e as permissões.
3. Instale a skill conforme as opções abaixo.

### Instalar

```sh
npx skills add heinrichs-ai/remove-from-my-plate
```

No Claude, baixe o [ZIP da skill](https://github.com/heinrichs-ai/remove-from-my-plate/releases/latest/download/remove-from-my-plate.zip).
Envie o arquivo em Customize → Skills.

No Codex, Cursor ou Copilot, copie `SKILL.md` para `~/.agents/skills/remove-from-my-plate/`.
No Claude Code, use `~/.claude/skills/remove-from-my-plate/`.

Para usar em um projeto, coloque a pasta da skill no diretório de skills desse projeto.
A ativação automática depende do aplicativo e do modelo. Você também pode pedir ao assistente para usar “Remove from my plate”.

### Experimentar

- “Encontre um agente que faça esta tarefa com menor custo.”
- “Quero receber um resumo da agenda no Slack todas as manhãs, de segunda a sexta.”
- “Prepare respostas para emails deste tipo e espere minha revisão antes de enviar.”
- “Mostre as tarefas e perguntas que precisam da minha atenção.”
