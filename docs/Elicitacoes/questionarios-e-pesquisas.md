# Questionários e pesquisas

**Histórico de Revisão**

| Data       | Versão | Descrição            | Autor(es)                                    |
| ---------- | ------ | -------------------- | -------------------------------------------- |
| 20/08/2024 | 0.0.1  | Criação e divulgação do questionário | Carlos Eduardo e Samara Letícia |
| 21/08/2024 | 0.1    | Pesquisa e criação do documento | Carlos Eduardo |

## Introdução
Este documento tem como objetivo apresentar os resultados de uma pesquisa exploratória realizada tanto na internet quanto através de questionários aplicados aos jogadores. A finalidade principal foi conduzir uma engenharia reversa, visando identificar funcionalidades recentemente adicionadas ao jogo, além de entender as percepções e opiniões dos jogadores sobre essas novas atualizações.

A pesquisa foi divulgada em grupos de jogadores de minecraft no Discord e facebook.

## Pesquisas
As pesquisas realizadas permitiram identificar diversas atualizações que foram bastante aguardadas pela comunidade e que introduziram novas funcionalidades ao jogo.

### Atualização Villager & Pillager (1.10)
Os aldeões receberam uma reformulação, com novas dinâmicas e profissões. Além disso, foram introduzidos os Pillagers, inimigos dos Villagers, que representam uma nova ameaça às vilas.

### Atualização Aquática (1.13)
Muito solicitada pela comunidade, a Atualização Aquática trouxe novos biomas oceânicos, introduziu novas dinâmicas e desafios, e adicionou vida marinha ao jogo. Novos [mobs](../modelagem/lexico.md#l19-criaturas), um novo [Boss](../modelagem/lexico.md#l02-chefes), e o Templo do Oceano foram implementados, criando um desafio novo para os jogadores.

### Update do [Nether](../modelagem/lexico.md#l01-nether) (1.16)
Esta atualização introduziu novos [mobs](../modelagem/lexico.md#l19-criaturas), estruturas, e três novos biomas ao [Nether](../modelagem/lexico.md#l01-nether). A exploração do [submundo](../modelagem/lexico.md#l01-nether) se tornou mais frequente com a introdução de novas mecânicas e desafios.

### Atualização Caves & Cliffs: Part I (1.17)
Trouxe várias novidades, principalmente focadas em novas funcionalidades e [blocos](../modelagem/lexico.md#l44-blocos) relacionados a cavernas e montanhas. Algumas das novidades:

- **Ametista e Geodos:** Foram adicionados geodos de ametista, usados para criar telescópios e [blocos](../modelagem/lexico.md#l44-blocos) decorativos.
- **Cobre:** Um novo minério que pode ser minerado e usado para criar [blocos](../modelagem/lexico.md#l44-blocos) de cobre, usado para fabricar [itens](../modelagem/lexico.md#l32-itens) como o para-raios e o telescópio.
- **Moss Block:** [blocos](../modelagem/lexico.md#l44-blocos) de musgo que pode ser usado para decoração e jardinagem.
- **Líquen brilhante:** Uma fonte de luz natural encontrada raramente em cavernas, crescendo em qualquer face de um [blocos](../modelagem/lexico.md#l44-blocos).
- **Azaleia:** Planta que inclui arbustos e árvores para decoração.
- **Axolote:** Mob aquático encontrado em cavernas de água. Pode ser capturado com baldes e auxilia os jogadores em combates subaquáticos. (primeiro anfíbio a ser adicionado ao Minecraft)
- **Cabra:** Mob encontrado em montanhas. Elas podem saltar grandes distâncias e eventualmente chifrar jogadores e outros [mobs](../modelagem/lexico.md#l19-criaturas).
- **Lula-brilhante:** Uma variante brilhante do lula normal, que solta bolsa de tinta brilhante ao ser derrotada, usada para criar [itens](../modelagem/lexico.md#l32-itens) que brilham, como placas iluminadas.
- **Telescópio:** Um item novo que permite que os jogadores dêem zoom para ver objetos distantes.
- **Para-raios:** Usado para proteger estruturas de serem incendiadas por raios, redirecionando os raios para o para-raios.


### Tricky Trials (1.21)
Uma das adições desta atualização foi a Câmara do Julgamento, onde os jogadores enfrentam hordas temporárias de inimigos gerados por spawners. Ao superar esse novo tipo de desafio, os jogadores são recompensados.

**Outras importantes adições:**

- **Armadura de Lobo:** Armadura protetora que pode ser equipada nos lobos do jogador, melhorando sua defesa e permitindo que sejam tingidas com diferentes cores.
- **Mace:** Uma nova arma poderosa que causa dano em área e é ideal para combates em masmorras.
- **Novos [mobs](../modelagem/lexico.md#l19-criaturas):** Breeze e Bogged Skeleton: O Breeze utiliza poderosas rajadas de ar​ nos jogadores, enquanto o Bogged Skeleton dispara flechas envenenadas. 
- **Crafter**: Um novo [blocos](../modelagem/lexico.md#l44-blocos) automatizado movido a [Redstone](../modelagem/lexico.md#l12-redstone) que facilita a criação de [itens](../modelagem/lexico.md#l32-itens).
- **Trial Chambers**: Novas masmorras subterrâneas com desafios, armadilhas e [mobs](../modelagem/lexico.md#l19-criaturas) únicos para os jogadores enfrentarem.

## Questionário
Sabemos que muitas pessoas não gostam de responder questionários, especialmente quando são longos. Com isso em mente, foi criado um questionário curto, com apenas três perguntas, mas que o grupo julgou ser suficientes para o propósito.

O formulário foi divido em duas seções:

- **Atualizações Recentes:** Visa identificar quais atualizações recentes do Minecraft geraram mais expectativa entre os jogadores.
- **Funcionalidades Futuras:** Busca saber quais funcionalidades ou melhorias os jogadores gostariam de ver nas próximas atualizações do Minecraft.

<a target="_blank" href="https://docs.google.com/spreadsheets/d/1GkpDggo6U045ei09ndmq1sSNqtbvvthf79wnJ_53gHc/"> Confira as respostas do questionário aqui.</a>

## Requisitos Elicitados
Com base no questionário e na pesquisa realizada, abaixo estão os requisitos identificados.

| Código       | Descrição 
| ---------- | -------- | 
| QP1 | Deve haver novos [blocos](../modelagem/lexico.md#l44-blocos) decorativos para expandir as opções de construção e paisagismo. | 
| QP2 | Devem ser adicionados novos biomas e ruínas para exploração.  |
| QP3 | Deve haver armaduras para que possam proteger os lobos durante o jogo. |
| QP4 | Deve ser adicionada uma nova arma de dano em área para facilitar combates enfrentando múltiplos inimigos de uma só vez|
| QP5 | Deve haver a inclusão de novos biomas do [Nether](../modelagem/lexico.md#l01-nether), adicionando desafios para incentivar a exploração do [submundo](../modelagem/lexico.md#l01-nether). |
|QP6| Deve ser introduzido um telescópio, permitindo aos jogadores maior alcance de visão. |
|QP7| Deve ser melhorada a dinâmica de interação com aldeões, com novas profissões e comportamentos |
|QP8| Deve haver mais opções de personalização para [mobs](../modelagem/lexico.md#l19-criaturas) de estimação. |
|QP9| Deve haver um sistema de crafting automático, que permita aos jogadores automatizar processos. |
|QP10| Deve haver vida marinha, incluindo novos [mobs](../modelagem/lexico.md#l19-criaturas) desafiadores. |
|QP11| Deve haver mais atualizações focadas em cavernas e montanhas, expandindo os [blocos](../modelagem/lexico.md#l44-blocos) e [recursos](../modelagem/lexico.md#l31-recursos) disponíveis. |
|QP12| Deve haver a inclusão do minério de cobre. |
|QP13| Nova mecânica de defesa contra raios, com a introdução de [blocos](../modelagem/lexico.md#l44-blocos) como o para-raios. |
|QP14| Deve ser incluídos novos [mobs](../modelagem/lexico.md#l19-criaturas) de animais. |
|QP15| Novo sistema de iluminação, com lâmpadas de cobre. |
|QP16| Deve haver novas estruturas geradas como masmorras subterrâneas, com novos desafios e recompensas. |
|QP17| Deve haver novos inimigos |
|QP18| Novos eventos e desafios temporários com recompensas exclusivas |

---
## Referências:
Adegilson. **Minecraft: Seria a atualização 1.21 a maior desde o update do Nether?**. Acesso em: ago de 2024. Disponível em: <a target="_blank" href="https://nationpop.com.br/seria-a-atualizacao-1-21-a-maior-desde-o-update-do-nether/">https://nationpop.com.br/seria-a-atualizacao-1-21-a-maior-desde-o-update-do-nether/</a>
<br>

Boddy, ZACHARY. **The Minecraft 1.21 update is official, with automated crafting, trial dungeons, and a brand-new mob**. Acesso em: ago de 2024. Disponível em: <a target="_blank" href="https://www.windowscentral.com/gaming/minecraft/the-minecraft-121-update-is-official-with-automated-crafting-trial-dungeons-and-a-brand-new-mob
">https://www.windowscentral.com/gaming/minecraft/the-minecraft-121-update-is-official-with-automated-crafting-trial-dungeons-and-a-brand-new-mob
</a>
<br>

Boddy, ZACHARY. **Minecraft 1.21 'Tricky Trials Update' FAQ: Release date, features, mobs, snapshots, and other questions answered**. Acesso em: ago de 2024. Disponível em: <a target="_blank" href="https://www.windowscentral.com/gaming/minecraft/minecraft-1-21-update-faq">https://www.windowscentral.com/gaming/minecraft/minecraft-1-21-update-faq
</a>
<br>

Minecraft Wiki. **Edição Java 1.17**. Acesso em: ago de 2024. Disponível em: <a target="_blank" href="https://minecraft.fandom.com/pt/wiki/Edi%C3%A7%C3%A3o_Java_1.17">https://minecraft.fandom.com/pt/wiki/Edi%C3%A7%C3%A3o_Java_1.17
</a>
<br>
















---
