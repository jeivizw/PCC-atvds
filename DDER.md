# Tarefa 08 — Desenvolvimento do Diagrama Entidade-Relacionamento (DER)

**Projeto:** Industrial Control Tower  
**Squad:** FNCS  
**Sprint:** 1 — Estruturação e Arquitetura do Sistema

## Objetivo

Desenvolver o Diagrama Entidade-Relacionamento (DER) do Industrial Control Tower, representando visualmente as entidades, seus atributos, chaves primárias, chaves estrangeiras e relacionamentos.

## Ferramenta utilizada

- **dbdiagram.io:** ferramenta utilizada para desenvolver, organizar e visualizar o modelo relacional do banco de dados.

## Desenvolvimento

A partir das entidades e atributos identificados na Tarefa 07, foram estabelecidos os relacionamentos entre as tabelas, utilizando chaves primárias (PK) e chaves estrangeiras (FK).

Foram definidas as cardinalidades dos relacionamentos, contemplando relações de um para um (1:1) e um para muitos (1:N).

O modelo contempla 14 entidades, organizadas em cinco áreas principais:

- **Administração:** departamentos e usuários.
- **Estoque:** materiais, estoques e movimentações de estoque.
- **Comercial:** clientes, produtos, pedidos e itens de pedido.
- **Produção:** linhas de produção, ordens de produção e registros de produção.
- **Monitoramento:** entregas e alertas.

## Diagrama Entidade-Relacionamento (DER)

O diagrama apresenta as 14 entidades, seus atributos, tipos de dados, chaves primárias, chaves estrangeiras e relacionamentos.

**Acesse o diagrama interativo:**

[Visualizar Diagrama no dbdiagram.io](https://dbdiagram.io/e/6b0597454af980b2fb71ab9b/6b0598904af980b2fb71c833)

## Validações do Modelo

Durante a revisão do diagrama, foram considerados os seguintes pontos:

- Associação obrigatória dos usuários aos departamentos.
- Relacionamento 1:1 entre materiais e estoques.
- Associação dos alertas com materiais, pedidos ou linhas de produção, conforme as regras de negócio.

## Resultado da Tarefa

Foi desenvolvido o Diagrama Entidade-Relacionamento do Industrial Control Tower, estabelecendo visualmente a estrutura das entidades e seus relacionamentos.

O modelo servirá como referência para a configuração e implementação do banco de dados PostgreSQL.

---

**Squad FNCS — Industrial Control Tower**
