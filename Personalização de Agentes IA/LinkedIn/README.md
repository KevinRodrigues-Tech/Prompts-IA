# LinkedIn

Esta pasta contém prompts de personalização para configurar agentes de IA especializados em **otimização de perfis e criação de conteúdo para o LinkedIn**. Dentro dela encontra-se um prompt geral de estruturação de perfil e uma subpasta `Projetos` com um prompt específico para geração de posts técnicos com infográficos.

## Descrição e Propósito
Os prompts nesta área são destinados a adaptar o comportamento de modelos de linguagem (ChatGPT, Claude, Gemini, etc.) para atender às necessidades de profissionais que desejam melhorar sua presença no LinkedIn, tanto em termos de perfil quanto de publicação de conteúdo. Eles se dividem em duas especializações:

1. **Prompt de Estruturação de Perfil do LinkedIn** (`Personalização de Agente.txt`)  
   - Define o usuário como buscando atuar como arquiteto oficial para estruturação de perfis de alto impacto.  
   - **Objetivo:** transformar informações profissionais brutas em um perfil magnético, otimizado para o algoritmo de busca do LinkedIn (SEO de Carreira) e atraente para recrutadores.  
   - **Estrutura de resposta esperada:** seções oficiais do LinkedIn:  
     - Título Profissional (Headline) – 2 a 3 opções estratégicas com palavras‑chave de busca, especialidade e diferencial.  
     - Sobre (Summary/About) – texto persuasivo em 1ª pessoa, com gancho, trajetória, conquistas, competências e chamada para ação.  
     - Experiência Profissional – foco em resultados e conquistas mensuráveis (método STAR), bullet points com verbos de ação.  
     - Competências (Skills) – lista de 10‑15 palavras‑chave essenciais (hard e soft skills).  
     - Recomendações (Opcional) – modelo de texto para solicitar recomendações.  
     - Diretrizes Visuais – sugestões para foto de perfil e foto de capa (banner).  
   - **Regras de comportamento:** tom corporativo, confiante, estratégico e moderno; otimização com palavras‑chave de alta relevância; fazer perguntas específicas se dados estiverem incompletos.

2. **Prompt de Criação de Conteúdo Técnico para LinkedIn** (`Projetos/Criação-de-Conteúdo.txt`)  
   - Define o usuário como Assistente Especialista de Conteúdo de TI da marca "Rodrigues | T.I".  
   - **Objetivo:** transformar estudos técnicos de TI em conteúdos educativos, visuais e de alto engajamento para o LinkedIn, gerando tanto uma imagem (infográfico/diagrama) quanto o texto do post associado.  
   - **Diretrizes de Imagem:**  
     - Título de destaque claro e legível no topo.  
     - Conteúdo explicativo: infográfico, diagrama ou cena ilustrativa com ícones, fluxogramas ou metáforas visuais; estilo limpo, moderno, tecnológico.  
     - Incorporação do logo "Rodrigues | T.I" (image_0.png) de forma discreta mas visível (canto inferior direito ou central).  
   - **Diretrizes de Texto do Post:**  
     - Título de post engajador (diferente do título da imagem).  
     - Hook (gancho) inicial impactante.  
     - Explicação estruturada (bullet points ou parágrafos curtos), focando no "porquê isso é importante".  
     - Jornada de aprendizado (menção sutil de que está aprendendo agora).  
     - Call to Action (CTA) – pergunta para gerar comentários.  
     - Hashtags estratégicas (5‑7 hashtags relevantes para TI e aprendizado).  
   - **Ciclo de geração:** ao receber tópico de estudo e contexto opcional, o agente processa o tópico, gera a imagem conforme as diretrizes, e depois gera o texto do post.

## Instruções de Uso
1. Para o prompt de perfil:  
   a. Abra o arquivo `Personalização de Agente.txt`.  
   b. Copie todo o conteúdo.  
   c. Cole na conversa com seu modelo de linguagem preferido (ChatGPT, Gemini, Claude, etc.).  
   d. Forneça os dados profissionais quando solicitado ou aguide o agente com as informações do profissional.  
2. Para o prompt de criação de conteúdo:  
   a. Acesse a subpasta `Projetos`.  
   b. Abra o arquivo `Criação-de-Conteúdo.txt`.  
   c. Copie todo o conteúdo.  
   d. Cole na conversa com seu modelo de linguagem preferido.  
   e. Forneça o tópico de estudo (ex: "Docker e Contêineres – o básico") e, opcionalmente, o contexto de aprendizado.  
3. A IA agora terá o contexto e as diretrizes para auxiliá-lo em otimizar perfis do LinkedIn (headline, about, experiência, skills, recomendações, elementos visuais) e para criar posts técnicos engajadores com infográficos e textos estruturados.  
4. Opcionalmente, adapte as seções para refletir sua área específica (ex: desenvolvimento, infraestrutura, dados, design) ou seu branding pessoal.

## Estrutura
- Personalização de Agente.txt
- Projetos/
  - Criação-de-Conteúdo.txt