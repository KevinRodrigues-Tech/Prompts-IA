# Copilot

Esta pasta contém scripts de prompt que definem papéis especializados (modos) para o Copilot, permitindo que você obtenha comportamentos específicos ao interagir com um modelo de linguagem. Cada Script coloca o modelo em uma identidade configurada (por exemplo, agente de implementação de código, planejador, assistente de perguntas ou tutor) com pilha tecnológica, personalidade e regras claras.

## Descrição e Propósito
Os prompts aqui são projetados para guiar o LLM a agir como um copilô técnico em diferentes cenários de desenvolvimento de software:
- **Agent**: foca em produzir mudanças de código implementáveis, com etapas de descoberta, planejamento, implementação, verificação e finalização.
- **Plano**: gera planos de implementação revisáveis (passos, arquivos, riscos, validações) sem escrever código.
- **ASK**: responde dúvidas, explica código, diagnostica erros e sugere abordagens, sem executar mudanças automaticamente.
- **STUDY**: atua como tutor, explicando conceitos com progressão didática, analogias, exemplos e checkpoints de compreensão.

Cada prompt inclui seções editáveis de identidade, stack (tecnologia), personalidade (estilo Cortana‑like) e regras específicas do modo.

## Instruções de Uso
1. Escolha o arquivo .md correspondente ao modo desejado (Agent.md, Plan, ASK ou Study – observe que Plan, ASK e Study estão sem extensão, mas seu conteúdo está nos arquivos sem extensão; os arquivos .md disponíveis são Agent.md e README.md).
2. Abra o arquivo e copie todo o bloco de instruções, desde o cabeçalho (ex.: `## Prompt (Instructions) — Copiloto`) até o final do arquivo.
3. Cole o bloco copiado na conversa com seu modelo de linguagem preferido (ChatGPT, Claude, Gemini, etc.).
4. Agora interaja normalmente: o modelo seguirá o papel e as regras definidas no prompt.
5. Se precisar adaptar a stack ou personalidade, edite as seções marcadas como “EDITÁVEL” antes de colar.

## Estrutura
- Agent.md
- README.md