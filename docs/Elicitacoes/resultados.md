# Resultado das técnicas de elicitação

| Data   | Versão  | Descrição | Autor(es)|
| --- | --- | --- | --- |
| 06/09/2024 | 0.1 | Criação do documento inicial e adição dos RF1 à RF23 e RNF1  | Carlos Eduardo Rodrigues |
| 07/09/2024 | 0.2 | Adição RF24 à RF52 e RNF2 | Carlos Eduardo Rodrigues |

## Requisitos Funcionais

|Código|Requisito|Técnica(s)|
|---|---|---|
| RF1 | O usuário deve ser capaz de criar uma conta no Minecraft. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.1#ap01-requisitos-elicitados) |
| RF2 | O usuário deve ser capaz de se locomover utilizando o teclado. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.2#ap01-requisitos-elicitados) |
| RF3 | O usuário deve ser capaz de interagir com o mundo utilizando o mouse. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.3#ap01-requisitos-elicitados) |
| RF4 | Os recursos devem ser armazenados no inventário do usuário. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.4#ap01-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting), [MoSCoW](Moscow.md#quadro-moscow), [Introspeccao](Introspeccao.md?h=int1.5#15-requisitos-elicitados) |
| RF5 | O jogo deve possuir um dicionário com a explicação de todos os itens descobertos pelo usuário. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.5#ap01-requisitos-elicitados) |
| RF6 | O usuário deve precisar de uma mesa de trabalho para fabricar ferramentas eficientes. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.6#ap01-requisitos-elicitados) |
| RF7 | O jogo deve permitir que, através de minérios, o usuário crie novas ferramentas. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.7#ap01-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting), [MoSCoW](Moscow.md#quadro-moscow) |
| RF8 | O jogo deve oferecer diferentes tipos de alimentos para evitar que o personagem do usuário morra de fome. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap1.8#ap01-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting) |
| RF9 | No modo hardcore, o usuário deve ter apenas uma vida, tornando o jogo mais desafiador e definitivo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap2.1#ap02-requisitos-elicitados), [Introspeccao](Introspeccao.md?h=int3.1#35-requisitos-elicitados) |
| RF10 | No modo hardcore, após a morte, o usuário deve ser capaz de entrar apenas no modo espectador, sem interagir com o mundo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap2.2#ap02-requisitos-elicitados) |
| RF11 | No modo hardcore, o jogo deve ser definido automaticamente na dificuldade mais alta e não pode ser alterado. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap2.3#ap02-requisitos-elicitados) |
| RF12 | No modo hardcore, os comandos de cheats devem estar desabilitados para garantir a integridade do desafio. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap2.4#ap02-requisitos-elicitados) |
| RF13 | No modo criativo, o inventário deve conter todos os itens do jogo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.1#ap03-requisitos-elicitados) |
| RF14 | No modo criativo, o usuário deve ser capaz de sobrevoar rapidamente pelo mapa para facilitar as criações. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.2#ap03-requisitos-elicitados), [Introspeccao](Introspeccao.md?h=int1.2#15-requisitos-elicitados) |
| RF15 | O usuário deve ser capaz de colocar e quebrar blocos com apenas um comando no modo criativo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.3#ap03-requisitos-elicitados), [Introspeccao](Introspeccao.md?h=int1.3#15-requisitos-elicitados) |
| RF16 | O usuário deve ter acesso a todos os itens do jogo no modo criativo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.4#ap03-requisitos-elicitados), [Introspeccao](Introspeccao.md?h=int1.1#15-requisitos-elicitados) |
| RF17 | O usuário não deve precisar se preocupar com vida ou barra de fome no modo criativo, focando apenas em criar. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.5#ap03-requisitos-elicitados) |
| RF18 | Mobs hostis devem ignorar a presença do usuário no modo criativo. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.6#ap03-requisitos-elicitados) |
| RF19 | No modo criativo, usuário deve ser capaz de alterar o clima e a hora do dia conforme necessário para suas criações. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap3.7#ap03-requisitos-elicitados) |
| RF20 | Deve haver um sistema de chat para comunicação entre os jogadores, com suporte a comandos especiais. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap4.2#ap04-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting), [Introspeccao](Introspeccao.md?h=int2.7#25-requisitos-elicitados) |
| RF21 | Jogos multiplayer devem permitir a criação e personalização de diversos modos de jogo, como construção, sobrevivência e PvP. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap4.3#ap04-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting) |
| RF22 | Jogos multiplayer devem fornecer um sistema de votação justo e intuitivo durante competições para escolher as melhores construções ou desempenhos. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap4.4#ap04-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting) |
| RF23 | Em Jogos multiplayer deve ser possível a criação e agendamento de eventos e competições especiais para os jogadores. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap4.5#ap04-requisitos-elicitados) |
| RF24 | O jogador dever ser capaz de colocar alguns blocos na [hotbar](../modelagem/lexico.md#l39-hotbar). | [Introspeccao](Introspeccao.md?h=int1.6#15-requisitos-elicitados)|
| RF25 | O jogador deve ser capaz de compartilhar o seu mapa com outro jogador. | [Introspeccao](Introspeccao.md?h=int1.7#15-requisitos-elicitados)|
| RF26 | Deve existir um modo de jogo onde o jogador pode morrer (sobrevivência) | [Introspeccao](Introspeccao.md?h=int2.1#25-requisitos-elicitados), [Brainstorming](Brainstorming.md#brainwriting), [MoSCoW](Moscow.md#quadro-moscow) |
|RF27| Com exceção dos modos Criativo e Espectador, o jogador deve ter uma quantidade limitada de vida|[Introspeccao](Introspeccao.md?h=int2.2#25-requisitos-elicitados)|
|RF28|O jogador deve ser capaz de criar ferramentas |[Introspeccao](Introspeccao.md?h=int2.3#25-requisitos-elicitados)|
|RF29|O jogador deve ser capaz de atacar os inimigos|[Introspeccao](Introspeccao.md?h=int2.4#25-requisitos-elicitados)|
|RF30|Com exceção do modo hardcore, o jogador deve ser capaz de escolher a dificuldade do jogo|[Introspeccao](Introspeccao.md?h=int2.5#25-requisitos-elicitados)|
|RF31| O mundo deve ser gerado com diversos biomas |[Introspeccao](Introspeccao.md?h=int2.8#25-requisitos-elicitados)|
|RF32| O jogador deve ser capaz de melhorar o material dos seus itens |[Introspeccao](Introspeccao.md?h=int2.9#25-requisitos-elicitados)|
|RF33| O jogador deve ser capaz de encantar os seus itens |[Introspeccao](Introspeccao.md?h=int2.10#25-requisitos-elicitados)|
|RF34| Quando um inimigo morrer ele deve deixar um drop |[Introspeccao](Introspeccao.md?h=int2.11#25-requisitos-elicitados)|
|RF35| O jogador deve ter uma barra de fome |[Introspeccao](Introspeccao.md?h=int2.12#25-requisitos-elicitados)|
|RF36|Cada dimensão deve ter diferentes inimigos|[Introspeccao](Introspeccao.md?h=int3.2#35-requisitos-elicitados), [Questionário](questionarios-e-pesquisas.md?h=qp17#requisitos-elicitados)|
|RF37|Devem existir inimigos de diferentes dificuldades|[Introspeccao](Introspeccao.md?h=int3.3#35-requisitos-elicitados)|
|RF38|O jogo deve apresentar um sistema de conquistas|[Introspeccao](Introspeccao.md?h=int3.4#35-requisitos-elicitados)|
|RF39|O jogador deve poder acessar o sistema de conquistas a qualquer momento|[Introspeccao](Introspeccao.md?h=int3.5#35-requisitos-elicitados)|
|RF40|O jogador deve ser capaz de compartilhar suas conquistas com outros jogadores|[Introspeccao](Introspeccao.md?h=int3.6#35-requisitos-elicitados)|
|RF41|O jogo deve possuir chefes|[Introspeccao](Introspeccao.md?h=int3.7#35-requisitos-elicitados)|
|RF42|Deve haver blocos decorativos para expandir as opções de construção e paisagismo.| [Questionário](questionarios-e-pesquisas.md?h=qp1+qp15#requisitos-elicitados)|
|RF43| Deve haver ruínas, cavernas, montanhas e masmorras subterrâneas, com desafios e recompensas para que os jogadores realizem explorações. | [Questionário](questionarios-e-pesquisas.md?h=qp2+qp10+qp16#requisitos-elicitados)|
|RF44| Deve haver armaduras para os jogadores e seus animais de combate. | [Questionário](questionarios-e-pesquisas.md?h=qp3#requisitos-elicitados)|
|RF45| Deve haver armas de dano em área para facilitar combates enfrentando múltiplos inimigos de uma só vez | [Questionário](questionarios-e-pesquisas.md?h=qp4#requisitos-elicitados)|
|RF46| Os biomas do Nether, devem possuir desafios e recompensas únicas para incentivar a exploração do submundo. | [Questionário](questionarios-e-pesquisas.md?h=qp5#requisitos-elicitados)|
|RF47| Deve haver mobs pacíficos com profissões | [Questionário](questionarios-e-pesquisas.md?h=qp7#requisitos-elicitados)|
|RF48| Os jogadores devem ser capazes de personalizar os seus mobs de estimação. | [Questionário](questionarios-e-pesquisas.md?h=qp8#requisitos-elicitados)|
|RF49| Deve haver um sistema de crafting automático, que permita aos jogadores automatizar processos. | [Questionário](questionarios-e-pesquisas.md?h=qp9#requisitos-elicitados)|
|RF50| Deve haver diferentes tipos de minérios e recursos | [Questionário](questionarios-e-pesquisas.md?h=qp12#requisitos-elicitados)|
|RF51| Deve haver diferentes tipos de mobs de animais. | [Questionário](questionarios-e-pesquisas.md?h=qp13+qp10#requisitos-elicitados)|
|RF52| Deve haver eventos e desafios temporários com recompensas exclusivas| [Questionário](questionarios-e-pesquisas.md?h=qp18#requisitos-elicitados)|


## Requisitos Não Funcionais

|Código|Requisito|Técnica(s)|
|---|---|---|
| RNF1 | O servidor deve suportar a conexão simultânea de múltiplos jogadores sem queda de desempenho. | [Análise de Protocolo](AnaliseProtocolo.md?h=ap4.1#ap04-requisitos-elicitados) |
| RNF2 | O jogo deve ter um sistema de salvamento automático | [Introspeccao](Introspeccao.md?h=int1.4#15-requisitos-elicitados)|
