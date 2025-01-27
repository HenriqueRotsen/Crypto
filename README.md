# Relatório de Atividades

Participantes do Grupo:


Gabriel Castelo Branco Rocha Alencar Pinto - 2020006523 

Henrique Rotsen Santos Ferreira  - 2020006795

# Introdução
## Objetivo do trabalho

Neste projeto prático, ojetivou-se desenvolver um token ERC-20 personalizado e funcional, baseado no padrão Ethereum. Além disso, visou-se a criação de funcionalidades, como cunhagem (`mint`), transferência (`transfer`) e consulta de saldo (`balanceOf`).

# Análise de Resultados

## Resultados Esperados
1. Contrato inteligente funcional seguindo o padrão ERC-20.
2. Funcionalidades principais:
  * Consulta de saldo (balanceOf).
  * Transferência de tokens (transfer).
  * Emissão adicional (mint).
3. Sucesso nos testes em redes Ethereum de teste.

## Resultados Realizados 

### Implementação do Contrato:

O contrato foi concluído com sucesso e implementa todas as funcionalidades principais previstas, incluindo a personalização de
controle de emissão (`mint`) para o criador do contrato.

### Testes Realizados:

Utilizamos a rede Sepolia para validar as funcionalidades.
Todas as operações testadas foram bem-sucedidas:
Transferências de tokens entre contas.
Consulta de saldos com atualizações consistentes.
Emissão adicional de tokens controlada pelo criador.

# Dificuldades e percalços 

A implementação do token SBU não veio sem desafios. Na fase inicial, a preparação do ambiente de desenvolvimento, como as ferramentas requeridas, MetaMask e OpenZeppelin, apresentou pequenos problemas, principalmente quanto ao entendimento de qual rede deveríamos utilizar para realização dos testes. Como solução, buscamos referências de outros indivíduos que já haviam realizado tarefa semelhante, para corrigir os pequenos problemas. 

Outro Grande problema enfrentado foi o pagamento de taxas para realizar as operações. Para poder colocar o token na rede de testes Sepolia, era necessário possuir Ether. Então, os membros da dupla dividiram os custos para adquirir a dita quantia através da Binance. Em seguida, as moedas foram transferidas para a carteira do MetaMask, para pagamento das taxas da criação do token e o gás necessário para adquirir o SepoliaEther (moeda da rede de teste da rede ethereum)

# Conclusão

Este projeto foi extremamente importante para a dupla entender melhor a dinâmica de funcionamento da rede Ethereum, principalmente no que tange à emissão de Tokens e criação de um Smart Contract. Apesar dos problemas enfrentados, conseguimos chegar ao resultado esperado, com a emissão de um token na rede de maneira eficiente. Os objetivos inicialmente estabelecidos foram todos cumpridos com êxito, tornando a criação do token Sobreviventes da UFMG (SBU) um sucesso.
