# Sistema Bancário Otimizado com POO em Python

Este repositório contém a resolução do desafio de projeto da trilha **Python AI Backend Developer** da [Digital Innovation One (DIO)](https://www.dio.me/).

## Objetivo do Desafio
Evoluir o sistema bancário estruturado anteriormente (baseado em dicionários e funções simples) para o paradigma de **Programação Orientada a Objetos (POO)**. O projeto foi totalmente remodelado seguindo o diagrama de classes UML fornecido pela plataforma.

## Conceitos de POO Aplicados
* **Abstração & Interfaces:** Uso do módulo nativo `abc` para criar a classe abstrata `Transacao`, servindo como contrato de métodos para depósitos e saques.
* **Herança:** Implementação de herança simples onde `PessoaFisica` herda de `Cliente`, e `ContaCorrente` estende as capacidades de `Conta`.
* **Encapsulamento:** Propriedades e métodos protegidos por meio de convenções de nomenclatura (atributos e métodos com prefixo `_`), garantindo o controle de acessos através de `@property` (Getters/Setters).
* **Composição:** Relacionamentos estruturais fortes, onde uma `Conta` possui um `Historico` de transações e pertence a um `Cliente`.

## Como Executar o Projeto

Certifique-se de ter o Python 3 instalado em sua máquina.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/deborabayril/sistema-bancario-poo-python.git](https://github.com/deborabayril/sistema-bancario-poo-python.git)
