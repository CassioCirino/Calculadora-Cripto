# Calculadora de Lucro em Criptomoedas com API da Binance

## Visão Geral

Este projeto foi desenvolvido durante minhas férias para ajudar investidores de criptomoedas a monitorar e calcular lucros ao converter moedas na Binance sem taxas. Utilizando apenas HTML e JavaScript, e aproveitando a API pública da Binance, esta calculadora obtém valores em tempo real e cria alertas de preços.

## Funcionalidades

- **Seleção de Criptomoeda:** A calculadora preenche dinamicamente uma lista suspensa com todas as criptomoedas disponíveis na Binance que têm paridade com USDT.
- **Preço Atual:** Ao selecionar uma criptomoeda, o código obtém e exibe o preço atual dessa moeda em tempo real usando a API pública da Binance.
- **Cálculo de Lucro:** Com base nos valores de compra, venda e aporte inseridos pelo usuário, a calculadora exibe a porcentagem de lucro e o valor absoluto do lucro.
- **Gráfico de Preços:** A calculadora plota um gráfico simples mostrando os preços de compra e venda para facilitar a visualização das variações de preços.
- **Alertas de Preço:** O usuário pode definir um alerta de preço, e o código verifica periodicamente o preço atual, notificando o usuário quando o preço desejado é atingido.

## Detalhes Técnicos

- **HTML e JavaScript:** Todo o código foi escrito em HTML e JavaScript puro, garantindo que seja fácil de portar e executar em qualquer navegador, sem necessidade de configurações adicionais.
- **API da Binance:** Utiliza a API pública da Binance para obter dados de preços em tempo real. Isso garante que os usuários sempre tenham acesso aos preços mais recentes.
- **Chart.js:** Para o gráfico de preços, integra a biblioteca Chart.js, que é leve e super fácil de usar para visualizações rápidas.

## Em Ação

A calculadora permite que você selecione uma criptomoeda, veja o preço atual, insira seus valores de compra e venda, e obtenha instantaneamente a porcentagem de lucro e o valor do lucro sobre o valor aportado. Tudo isso em um arquivo HTML que você pode carregar em qualquer navegador. Você também pode definir alertas de preços, e a calculadora vai te avisar quando o preço atingir o valor desejado.

## Como Usar

1. Clone o repositório ou baixe o arquivo HTML.
2. Abra o arquivo HTML em um navegador.
3. Selecione uma criptomoeda na lista suspensa.
4. Insira os valores de compra, venda e aporte.
5. Clique em "Calcular Lucro" para ver os resultados.
6. Defina alertas de preço, se desejar, e deixe a página aberta para monitorar os preços em tempo real.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com melhorias.
