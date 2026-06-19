# ♟️ Chess System - Java

Um sistema de jogo de xadrez completo desenvolvido em **Java Core**, executado diretamente no terminal. Este projeto foi construído com o objetivo de consolidar conceitos fundamentais e avançados de Programação Orientada a Objetos (POO).

## Funcionalidades Demonstradas
* **Lógica Completa de Xadrez:** Validação de movimentos dinâmicos para cada tipo de peça.
* **Movimentos Especiais:** Suporte a regras clássicas como *Roque* (Castling), *Peão Promovido* (Promotion) e *En Passant*.
* **Sistema de Turnos:** Controle estrito de jogadas alternadas entre as peças brancas e pretas.
* **Mecanismo de Xeque e Xeque-Mate:** Detecção automática de situações de perigo ao Rei e fim de jogo.

## 🛠️ Conceitos de Programação Aplicados
* **Programação Orientada a Objetos (POO):** Encapsulamento, Herança, Polimorfismo e Associação entre objetos.
* **Tratamento de Exceções:** Criação de exceções personalizadas (`ChessException` e `BoardException`) para garantir a robustez e integridade do tabuleiro, impedindo movimentos inválidos.
* **Estruturas de Dados:** Uso de matrizes para renderização do tabuleiro e listas para controle de peças capturadas.
* **Clean Code:** Organização do projeto em camadas lógicas (Tabuleiro, Peças, Jogo e Aplicação).

## 🎮 Como Executar

1. Certifique-se de ter o **Java JDK** instalado na sua máquina.
2. Clone o repositório:
   ```bash
   git clone [https://github.com/Manuelcamp/JavaXadrez.git](https://github.com/Manuelcamp/JavaXadrez.git)
   ```
3. Navegue até a pasta raiz do projeto no terminal:
   ```bash
   cd JavaXadrez
   ```
4. Para executar o jogo diretamente pelo terminal, basta compilar e rodar o arquivo principal `Program.java` (localizado em `chessSystem/src/application/`):
   ```bash
   # Compila todos os arquivos do projeto
   javac chessSystem/src/application/Program.java chessSystem/src/*/*.java
   
   # Executa o programa principal
   java chessSystem/src/application/Program
   ```
💡 **Nota:** Você também pode simplesmente abrir a pasta raiz em sua IDE de preferência (IntelliJ, Eclipse ou VS Code) e rodar o arquivo `Program.java` clicando em **Run**.
### Dica extra:
Se o seu terminal suportar cores (como o Git Bash ou o terminal do Linux/Mac), você pode destacar no README que o jogo possui um design colorido no terminal para diferenciar as peças brancas das pretas!
