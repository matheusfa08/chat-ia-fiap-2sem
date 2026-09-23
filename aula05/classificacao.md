# 🤖 Algoritimos de Classificação

# Tipos:

## Regressão Logística

### Descrição:

Algorítimo que assume relação linear das variáveis de entrada com a variável target preditora

### ✅Vantagens:

- Simples implementação;
- Simples interpretação;
- Bom para dados que tem relações lineares.

### ❎Desvantagens:

- Sempre assuma a relação Linear entre as variáveis;
- Sensiveis a outliers;
- Não captura padrões não lineares.

## Árvore de Decisão

### Descrição:

Algorítimo que utiliza uma estrutura em forma de árvore para prever valores continuos. Ele divide os dados em subconuntos com base em condições lógicas das variáveis de entrada, até chegar a folhas que representam a predição de valor alvo

### ✅Vantagens:

- Captura tendências não lineares dos dados;
- Fácil interpretação;
- Não ec

### ❎Desvantagens:

- Pode dar overfit

## KNN

### Descrição:

Algorítimo que prediz o valor da variável alvo considerando quais vetores estão mais similares a eles. A proximidade é definida por uma métrica de distância.

### ✅Vantagens:

- Bom para problemas com relações não lineares;
- Simples de entender e implementar.

### ❎Desvantagens:

- Sensível à escolha do valor de K;
- Sensível à escala das variáveis (Necessita normalização/padronização);
- Pode ser afetado por ruído e outliers

# Métricas algorítimos de Classificação

## Criando uma matriz de confusão (SPAM)

Exemplo de matriz de confusão e e-mails de SPAM:

    24 e-mails
     expostos ao modelo que realmente são SPAMs
    558 e-mails expostos ao modelo que não são SPAMs

## F1 Score

- Quando o problema não é tão simples de ser analisado, isto é, não é fácil decidir entre Precisão e Revocação, podemos usar o F1 SCORE;
- O F1 SCORE é a méia harmônica da Precisão  e da Revocação;

        F1 = (2 / 1/recall + 1/precisão) = 2 * precision * recall / precision + recall