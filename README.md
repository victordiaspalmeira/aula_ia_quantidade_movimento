# Aula IA — Quantidade de Movimento

Projeto pedagógico de aula de **reforço escolar individual (atendimento 1 a 1)** sobre **Quantidade de Movimento (momento linear)** para o **1º ano do Ensino Médio**, planejada para 50 minutos em formato remoto síncrono via **Google Meet**, com lousa digital no **Microsoft OneNote** e **Mesa Digitalizadora**. 

A proposta contempla materiais didáticos diferenciados para dois perfis de estudantes atendidos em sessões particulares separadas:
1. **Perfil Padrão:** Estudante com facilidade de compreensão, raciocínio rápido e boa autonomia.
2. **Perfil com TDAH:** Estudante que necessita de suporte intencional ao foco, com lousa setorizada, código de cores com a mesa digitalizadora, etapas sequenciais explícitas (chunking), temporização com cronômetro na tela e opções flexíveis de resposta.

---

## Sobre o projeto

O repositório reúne o plano de aula detalhado para atendimento individual, a apresentação em slides para compartilhamento no Meet, materiais didáticos complementares (textos de apoio para o OneNote, atividade de análise dirigida dos Casos A, B e C e listas de 5 exercícios contextualizados com gabarito), a reflexão crítica sobre o uso de IA e ferramentas digitais, diretrizes éticas e de LGPD, internacionalização de trecho e a cadeia completa de prompts de comando.

**Autor e professor responsável:** Victor Palmeira  
**Disciplina:** Física • 1º ano do Ensino Médio • Duração: 50 minutos  
**Ambiente Tecnológico:** Google Meet • Microsoft OneNote • Mesa Digitalizadora • Timer Digital  

---

## Objetivos de aprendizagem

Ao final da sessão individual, o estudante será capaz de:

- **Definir** quantidade de movimento (momento linear) e identificar massa e velocidade na relação vetorial \(\vec{p} = m \cdot \vec{v}\).
- **Calcular** seu módulo em situações práticas e registrar a unidade correta no SI (\(\text{kg·m/s}\)).
- **Relacionar** a direção e o sentido de \(\vec{p}\) aos da velocidade, compreendendo seu caráter vetorial e os sinais em eixos unidimensionais.
- **Diferenciar** quantidade de movimento de força e compreender criticamente por que \(p\), isoladamente, não determina tempo ou distância de frenagem.
- **Reconhecer qualitativamente** a conservação da quantidade de movimento total em sistemas isolados, preparando a base para o estudo posterior de colisões.

---

## Entregáveis do Projeto

| Item da Especificação | Arquivo no Repositório | Descrição / Formato |
|---|---|---|
| **1. Plano de Aula Oficial (MD)** | [Plano_de_Aula_IA.md](./01_plano_de_aula/Plano_de_Aula_IA.md) | Versão estruturada em Markdown com cronometragem minuto a minuto, dinâmica 1 a 1 e transparência de IA |
| **1. Plano de Aula Oficial (DOCX/ODT)** | [Plano_de_Aula_IA.docx](./01_plano_de_aula/Plano_de_Aula_IA.docx) / [Plano_de_Aula_IA.odt](./01_plano_de_aula/Plano_de_Aula_IA.odt) | Documento formatado em Word (.docx) e LibreOffice (.odt) |
| **2. Apresentação em Slides** | [Apresentacao_Aula_IA.pptx](./02_apresentacao/Apresentacao_Aula_IA.pptx) | Apresentação com 14 slides visualmente limpos para compartilhamento no Google Meet |
| **Roteiro da Apresentação** | [Roteiro_Apresentacao_Aula_IA.md](./02_apresentacao/Roteiro_Apresentacao_Aula_IA.md) | Guia slide a slide integrado ao uso do OneNote e mesa digitalizadora |
| **Instruções PowerPoint** | [Instrucoes_PowerPoint.md](./02_apresentacao/Instrucoes_PowerPoint.md) | Orientações de layout, tipografia e boas práticas visuais |
| **3. Documento de Reflexão (MD)** | [Reflexao_IA.md](./03_reflexao/Reflexao_IA.md) | Reflexão crítica no GitHub sobre ferramentas (Meet/OneNote/Mesa), limitações, ética e LGPD |
| **3. Documento de Reflexão (DOCX)** | [Reflexao_IA.docx](./03_reflexao/Reflexao_IA.docx) | Versão em documento Word (.docx) formatada |
| **Materiais — Perfil Padrão** | [Pasta Perfil Padrão](./04_materiais/materiais_perfil_padrao/) | Texto expositivo, análise dos Casos A, B e C no OneNote (7 min) e 5 exercícios com gabarito |
| **Materiais — Perfil TDAH** | [Pasta Perfil TDAH](./04_materiais/materiais_perfil_tdah/) | Mesmos objetivos e exercícios, com andaimes visuais, etapas e respostas flexíveis |
| **Internacionalização** | [trecho_traduzido.md](./06_outros/trecho_traduzido.md) | Trecho em português e inglês com nota pedagógica para aulas bilíngues ou acolhimento |
| **Cadeia de Prompts (Pasta)** | [Pasta de Prompts](./05_prompts/) | Prompts individuais 01 a 04 completos e comentados |
| **Cadeia de Prompts (Guia Único)** | [prompts.md](./prompts.md) | Fluxo sequencial dos comandos utilizados para reproduzir o processo |

---

## Estrutura do Repositório

```text
aula_ia_quantidade_movimento/
├── 01_plano_de_aula/
│   ├── Plano_de_Aula_IA.docx
│   ├── Plano_de_Aula_IA.md
│   └── Plano_de_Aula_IA.odt
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
├── .gitignore
├── objetivos.md
├── prompts.md
└── README.md
```

---

## Dinâmica da Prática e Rigor dos Exercícios

- **Análise dos Casos A, B e C (7 minutos):** Substitui atividades experimentais soltas por uma investigação dialogada direta entre professor e aluno na lousa digital do OneNote. Com o auxílio de desenhos e cores na mesa digitalizadora, o aluno compara três carrinhos com variações de massa e velocidade, descobrindo por que corpos diferentes podem ter a mesma quantidade de movimento e por que isso não define a distância de parada.
- **Exercícios no OneNote:** Cinco questões calibradas para atendimento individual:
  1. **Conceito físico:** Relação vetorial \(\vec{p} = m \cdot \vec{v}\) e unidade SI (\(\text{kg·m/s}\)).
  2. **Proporcionalidade:** Duplicação da velocidade mantendo a massa constante.
  3. **Cálculo no SI:** Aplicação direta com bola de futebol (\(0,4\,\text{kg} \times 20\,\text{m/s} = 8\,\text{kg·m/s}\)).
  4. **Caráter vetorial:** Dois patinadores em sentidos opostos (\(+150\,\text{kg·m/s}\) e \(-150\,\text{kg·m/s}\)) evidenciando que vetores contrários não são iguais.
  5. **Contexto cotidiano:** Comparação de automóvel e caminhonete com reflexão física crítica sobre frenagem e forças dissipativas.

---

## Autoria Docente, Ética e Proteção de Dados (LGPD)

- **Uso Assistido de IA e Autoria:** ChatGPT e Microsoft Copilot atuaram como aceleradores de planejamento e suporte à redação. A autoria conceitual, o controle epistemológico e a validação são do **professor Victor Palmeira**.
- **Conformidade com a LGPD (Lei nº 13.709/2018):** O projeto preza pelo absoluto respeito à privacidade dos estudantes. Nenhum dado pessoal, nome real, histórico acadêmico ou diagnóstico clínico individual foi compartilhado com as ferramentas de IA. As adaptações para o perfil com TDAH fundamentam-se em personas didáticas universais e diretrizes do Desenho Universal para a Aprendizagem (DUA).

---

## Licença

Projeto desenvolvido para fins educacionais e de demonstração prática de aplicação de IA na educação. Consulte o autor antes de redistribuir ou reutilizar comercialmente os materiais.
