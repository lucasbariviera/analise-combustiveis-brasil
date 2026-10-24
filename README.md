# ⛽ Análise de Preços de Combustíveis no Brasil (2025)

## 📌 Sobre o Projeto
Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre os preços de combustíveis automotivos comercializados no Brasil no primeiro semestre de 2025, utilizando dados abertos da ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis). O objetivo é entender a variação de preços entre diferentes regiões, estados e bandeiras de postos de atendimento.

## 🛠️ Ferramentas Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** Pandas (Limpeza e manipulação de dados), Matplotlib e Seaborn (Visualização de dados)
- **Ambiente:** Jupyter Notebook

## 🔍 Questões Respondidas na Análise
1. Qual é a região com a gasolina mais cara e mais barata do Brasil?
2. Como se comporta a distribuição de preços entre as principais bandeiras (BR, Ipiranga, Shell, etc.) e os postos de bandeira branca?
3. Qual é a correlação e variância de preços da Gasolina em relação ao Diesel?

## 📈 Principais insights
- Inflação nos Combustíveis Líquidos (2025-2026): Os dados revelam um aumento generalizado. O preço médio da Gasolina Comum subiu cerca de 5% (de R$ 6,24 em 2025 para R$ 6,56 em 2026). O impacto foi ainda mais severo no Diesel S10, que registou um salto considerável de quase 11%, passando de uma média de R$ 6,20 para R$ 6,88 no mesmo período.

- GNV na Contramão da Inflação: Enquanto o Etanol, a Gasolina e o Diesel sofreram aumentos, o Gás Natural Veicular (GNV) foi o único produto a apresentar uma queda no seu preço médio nacional, descendo de R$ 4,73 para R$ 4,53, consolidando-se como uma alternativa económica mais estável.

- Elevada Dispersão e Volatilidade de Preços: A análise demonstra uma enorme amplitude de valores praticados no mercado. Em 2026, por exemplo, a Gasolina Comum apresentou uma diferença de quase 100% entre o valor mais baixo registado (R$ 5,09) e o mais alto (R$ 9,79), o que evidencia o forte impacto da localização regional e das dinâmicas comerciais das diferentes bandeiras na precificação final ao consumidor.




## 🚀 Como Executar
1. Clone este repositório.

2. Certifique-se de ter as bibliotecas necessárias instaladas (`pip install pandas matplotlib seaborn`).
3. Baixe os três arquivos de dados originais da ANP e coloque-os na mesma pasta do projeto:
   - `Preços semestrais - AUTOMOTIVOS_2025.01.csv`
   - `Preços semestrais - AUTOMOTIVOS_2025.02.csv`
   - `Preços semestrais - AUTOMOTIVOS_2026.01.csv`
4. Abra e execute o notebook `analise_combustiveis.ipynb` (localmente ou no Google Colab) para visualizar os dados e gerar os gráficos.
