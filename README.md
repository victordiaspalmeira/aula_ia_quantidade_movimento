# Aula IA — Quantidade de Movimento

Projeto pedagógico de aula interativa sobre **Quantidade de Movimento (momento linear)** para o **1º ano do Ensino Médio**, planejada para 50 minutos e acompanhada por recursos didáticos diferenciados para dois perfis de estudantes: sem adaptação específica (padrão) e com TDAH (Transtorno do Déficit de Atenção com Hiperatividade).

---

## Sobre o projeto

O repositório reúne o plano de aula detalhado, a apresentação visual em slides, materiais didáticos complementares (textos de apoio, atividade prática guiada e listas de exercícios contextualizados com gabarito), a reflexão crítica sobre o uso pedagógico de IA, conformidade ética/LGPD, internacionalização de trecho científico e a cadeia completa de prompts de comando.

**Autor e professor responsável:** Victor Palmeira  
**Disciplina:** Física • 1º ano do Ensino Médio • Duração: 50 minutos  

---

## Objetivos de aprendizagem

Ao final da aula, espera-se que o estudante seja capaz de:

- **Definir** quantidade de movimento (momento linear) e identificar massa e velocidade na relação vetorial \(\vec{p} = m \cdot \vec{v}\).
- **Calcular** seu módulo em situações práticas e informar a unidade correta no SI (\(\text{kg·m/s}\)).
- **Relacionar** a direção e o sentido de \(\vec{p}\) aos da velocidade, compreendendo seu caráter vetorial e os sinais em eixos unidimensionais.
- **Diferenciar** quantidade de movimento de força e compreender criticamente por que \(p\), isoladamente, não determina tempo ou distância de frenagem.
- **Reconhecer qualitativamente** a conservação da quantidade de movimento total em sistemas isolados, preparando a base para o estudo posterior de colisões.

---

## Entregáveis do Projeto

| Item da Especificação | Arquivo no Repositório | Descrição / Formato |
|---|---|---|
| **1. Plano de Aula Oficial (MD)** | [Plano_de_Aula_IA.md](./01_plano_de_aula/Plano_de_Aula_IA.md) | Versão estruturada em Markdown com cronometragem minuto a minuto e transparência de IA |
| **1. Plano de Aula Oficial (DOCX)** | [Plano_de_Aula_IA.docx](./01_plano_de_aula/Plano_de_Aula_IA.docx) | Documento Word formatado e alinhado integralmente ao plano oficial |
| **2. Apresentação em Slides** | [Apresentacao_Aula_IA.pptx](./02_apresentacao/Apresentacao_Aula_IA.pptx) | Apresentação com 14 slides visualmente limpos, objetivos e dinâmicos |
| **Roteiro da Apresentação** | [Roteiro_Apresentacao_Aula_IA.md](./02_apresentacao/Roteiro_Apresentacao_Aula_IA.md) | Guia slide a slide com orientações de fala e temporização |
| **Instruções PowerPoint** | [Instrucoes_PowerPoint.md](./02_apresentacao/Instrucoes_PowerPoint.md) | Orientações de layout, tipografia e boas práticas de design |
| **3. Documento de Reflexão (MD)** | [Reflexao_IA.md](./03_reflexao/Reflexao_IA.md) | Reflexão crítica no GitHub sobre ferramentas, limitações, ética e LGPD |
| **3. Documento de Reflexão (DOCX)** | [Reflexao_IA.docx](./03_reflexao/Reflexao_IA.docx) | Versão em documento Word (.docx) formatada |
| **Materiais — Perfil Padrão** | [Pasta Perfil Padrão](./04_materiais/materiais_perfil_padrao/) | Texto expositivo, atividade comparativa (7 min) e 5 exercícios com gabarito |
| **Materiais — Perfil TDAH** | [Pasta Perfil TDAH](./04_materiais/materiais_perfil_tdah/) | Mesmos objetivos e exercícios, com andaimes visuais, etapas e respostas flexíveis |
| **Internacionalização** | [trecho_traduzido.md](./06_outros/trecho_traduzido.md) | Trecho em português e inglês com nota pedagógica para aulas bilíngues |
| **Cadeia de Prompts (Pasta)** | [Pasta de Prompts](./05_prompts/) | Prompts individuais 01 a 04 completos e comentados |
| **Cadeia de Prompts (Guia Único)** | [prompts.md](./prompts.md) | Fluxo sequencial dos comandos utilizados para reproduzir o processo |

---

## Estrutura do Repositório

```text
aula_ia_quantidade_movimento/
├── 01_plano_de_aula/
│   ├── Plano_de_Aula_IA.docx
│   └── Plano_de_Aula_IA.md
├── 02_apresentacao/
│   ├── Apresentacao_Aula_IA.pptx
│   ├── Instrucoes_PowerPoint.md
│   └── Roteiro_Apresentacao_Aula_IA.md
├── 03_reflexao/
│   ├── Reflexao_IA.docx
│   └── Reflexao_IA.md
├── 04_materiais/
│   ├── materiais_perfil_padrao/
│   │   ├── atividade_pratica.md
│   │   ├── exercicios.md
│   │   └── texto_explicativo.md
│   └── materiais_perfil_tdah/
│       ├── atividade_pratica.md
│       ├── exercicios.md
│       └── texto_explicativo.md
├── 05_prompts/
│   ├── prompt_01_especialista.md
│   ├── prompt_02_plano_de_aula.md
│   ├── prompt_03_materiais.md
│   └── prompt_04_adaptacao_tdah.md
├── 06_outros/
│   └── trecho_traduzido.md
├── objetivos.md
├── prompts.md
└── README.md
```

---

## Qualidade Pedagógica e Rigor dos Exercícios

As listas de exercícios foram rigorosamente calibradas para a realidade de uma aula de 50 minutos do 1º ano do Ensino Médio, combinando rigor conceitual e contextualização:
1. **Conceito físico e grandezas:** Dependência funcional de massa e velocidade e natureza vetorial (\(\vec{p} = m \cdot \vec{v}\)).
2. **Proporcionalidade direta:** Análise do efeito da duplicação da velocidade mantendo a massa constante.
3. **Cálculo e unidade no SI:** Aplicação direta com dados realistas (bola de futebol) e fixação da unidade \(\text{kg·m/s}\).
4. **Caráter vetorial e sentido:** Patinadores na pista de gelo em sentidos opostos (\(+x\) e \(-x\)), enfatizando que vetores opostos não são iguais.
5. **Situação do cotidiano e pensamento crítico:** Comparação entre veículo de passeio e caminhonete utilitária, desmistificando o erro comum de associar quantidade de movimento diretamente a força de frenagem ou distância de parada.

---

## Autoria Docente, Ética e Proteção de Dados (LGPD)

- **Uso Assistido de IA e Autoria:** ChatGPT e Microsoft Copilot foram utilizados como ferramentas de apoio operacional para rascunhos, organização e diagramação. A autoria conceitual, o controle epistemológico e a responsabilidade pedagógica são do **professor Victor Palmeira**, cabendo ao docente a validação prévia antes de qualquer aplicação em sala.
- **Conformidade com a LGPD (Lei nº 13.709/2018):** O projeto preza pelo absoluto respeito à privacidade dos estudantes. Nenhum dado pessoal, nome real, histórico acadêmico ou relatório médico individual foi compartilhado com as ferramentas de IA. As adaptações para o perfil com TDAH fundamentam-se em personas didáticas universais e literatura de neuroeducação.

---

## Licença

Projeto desenvolvido para fins educacionais e de demonstração prática de aplicação de IA na educação. Consulte o autor antes de redistribuir ou reutilizar comercialmente os materiais.
