# Guia de Prompts do Projeto — Ecossistema IA

Este documento reúne a cadeia sequencial de prompts utilizada com o ChatGPT e o ecossistema de IA generativa para planejar e produzir os materiais da aula sobre **Quantidade de Movimento (Momento Linear)** para o 1º ano do Ensino Médio.

---

## Fluxo da Cadeia de Prompts

```text
[Prompt 1: Especialista e Contexto Ético/LGPD]
                     │
                     ▼
[Prompt 2: Estruturação do Plano de Aula (50 min)]
                     │
                     ▼
[Prompt 3: Geração dos Materiais Complementares (Padrão)]
                     │
                     ▼
[Prompt 4: Adaptação Didática Inclusiva (Perfil TDAH)]
```

---

## Prompt 1 — Especialista em Educação, Física e Contexto Ético

**Objetivo:** Calibrar a IA para atuar como assistente pedagógico especializado em Física, estabelecendo as diretrizes metodológicas, a separação dos perfis de estudantes e os princípios inegociáveis de ética, autoria docente e conformidade com a LGPD.

```text
Atue como um assistente especializado em educação e no ensino de Física para o 1º ano do Ensino Médio. Você apoiará o professor na criação de uma aula interativa sobre Quantidade de Movimento.

## Contexto da turma
O material será planejado para dois perfis de estudantes:
1. Um estudante sem necessidade de adaptação específica (perfil padrão).
2. Um estudante com TDAH, para quem serão preparados materiais e estratégias adaptados.

Quando eu pedir materiais ou atividades, apresente os dois conjuntos separadamente e identifique claramente para qual perfil cada um foi preparado. Mantenha os mesmos objetivos de aprendizagem e o rigor conceitual nos dois conjuntos, adaptando a apresentação, a extensão, as instruções e as estratégias de participação conforme necessário.

## Orientações pedagógicas
- Proponha experiências interativas, exemplos concretos e situações do cotidiano que ajudem a compreender Quantidade de Movimento.
- Explique os conceitos de forma correta e adequada à faixa escolar. Ao trabalhar fórmulas, explique o significado das grandezas, suas unidades e, quando pertinente, seu caráter vetorial.
- Para o estudante com TDAH, favoreça instruções curtas e explícitas, tarefas divididas em etapas, organização visual, participação ativa e pausas ou mudanças de atividade quando forem apropriadas.
- Não presuma que todos os estudantes com TDAH têm as mesmas necessidades. Não use linguagem infantilizada, não reduza a expectativa de aprendizagem e não invente características do estudante além das informações fornecidas pelo professor.
- Use linguagem clara, acolhedora e respeitosa. Explique termos técnicos e evite excesso de informação em um único bloco.
- Se uma solicitação estiver ambígua ou faltar uma informação essencial para produzir um material adequado, faça uma pergunta objetiva ao professor antes de prosseguir.

## Ética e Proteção de Dados (LGPD)
- Em estrito respeito à Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018) e à ética docente, não forneça nem solicite dados pessoais, nomes reais ou relatórios clínicos confidenciais de alunos.
- Trabalhe sempre com personas didáticas genéricas fundamentadas nas diretrizes de Desenho Universal para a Aprendizagem (DUA).

## Papel da IA e do professor
A IA é uma ferramenta de apoio e não substitui o julgamento profissional do professor. A autoria e a responsabilidade pelo plano de aula e pelos materiais são do professor. Apresente conteúdos para revisão docente e sinalize eventuais limites ou pontos que precisem ser conferidos.

Por enquanto, apenas assuma este papel e confirme que compreendeu as orientações. Aguarde minha próxima solicitação para criar o plano de aula.
```

---

## Prompt 2 — Estruturação do Plano de Aula

**Objetivo:** Gerar o esqueleto detalhado do plano de aula de 50 minutos, alinhado à BNCC, com cronometragem minuto a minuto, avaliação formativa e diferenciação pedagógica.

```text
Com base no seu papel de assistente pedagógico de Física, crie o plano de aula detalhado para uma aula de 50 minutos destinada ao 1º ano do Ensino Médio sobre o tema "Quantidade de Movimento (Momento Linear)".

O plano deve ser assinado pelo professor Victor Palmeira e conter rigorosamente a seguinte estrutura em Markdown:

1. Objetivos de Aprendizagem:
   - Definir quantidade de movimento e sua relação vetorial (p = m · v);
   - Calcular módulo no SI e expressar a unidade correta (kg·m/s);
   - Relacionar direção e sentido de p aos da velocidade;
   - Introduzir apenas qualitativamente a ideia de conservação em sistemas isolados, sem desenvolver cálculos ou fórmulas de conservação nesta aula.

2. Conteúdo Programático: listagem dos tópicos conceituais abordados.

3. Metodologia: dinâmica interativa contemplando problematização inicial, explicação dialogada, exemplos guiados, prática de análise, exercícios e síntese.

4. Recursos Necessários: projetor, apresentação em slides, cronômetro visual, quadro e materiais didáticos impressos/digitais.

5. Desenvolvimento Passo a Passo (com cronometragem exata somando 50 minutos):
   - 0–5 min: Abertura e problematização inicial com situação prática (esclarecendo que quantidade de movimento não é força);
   - 5–15 min: Construção do conceito, fórmula, unidade e vetor;
   - 15–25 min: Exemplos e aplicação guiada no quadro (cálculo e comparação vetorial com sentidos opostos);
   - 25–40 min: Prática de análise guiada (7 min) e resolução de questões selecionadas em folhas diferenciadas (8 min);
   - 40–50 min: Sistematização dos conceitos, introdução qualitativa à conservação e fechamento.

6. Avaliação: critérios formativos, participação e acolhimento de múltiplas formas de resposta.

7. Diferenciação Pedagógica:
   - Seção 7.1: Perfil sem adaptação específica (padrão);
   - Seção 7.2: Perfil com TDAH (estratégias com instruções curtas e em etapas, destaque visual, temporização explícita e opções flexíveis de registro).

8. Referências: menção à BNCC (Ensino Médio), Halliday & Resnick (Mecânica) e fonte educacional de apoio.

9. Transparência sobre o Uso de IA e Proteção de Dados (LGPD): nota destacando que a autoria e revisão final são do professor Victor Palmeira e que nenhum dado pessoal de alunos foi utilizado (LGPD).
```

---

## Prompt 3 — Geração dos Materiais Didáticos Complementares

**Objetivo:** Produzir o material instrucional completo (texto explicativo, atividade prática controlada de 7 minutos e lista de 5 exercícios calibrados com gabarito comentado).

```text
Agora que o plano de aula está definido, elabore o conjunto de materiais didáticos complementares para os estudantes do 1º ano do Ensino Médio sobre "Quantidade de Movimento (Momento Linear)".

Gere os três materiais a seguir:

1. Texto Explicativo (Texto de Apoio):
   - Definição clara e acessível de quantidade de movimento;
   - Apresentação da fórmula p = m · v com explicação do significado físico de cada letra e da unidade kg·m/s;
   - Enfatização do caráter vetorial (mesma direção e sentido da velocidade);
   - Três exemplos concretos do cotidiano (carrinhos com massas diferentes, mesma bola com velocidades diferentes, inversão de sentido de um móvel);
   - Parágrafo de alerta conceitual: quantidade de movimento NÃO é força e não define sozinha tempo ou distância de parada.

2. Atividade Prática Guiada ("Comparação Guiada"):
   - Duração prevista de 7 minutos;
   - Análise de três casos controlados:
     * Caso A: carrinho de 2 kg a 3 m/s;
     * Caso B: carrinho de 4 kg a 3 m/s;
     * Caso C: carrinho de 2 kg a 6 m/s;
   - Etapas temporizadas (cálculo de p, comparação das grandezas que mudam e reflexão sobre a variação de p ao parar);
   - Gabarito orientador com conclusão esperada.

3. Lista de Exercícios com Gabarito:
   - Indicação de uso em aula: cerca de 8 minutos para debater as questões 1 e 3;
   - Questão 1 (Conceitual): definição física, fórmula vetorial e unidade SI;
   - Questão 2 (Proporcionalidade): efeito de duplicar a velocidade com massa constante;
   - Questão 3 (Cálculo): aplicação direta com bola de 0,4 kg a 20 m/s no SI;
   - Questão 4 (Caráter Vetorial): dois patinadores de 50 kg a 3 m/s em sentidos opostos (+x e -x), exigindo raciocínio sobre igualdade vetorial;
   - Questão 5 (Interpretação e Frenagem): comparação de automóvel de passeio e caminhonete com massas e velocidades diferentes, e refutação fundamentada da ideia de que maior quantidade de movimento implica necessariamente maior distância de frenagem;
   - Gabarito comentado completo e indicação de fonte consultada.
```

---

## Prompt 4 — Adaptação dos Materiais para Estudantes com TDAH

**Objetivo:** Adaptar o conjunto didático com base em neurociência e DUA, reduzindo a carga cognitiva extrínseca sem comprometer o rigor ou a profundidade dos conceitos físicos.

```text
Com base nos materiais complementares gerados anteriormente, elabore a versão adaptada especificamente para o perfil de estudante com TDAH (Transtorno do Déficit de Atenção com Hiperatividade), contemplando texto explicativo, atividade prática e lista de exercícios.

Siga rigorosamente as seguintes diretrizes pedagógicas e neuroeducacionais:

1. Preservação do Rigor e dos Objetivos:
   - Os objetivos de aprendizagem, as equações, os valores numéricos dos exemplos e exercícios e o nível de exigência conceitual devem permanecer rigorosamente IDÊNTICOS aos do material padrão;
   - NÃO infantilize a linguagem e NÃO reduza o desafio cognitivo.

2. Estrutura Visual e Carga Cognitiva:
   - Divida os textos em blocos curtos, tópicos numerados e frases diretas, eliminando parágrafos longos ou sobrecarga de texto;
   - Destaque termos-chave, grandezas e fórmulas essenciais com negrito e formatação em caixas limpas;
   - Evite poluição visual ou elementos puramente decorativos que distraiam do foco da tarefa.

3. Instruções em Etapas (Chunking) e Temporização:
   - Divida os exercícios e as atividades em etapas sequenciais explícitas (ex.: Etapa 1: Dados; Etapa 2: Fórmula; Etapa 3: Cálculo e Unidade);
   - Indique estimativas de tempo realistas e pausas/transições entre blocos de atividade.

4. Formatos Múltiplos de Resposta:
   - Permita e sugira diferentes modos de demonstrar compreensão (cálculo algébrico, diagramação com setas/desenhos para vetores ou explicação oral direta ao professor);
   - Forneça caixas de preenchimento estruturadas nos enunciados das questões de cálculo.

5. Adaptação dos Três Itens:
   - Texto Explicativo adaptado com tópicos diretos e destaque para unidades e fórmula;
   - Comparação Guiada particionada em passos com tempos de 3 min, 2 min e 2 min;
   - Lista de Exercícios contendo as mesmas 5 questões do material padrão, mas organizadas com andaimes cognitivos de preenchimento guiado e gabarito correspondente.
```
