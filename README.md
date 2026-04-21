# ☕ Exercícios Práticos em Java - Comecei 23/03/2026

> Coleção de exercícios em Java com foco em lógica de programação, estruturas de repetição, condicionais, entrada de dados com `Scanner` e matemática aplicada.

---

## 📂 Estrutura do Repositório

```
📦 exercicios-java
 ┣ 🔐 validacao/
 ┃ ┣ ValidadorDeNotas.java
 ┃ ┣ NomeDiferenteDeSenha.java
 ┃ ┗ Validador.java
 ┣ 📊 calculos/
 ┃ ┣ maiorNumero.java
 ┃ ┣ mediaNumeros.java
 ┃ ┗ numerosImpar.java
 ┣ 🔢 sequencias/
 ┃ ┣ numeros.java
 ┃ ┗ numerosInteiros.java
 ┗ 🌍 simulacoes/
   ┣ Populacao.java
   ┗ PopulacaoV2ex5.java
```

---

## 🔐 Validação e Segurança

### `ValidadorDeNotas.java`
Garante que apenas notas entre **0 e 10** sejam aceitas, rejeitando entradas inválidas com mensagem de erro.

### `NomeDiferenteDeSenha.java`
Implementa uma regra de segurança básica: **nome de usuário e senha não podem ser iguais**, solicitando nova entrada até que a condição seja satisfeita.

### `Validador.java`
Validação completa de cadastro de usuário, verificando:
- Nome
- Idade
- Salário
- Sexo
- Estado civil

---

## 📊 Cálculos

### `maiorNumero.java`
Lê **cinco números** e identifica qual deles é o maior, utilizando estruturas condicionais encadeadas.

### `mediaNumeros.java`
Realiza o cálculo da **soma** e da **média aritmética** de uma sequência de números informados pelo usuário.

### `numerosImpar.java`
Percorre o intervalo de **1 a 50** e exibe apenas os números ímpares, utilizando o operador módulo `%`.

---

## 🔢 Sequências

### `numeros.java`
Gera e exibe a sequência de números de **1 a 20** usando estrutura de repetição.

### `numerosInteiros.java`
Lê dois números inteiros e exibe todos os valores do intervalo entre eles, do menor para o maior.

---

## 🌍 Simulações

### `Populacao.java`
Calcula o tempo necessário para que uma população atinja determinado tamanho, considerando uma taxa de crescimento fixa.

### `PopulacaoV2ex5.java`
Versão aprimorada com **entrada do usuário** para população inicial, meta e taxa de crescimento, além de validações de entrada.

---

## 🧠 Conceitos Praticados

| Conceito | Exercícios |
|----------|------------|
| `if / else if / else` | ValidadorDeNotas, Validador, maiorNumero |
| `while / for` | numeros, numerosInteiros, numerosImpar |
| `Scanner` (entrada de dados) | Todos |
| Operador módulo `%` | numerosImpar |
| Laços com condição de parada | Populacao, PopulacaoV2ex5 |
| Validação de entrada | NomeDiferenteDeSenha, Validador |

---

## 📌 Observações

- Todos os programas utilizam **entrada pelo teclado** via `Scanner`
- Os exercícios são **independentes** entre si e podem ser executados separadamente

---

## 👨‍💻 Tecnologias

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

> 📖 Desenvolvido para fins educacionais — aprendendo lógica de programação com Java.
