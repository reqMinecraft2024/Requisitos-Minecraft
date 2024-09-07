# Introspecção

## Histórico de Revisão

| Data       | Versão | Descrição            | Autor(es)                                    |
| ---------- | ------ | -------------------- | -------------------------------------------- |
| 31/07/2024 | 0.1    | Criação do documento | Danilo Melo |
| 01/08/2024 | 0.2    | Classificação dos requisitos | Danilo Melo |
| 06/09/2024 | 0.3 | Correção de duplicata | Carlos Eduardo |

---

## Introdução

Introspecção é uma técnica muito rica e profunda. Consiste em entender quais propriedades o sistema deve possuir para que seja um sucesso. Demanda o Engenheiro de Requisitos imaginar o que ele gostaria, se ele tivesse que desempenhar uma dada tarefa, com os equipamentos disponíveis e demais recursos.

## Metodologia

Foi feita uma introspecção ao visualizar diferentes fluxos de usuários na plataforma, com base nas definições estabelecidas após o [Brainstorming](../Elicitacoes/Brainstorming.md) e definição de [personas](../modelagem/personas.md). A introspecção foi estruturada em formato de storytelling, focando nos diversos tipos de usuários da aplicação.

## Introspecção 1

### 1.1 Contexto
[Sarah](../modelagem/personas.md#sarah) deseja poder criar construções impressionantes no jogo para compartilhar com seus seguidores. Seu plano é erguer um castelo extremamente realista, um projeto que demanda uma atenção meticulosa aos detalhes e uma ampla gama de recursos do jogo. No entanto, Sarah enfrenta um desafio: sua agenda está bastante apertada, deixando-a com pouco tempo livre para se dedicar ao processo de coleta de materiais, que pode ser um dos aspectos mais demorados e tediosos da construção. Portanto, ela busca uma solução que permita a realização do projeto sem a necessidade de passar por essa fase de coleta extensiva.

### 1.2 Necessidades Técnicas
* Um modo com recursos ilimitados
* Possibilidade de construir coisas
* Movimentação facilitada
* Opção de salvar o progresso

### 1.3 Necessidades Individuais
* Controle do tempo
* Uso da criatividade

### 1.4 Necessidades Sociais
* Poder exibir suas construções para os seus seguidores
* Poder compartilhar os seus mapas com outras pessoas

### 1.5 Requisitos Elicitados

| Código       | Descrição | Prioridade        | Classificação  |
| ---------- | -------- | -------------------- | -------------------------------------------- |
| INT1.1 | Deve existir um modo de jogo onde o jogador é possuí recursos ilimitados  ([Modo Criativo](../modelagem/lexico.md#l07-criativo))  | Must | Funcional |
| INT1.2 | O jogador deve ser capaz de voar no [Modo Criativo](../modelagem/lexico.md#l07-criativo)| Must | Funcional |
| INT1.3 | O jogador deve ser capaz de remover blocos | Must | Funcional |
| INT1.4 | O jogo deve ter um sistema de salvamento automático | Must | Não funcional |
| INT1.5 | O jogador deve ter acesso a todos os [itens](../modelagem/lexico.md#l32-itens) de forma prática | Must | Funcional |
| INT1.6 | O jogador dever ser capaz de colocar alguns blocos na [hotbar](../modelagem/lexico.md#l39-hotbar) | Must | Funcional |
| INT1.7 | O jogador deve ser capaz de compartilhar o seu mapa com outro jogador | Could | Funcional |


---

## Introspecção 2

### 2.1 Contexto
Após explorar diversos jogos de exploração, [Arthur](../modelagem/personas.md#arthur) está em busca de uma nova experiência que combine exploração da natureza com desafios moderados. Ele deseja jogar um jogo que permita enfrentar esses desafios de maneira cooperativa com seus amigos, criando uma experiência de jogo mais envolvente e colaborativa. Além disso ele espera encontrar alguma forma de melhorar os seus itens para ficar mais forte durante sua jornada.

### 2.2 Necessidades Técnicas
* Um modo que desafie o jogador 
* Inimigos para o jogador enfrentar
* Sistema de biomas
* Multiplayer
* Diferentes materiais
* Sistema de encantamentos
* Ajuste de dificuldade
* Sistema de chat

### 2.3 Necessidades Individuais
* Nível de habilidade

### 2.4 Necessidades Sociais
* Conexão com internet
* Comunicação entre os jogadores

### 2.5 Requisitos Elicitados

| Código       | Descrição | Prioridade        | Classificação  |
| ---------- | -------- | -------------------- | -------------------------------------------- |
| INT2.1 | Deve existir um modo de jogo onde o jogador pode morrer ([sobrevivência](../modelagem/lexico.md#l09-sobrevivencia) sobrevivência)  | Must | Funcional |
| INT2.2 | O jogador deve ter uma quantidade limitada de vida  | Must | Funcional |
| INT2.3 | O jogador deve ser capaz de criar [ferramentas](../modelagem/lexico.md#l18-ferramentas) | Must | Funcional |
| INT2.4 | O jogador deve ser capaz de atacar os inimigos | Must | Funcional |
| INT2.5 | O jogador deve ser capaz de escolher a dificuldade do jogo | Should | Funcional |
| INT2.6 | Um jogador deve ser capaz de entrar no mundo de outro jogador | Should | Funcional |
| INT2.7 | O jogador deve ser capaz de acessar o chat | Should | Funcional |
| INT2.8 | O mundo deve ser gerado com diversos biomas | Must | Funcional |
| INT2.9 | O jogador deve ser capaz de melhorar o material dos seus [itens](../modelagem/lexico.md#l32-itens) | Must | Funcional |
| INT2.10 | O jogador deve ser capaz de encantar os seus itens | Should | Funcional |
| INT2.11 | Quando um inimigo morrer ele deve deixar um [drop](../modelagem/lexico.md#l30-drops) | Must | Funcional |
| INT2.12 | O jogador deve ter uma barra de fome | Must | Funcional |

## Introspecção 3

### 3.1 Contexto
[Victor](../modelagem/personas.md#victor) é apaixonado por jogos que oferecem um alto nível de dificuldade, sempre buscando se desafiar ao conquistar todas as [conquistas](../modelagem/lexico.md#l40-conquistas) disponíveis. Por isso, ele espera que o jogo ofereça um modo mais desafiador, com inimigos progressivamente mais poderosos. Além disso, ele deseja um sistema de [conquistas](../modelagem/lexico.md#l40-conquistas) robusto, que torne os desafios ainda mais dinâmicos e estimulantes.


### 3.2 Necessidades Técnicas
* [Modo hardcore](../modelagem/lexico.md#l10-hardcore)
* Diversidades de inimigos
* Sistema de [conquistas](../modelagem/lexico.md#l40-conquistas)
* [chefes](../modelagem/lexico.md#l02-chefes)

### 3.3 Necessidades Individuais
* Habilidade
* Conhecimento sobre o jogo

### 3.4 Necessidades Sociais
* Compartilhar as suas [conquistas](../modelagem/lexico.md#l40-conquistas) com outras pessoas

### 3.5 Requisitos Elicitados

| Código       | Descrição | Prioridade        | Classificação  |
| ---------- | -------- | -------------------- | -------------------------------------------- |
| INT3.1 | Deve existir um modo de jogo onde o jogador pode morrer permanentemente([Hardcore](../modelagem/lexico.md#l10-hardcore))  | Should | Funcional |
| INT3.2 | Cada [dimensão](../modelagem/lexico.md#l33-dimensao) deve ter diferentes inimigos | Must | Funcional |
| INT3.3 | Devem existir inimigos de diferentes dificuldades | Should | Funcional |
| INT3.4 | O jogo deve apresentar um sistema de [conquistas](../modelagem/lexico.md#l40-conquistas) | Should | Funcional |
| INT3.5 | O jogador deve poder acessar o sistema de [conquistas](../modelagem/lexico.md#l40-conquistas) a qualquer momento | Should | Funcional |
| INT3.6 | O jogador deve ser capaz de compartilhar suas [conquistas](../modelagem/lexico.md#l40-conquistas) com outras pessoas | Won't | Funcional |
| INT3.7 | O jogo deve possuir [chefes](../modelagem/lexico.md#l02-chefes) | Must | Funcional |


## Referências 

Slide Requisitos Aula 7 - Milene Serrano e Maurício Serrano