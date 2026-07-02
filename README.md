# ☕ Ambientação Inicial com Scanner e Médias em Java

Projeto desenvolvido durante os estudos iniciais de **Java**, com foco na entrada de dados pelo terminal e na realização de cálculos de médias.

## 📖 Sobre o projeto

O programa utiliza a classe `Scanner` para receber informações digitadas pelo usuário.

A partir desses dados, são realizadas operações matemáticas e cálculos de médias, permitindo praticar conceitos fundamentais da linguagem Java.

## 🧠 Conceitos utilizados

* Linguagem Java
* Classe `Scanner`
* Entrada de dados pelo terminal
* Variáveis
* Tipos numéricos
* Operadores aritméticos
* Cálculo de médias
* Exibição de resultados com `System.out.println`
* Estrutura do método `main`

## ⌨️ Uso do Scanner

A classe `Scanner` permite que o programa receba informações digitadas pelo usuário.

```java
import java.util.Scanner;
```

Exemplo de criação do objeto:

```java
Scanner scanner = new Scanner(System.in);
```

Exemplo de leitura de um número:

```java
double nota = scanner.nextDouble();
```

Ao final do programa, o objeto pode ser fechado:

```java
scanner.close();
```

## 🧮 Cálculo de média

A média aritmética é calculada somando os valores e dividindo o resultado pela quantidade de valores utilizados.

Exemplo:

```java
double media = (nota1 + nota2 + nota3) / 3;
```

O resultado pode ser exibido da seguinte forma:

```java
System.out.println("Média: " + media);
```

## ⚙️ Funcionamento geral

O programa segue este fluxo:

1. Inicia a execução.
2. Cria um objeto da classe `Scanner`.
3. Solicita os dados ao usuário.
4. Armazena os valores em variáveis.
5. Realiza os cálculos.
6. Exibe o resultado no terminal.
7. Fecha o `Scanner`.
8. Encerra o programa.

## ▶️ Como executar

### Pela IDE

O projeto pode ser executado utilizando uma IDE como:

* IntelliJ IDEA
* Eclipse
* Visual Studio Code

Abra o projeto, localize a classe que possui o método `main` e execute o programa.

### Pelo terminal

Compile o arquivo:

```bash
javac NomeDaClasse.java
```

Execute o programa:

```bash
java NomeDaClasse
```

Substitua `NomeDaClasse` pelo nome da classe principal do projeto.

## 🎯 Objetivo de aprendizado

Este projeto foi criado para praticar os primeiros conceitos da linguagem Java, principalmente:

* Leitura de dados;
* Manipulação de variáveis;
* Operações matemáticas;
* Cálculo de médias;
* Interação com o usuário pelo terminal.

## 👨‍💻 Autor

**Frederico de Oliveira Brigido**

Projeto desenvolvido durante os estudos iniciais de programação em Java.
