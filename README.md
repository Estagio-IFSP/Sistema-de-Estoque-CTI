
# Controle-de-Estoque
=======
# Sistema-de-Estoque-CTI

## Table of contents
* [Introduction](#Intro)
* [Installation](#Installation)
* [Start](#start)

## Intro
The scope of this project...

### Objetivos

### Requisitos Funcionais:

| Nº | Requisito                               | Tipo      | Prioridade | Descrição                                                                                           |
|----|-----------------------------------------|-----------|------------|-----------------------------------------------------------------------------------------------------|
| 1  | Gerenciamento de Estoque                | Funcional | Alta       | Manter o registro do estoque mínimo e atual de produtos.                                           |
| 2  | Lista de E-mails da CTI                | Funcional | Média      | Manter uma lista atualizada de endereços de e-mail da equipe de CTI.                               |
| 3  | Pedido de Reabastecimento de Produto   | Funcional | Alta       | Permitir que os usuários solicitem o reabastecimento de um produto, especificando a quantidade e a urgência. |
| 4  | Pedido de Empréstimo de Produto        | Funcional | Alta       | Permitir que os usuários solicitem o empréstimo de um produto, especificando a quantidade e a urgência.    |
| 5  | Emissão de Relatórios de Pedidos       | Funcional | Alta       | Gerar relatórios de pedidos para acompanhamento e enviá-los por e-mail.                             |
| 6  | Movimentações                          | Funcional | Alta       | Registrar todas as movimentações de entrada e saída de produtos no estoque.                         |
| 7  | Histórico de Mudanças no Estoque      | Funcional | Média      | Manter um histórico de todas as mudanças significativas no estoque.                                |

### Legenda:
- **Tipo:**
  - Funcional: Descreve uma função específica do sistema.
- **Prioridade:**
  - Alta: Requisitos essenciais para o funcionamento básico do sistema ou que agregam alto valor ao usuário.
  - Média: Requisitos importantes, mas que podem ser implementados em fases posteriores ou têm menor impacto imediato.

### Funcionalidades


=======
## Diagramas

### Diagrama de Classes
![image](./documents/diagrams/Diagrama%20de%20Classe%20-%20Estoque.drawio.png)

### Diagrama Entidade Relacionamento
![image](./documents/diagrams/DER%20-%20Estoque.drawio.png)

## Installation
Project is created with:
* Python 3.7
* asgiref 3.7.2
* Django 4.2.7
* psycopg2 2.9.9
* sqlparse 0.4.4
* tzdata 2023.3