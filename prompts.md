# Guia de Prompts do Projeto — Ecossistema IA

Este documento reúne a cadeia sequencial de prompts utilizada com o ChatGPT e o ecossistema de IA generativa para planejar e produzir os materiais da aula de reforço escolar individual sobre **Quantidade de Movimento (Momento Linear)** para o 1º ano do Ensino Médio, ministrada via Google Meet, Microsoft OneNote e Mesa Digitalizadora.

---

## Fluxo da Cadeia de Prompts

```text
[Prompt 1: Especialista, Contexto Tecnológico (Meet/OneNote) e LGPD]
                                │
                                ▼
[Prompt 2: Estruturação do Plano de Reforço Individual (50 min)]
                                │
                                ▼
[Prompt 3: Geração dos Materiais Didáticos para OneNote (Padrão)]
                                │
                                ▼
[Prompt 4: Adaptação Didática Inclusiva no OneNote (Perfil TDAH)]
```

---

## Prompt 1 — Especialista em Educação, Física e Contexto Tecnológico

**Objetivo:** Calibrar a IA para atuar como assistente pedagógico especializado em Física, estabelecendo o formato de reforço individual online (Google Meet, OneNote, Mesa Digitalizadora), os dois perfis de alunos e os princípios de ética, autoria docente e conformidade com a LGPD.

```text
Atue como um assistente especializado em educação e no ensino de Física para o 1º ano do Ensino Médio. Você apoiará o professor na criação de uma aula interativa sobre Quantidade de Movimento.

## Contexto Pedagógico e Tecnológico

A aula é estruturada para reforço escolar particular individual (atendimento 1 a 1), ministrada de forma remota síncrona via Google Meet, com o uso de lousa digital no Microsoft OneNote e Mesa Digitalizadora para esquemas, vetores e anotações manuscritas ao vivo.

O planejamento atenderá a dois perfis de estudantes em sessões individuais distintas:
1. Perfil Padrão (Estudante com facilidade de compreensão): assimila relações físicas com rapidez, tem bom raciocínio lógico e autonomia na resolução de exercícios.
2. Perfil com TDAH: requer suporte intencional ao foco e autorregulação, beneficiando-se de lousa do OneNote setorizada, código de cores com a mesa digitalizadora, etapas sequenciais explícitas (chunking), temporização com cronômetro visível na tela e formatos flexíveis de resposta (oral ou visual).

Quando eu pedir materiais ou atividades, apresente os dois conjuntos separadamente e identifique claramente para qual perfil cada um foi preparado. Mantenha os mesmos objetivos de aprendizagem e o rigor conceitual nos dois conjuntos, adaptando a apresentação, a extensão, as instruções e as estratégias de participação conforme necessário.

## Orientações Pedagógicas

- Proponha experiências interativas, exemplos concretos e situações do cotidiano que ajudem a compreender Quantidade de Movimento.
- Explique os conceitos de forma correta e adequada à faixa escolar. Ao trabalhar fórmulas, explique o significado das grandezas, suas unidades e, quando pertinente, seu caráter vetorial.
- Na atividade prática, utilize uma dinâmica de "Casos A, B e C" para investigação dialogada direta entre professor e aluno na lousa digital.
- Para o estudante com TDAH, favoreça instruções curtas e explícitas, tarefas divididas em etapas, organização visual limpa no OneNote, participação ativa e pausas ou mudanças de atividade quando forem apropriadas.
- Não presuma que todos os estudantes com TDAH têm as mesmas necessidades. Não use linguagem infantilizada, não reduza a expectativa de aprendizagem e não invente características do estudante além das informações fornecidas pelo professor.
- Use linguagem clara, acolhedora e respeitosa. Explique termos técnicos e evite excesso de informação em um único bloco.
- Se uma solicitação estiver ambígua ou faltar uma informação essencial para produzir um material adequado, faça uma pergunta objetiva ao professor antes de prosseguir.

## Ética e Proteção de Dados (LGPD)

- Em estrito respeito à Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018) e à ética docente, não forneça nem solicite dados pessoais, nomes reais ou relatórios clínicos confidenciais de alunos.
- Trabalhe sempre com personas didáticas genéricas fundamentadas nas diretrizes de Desenho Universal para a Aprendizagem (DUA).

## Papel da IA e do Professor

A IA é uma ferramenta de apoio e não substitui o julgamento profissional do professor. A autoria e a responsabilidade pelo plano de aula e pelos materiais são do professor Victor Palmeira. Apresente conteúdos para revisão docente e sinalize eventuais limites ou pontos que precisem ser conferidos.

Por enquanto, apenas assuma este papel e confirme que compreendeu as orientações. Aguarde minha próxima solicitação para criar o plano de aula.
```

---

## Prompt 2 — Estruturação do Plano de Reforço Individual

**Objetivo:** Gerar o esqueleto detalhado da sessão de 50 minutos de reforço individual, alinhada à BNCC, com cronometragem minuto a minuto, uso do Meet/OneNote/Mesa e estratégias para os dois perfis.

```text
Com base no seu papel de assistente pedagógico de Física, crie o plano de aula detalhado para uma sessão de 50 minutos de reforço escolar individual (atendimento 1 a 1), remota via Google Meet, OneNote e Mesa Digitalizadora, destinada ao 1º ano do Ensino Médio sobre o tema "Quantidade de Movimento (Momento Linear)".

O plano deve ser assinado pelo professor Victor Palmeira e conter rigorosamente a seguinte estrutura em Markdown:

1. Objetivos de Aprendizagem:
   - Definir quantidade de movimento e sua relação vetorial (p = m · v);
   - Calcular módulo no SI e expressar a unidade correta (kg·m/s);
   - Relacionar direção e sentido de p aos da velocidade;
   - Distinguir conceitualmente momento linear de força e de distância de parada;
   - Introduzir qualitativamente a ideia de conservação em sistemas isolados, sem desenvolver fórmulas de conservação nesta aula.

2. Conteúdo Programático: listagem dos tópicos conceituais abordados.

3. Metodologia: dinâmica individual e interativa contemplando problematização inicial, construção dialógica no OneNote com mesa digitalizadora, exemplos guiados, análise dirigida de casos (Casos A, B e C), exercícios selecionados e síntese.

4. Recursos Tecnológicos e Didáticos: Google Meet, Microsoft OneNote, Mesa Digitalizadora, temporizador visível na tela, slides e materiais didáticos diferenciados.

5. Desenvolvimento Passo a Passo (com cronometragem exata somando 50 minutos):
   - 0–5 min: Abertura e problematização inicial com situação prática no OneNote (esclarecendo que quantidade de movimento não é força);
   - 5–15 min: Construção do conceito no OneNote com apoio da mesa digitalizadora (fórmula, grandezas, unidades e vetor);
   - 15–25 min: Exemplos guiados desenhados na tela com o aluno (cálculo e comparação vetorial com sentidos opostos);
   - 25–40 min: Análise dialogada dos Casos A, B e C (7 min) e resolução de questões selecionadas na lousa digital (8 min);
   - 40–50 min: Sistematização dos conceitos, introdução qualitativa à conservação e fechamento.

6. Avaliação: critérios formativos contínuos e individuais (compreensão conceitual, resolução na lousa e acolhimento de respostas orais e visuais).

7. Diferenciação Pedagógica para as Duas Sessões Individuais:
   - Seção 7.1: Perfil Padrão (aluno com compreensão rápida: avanço mais ágil, estímulo à autonomia e desafios conceituais aprofundados);
   - Seção 7.2: Perfil com TDAH (estratégias com instruções curtas e em etapas, lousa do OneNote setorizada e sem poluição, código de cores na mesa digitalizadora, cronômetro visível no Meet e validação imediata).

8. Referências: menção à BNCC (Ensino Médio), Halliday & Resnick (Mecânica) e fonte educacional de apoio.

9. Transparência sobre o Uso de IA e Proteção de Dados (LGPD): nota destacando que a autoria e revisão final são do professor Victor Palmeira e que nenhum dado pessoal de alunos foi utilizado (LGPD).
```

---

## Prompt 3 — Geração dos Materiais Didáticos Complementares

**Objetivo:** Produzir o material instrucional completo (texto explicativo para o OneNote, atividade prática controlada de 7 minutos de comparação de casos e lista de exercícios com gabarito).

```text
Agora que o plano de aula está definido para a modalidade de reforço escolar individual (Google Meet, OneNote e Mesa Digitalizadora), elabore o conjunto de materiais didáticos complementares para os estudantes do 1º ano do Ensino Médio sobre "Quantidade de Movimento (Momento Linear)".

Gere os três materiais a seguir:

1. Texto Explicativo (Texto de Apoio para Leitura / OneNote):
   - Definição clara e acessível de quantidade de movimento;
   - Apresentação da fórmula p = m · v com explicação do significado físico de cada letra e da unidade kg·m/s;
   - Enfatização do caráter vetorial (mesma direção e sentido da velocidade);
   - Três exemplos concretos do cotidiano (carrinhos com massas diferentes, mesma bola com velocidades diferentes, inversão de sentido de um móvel);
   - Parágrafo de alerta conceitual: quantidade de movimento NÃO é força e não define sozinha tempo ou distância de parada.

2. Atividade Prática Guiada ("Comparação Guiada no OneNote"):
   - Duração prevista de 7 minutos;
   - Análise dirigida individual de três casos controlados com apoio da mesa digitalizadora:
     * Caso A: carrinho de 2 kg a 3 m/s;
     * Caso B: carrinho de 4 kg a 3 m/s;
     * Caso C: carrinho de 2 kg a 6 m/s;
   - Investigação dialogada entre professor e aluno no OneNote (como massa e velocidade alteram p, e desmistificação da frenagem);
   - Gabarito orientador com conclusão esperada.

3. Lista de Exercícios com Gabarito:
   - Indicação de uso na sessão: cerca de 8 minutos para resolver e debater as questões 1 e 3 no OneNote;
   - Questão 1 (Conceitual): definição física, fórmula vetorial e unidade SI;
   - Questão 2 (Proporcionalidade): efeito de duplicar a velocidade com massa constante;
   - Questão 3 (Cálculo): aplicação direta com bola de 0,4 kg a 20 m/s no SI;
   - Questão 4 (Caráter Vetorial): dois patinadores de 50 kg a 3 m/s em sentidos opostos (+x e -x), exigindo raciocínio sobre igualdade vetorial;
   - Questão 5 (Interpretação e Frenagem): comparação de automóvel de passeio e caminhonete com massas e velocidades diferentes, e refutação fundamentada da ideia de que maior quantidade de movimento implica necessariamente maior distância de frenagem;
   - Gabarito comentado completo e indicação de fonte consultada.
```

---

## Prompt 4 — Adaptação dos Materiais para Estudantes com TDAH

**Objetivo:** Adaptar o conjunto didático para o estudante com TDAH no reforço individual online, priorizando código de cores na lousa digital, blocos temporizados e andaimes cognitivos sem redução de rigor.

```text
Com base nos materiais complementares gerados anteriormente, elabore a versão adaptada especificamente para o atendimento individual de estudante com TDAH (Transtorno do Déficit de Atenção com Hiperatividade) via Google Meet, OneNote e Mesa Digitalizadora.

Siga rigorosamente as seguintes diretrizes pedagógicas e neuroeducacionais:

1. Preservação do Rigor e dos Objetivos:
   - Os objetivos de aprendizagem, as equações, os valores numéricos dos exemplos e exercícios e o nível de exigência conceitual devem permanecer rigorosamente IDÊNTICOS aos do material padrão;
   - NÃO infantilize a linguagem e NÃO reduza o desafio cognitivo.

2. Estrutura Visual na Lousa do OneNote e Carga Cognitiva:
   - Divida os textos em blocos curtos, tópicos numerados e frases diretas, eliminando parágrafos longos ou sobrecarga na tela;
   - Preveja o uso intencional da mesa digitalizadora com código de cores (ex.: Verde para massa, Azul para velocidade, Laranja/Vermelho para vetores);
   - Mantenha a lousa setorizada, com uma questão por vez em foco, evitando poluição visual.

3. Instruções em Etapas (Chunking) e Temporização:
   - Divida os exercícios e as atividades em etapas sequenciais explícitas (Passo 1: Dados; Passo 2: Fórmula; Passo 3: Cálculo e Unidade);
   - Preveja a utilização de um cronômetro digital visível compartilhado na chamada do Google Meet (blocos de 3 min, 2 min, etc.) para apoiar a regulação do tempo.

4. Formatos Múltiplos de Resposta:
   - Permita e sugira diferentes modos de demonstrar compreensão (anotação direta no OneNote, cálculo orientado, ditado para o professor escrever com a mesa digitalizadora ou explicação verbal);
   - Forneça caixas de preenchimento estruturadas nos enunciados das questões.

5. Adaptação dos Três Itens:
   - Texto Explicativo adaptado com tópicos diretos e destaque para unidades e fórmula;
   - Comparação Guiada de Casos (A, B e C) particionada em passos com tempos de 3 min, 2 min e 2 min no OneNote;
   - Lista de Exercícios contendo as mesmas 5 questões do material padrão, mas organizadas com andaimes cognitivos de preenchimento guiado e gabarito correspondente.
```
