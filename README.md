
#  Consultoria — Projetos de Análise Exploratória de Dados (EDA)

Este repositório reúne estudos de caso de consultoria e análise de dados desenvolvidos em **Python**, abrangendo três cenários distintos: varejo comercial, monitoramento operacional de máquinas e desempenho acadêmico.

---

## 📁 Estrutura do Repositório

```text
Consultoria/
├── monitoramento_maquinas.csv      # Base de dados de operação e sensores das máquinas
├── relatorio_maquinas.ipynb        # Análise exploratória e diagnóstico das máquinas
├── student_habits_performance.csv  # Base de dados de hábitos diários e notas de estudantes
├── relatorio_estudantes.ipynb      # Análise de correlação entre rotina e desempenho escolar
├── vendas_eletronicos.csv          # Base de dados transacionais de vendas de eletrônicos
├── relatorio_eletronicos.ipynb     # Análise comercial, faturamento e comportamento de vendas
└── README.md                       # Documentação do projeto

```

---

##  Detalhamento das Análises

| Frente de Estudo | Notebook (Relatório) | Base de Dados | Objetivo da Análise |
| --- | --- | --- | --- |
| **Vendas de Eletrônicos** | `relatorio_eletronicos.ipynb` | `vendas_eletronicos.csv` | Avaliação de faturamento, produtos de maior saída, ticket médio e tendências comerciais. |
| **Monitoramento de Máquinas** | `relatorio_maquinas.ipynb` | `monitoramento_maquinas.csv` | Acompanhamento de indicadores operacionais, identificação de anomalias e padrões de desempenho industrial. |
| **Desempenho de Estudantes** | `relatorio_estudantes.ipynb` | `student_habits_performance.csv` | Investigação do impacto de hábitos (estudo, sono, rotina) nos resultados e notas acadêmicas. |

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Ambiente de Desenvolvimento:** Jupyter Notebook / VS Code / Google Colab
* **Bibliotecas Principais:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

##  Metodologia Aplicada

Todos os relatórios seguem um fluxo estruturado de Análise Exploratória de Dados:

1. **Inspeção Inicial:** Verificação de dimensões, tipos de dados (`df.info()`) e estatísticas descritivas (`df.describe()`).
2. **Limpeza e Tratamento:** Verificação de valores ausentes, registros duplicados e padronização de colunas.
3. **Análise Exploratória e Visualização:** Cruzamento de variáveis, agrupamentos e criação de gráficos para extração de padrões.
4. **Diagnóstico de Consultoria:** Síntese dos *insights* obtidos para apoiar a tomada de decisão em cada cenário.

---

##  Como Executar Localmente

1. Clone o repositório:
```bash
git clone [https://github.com/KauamDeSouzaBelsi/Consultoria.git](https://github.com/KauamDeSouzaBelsi/Consultoria.git)

```


2. Entre no diretório do projeto:
```bash
cd Consultoria

```


3. Instale as dependências necessárias:
```bash
pip install pandas numpy matplotlib seaborn jupyter

```


4. Inicie o Jupyter Notebook e abra o relatório desejado:
```bash
jupyter notebook
