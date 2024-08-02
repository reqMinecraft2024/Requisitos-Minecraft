# Cenários

## Histórico de Versões

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 30/07/2024 |  0.1   | Criação de Cenários | [Samara Letícia](https://github.com/samarawwleticia)|
| 01/08/2024 | 0.2 | Revisão | Danilo Melo |

### Cenário 01

| **Título:** | Dinâmica do Minecraft [survival](../modelagem/lexico.md#l09-sobrevivência) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Descrever o início do Minecraft| 
|**Contexto:** | Início de Jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador [cria mundo](../modelagem/lexico.md#l25-criar-mundo)<br> Jogador escolhe modo de jogo [sobrevivência](../modelagem/lexico.md#l09-sobrevivência)<br> Jogador escolhe dificuldade do jogo (pacífico, fácil, normal ou difícil)<br> Jogador nomeia o mundo<br> Jogador entra no mundo ([overworld](../modelagem/lexico.md#l05-overworld)) |
|**Restrição:**| Carregamento e atualizações rápidas<br> Começar em um bioma com bons recursos |
|**Exceção**| Launcher não carregar o mundo<br> Erro na geração de biomas<br> [Estruturas](../modelagem/lexico.md#l03-estruturas-geradas) não encontradas |

### Cenário 02

| **Título:** | Dinâmica do Minecraft [criativo](../modelagem/lexico.md#l07-criativo) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar uma [construção](../modelagem/lexico.md#l34-estruturas) no Minecraft| 
|**Contexto:** | Modo de Jogo: [criativo](../modelagem/lexico.md#l07-criativo) |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador escolhe coordenadas da construção<br> Jogador abre o inventário<br> Jogador escolhe [recursos](../modelagem/lexico.md#l31-recursos)<br> Jogador coloca [recursos](../modelagem/lexico.md#l31-recursos) no mundo, construindo a [estrutura](../modelagem/lexico.md#l34-estruturas) desejada  |
|**Restrição:**| Bom desempenho do jogo<br> Localizar facilmente os [recursos](../modelagem/lexico.md#l31-recursos) |
|**Exceção**| Falta de memória para carregar a construção<br> Desempenho lento do jogo |

### Cenário 03

| **Título:** | Ir ao [end](../modelagem/lexico.md#l04-end) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Descrever como chegar a dimensão [end](../modelagem/lexico.md#l04-end)| 
|**Contexto:** | Jogo avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador cria olho de ender<br> Jogador usa olho de ender para localizar a fortaleza<br> Jogador entra na sala de portal<br> Jogador coloca os Olhos de Ender no portal<br> Jogador entra no portal |
|**Restrição:**| Carregamento e atualizações rápidas<br> Entrar na plataforma principal do [End](../modelagem/lexico.md#l04-end) |
|**Exceção**| Launcher não carregar o [End](../modelagem/lexico.md#l04-end)<br> Cair no vazio<br> Não localizar a fortaleza<br> Não obter [Ender pearls](../modelagem/lexico.md#l36-ender-pearls) |

                
