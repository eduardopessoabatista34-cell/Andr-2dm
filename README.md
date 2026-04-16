🧩 Modos do Copiloto (Ask, Edit, Plan, Agent e Study)

O Copiloto oferece diferentes modos de interação para você escolher como quer trabalhar: desde tirar dúvidas sem mexer no código, até editar trechos específicos, planejar mudanças maiores ou delegar tarefas mais complexas com um modo mais autônomo.

A ideia é simples: você seleciona o modo que melhor combina com seu objetivo no momento e ganha velocidade com mais controle.

---

❓ Ask — Entender Sem Alterar

O modo Ask é para fazer perguntas e entender coisas sem alterar seu código.

Você pode perguntar sobre:

- Arquivo específico
- Erro no código
- Função
- Stack trace
- Conceitos gerais

O Copiloto lê o contexto do projeto (arquivos abertos, seleção, etc.) e responde como um mentor técnico, explicando o que está acontecendo e por quê.

Importante:
👉 Não modifica nada — apenas analisa e explica.

📄 Prompt: "prompts/prompt-ask.md"

---

✏️ Edit — Alterar Código

O modo Edit serve para alterar código existente.

Você seleciona:

- Um trecho
- Um arquivo inteiro

Depois descreve o que quer mudar, e o Copiloto aplica a modificação diretamente.

Ideal para:

- Refactors
- Ajustes de lógica
- Melhoria de performance
- Mudança de estilo
- Conversão de linguagem
- Adicionar logs
- Tratar erros

👉 Aqui o foco é: "Pegue isso que já existe e transforme"

📄 Prompt: "prompts/prompt-edit.md"

---

🧭 Plan — Planejar Antes de Codar

Quando você pede algo mais complexo, o Copiloto entra no modo Plan.

Ele:

1. Divide o problema em etapas
2. Explica o que vai fazer
3. Depois executa

Esse modo é muito útil para:

- Mudanças grandes
- Novas features
- Refatorações complexas
- Validação de abordagem

📄 Prompt: "prompts/prompt-plan.md"

---

🤖 Agent — Modo Autônomo

O Agent é o modo mais autônomo do Copiloto.

Ele pode:

- Navegar pelo projeto
- Criar arquivos
- Modificar múltiplos pontos
- Manter contexto entre passos

Funciona como um dev júnior trabalhando com você.

Exemplo:

«"Implemente login com JWT"»

O Agent decide:

- Quais arquivos criar
- O que modificar
- Como conectar tudo

📄 Prompt: "prompts/prompt-agent.md"

---

📚 Study — Aprendizado Ativo

O modo Study é focado em aprendizado, não apenas em chegar na resposta.

Ele:

- Ensina e guia o raciocínio
- Destaca conceitos importantes
- Mostra trade-offs
- Faz perguntas reflexivas
- Avança gradualmente

Funciona como um tutor particular.

📄 Prompt: "prompts/prompt-study.md"

---

🧠 Resumo Mental Rápido

Modo| Objetivo
❓ Ask| Entender
✏️ Edit| Mudar código
🧭 Plan| Planejar antes
🤖 Agent| Executar tarefas grandes
📚 Study| Aprender ativamente

---

🚀 Quando Usar Cada Um

- Dúvida sobre código → Ask
- Pequena alteração → Edit
- Feature complexa → Plan
- Tarefa grande → Agent
- Aprender conceito → Study

---

💡 Dica:
Você pode combinar modos durante o desenvolvimento:

1. Ask → Entender
2. Plan → Planejar
3. Edit → Alterar
4. Agent → Automatizar

---
