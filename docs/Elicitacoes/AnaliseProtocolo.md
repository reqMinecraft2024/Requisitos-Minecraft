# Analise de Protocolo

**Histórico de Revisão**

| Data   | Versão  | Descrição | Autor(es)|
| --- | --- | --- | --- |
| 31/07/2024 | 0.1 | Criação do documento inicial e adição da introdução | Patrícia Helena |
| 31/07/2024 | 0.2 | Analise de Protocolo 1 e 2 | Samara Letícia |
| 31/07/2024 | 0.3 | Analise de Protocolo 3 e 4 | Patrícia Helena |
| 01/08/2024 | 1.0 | Aplicação de MoSCoW em todas as análises  | Patrícia Helena |


## Introdução
Trata-se de um método onde o usuário é solicitado a realizar uma tarefa enquanto, simultaneamente, explica em voz alta o processo que está seguindo. Analisamos diferentes modos de jogo do minecraft.

## Metodologia
Todas as descrições e ações do usuário são feitas em voz alta para que o Analisador consiga acompanhar cada passo e classifica-los por prioridades.

**Vídeo da Analise do modo sobrevivência, Hardcore e multiplayer**
<iframe src="https://drive.google.com/file/d/1YRjdllwaTgr4e3BX6oIpFw4BpB2aT2nY/preview" allow="fullscreen"></iframe>
<img class="img-iframe" src="../../assets/imgs/transition-grey-6.png">

**Vídeo da Analise do criativo**
<iframe src="https://drive.google.com/file/d/1Ha3QPbPp83Je9FLDI6ieR8Wd7KLkBU4Y/preview" allow="fullscreen"></iframe>
<img class="img-iframe" src="../../assets/imgs/transition-grey-6.png">

## AP01
##Análise de Protocolo 1

**Relator**: Patrícia Helena  
**Analisador**: Samara Letícia   
**Modo de jogo** :  [Sobrevivência](../modelagem/lexico.md#l09-sobrevivencia) 

O método foi realizado com uma pessoa que já conhecia o minecraft, os objetivos eram [explorar](../modelagem/lexico.md#l21-exploracao) um pouco o mapa, conseguir recursos, descobrir estruturas e interagir com os mobs.         


#### Resumo da Narração

Ela entra no Minecraft Launcher com sua conta já logada e cria o mundo no modo [Sobrevivência](../modelagem/lexico.md#l09-sobrevivencia). Anda pelo mapa através do teclado com as teclas w, a, s e d. Coleta um pouco de madeira e usa a [ferramenta](../modelagem/lexico.md#l18-ferramentas) [crafting](../modelagem/lexico.md#l11-craft) do jogo para criar uma mesa de trabalho. Cria uma [ferramenta](../modelagem/lexico.md#l18-ferramentas) com ela e a usa para coletar carvão e pedra. Ela [explora](../modelagem/lexico.md#l21-exploracao) outras partes do mapa como o rio, e após [minerar](../modelagem/lexico.md#l17-mineracao) um pouco chega a uma caverna. Após [explorar](../modelagem/lexico.md#l21-exploracao) um pouco a caverna ela encontra um [mob](../modelagem/lexico.md#l19-criaturas) e tem um combate com ele, que após ser derrotado, libera [drops](../modelagem/lexico.md#l30-drops) usuária. Após [explorar](../modelagem/lexico.md#l21-exploracao) um pouco a caverna a usuária encontra um minério raro e uma nova [estrutura](../modelagem/lexico.md#l03-estruturas-geradas) da atualização, chamada de Trial Chamber. Após explorar um pouco essa [estrutura](../modelagem/lexico.md#l03-estruturas-geradas), o personagem da usuária morre após ser espetado por um cacto e volta no local de início do jogo.

#### Requisitos Elicitados

| Código | Requisito | Descrição | Prioridade |
| :----: | :-------: | :-------: | :-------: |
| AP1.1 | Cadastro | Usuário ter conta no minecraft | C |
| AP1.2 | Uso do Teclado | O usuário se locomove através do teclado | M |
| AP1.3 | Mouse | O usuário interage com o mundo através do mouse | S |
| AP1.4 | Inventário | Os recursos ficam no inventário do usuário | M |
| AP1.5 | Dicionário de Itens | Recurso com explicação de todos os itens ja descobertos | M | 
| AP1.6 | Mesa de trabalho | O usuário precisa dela para fazer ferramentas eficientes | S |
| AP1.7 | Minérios | Através dos minérios é possível conseguir novas ferramentas | S |
| AP1.8 | Alimento | O jogo oferece diferentes tipos de alimento para o personagem do usuário não morrer de fome | M |

Legenda - técnica de priorização:

*   M: **Must have**; S: **Should have**; C: **Could have**; W: **Would have**.

## AP02
##Análise de Protocolo 2

**Relator**: Patrícia Helena  
**Analisador**: Samara Letícia   
**Modo de jogo** :  [Hardcore](../modelagem/lexico.md#l10-hardcore) 

O método foi realizado com uma pessoa já familiarizada com Minecraft, tendo experimentado anteriormente todos os recursos do modo [sobrevivência]. Desta vez, a usuária explorou as características únicas do modo [Hardcore](../modelagem/lexico.md#l10-hardcore).

#### Resumo da Narração

 Após criar um novo mundo, ela notou imediatamente a diferença na interface de vida do modo [Hardcore](../modelagem/lexico.md#l10-hardcore). Para [explorar](../modelagem/lexico.md#l21-exploracao) a mecânica de vida única desse modo, ela subiu em uma colina alta e deliberadamente caiu, esvaziando sua barra de vida. Ao fazer isso, ela percebeu que não podia retornar ao jogo no mesmo local, sendo forçada a entrar no modo [espectador](../modelagem/lexico.md#l06-espectador). Assim, sua jornada naquele mapa chegou ao fim, destacando a intensidade das consequências no modo [Hardcore](../modelagem/lexico.md#l10-hardcore).

#### Requisitos Elicitados

| Código | Requisito | Descrição | Prioridade |
| :----: | :-------: | :-------: | :-------: |
| AP2.1 | Vida única | O usuário tem apenas uma vida, tornando o jogo mais desafiador e definitivo | S |
| AP2.2 | Modo espectador após a morte | Após a morte, o usuário só pode entrar no modo espectador e não pode interagir mais com o mundo | M |
| AP2.3 | Dificuldade Fixa | O jogo é automaticamente definido na dificuldade mais alta e não pode ser alterado | M |
| AP2.4 | Sem cheats | Os comandos de cheats são desabilitados, garantindo a integridade do desafio | S |

Legenda - técnica de priorização:

*   M: **Must have**; S: **Should have**; C: **Could have**; W: **Would have**.


## AP03
##Análise de Protocolo 3

**Relator**: Samara Letícia 
**Analisador**: Patícia Helena    
**Modo de jogo** :  [Criativo](../modelagem/lexico.md#l07-criativo)

O método foi realizado com uma pessoa que já conhecia o minecraft, com objetivo de Criatividade e contrução 


#### Resumo da Narração
 
A usuária, já experiente no jogo e com cadastro feito na plataforma, entrou no modo [Criativo](../modelagem/lexico.md#l07-criativo)  e [criou um novo mundo]  do zero. Imediatamente, notou as diferenças da HUB em relação aos outros modos de jogo. Aproveitando a principal característica do modo [Criativo](../modelagem/lexico.md#l07-criativo), que é a capacidade de voar, ele [explorou](../modelagem/lexico.md#l21-exploracao) o ambiente. Ao acessar o inventário, que contém todos os itens disponíveis no jogo, decidiu iniciar um dos diversos objetivos possíveis: a construção de [estruturas](../modelagem/lexico.md#l34-estruturas). Utilizando os recursos ilimitados do inventário(diferencial do modo Criativo), o usuário construiu uma casa simples como demonstração.
#### Requisitos Elicitados

| Código | Requisito | Descrição | Prioridade |
| :----: | :-------: | :-------: | :-------:  |
| AP3.1 | Inventário criativo | Neste modo o inventario possui TODOS os itens do jogo | M |
| AP3.2 | Locomoção eficiente | O usuário consegue sobrevoar com rapidez pelo mapa, facilitando as criações | S |
| AP3.3 | Blocos com mesma resistência | O usuário consegue colocar blocos e quebra-los com apenas um comando | S |
| AP3.4 | Inventário completo | Neste modo o inventario possui TODOS os itens do jogo  | M |
| AP3.5 | Imortalidade | O usuário não precisa se preocupar com vida nem com barra de fome neste modo, focando assim na criatividade e nao sobrevivência | M | 
| AP3.6 | Ambiente Pacifico | Mobs hóstis ignoram a presença do usuário | S |
| AP3.7 | Clima e hora do dia ajustáveis | O usuário pode alterar o clima e a hora do dia conforme necessário para suas criações | S |

Legenda - técnica de priorização:

*   M: **Must have**; S: **Should have**; C: **Could have**; W: **Would have**.

## AP04
##Análise de Protocolo 4

**Relator**: Patrícia Helena 
**Analisador**: Samara Letícia    
**Modo de jogo** :  [multiplayer](../modelagem/lexico.md#l41-multiplayer)

O método foi realizado com uma pessoa que já conhecia o minecraft, com objetivo de [socialização](../modelagem/lexico.md#l26-socializacao) e [cooperação](../modelagem/lexico.md#l22-cooperacao)


#### Resumo da Narração
 
A usuária, já experiente no jogo e com cadastro feito na plataforma, clicou na aba de [multiplayer](../modelagem/lexico.md#l41-multiplayer) e selecionou a opção de adicionar um novo [servidor](../modelagem/lexico.md#l14-servidores). Ela inseriu o IP do [servidor](../modelagem/lexico.md#l14-servidores) e rapidamente se conectou. Dentro do [servidor](../modelagem/lexico.md#l14-servidores) privado, notou a quantidade de jogadores e novos recursos disponíveis, como um [chat](../modelagem/lexico.md#l23-chat) repleto de comandos e vários modos de jogos personalizados. Para testar essas funcionalidades, ela entrou em uma competição de construção, onde competiu com outros jogadores. O objetivo era escolher um tema e construir algo relacionado; a melhor construção ganhava a rodada. No início da rodada, percebeu que o modo de jogo era [criativo](../modelagem/lexico.md#l07-criativo) para melhor fluidez da construção. Após alguns minutos construindo, a rodada terminou e começou a votação das construções, onde nossa usuária ficou em oitavo lugar.
#### Requisitos Elicitados

| Código | Requisito | Descrição | Prioridade |
| :----: | :-------: | :-------: | :-------:  |
| AP4.1 | Suporte para Vários Jogadores| O servidor deve suportar a conexão simultânea de múltiplos jogadores sem queda de desempenho | M |
| AP4.2 | Sistema de chat| Deve haver um sistema de chat integrado para comunicação entre jogadores, com suporte a comandos especiais | S |
| AP4.3 | Modos de jogos personalizados | O servidor deve permitir a criação e personalização de diversos modos de jogo, como construção, sobrevivência e PvP| S |
| AP4.4 | Sistema de votação | Durante competições, deve haver um sistema de votação justo e intuitivo para escolher as melhores construções ou desempenhos  | S |
| AP4.5 | Eventos Programados | O servidor deve permitir a criação e agendamento de eventos e competições especiais para os jogadores | S | 


Legenda - técnica de priorização:

*   M: **Must have**; S: **Should have**; C: **Could have**; W: **Would have**.




---
