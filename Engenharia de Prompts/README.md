# Engenharia de Prompts

Esta pasta contém um guia de boas práticas para elaborar prompts eficazes que extraem o máximo de relevância e precisão de modelos de linguagem (LLMs). O documento apresenta técnicas comprovadas para melhorar a qualidade das respostas obtidas.

## Descrição e Propósito
O guia ensina como ajustar seus prompts para obter respostas mais personalizadas, detalhadas e úteis. Ele aborda seis princípios fundamentais:
1. **Especificidade**: fornecer o máximo de detalhes possíveis para evitar ambiguidades.
2. **Formato da Resposta**: definir claramente como a resposta deve ser estruturada (tópicos, passo a passo, parágrafo ou tabela).
3. **Perguntas do Modelo**: solicitar que o LLM faça perguntas antes de responder, garantindo que tutte as informações necessárias sejam coletadas.
4. **Contexto**: descrever a situação, o cenário e o objetivo para que o modelo compreenda plenamente o pedido.
5. **Verificação**: pedir que o modelo confira se todos os itens da solicitação foram atendidos na resposta gerada.
6. **Expertise / Função**: atribuir uma papel ou especialidade ao modelo (ex.: “Imagine que você é um renomado chef de cozinha”) para respostas mais especializadas e menos genéricas.

## Instruções de Uso
Ao criar um prompt para qualquer LLM (ChatGPT, Claude, Gemini, etc.):
- Seja **específico**: inclua detalhes como números, prazos, restrições, preferências e exemplos concretos.
- Defina o **formato** desejado da resposta (ex.: “Responda em tópicos”, “Forneça um passo a passo”, “Resuma em um parágrafo”, “Apresente em uma tabela”).
- Adicione ao final: **“Faça perguntas antes de responder.”** Isso estimula o modelo a esclarecer dúvidas antes de producir a saída.
- Forneça **contexto rico**: explique quem você é, qual o problema, o ambiente e qualquer informação relevante.
- Após obter a resposta, peça verificação: **“Confira essa solicitação e verifique se todos os itens foram adicionados na resposta.”**
- Opcionalmente, atribua uma **função** ou especialidade ao modelo para direcionar o tom e o conteúdo (ex.: “Você é um professor especialista em inglês”).

Aplicando essas diretrizes, você aumenta significativamente a chance de obter respostas alinhadas às suas expectativas.

## Estrutura
- Estrutura de Prompts.md