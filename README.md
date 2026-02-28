# 📊 Miniguia de Estudo: Análise de Demonstrações Financeiras
> **Desafio de Projeto: Criando um Caderno Temático com NotebookLM e IA Generativa**
> *Desenvolvido para a plataforma [DIO](https://www.dio.me/)*

Este repositório contém um guia estratégico desenvolvido para traduzir a complexidade contábil em ferramentas práticas para tomada de decisão. O projeto foi construído utilizando o **NotebookLM** como motor de curadoria e síntese, fundamentado na Lei 6.404/76 e normas internacionais (IFRS).

---

## 🎯 Objetivos de Estudo
1. **Compreensão Estrutural:** Dominar a anatomia do Balanço Patrimonial (BP) e da Demonstração do Resultado do Exercício (DRE).
2. **Capacidade Analítica:** Aplicar índices de liquidez, endividamento e rentabilidade.
3. **Visão Crítica:** Identificar sinais de *earnings management* (maquiagem contábil) através de análise de fluxos.
4. **Prática com IA:** Aplicar Engenharia de Prompt para acelerar a análise de relatórios financeiros.

---

## 📚 Fontes de Curadoria
Para a construção deste guia, foram selecionadas 5 fontes abertas e técnicas:
1. **IFRO (Campus Porto Velho):** Material sobre Análise de Demonstrações Financeiras (2018-2024).
2. **UFBA (Antonio Gualberto Pereira):** Caderno de Análise das Demonstrações Contábeis (2018).
3. **INFOMONEY:** Guia de Análise Fundamentalista (2024).
4. **TRATADO (Documento Técnico):** Análise de Demonstrações Financeiras (2024).
5. **MANUAL TÉCNICO:** Engenheiro de Prompt e IA: Edição de Maestria 2026.

---

## 📖 Resumos Estruturados

### 1. O Balanço Patrimonial (BP) - O Retrato Estático
O BP segue a equação fundamental: **Ativo = Passivo + Patrimônio Líquido**.

| Componente | Função Estratégica | Classificação (Lei 6.404/76) |
| :--- | :--- | :--- |
| **Ativo Circulante** | Bens e direitos de alta liquidez. | Realizável em até 12 meses. |
| **Ativo Não Circulante** | Investimentos, imobilizado e intangíveis. | Realizável após 12 meses. |
| **Passivo Circulante** | Obrigações de curto prazo. | Exigível em até 12 meses. |
| **Passivo Não Circulante** | Dívidas estruturais e de longo prazo. | Exigível após 12 meses. |
| **Patrimônio Líquido** | Capital próprio e reservas. | Capital residual (A - P). |

### 2. A Demonstração do Resultado (DRE) - O Filme da Operação
Regida pelo **Regime de Competência**. Diferencia o lucro contábil do fluxo de caixa financeiro.
* **Sequência:** Receita Bruta ⮕ Deduções ⮕ Receita Líquida ⮕ Custos ⮕ Resultado Bruto ⮕ Despesas Operacionais ⮕ EBIT ⮕ Impostos ⮕ **Lucro Líquido**.

---

## 📈 O Tripé da Análise Financeira

### 🧪 Índices de Liquidez
* **Corrente (LC):** $AC / PC$
* **Seca (LS):** $(AC - Estoques) / PC$
* **Geral (LG):** $(AC + RLP) / (PC + PNC)$

### 🏗️ Índices de Endividamento
* **Endividamento Geral:** $(PC + PNC) / Ativo Total$
* **Composição do Endividamento:** $PC / (PC + PNC)$ (Foco no perfil da dívida).

### 💰 Rentabilidade
* **ROE (Return on Equity):** $Lucro Líquido / Patrimônio Líquido$
* **ROIC:** Retorno sobre o capital investido (próprio e terceiros).

---

## 🤖 Laboratório de Engenharia de Prompt
Abaixo, os prompts testados e validados para apoio ao estudo:

### Prompt 1: Auditor Sênior (Role-Prompting + CCRF)
> **Contexto:** Auditor Sênior focado em IFRS e Lei 6.404/76. 
> **Comando:** Analise o Balanço e a DRE em anexo em busca de sinais de maquiagem contábil. 
> **Restrição:** Foque em discrepâncias entre Lucro Líquido e Fluxo de Caixa Operacional.

### Prompt 2: Ciclo de Caixa (Chain-of-Thought)
> **Comando:** Resolva o cálculo do Ciclo de Caixa da Empresa X. Pense passo a passo:
> 1. Identifique CMV, Estoque Inicial e Final.
> 2. Calcule as Compras ($CMV + EF - EI$).
> 3. Calcule os prazos médios (PME, PMR, PMP).
> 4. Subtraia o PMP do Ciclo Operacional para chegar ao Ciclo de Caixa.

---

## 📒 Glossário de Conceitos
* **EBITDA:** Lucro antes de juros, impostos, depreciação e amortização.
* **NOPAT:** Lucro operacional livre de efeitos financeiros e tributários.
* **Valuation:** Relação entre valor de mercado e valor contábil (P/VPA).

---

## 🚀 Acesso ao Caderno
> *Você também pode acessar o caderno original que serviu de base para este guia através deste link: [NOTEBOOKLM](https://notebooklm.google.com/notebook/3ee54b29-fc1d-4754-a70c-ab952b26ac5a)* 

*Este material foi produzido para fins educacionais e não constitui recomendação de investimento.*
