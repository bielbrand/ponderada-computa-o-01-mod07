# EcoPass Token

## 1. Visão geral

O EcoPass Token (ECO) é um token fungível desenvolvido para um ecossistema de recompensas por comportamentos sustentáveis.

A proposta é utilizar blockchain para criar um ativo digital transferível entre carteiras, permitindo que usuários recebam, armazenem e transfiram ECO dentro do ecossistema.

---

## 2. Problema

Programas tradicionais de recompensas normalmente utilizam sistemas de pontos restritos às plataformas que os emitiram.

O EcoPass propõe utilizar um token ERC-20 para representar as unidades de recompensa em uma infraestrutura blockchain.

---

## 3. Proposta de valor

O ECO poderá ser utilizado dentro do ecossistema EcoPass para recompensas, benefícios, descontos e outras funcionalidades futuras.

A utilização de um token permite registrar as movimentações em blockchain e possibilita a transferência dos ativos entre diferentes carteiras.

---

## 4. Tipo do token

O ECO será um Utility Token.

A escolha ocorre porque o token foi concebido para possuir uma função prática dentro do ecossistema EcoPass.

Ele não foi projetado como uma stablecoin e não representa participação societária no projeto.

---

## 5. Modelagem do token

| Parâmetro | Definição |
|---|---|
| Nome | EcoPass Token |
| Símbolo | ECO |
| Padrão | ERC-20 |
| Blockchain | Ethereum |
| Rede de testes | Sepolia |
| Supply total | 1.000.000 ECO |
| Decimais | 18 |
| Emissão | Supply fixo |
| Mint após deploy | Não |

---

## 6. Supply e emissão

O supply total do EcoPass será de 1.000.000 ECO.

Todos os tokens serão criados durante a implantação do contrato.

Após a implantação, não será possível criar novos tokens.

Dessa forma, o supply permanece fixo em 1.000.000 ECO.

---

## 7. Distribuição planejada

A distribuição conceitual do supply será:

- 60% — recompensas aos usuários;
- 20% — parcerias e benefícios;
- 10% — desenvolvimento do projeto;
- 10% — reserva do ecossistema.

No protótipo desenvolvido nesta atividade, os tokens serão inicialmente enviados para a carteira que realizar o deploy.

---

## 8. Divisibilidade

O ECO possui 18 casas decimais.

Isso significa que 1 ECO corresponde internamente a:

1.000.000.000.000.000.000 unidades mínimas.

---

## 9. Circulação

Os tokens poderão ser transferidos entre diferentes carteiras utilizando as funções padrão do ERC-20.

Exemplo:

Carteira A → 10 ECO → Carteira B

A transferência reduz o saldo da carteira de origem e aumenta o saldo da carteira de destino.

A transferência não altera o supply total.

---

## 10. Permissões

Os usuários poderão:

- consultar seus saldos;
- transferir tokens;
- autorizar outros endereços a utilizar determinada quantidade de tokens;
- consultar o supply total.

O contrato não possui função para criar novos tokens após o deploy.

---

## 11. Relação com o ecossistema

O ECO funciona como a unidade digital de valor do EcoPass Ecosystem.

Em uma aplicação futura, os tokens poderão ser utilizados para:

- recompensas;
- descontos;
- benefícios;
- acesso a experiências;
- interações com parceiros.

---

## 12. Smart Contract

O contrato foi desenvolvido em Solidity seguindo o padrão ERC-20.

O contrato utiliza a implementação ERC-20 da OpenZeppelin.

O supply inicial de 1.000.000 ECO é criado durante o deploy e enviado para a carteira responsável pela implantação.

---

## 13. Deploy

Rede:

Sepolia Testnet

Contract Address:

A preencher após o deploy.

---

## 14. Demonstração

Será realizada uma transferência de ECO entre duas carteiras.

Carteira de origem:

A preencher.

Carteira de destino:

A preencher.

Quantidade transferida:

A preencher.

Transaction Hash:

A preencher após a transferência.

---

## 15. Conclusão

O projeto demonstra a criação, implantação e transferência de um token ERC-20 na rede de testes Sepolia.

O protótipo representa a infraestrutura básica do EcoPass Token e poderá futuramente ser integrado a uma aplicação de recompensas.