# Análise de Salários na Área de Dados

Este projeto tem como objetivo analisar dados salariais de profissionais da área de dados, para entender padrões de remuneração, identificar discrepâncias entre cargos, senioridade e localização geográfica, e auxiliar profissionais e empresas na tomada de decisões relacionadas a salários.
A análise fornece uma visão clara do mercado de trabalho em dados, ajudando a comparar salários médios, detectar tendências e apoiar planejamento de carreira ou estratégias de contratação.

## Funcionalidades

* Histograma da distribuição de salários anuais.
* Gráfico de pizza mostrando proporção de trabalho remoto vs presencial.
* Top 10 cargos por média salarial.
* Mapa mundial com salário médio de cientistas de dados por país.
* Código pronto para exibição de gráficos no GitHub e execução interativa no Jupyter/VS Code.

## Estrutura do repositório

```
Projeto-Analise-Salarios-na-Area-de-Dados/
│
├─ notebooks/             # Notebooks de análise
│   └─ analise_salarios.ipynb
├─ Scripts/               # Código do app Streamlit
│   └─ app.py
├─ data/                  # Base de dados usada
│   └─ Dados-Final.csv
├─ imagens/               # Gráficos salvos
│   ├─ histograma_salarios_anuais.png
│   ├─ proporcao_tipos_trabalho.png
│   ├─ top10_cargos_salario_medio.png
│   └─ mapa_salario_cientista_dados.png
├─ requirements.txt       # Dependências do projeto
└─ README.md              # Este arquivo
```

## Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone <link-do-repositorio>
cd meu_projeto
```

### 2. Criar ambiente virtual (opcional, mas recomendado)

```bash
python -m venv .venv
source .venv/bin/activate  # Linux / Mac
.venv\Scripts\activate     # Windows
```

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

### 4. Executar o app Streamlit

```bash
streamlit run Scripts/app.py
```

### 5. Visualizar notebooks

* Abra `notebooks/analise_salarios.ipynb` no Jupyter Notebook ou VS Code.
* Os gráficos já estão salvos em `imagens/` e podem ser visualizados via Markdown.

## Observações

* Todos os gráficos foram salvos como imagens para que possam ser exibidos corretamente no GitHub, que não executa código.
* Para versão interativa dos gráficos, abra o notebook localmente ou utilize o app Streamlit.

## Tecnologias utilizadas

* Python 3.13
* Pandas
* Plotly + Kaleido
* Streamlit

---

Quer que eu faça isso?
