# Projeto Conta Bancária - BANCDAY

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)
![POO](https://img.shields.io/badge/POO-Orientação%20a%20Objetos-blueviolet?style=for-the-badge)
![STS Eclipse](https://img.shields.io/badge/STS-Eclipse-purple?style=for-the-badge&logo=eclipseide)
![Git](https://img.shields.io/badge/Git-Versionamento-red?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-black?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/Status-Refatorado-success?style=for-the-badge)
![Licença](https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge)

Sistema bancário desenvolvido em Java para simular operações básicas de contas bancárias via console.
O projeto permite cadastrar, listar, buscar, atualizar e excluir contas, além de realizar operações bancárias como saque, depósito e transferência entre contas.

---

## Objetivo do projeto

O objetivo deste projeto é praticar os principais conceitos de Programação Orientada a Objetos em Java, como:

- Classes e objetos
- Encapsulamento
- Herança
- Polimorfismo
- Classe abstrata
- Interface
- Enum
- Coleções com `List`
- Uso de `Optional`
- Uso de `BigDecimal` para valores monetários
- Separação de responsabilidades por pacotes

---

## Funcionalidades

O sistema permite:

- Criar conta corrente
- Criar conta poupança
- Listar todas as contas cadastradas
- Buscar conta pelo número
- Atualizar dados da conta
- Excluir conta
- Realizar saque
- Realizar depósito
- Realizar transferência entre contas

---

## Estrutura do projeto

```text
src
└── conta_bancaria
    ├── menu
    │   └── Menu.java
    ├── model
    │   ├── Conta.java
    │   ├── ContaCorrente.java
    │   ├── ContaPoupanca.java
    │   └── TipoConta.java
    ├── controller
    │   └── ContaController.java
    ├── repository
    │   └── ContaRepository.java
    └── util
        └── Cores.java
```

---

## Como executar

Pré-requisito: Java 21 (JDK).

```bash
git clone https://github.com/Day-Barbosa/banco-console.git
cd banco-console
javac -encoding UTF-8 -d out $(find src -name "*.java")
java -cp out conta_bancaria.menu.Menu
```

No Eclipse / STS: importe a pasta como projeto Java e execute `src/conta_bancaria/menu/Menu.java`.

---

## Status

Projeto de estudo concluído na formação Java Fullstack da Generation Brasil e **arquivado**. A evolução desses conceitos (POO, coleções, exceções e testes) continua na [Lojinha do Logan](https://github.com/Day-Barbosa/lojinha-logan).

## Autora

**Dayana Barbosa** · [LinkedIn](https://www.linkedin.com/in/dayanabarbosa-devjava/) · [GitHub](https://github.com/Day-Barbosa)

<sub>Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE).</sub>
