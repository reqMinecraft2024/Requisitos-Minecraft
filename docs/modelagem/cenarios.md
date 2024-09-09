# Cenários

## Histórico de Versões

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 30/07/2024 |  0.1   | Criação de Cenários | [Samara Letícia](https://github.com/samarawwleticia)|
| 01/08/2024 | 0.2 | Revisão | Danilo Melo |
| 06/09/2024 | 0.3 | Atualizações e adições de cenários| Samara Letícia |
| 08/09/2024 | 0.4 | Adição de mais cenários | Samara Letícia |

## Introdução

Os cenários são empregados como uma ferramenta para modelar as interações usuário-sistema. Essa abordagem permite detalhar os fluxos de trabalho, desde a iniciação até a conclusão de uma tarefa, considerando as diversas possibilidades e exceções. Através da análise de cenários, é possível identificar requisitos funcionais e não funcionais de forma mais precisa, garantindo a qualidade e a usabilidade do sistema desenvolvido.

## Metodologia

A metodologia utilizada neste trabalho baseia-se na modelagem de casos de uso e na análise de fluxos de interação, além do uso de brainstorming.

## Cenário 01

| **Título:** | Dinâmica do Minecraft [survival](../modelagem/lexico.md#l09-sobrevivencia) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Descrever o início do Minecraft| 
|**Contexto:** | Início de Jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador [cria mundo](../modelagem/lexico.md#l25-criar-mundo)<br> Jogador escolhe modo de jogo [sobrevivência](../modelagem/lexico.md#l09-sobrevivencia)<br> Jogador escolhe dificuldade do jogo (pacífico, fácil, normal ou difícil)<br> Jogador nomeia o mundo<br> Jogador entra no mundo ([overworld](../modelagem/lexico.md#l05-overworld)) |
|**Restrição:**| Carregamento e atualizações rápidas<br> Começar em um bioma com bons recursos |
|**Exceção**| Launcher não carregar o mundo<br> Erro na geração de biomas<br> [Estruturas](../modelagem/lexico.md#l03-estruturas-geradas) não encontradas |

## Cenário 02

| **Título:** | Dinâmica do Minecraft [criativo](../modelagem/lexico.md#l07-criativo) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar uma [construção](../modelagem/lexico.md#l34-estruturas) no Minecraft| 
|**Contexto:** | Modo de Jogo: [criativo](../modelagem/lexico.md#l07-criativo) |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador escolhe coordenadas da construção<br> Jogador abre o inventário<br> Jogador escolhe [recursos](../modelagem/lexico.md#l31-recursos)<br> Jogador coloca [recursos](../modelagem/lexico.md#l31-recursos) no mundo, construindo a [estrutura](../modelagem/lexico.md#l34-estruturas) desejada. <br> Mobs hostis ignoram a presença do jogador. <br> Jogador é capaz de quebrar itens com apenas um clique. <br> Jogador não se preocupa com fome ou vida.  |
|**Restrição:**| Bom desempenho do jogo<br> Localizar facilmente os [recursos](../modelagem/lexico.md#l31-recursos) |
|**Exceção**| Falta de memória para carregar a construção<br> Desempenho lento do jogo |

## Cenário 03

| **Título:** | Ir ao [end](../modelagem/lexico.md#l04-end) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Descrever como chegar a dimensão [end](../modelagem/lexico.md#l04-end)| 
|**Contexto:** | Jogo avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador cria olho de ender<br> Jogador usa olho de ender para localizar a fortaleza<br> Jogador entra na sala de portal<br> Jogador coloca os Olhos de Ender no portal<br> Jogador entra no portal |
|**Restrição:**| Carregamento e atualizações rápidas<br> Entrar na plataforma principal do [End](../modelagem/lexico.md#l04-end) |
|**Exceção**| Launcher não carregar o [End](../modelagem/lexico.md#l04-end)<br> Cair no vazio<br> Não localizar a fortaleza<br> Não obter [Ender pearls](../modelagem/lexico.md#l36-ender-pearls) |

## Cenário 04

| **Título:** | Derrotar o Ender Dragon |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar o Ender Dragon e completar o jogo | 
|**Contexto:** | Final do jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, armas, armaduras, poções|
|**Episódios:**  |  Jogador encontra a fortaleza do End<br> Jogador ativa o portal do End<br> Jogador vai ao End<br> Jogador destrói cristais do End<br> Jogador ataca o Dragão até derrotá-lo |
|**Restrição:**| Ter todos os itens necessários para o combate |
|**Exceção**| Launcher não carregar o [End](../modelagem/lexico.md#l04-end)<br> Cair no vazio<br> Não localizar a fortaleza<br> Ser morto pelo Ender Dragon |                

## Cenário 05

| **Título:** | Derrotar o Warden |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar o Warden no subterrâneo | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, armadura, armas|
|**Episódios:**  | Jogador encontra cidade ancestral<br> Jogador atrai o Warden com vibrações<br> Jogador ataca o Warden com estratégia à distância e corpo-a-corpo |
|**Restrição:**| Ter todos os itens necessários para o combate |
|**Exceção**| Jogador é derrotado pelo Warden<br> Jogador perde todos os itens durante a batalha<br> Jogador não consegue encontrar Cidade Ancestral|

## Cenário 06

| **Título:** | Chocar um Ovo de Farejador |
| ----------  | -----------------------------  |
|**Objetivo:**|   Obter um Farejador | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, pincel|
|**Episódios:**  | Jogador encontra ruínas<br> Jogador utiliza pincel nos blocos para tentar obter Ovo de Farejador<br> Jogador coloca ovo de farejador sobre bloco de terra ou musgo<br> Farejador sai do ovo depois de um determinado tempo |
|**Restrição:**| Ter todos os itens necessários para crafitar um pincel<br> Achar Ovo de Farejador com facilidade |
|**Exceção**| Jogador não consegue localizar uma ruína<br> Jogador não consegue encontrar Ovo de Farejador |

## Cenário 07

| **Título:** | Derrotar um Mob Simples (Zumbi, Esqueleto, Creeper) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar um mob simples | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  | Jogador espera anoitecer<br> Jogador encontra mob<br> Jogador ataca mob até derrotá-lo |
|**Restrição:**| Utilizar armas e armadura forte |
|**Exceção**| Jogador é derrotado pelo Mob<br> Jogador perde todos os itens durante a batalha |

## Cenário 08

| **Título:** | Fazer uma Farm de Pedra |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar uma Farm automática de pedra | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, lava, água, redstone |
|**Episódios:**  | Jogador coleta materiais<br> Jogador utiliza materiais para construir a farm de pedra<br> Jogador coleta as pedras |
|**Restrição:**| Boa construção e otimização |
|**Exceção**| Não conseguir encontrar lava<br> Não utilizar corretamente a redstone<br> Farm falhar ao produzir pedra |

## Cenário 09

| **Título:** | Crafitar uma Cama |
| ----------  | -----------------------------  |
|**Objetivo:**|   Construir uma cama no minecraft utilizando a mesa de construção | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, mesa de construção|
|**Episódios:**  | Jogador encontra ovelhas<br> Jogador obtem lã de ovelhas<br> Jogador obtém madeira de qualquer árvore<br> Jogador transforma madeira bruta em tábua de madeira<br> Jogador utiliza mesa de construção para construir cama utilizando as lãs e as tábuas de madeira |
|**Restrição:**| Obter todos os itens necessários |
|**Exceção**| Jogador não encontra lãs da mesma coloração<br> Jogador não encontra ovelhas<br> Jogador não obtem recursos suficientes |

## Cenário 10

| **Título:** | Reproduzir Villagers |
| ----------  | -----------------------------  |
|**Objetivo:**|   Reproduzir villagers no jogo | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, comida, camas|
|**Episódios:**  | Jogador encontra vila<br> Jogador posiciona cama perto dos villagers<br> Jogador coloca dá comida a 2 villagers<br> Villagers se reproduzem |
|**Restrição:**| Villagers disponíveis, espaço suficiente |
|**Exceção**| Villagers não se reproduzem |

## Cenário 11

| **Título:** | Voar com Elytra |
| ----------  | -----------------------------  |
|**Objetivo:**| Voar utilizando a Elytra | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, Elytra|
|**Episódios:**  | Jogador crafita foguetes<br> Jogador equipa a Elytra<br> Jogador aciona foguete enquanto o segura  |
|**Restrição:**| Durabilidade da Elytra e número de foguetes |
|**Exceção**| Elytra quebra durante o jogo<br> Não obtém os recursos necessários para crafitar foguetes |

## Cenário 12

| **Título:** | Domar um Lobo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Domar um lobo no minecraft | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, ossos |
|**Episódios:**  | Jogador encontra Lobo<br> Jogador alimenta Lobo com ossos<br> Lobo é domado pelo Jogador |
|**Restrição:**| Ter ossos suficientes |
|**Exceção**| Lobo não é domado<br> Jogador não encontra um Lobo |

## Cenário 13

| **Título:** | Encontrar um tesouro escondido |
| ----------  | -----------------------------  |
|**Objetivo:**|   Encontrar um tesouro no minecraft | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  | Jogador encontra Naufrágio<br> Jogador obtém mapa do tesouro<br> Jogador procura o tesouro utilizando o mapa<br> Jogador obtém tesouro escondido |
|**Restrição:**| Encontrar um mapa do tesouro<br> Encontrar um naufrágio<br> Localização precisa |
|**Exceção**| Naufrágio não produz mapa do tesouro<br> Jogador não consegue localizar o tesouro|

## Cenário 14

| **Título:** | Adicionar um amigo (versão Bedrock) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Conectar com amigos na versão Bedrock | 
|**Contexto:** | Multiplayer |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Bedrock Edition|
|**Episódios:**  |  Jogador abre o menu de amigos<br> Jogador seleciona a opção de adicionar amigo<br> Jogador insere o gamertag do amigo<br> Jogador confirma a solicitação de amizade<br>|
|**Restrição:**| Conexão estável com a internet<br> Amigo deve ter uma conta na mesma plataforma |
|**Exceção**| Gamertag inválido<br> Amigo não aparecer online |

## Cenário 15

| **Título:** | Conectar-se com amigo (versão Java) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Conectar com amigos na versão Java | 
|**Contexto:** | Multiplayer |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Java Edition |
|**Episódios:**  |  Jogador abre o menu de multiplayer<br> Jogador insere o endereço IP do servidor onde o amigo está jogando<br> Jogador se conecta ao servidor<br> Jogador entra no mesmo servidor onde o amigo está jogando<br>|
|**Restrição:**| Servidor configurado corretamente<br> Amigo deve estar online |
|**Exceção**| Falha na conexão com o servidor<br> IP do servidor inválido |

## Cenário 16

| **Título:** | Adicionar um amigo (através do QRCode) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Adicionar um amigo utilizando o QRCode | 
|**Contexto:** | Multiplayer |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Bedrock Edition, Dispositivo com câmera, QRCode |
|**Episódios:**  |  Jogador acessa câmera do seu dispositivo<br> Jogador escaneia o código QR fornecido pelo amigo<br> Jogador confirma a solicitação de amizade<br>|
|**Restrição:**| QRCode válido<br> Conexão estável com a internet |
|**Exceção**| QRCode não reconhecido<br> |

## Cenário 17

| **Título:** | Entrar em um realms |
| ----------  | -----------------------------  |
|**Objetivo:**|   Entrar em um servidor realms | 
|**Contexto:** | Multiplayer |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Realms, Convite para realms |
|**Episódios:**  | Jogador abre o menu de realms<br> Jogador seleciona o convite recebido para o realms<br> Jogador confirma a entrada no servidor realms<br> Jogador entra no mundo do realms|
|**Restrição:**| Convite válido<br> Conexão estável com a internet |
|**Exceção**| Convite inválido<br> Realms não acessível<br> Realms atingiu limite de usuários |

## Cenário 18

| **Título:** | Criar um realms |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar um servidor realms para multiplayer | 
|**Contexto:** | Multiplayer |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Realms, Assinatura de Minecraft Realms |
|**Episódios:**  | Jogador abre o menu de realms<br> Jogador seleciona a opção de criar realms<br> Jogador define o nome e as configurações do realms<br> Jogador confirma a criação do realms|
|**Restrição:**| Assinatura ativa<br> Conexão estável com a internet |
|**Exceção**| Falha na criação do realms<br> Assinatura expirada |

## Cenário 19

| **Título:** | Utilizar um baú |
| ----------  | -----------------------------  |
|**Objetivo:**|   Armazenar e organizar itens no baú | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Baú |
|**Episódios:**  |  Jogador abre o inventário<br> Jogador coloca o baú no mundo<br> Jogador interage com o baú<br> Jogador arrasta os itens do inventário para o baú<br> Jogador fecha o inventário |
|**Restrição:**| O baú deve estar colocado em um local acessível |
|**Exceção**| Baú cheio<br> Itens não transferidos corretamente |

## Cenário 20

| **Título:** | Criar picareta de ferro |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar uma picareta de ferro para mineração | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Bancada de trabalho, Ferro fundido, Graveto |
|**Episódios:**  | Jogador coleta minério de ferro<br> Jogador funde o minério de ferro em lingotes usando uma fornalha<br> Jogador abre a bancada de trabalho<br> Jogador insere 3 lingotes de ferro e 2 gravetos na bancada de trabalho<br> Jogador coleta a picareta de ferro criada|
|**Restrição:**| O jogador deve ter os materiais necessários |
|**Exceção**| Materiais insuficientes<br> Erro ao colocar os itens na bancada |

## Cenário 21

| **Título:** | Alimentar-se |
| ----------  | -----------------------------  |
|**Objetivo:**|   Recuperar a barra de fome e saúde | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Comida (maçã, pão, carne, etc.) |
|**Episódios:**  |  Jogador seleciona a comida no inventário<br> Jogador come a comida (utilizando o botão de interação)<br> Barra de fome do jogador aumenta, e a saúde começa a se regenerar|
|**Restrição:**| O jogador só pode comer se sua barra de fome não estiver cheia |
|**Exceção**| Jogador tentar comer sem estar com fome<br> Comida insuficiente para restaurar a barra de fome |

## Cenário 22

| **Título:** | Alterar modo de jogo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Alterar o modo de jogo (sobrevivência, criativo, aventura, espectador) | 
|**Contexto:** | Durante o jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Chat |
|**Episódios:**  |  Jogador abre o menu de comandos<br> Jogador digita o comando ```/gamemode``` [modo] (sobrevivência, criativo, aventura, espectador)<br> Jogador confirma a alteração do modo de jogo|
|**Restrição:**| O jogador deve ter permissão de administrador no servidor ou em singleplayer |
|**Exceção**| Comando inválido<br> Permissão insuficiente para alterar o modo de jogo |

## Cenário 23

| **Título:** | Buscar item no modo criativo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Adicionar itens do inventário criativo ao inventário do jogador | 
|**Contexto:** | Jogo no modo criativo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft |
|**Episódios:**  |  Jogador abre o inventário criativo<br> Jogador busca o item desejado, digitando o nome na barra de pesquisa<br> Jogador arrasta o item para o inventário pessoal|
|**Restrição:**| O jogador deve estar no modo criativo |
|**Exceção**| Item não encontrado no inventário criativo |

## Cenário 24

| **Título:** | Usar comando ```/time``` no modo criativo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Alterar o horário no jogo usando o comando ```/time``` | 
|**Contexto:** | Jogo no modo criativo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft |
|**Episódios:**  |  Jogador abre o menu de comandos<br> Jogador digita ```/time set [day/night/noon/midnight]``` ou ```/time set [valor]```<br> O horário do jogo é alterado de acordo com o comando inserido|
|**Restrição:**| O jogador deve estar no modo criativo ou ter permissões de administrador |
|**Exceção**| Comando inválido<br> Permissão insuficiente para usar o comando |

## Cenário 25

| **Título:** | Jogar Build Wars em um servidor |
| ----------  | -----------------------------  |
|**Objetivo:**|   Competir em um minigame de construção (Build Wars) em um servidor | 
|**Contexto:** | Multiplayer, servidores minigame |
|**Atores:** |Jogador, outros jogadores|
|**Recursos:**| Minecraft, servidor Build Wars |
|**Episódios:**  |  Jogador entra em um servidor de minigames<br> Jogador seleciona o modo Build Wars no servidor<br> Jogador recebe um tema para construir<br> Jogador utiliza blocos criativos para construir dentro do tempo limite<br> Votações ocorrem após a conclusão das construções|
|**Restrição:**| Conexão estável com a internet<br> Tempo limitado para construir |
|**Exceção**|  Desconexão durante o jogo<br> Erro no servidor |

## Cenário 26

| **Título:** | Explorar mundo Hardcore |
| ----------  | -----------------------------  |
|**Objetivo:**|   Experimentar a dinâmica do modo de jogo Hardcore | 
|**Contexto:** | Multiplayer ou singleplayer |
|**Atores:** |Jogador |
|**Recursos:**| Minecraft Java Edition |
|**Episódios:**  |  Jogador entra no menu principal<br> Jogador seleciona modo de jogo<br> Jogador seleciona criar mundo<br> Jogador coloca mundo no modo hardcore<br> Jogador entra no mundo<br> Jogador explora o mundo<br> |
|**Restrição:**| Conseguir bons recursos no modo hardcore |
|**Exceção**| Jogo corrompido<br> Ser derrotado e perder mapa hardcore<br> |

## Cenário 27

| **Título:** | Alterar dificuldade do jogo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Alterar a dificuldade do jogo (pacífico, fácil, normal, difícil) | 
|**Contexto:** | Durante o jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft |
|**Episódios:**  |  Jogador abre o menu de configurações<br> Jogador seleciona a opção de alterar a dificuldade<br> Jogador escolhe entre pacífico, fácil, normal ou difícil<br> A dificuldade do jogo é alterada|
|**Restrição:**|Jogador deve ter permissão para alterar a dificuldade |
|**Exceção**| Comando inválido<br> Permissão insuficiente para mudar a dificuldade |

## Cenário 28

| **Título:** | Melhorar um capacete de diamante para netherita |
| ----------  | -----------------------------  |
|**Objetivo:**|   Atualizar um capacete de diamante para netherita | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Mesa de ferraria, Molde de ferraria, Capacete de diamante, Lingote de netherita |
|**Episódios:**  |  Jogador abre a mesa de ferraria<br> Jogador coloca o molde de ferraria, capacete de diamante e o lingote de netherita na mesa de ferraria<br> Capacete de diamante é atualizado para capacete de netherita<br> Jogador confirma atualização colocando o novo capacete no inventário|
|**Restrição:**| Jogador deve ter todos os itens necessários |
|**Exceção**| Materiais insuficientes para a atualização |

## Cenário 29

| **Título:** | Consertar um arco |
| ----------  | -----------------------------  |
|**Objetivo:**|  Consertar um arco quebrado usando uma bigorna ou mesa de trabalho | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Bigorna ou mesa de trabalho, Arcos quebrados ou materiais |
|**Episódios:**  |  Jogador abre a bigorna ou mesa de trabalho<br> Jogador coloca o arco quebrado e outro arco na bigorna ou mesa<br> Jogador confirma a reparação<br> Arco é reparado|
|**Restrição:**| O jogador deve ter um arco quebrado e os materiais necessários|
|**Exceção**| Materiais insuficientes para o reparo<br> Arco não reparável (durabilidade esgotada) |

## Cenário 30

| **Título:** | Obter carne podre |
| ----------  | -----------------------------  |
|**Objetivo:**|   Coletar carne podre de um zumbi | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft |
|**Episódios:**  |  Jogador encontra um zumbi<br> Jogador derrota o zumbi<br> Carne podre é dropada pelo zumbi<br> Jogador coleta a carne podre|
|**Restrição:**| O jogador deve derrotar o zumbi antes que ele desapareça<br> Carne podre só é dropada por zumbis|
|**Exceção**| Carne podre não é dropada (erros no drop)<br> Zumbi desapareceu antes da coleta |

## Cenário 31

| **Título:** | Encantar uma espada |
| ----------  | -----------------------------  |
|**Objetivo:**|   Encantar uma espada para obter propriedades especiais | 
|**Contexto:** | Jogo no modo sobrevivência |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft, Mesa de encantamentos, Espada, Lápis-lazúli |
|**Episódios:**  |  Jogador abre a mesa de encantamentos<br> Jogador coloca a espada e os lápis-lazúli na mesa de encantamentos<br> Jogador seleciona o encantamento desejado<br> Jogador confirma o encantamento<br> Espada é encantada com as propriedades selecionadas|
|**Restrição:**| Jogador deve ter a quantidade necessária de lápis-lazúli e nível de experiência<br> A mesa de encantamentos deve estar em um local apropriado |
|**Exceção**| Encantamento não aplicado (problemas na mesa ou falta de recursos)<br> Espada não encantada conforme o desejado<br> Não possuir experiência o suficiente |
