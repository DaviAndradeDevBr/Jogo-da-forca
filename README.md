# Jogo da Forca


## Sobre o projeto

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2026

## Detalhes 🔍

O **Jogo da Forca** é um sistema de adivinhação onde o computador seleciona uma palavra secreta de forma aleatória. O desafio do jogador é descobrir a palavra oculta informando uma letra por vez através do console.

A cada acerto, a letra é revelada em sua respectiva posição. A cada erro, o desenho da forca progride visualmente no terminal. O jogo termina com a vitória do usuário ao completar a palavra ou com a derrota caso o limite de **5 erros** seja atingido.

## Principais funcionalidades 🛠️

- **Sorteio Aleatório**: Seleção dinâmica da palavra secreta pelo sistema a cada nova partida.
- **Renderização da Forca**: Representação visual evolutiva do boneco conforme os erros cometidos.
- **Máscara de Palavra**: Exibição intuitiva das lacunas e das letras já descobertas em suas posições.
- **Gerenciamento de Estado**: Controle rigoroso de tentativas, acertos e condições de encerramento do jogo.

## Instruções de Uso 💻

1.  Obtenha o código via clone de repositório ou download do arquivo `.zip`.
2.  Acesse o diretório raiz através do terminal.
3.  Execute a restauração dos pacotes do projeto:
    ```bash
    dotnet restore
    ```
4.  Inicie a aplicação:
    ```bash
    dotnet run --project jogodaforca.ConsoleApp


## Requisitos de Sistema

.NET SDK 10.0 ou superior.
