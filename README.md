<h1 align="center">Curso Udemy - Java e POO</h1>

# Chess System - Java

# Modelo de domínio Chess System

![Modelo de domínio Chess System](chess-system-design.png)

## Sobre o Projeto

Este projeto é uma implementação de um sistema de xadrez em Java, desenvolvido com princípios de Programação Orientada a Objetos (POO). Ele permite jogar uma partida de xadrez diretamente pelo terminal, com regras implementadas e movimentação das peças seguindo as normas oficiais do jogo.

## Funcionalidades

✅ Representação do tabuleiro e peças usando matriz <br>
✅ Movimentação das peças com validação de jogadas <br>
✅ Troca de turno entre os jogadores <br>
✅ Controle de peças capturadas <br>
✅ Verificação de xeque e xeque-mate <br>
✅ Implementação de regras especiais: Roque, En Passant e Promoção <br>
✅ Tratamento de exceções e validação de entrada do usuário <br>

## Conceitos Utilizados

### 🔹 Programação Orientada a Objetos (POO)

- Encapsulamento
- Herança
- Polimorfismo
- Classes e Métodos Abstratos
- Modificadores de Acesso
- Enumerações
- Sobrescrita de Métodos (Overriding)
- Sobrecarga de Métodos (Overloading)

### 🔹 Estruturas de Dados

- Matriz (para representar o tabuleiro)
- Listas (para controle de peças capturadas e em jogo)

### 🔹 Padrões e Boas Práticas

- Camadas organizadas: UI, lógica do jogo, e modelo de dados
- Tratamento de exceções personalizado (`BoardException`, `ChessException`)
- Métodos auxiliares para facilitar a leitura e manutenção do código

## Estrutura do Projeto

```
Chess-System-Java/
│── src/
│   ├── boardgame/         # Lógica do tabuleiro e peças
│   ├── chess/             # Lógica do jogo de xadrez
│   ├── application/       # Ponto de entrada do jogo
│   ├── ui/                # Interface de exibição no console
│── README.md              # Documentação do projeto
│── .gitignore             # Arquivos ignorados pelo Git
```

## Como Executar o Projeto

### 🔹 Pré-requisitos

- Java JDK 8 ou superior
- Git Bash (para melhor exibição de cores no terminal)

### 🔹 Passos para execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/Albertinesilva/Chess-System-Java.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd Chess-System-Java
   ```
3. Compile e execute o projeto:
   ```sh
   javac application/Program.java
   java application.Program
   ```

## Exemplo de Saída no Terminal

```
8  -  -  -  -  -  -  -  -
7  -  -  -  -  -  -  -  -
6  -  -  -  -  -  -  -  -
5  -  -  -  -  -  -  -  -
4  -  -  -  -  -  -  -  -
3  -  -  -  -  -  -  -  -
2  P  P  P  P  P  P  P  P
1  R  N  B  Q  K  B  N  R
   a  b  c  d  e  f  g  h
Turno: 1 | Jogador atual: Brancas
Escolha uma peça para mover:
```

## Próximos Passos

🔹 Melhorar a interface no console <br>
🔹 Implementar uma versão gráfica (GUI) usando JavaFX <br>
🔹 Suporte a multiplayer online <br>

## Sobre o projeto

Este projeto de xadrez foi desenvolvido em Java como parte do curso ministrado pelo professor [Nélio Alves](https://github.com/acenelio). O código segue a implementação feita pelo professor, com o objetivo de praticar conceitos de Programação Orientada a Objetos (POO) e estrutura de dados.

## Aluno

👤 **Albert Silva**
