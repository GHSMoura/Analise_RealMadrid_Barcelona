# ⚽️ Análise Comparativa Financeira: Real Madrid x Barcelona

Bem-vindo ao repositório! Aqui você encontrará uma análise detalhada e visual das métricas financeiras de dois gigantes do futebol mundial: **Real Madrid** e **Barcelona**. Este projeto tem como objetivo explorar a saúde financeira dos clubes, identificando tendências, riscos e projeções de desempenho futuro.

---

## 📌 Descrição do Projeto

Este projeto busca fornecer respostas para questões financeiras cruciais envolvendo os dois clubes, como:

- Como as métricas financeiras se comparam entre Real Madrid e Barcelona?
- Quais são os indicadores de risco mais relevantes para ambos os clubes?
- Quais são as projeções de receita dos clubes para os próximos anos?
- Como o modelo **Altman Z-Score** avalia a solvência dos clubes?  
- Quais impactos as variações de dívidas podem ter nas métricas financeiras?

Com base em análise de dados e técnicas estatísticas, o projeto visa fornecer insights detalhados e confiáveis.

---

## 🛠️ Ferramentas e Tecnologias Utilizadas

- **Python**: Para manipulação e análise de dados.
- **Bibliotecas**:
  - `Pandas`: Organização e análise de métricas financeiras.
  - `Seaborn` e `Matplotlib`: Criação de gráficos comparativos e dinâmicos.
  - `Scikit-learn`: Aplicação de modelo de previsão de solvência financeira.
- **Modelagem**:
  - **Altman Z-Score**: Previsão da saúde financeira dos clubes com base em variáveis-chave.

---

## 📂 Estrutura do Projeto

1. **Comparação Financeira: Real Madrid x Barcelona**
   - Métricas analisadas:
     - Receita Total (€)
     - EBITDA (€)
     - Dívida Líquida (€)
     - Relação Wage-to-Revenue (%)
     - Liquidez Corrente
     - Patrimônio Líquido (€)
     - Valor de Mercado do Elenco (€)

2. **Indicadores de Risco**
   - **Dívida/EBITDA**:
     - Mede a capacidade dos clubes de pagar suas dívidas com base nos lucros.
     - Limite de risco alto incluído como linha de referência.
   - **Wage-to-Revenue Ratio**:
     - Proporção dos gastos com salários em relação às receitas.
     - Limite financeiro estabelecido pela La Liga: **70%**.

3. **Projeção de Receitas (2023-2026)**
   - Projeções baseadas em dados históricos e desempenho recente dos clubes.

4. **Modelo de Altman Z-Score**
   - Variáveis incluídas:
     - **WC_TA**: Capital de Giro / Ativos Totais.
     - **RE_TA**: Lucros Retidos / Ativos Totais.
     - **EBIT_TA**: EBIT / Ativos Totais.
     - **MVE_TL**: Valor de Mercado / Passivo Total.
   - **Previsões**:
     - Probabilidades de falência estimadas para os clubes em 2024.

5. **Análise de Sensibilidade das Dívidas**
   - Simulações de variações na dívida líquida e seus impactos nas métricas financeiras principais.

---

## 📊 Exemplos de Visualizações

1. **Comparação Financeira: Real Madrid vs Barcelona**  
   Barplot comparando métricas financeiras, incluindo receitas, EBITDA, dívidas e mais.

2. **Indicadores de Risco**
   - Gráficos de barras ilustrando:
     - Dívida/EBITDA com linhas de referência para risco.
     - Wage-to-Revenue (%) com destaque para o limite financeiro permitido pela La Liga.

3. **Projeção de Receitas (2023-2026)**
   Gráfico de linha mostrando as projeções de receita para os próximos quatro anos.

4. **Gráfico de Radar Comparativo**
   Comparação de métricas-chave entre os clubes, incluindo:
   - Receita
   - EBITDA
   - Liquidez Corrente
   - Patrimônio Líquido
   - Valor de Mercado

5. **Sensibilidade das Dívidas**
   Gráficos de linha mostrando os impactos das variações de dívidas nas principais métricas financeiras.

6. **Altman Z-Score: Previsões**
   Visualização das probabilidades de falência previstas para 2024:
   - **Barcelona**: Probabilidade de falência de X%.
   - **Real Madrid**: Probabilidade de falência de Y%.


