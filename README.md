# Desafio Cartola

**Contexto:**
O Cartola é um jogo eletrônico amplamente reconhecido no Brasil, desenvolvido pelo Grupo Globo. Trata-se
de uma plataforma que permite aos entusiastas do futebol montarem seus próprios times virtuais com
jogadores da vida real, competindo em ligas de fantasia baseadas no Campeonato Brasileiro de futebol. Os
participantes devem usar seus conhecimentos esportivos e estratégias para selecionar os melhores
jogadores e criar escalações vencedoras a cada rodada.

Nesse contexto, surge uma questão fundamental que desejamos explorar: a identificação dos fatores e
padrões que influenciam a propensão dos jogadores a se tornarem assinantes da versão pró do Cartola. O
nosso objetivo é compreender o que motiva um usuário a aderir à versão premium do jogo, com o intuito de
ampliar o engajamento e a receita relacionados ao Cartola.

Para alcançar esse objetivo, é essencial conduzir uma análise exploratória de dados abrangente, permitindo-
nos compreender os diversos comportamentos de consumo dos jogadores. Além disso, é fundamental

construir um modelo de propensão, como uma classificação binária, que viabilize a avaliação da hipótese
levantada, identificando grupos com maior probabilidade de conversão em assinantes. Os resultados dessa
análise deverão ser consolidados e apresentados de forma convincente. O público-alvo da apresentação
incluirá designers, Product Owners (POs) e gerentes de produto, aos quais você defenderá a implementação
da sua solução.

**Objetivos:**

• Realizar uma análise exploratória dos dados com o objetivo de encontrar informações úteis para
identificação de perfis de usuários propensos a assinarem o Cartola. Utilize técnicas de estatística e
visualização de dados para apoiar suas conclusões.

• Ajustar um modelo preditivo simples para identificar os perfis de usuários propensos a assinarem o
Cartola. Apresente os métodos de limpeza e processamento de dados para gerar a entrada do
modelo preditivo. Justifique a escolha das técnicas e modelo utilizados.

• Elaborar uma apresentação com a análise, resultados e sugestões de melhorias para o projeto
desenvolvido.

• Disponibilizar o código fonte utilizado no exercício. Sua solução deve ser organizada, legível e limpa,
evitando soluções com over-engineering. Tente ser sucinto, mas preze pela qualidade do código.

# Análise dos resultados.

Para compreender o que motiva um usuário a aderir à versão premium do Cartola, podemos analisar os dados disponíveis no arquivo `leads_cartola.csv`. 
A seguir, apresento uma análise baseada nas variáveis que podem influenciar a decisão de um usuário em optar pela versão Cartola Pro em vez da gratuita.

### **Análise das Variáveis Relevantes**

1. **Idade**:
   - A distribuição da idade entre usuários Cartola Free e Cartola Pro pode indicar se há uma faixa etária mais propensa a assinar a versão premium.

2. **Atividade (dias e pviews)**:
   - O número de dias ativos e as visualizações (pviews) são indicadores importantes de engajamento. Usuários com maior atividade tendem a ter mais chances de se tornarem assinantes.

3. **Tempo Total Gasto**:
   - O tempo total gasto na plataforma pode refletir o interesse do usuário. Quanto mais tempo um usuário passa no Cartola, maior a probabilidade de ele considerar a assinatura.

### **Resultados das Visualizações**

#### **1. Distribuição da Idade por Status do Lead**
O boxplot da idade mostra que:

- Usuários Cartola Pro tendem a ser mais jovens, enquanto os Cartola Free têm uma faixa etária mais ampla.
- A presença de outliers pode indicar usuários muito velhos que ainda estão ativos na versão gratuita.

#### **2. Pviews vs Tempo Total**
O gráfico de dispersão entre pviews e tempo total revela:

- Há uma concentração significativa de usuários Cartola Pro em áreas com maior número de pviews e tempo total gasto.
- Isso sugere que usuários com maior engajamento e visualizações estão mais inclinados a optar pela versão premium.

### **Conclusões e Recomendações**

1. **Foco na Faixa Etária Jovem**:
   - Considerar campanhas direcionadas para usuários mais jovens, que demonstram maior interesse em se tornar Cartola Pro.

2. **Estimular o Engajamento**:
   - Criar incentivos para aumentar o número de dias ativos e visualizações, como promoções ou conteúdos exclusivos para usuários ativos.

3. **Análise Contínua**:
   - Monitorar continuamente as métricas de engajamento para identificar padrões que possam ajudar a entender melhor o comportamento dos usuários.

4. **Feedback dos Usuários**:
   - Coletar feedback diretamente dos usuários sobre o que os motivaria a assinar a versão premium pode oferecer insights valiosos.

Essas análises podem ajudar a formular estratégias para aumentar tanto o engajamento quanto a receita do Cartola, focando nas características dos usuários que mais se beneficiam da versão premium.
