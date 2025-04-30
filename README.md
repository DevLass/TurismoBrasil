# Análise de Turismo Internacional no Brasil

Este projeto foi desenvolvido com o objetivo de explorar os dados de turismo internacional com foco na chegada de estrangeiros ao Brasil. Utilizando uma base de dados oficial do Governo Federal, foi possível realizar diversas análises para entender melhor os padrões e comportamentos dos turistas que visitam o país.

Durante o processo, foram aplicadas técnicas de limpeza, tratamento e visualização de dados utilizando Python e bibliotecas como Pandas e Matplotlib.

---

## 🧰 Ferramentas e Tecnologias

- Python 3.x  
- Pandas  
- Matplotlib

> Para instalar as dependências:  
> ```bash
> pip install pandas matplotlib
> ```

---

##  Pré-processamento dos Dados

Antes da análise, algumas ações de preparação dos dados foram realizadas:

-  Remoção de colunas não úteis para os objetivos do projeto: `Cod Continente`, `Pais`, `UF`, `Via`, `Mês / Ano`.
-  Verificação e tratamento de valores nulos para garantir consistência nas análises.

---

##  Descrição das Análises

Foram criadas seis visualizações principais para explorar as chegadas internacionais ao Brasil:

1. **Chegadas por Continente**  
   Total de turistas que chegaram ao Brasil, agrupados por continente de origem.
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/continente_chegadas.png" width="650"/>

2. **Chegadas por País**  
   Comparação entre os países com maior número de visitantes ao Brasil.
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/pais_chegadas.png" width="650"/>

3. **Chegadas por Modalidade de Transporte (Via)**  
   Análise de como os turistas chegam ao país (aéreo, marítimo, terrestre).
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/via_chegadas.png" width="650"/>

4. **Chegadas por Mês**  
   Gráfico de linhas mostrando a sazonalidade das visitas ao longo do ano.
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/mes_chegadas.png" width="650"/>

5. **Continente x Via**  
   Relação entre o continente de origem e a via de chegada mais utilizada.
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/continente_vias.png" width="650"/>

6. **Chegadas por Continente ao Longo do Tempo**  
   Como a chegada de turistas de cada continente se comporta ao longo dos meses.
   <img src="https://raw.githubusercontent.com/DevLass/TurismoBrasil/main/mes_continente.png" width="650"/>

---

##  Principais Insights Percebidos

-  **Europa e América do Sul como principais emissores**: são os continentes com maior número de visitantes.  
-  **Viagens aéreas dominam**: a principal forma de entrada no Brasil é por via aérea.  
-  **Sazonalidade clara**: há picos de chegada em meses específicos, indicando alta temporada turística.  
-  **Padrões distintos por continente**: por exemplo, turistas da América do Sul tendem a vir também por via terrestre, ao contrário dos demais continentes.

---

## 📂 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos do portal oficial de dados abertos do Governo Federal do Brasil:

- **Ministério do Turismo - Dados de Chegadas Internacionais**  
  Disponível em: [https://dados.gov.br/dados/conjuntos-dados/chegadas-de-visitantes-internacionais](https://dados.gov.br/dados/conjuntos-dados/chegadas-de-visitantes-internacionais)
