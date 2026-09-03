# Documentação do Projeto: Jokenpô

## 1. Descrição do Projeto
O **Jokenpô** é um aplicativo mobile desenvolvido para o sistema operacional Android que replica o clássico jogo "Pedra, Papel e Tesoura". O usuário joga contra a Inteligência Artificial (IA) do próprio aplicativo, que faz escolhas de forma totalmente aleatória.

## 2. Como Funciona o Jogo
* **Escolha do Jogador:** Na tela principal, o usuário clica em um dos três botões ou imagens representados por: **Pedra**, **Papel** ou **Tesoura**.
* **Jogada do App:** Assim que o usuário faz sua escolha, o aplicativo gera uma jogada aleatória para o adversário (computador).
* **Resultado:** O app compara as duas jogadas seguindo as regras clássicas:
  * Pedra ganha de Tesoura.
  * Tesoura ganha de Papel.
  * Papel ganha de Pedra.
  * Escolhas iguais resultam em **Empate**.
* **Feedback:** A tela exibe a escolha do computador e atualiza uma mensagem textual informando se o usuário **Ganhou**, **Perdeu** ou **Empatou**.

## 3. Tecnologias Utilizadas
* **IDE:** Android Studio
* **Linguagem de Programação:** Java ou Kotlin
* **Interface Gráfica (UI):** XML tradicional (Views) com ConstraintLayout

## 4. Estrutura de Arquivos Principal
* `MainActivity`: Contém a lógica do jogo, a captura dos cliques dos botões e a validação do vencedor.
* `activity_main.xml`: Define o visual do aplicativo, incluindo o título, as imagens de exibição do resultado e os botões de escolha.
* `res/drawable`: Pasta que armazena os ícones e imagens da pedra, papel, tesoura e o plano de fundo.
