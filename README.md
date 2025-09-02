# 🧩 Sudoku com Interface Gráfica — Projeto Bootcamp DIO

Este projeto é um jogo de Sudoku desenvolvido em Java com interface gráfica utilizando Swing. Criado como parte do Bootcamp da [Digital Innovation One (DIO)](https://www.dio.me/), o objetivo é aplicar conceitos de orientação a objetos, manipulação de arrays e eventos gráficos.

## 🎮 Funcionalidades

- Sorteio de um dos cinco tabuleiros pré-definidos
- Interface gráfica com botões interativos
- Validação de jogadas com contador de erros
- Destaque visual para seleção de números
- Bordas estilizadas para delimitar os blocos 3x3

## 🧱 Estrutura do Projeto

- `Games.java`: Classe responsável por armazenar os tabuleiros e suas soluções.
- `Sudoku.java`: Classe principal que renderiza a interface gráfica e gerencia a lógica do jogo.
- `rules/`: Pacote onde as classes estão organizadas.

## 🖥️ Tecnologias Utilizadas

- **Java 21**
- **Swing** para interface gráfica
- **AWT** para manipulação de eventos
- **Git & GitHub** para versionamento

## 📷 Interface

O jogo é exibido em uma janela com:

- Um painel superior com o contador de erros
- Um painel central com o tabuleiro 9x9
- Um painel inferior com os botões de números de 1 a 9

Cada célula vazia pode ser preenchida pelo jogador. Se o número estiver correto de acordo com a solução, ele é inserido; caso contrário, o contador de erros é incrementado.

## 🧠 Lógica de Validação

- O jogador seleciona um número clicando em um botão.
- Ao clicar em uma célula vazia, o número é inserido se estiver correto.
- Caso contrário, o contador de erros é atualizado.

## 📈 Possíveis Melhorias

- Adicionar botão de reiniciar jogo
- Implementar cronômetro
- Salvar progresso do jogador
- Adicionar níveis de dificuldade
- Exportar para versão web com JavaScript

## 👨‍💻 Autor

**Marcus**  
📍 Duque de Caxias - RJ, Brasil  
Bootcamp DIO | Desenvolvedor em formação

---

> Este projeto representa minha evolução como desenvolvedor. Feedbacks são sempre bem-vindos!