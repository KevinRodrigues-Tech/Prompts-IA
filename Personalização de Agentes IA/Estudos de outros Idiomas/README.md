# Estudos de outros Idiomas

Esta pasta contém prompts de personalização para configurar agentes de IA especializados no **estudo e prática de idiomas estrangeiros**, com foco no inglês para falantes nativos de português brasileiro. Dentro dela encontram-se um prompt principal de personalização de agente e uma subpasta `Estruturas` com módulos especializados de estudo (gramática, vocabulário, conversação diária, imersão, profissional, clube do livro).

## Descrição e Propósito
Os prompts nesta área são destinados a adaptar o comportamento de modelos de linguagem (ChatGPT, Claude, Gemini, etc.) para atender às necessidades de aprendizado de idiomas, fornecendo correções, explicações, exercícios e interações imersivas. Eles se dividem em duas partes:

1. **Prompt Principal de Personalização de Agente** (`Personalização Agente IA.txt`)  
   - Define o usuário como buscando fluência máxima em inglês (compreensão, escrita, fala e leitura).  
   - **Abordagem de Comunicação e Idioma:** imersão gradual em inglês sempre que possível, uso do português apenas para explicar conceitos gramaticais complexos ou quando solicitado explícitamente; tom encorajador, paciente, mas focado no progresso real.  
   - **Método de Correção (Essencial):** quando o usuário cometer erro de gramática, vocabulário ou ortografia, a IA deve: (1) validar o conteúdo da mensagem normalmente; (2) incluir uma seção de correção chamada "The Polish Station" no final, apontando o erro, explicando por que está errado (em português, se necessário) e fornecendo a versão correta e natural; (3) sempre que a frase estiver gramaticalmente correta mas soar robótica ou pouco natural, sugerir um idiom, phrasal verb ou slang que um nativo usaria.  
   - **Dinâmica das Conversas e Engajamento:** término quase sempre das mensagens com uma pergunta aberta em inglês relacionada ao assunto para forçar resposta e continuidade da prática; introdução de 1 ou 2 palavras novas ou expressões avançadas sempre que mudar de assunto (vocabulário do dia).  
   - **Comandos Especiais:** palavras‑chave para mudar o modo de aula:  
     - `[GRAMMAR] + assunto`: aula teórica focada, direta e com exercícios práticos sobre ponto gramatical.  
     - `[ROLEPLAY] + cenário`: simulação de cenário real (ex: entrevista de emprego, imigração, pedindo café).  
     - `[QUIZ]`: teste rápido de 5 perguntas baseado em erros recentes ou vocabulário aprendido.  

2. **Subpasta Estruturas – Módulos Especializados de Estudo**  
   Contém arquivos de prompt que configuram a IA para atividades específicas de aprendizado de inglês:  
   - **Gramática.txt** – foco em precisão gramatical, estrutura lógica, correção de vícios e domínio dos tempos verbais; atua como professor de gramática de alta performance; inclui comandos de ativação como `[EXPLAIN]`, `[DRILL]`, `[WHY]` e manutenção de um "error log" para revisão espaçada.  
   - **Vocabulário.txt** – (presumivelmente) expansão de lexicão, definições, uso em contextos, sinônimos/antônimos.  
   - **Conversação Diária.txt** – prática de situações cotidianas, melhoria de fluência espontânea.  
   - **Imersão.txt** – ambiente de imersão total em inglês, reduzindo uso do português.  
   - **Profissional.txt** – inglês paraContextos de trabalho, negócios, entrevistas, apresentações.  
   - **Clube do Livro.txt** – discussão de literatura, análise de textos, melhoria de leitura crítica.  
   - (Já existe um `README.md` dentro da subpasta, possivelmente criado anteriormente.)

## Instruções de Uso
1. Para o prompt geral de estudo de idioma:  
   a. Abra o arquivo `Personalização Agente IA.txt`.  
   b. Copie todo o conteúdo.  
   c. Cole na conversa com seu modelo de linguagem preferido (ChatGPT, Gemini, Claude, etc.).  
2. Para os módulos especializados:  
   a. Acesse a subpasta `Estruturas`.  
   b. Escolha o arquivo correspondiente ao aspecto que deseja praticar (gramática, vocabulário, conversação, imersão, profissional, clube do livro).  
   c. Copie todo o conteúdo do arquivo escolhido.  
   d. Cole na conversa com seu modelo de linguagem preferido.  
3. A IA agora terá o contexto e as diretrizes para auxiliá-lo em imersão gradual, correção de erros, expansão de vocabulário, prática de conversação diária, estudo focado de gramática, preparação para uso profissional e discussão literária.  
4. Opcionalmente, você pode adaptar as seções para refletir seu nível específico ou objetivos de aprendizado.

## Estrutura
- Personalização Agente IA.txt
- Estruturas/
  - Clube do Livro.txt
  - Conversação Diária.txt
  - Gramática.txt
  - Imersão.txt
  - Profissional.txt
  - Vocabulário.txt
  - README.md