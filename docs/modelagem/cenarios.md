# Cenários

## Histórico de Versões

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 30/07/2024 |  0.1   | Criação de Cenários | [Samara Letícia](https://github.com/samarawwleticia)|
| 01/08/2024 | 0.2 | Revisão | Danilo Melo |

### Cenário 01

| **Título:** | Dinâmica do Minecraft [survival](../modelagem/lexico.md#l09-sobrevivencia) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Descrever o início do Minecraft| 
|**Contexto:** | Início de Jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  |  Jogador [cria mundo](../modelagem/lexico.md#l25-criar-mundo)<br> Jogador escolhe modo de jogo [sobrevivência](../modelagem/lexico.md#l09-sobrevivencia)<br> Jogador escolhe dificuldade do jogo (pacífico, fácil, normal ou difícil)<br> Jogador nomeia o mundo<br> Jogador entra no mundo ([overworld](../modelagem/lexico.md#l05-overworld)) |
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

### Cenário 04

| **Título:** | Derrotar o Ender Dragon |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar o Ender Dragon e completar o jogo | 
|**Contexto:** | Final do jogo |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, armas, armaduras, poções|
|**Episódios:**  |  Jogador encontra a fortaleza do End<br> Jogador ativa o portal do End<br> Jogador vai ao End<br> Jogador destrói cristais do End<br> Jogador ataca o Dragão até derrotá-lo |
|**Restrição:**| Ter todos os itens necessários para o combate |
|**Exceção**| Launcher não carregar o [End](../modelagem/lexico.md#l04-end)<br> Cair no vazio<br> Não localizar a fortaleza<br> Ser morto pelo Ender Dragon |                

### Cenário 05

| **Título:** | Derrotar o Warden |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar o Warden no subterrâneo | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, armadura, armas|
|**Episódios:**  | Jogador encontra cidade ancestral<br> Jogador atrai o Warden com vibrações<br> Jogador ataca o Warden com estratégia à distância e corpo-a-corpo |
|**Restrição:**| Ter todos os itens necessários para o combate |
|**Exceção**| Jogador é derrotado pelo Warden<br> Jogador perde todos os itens durante a batalha<br> Jogador não consegue encontrar Cidade Ancestral|

### Cenário 06

| **Título:** | Chocar um Ovo de Farejador |
| ----------  | -----------------------------  |
|**Objetivo:**|   Obter um Farejador | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, pincel|
|**Episódios:**  | Jogador encontra ruínas<br> Jogador utiliza pincel nos blocos para tentar obter Ovo de Farejador<br> Jogador coloca ovo de farejador sobre bloco de terra ou musgo<br> Farejador sai do ovo depois de um determinado tempo |
|**Restrição:**| Ter todos os itens necessários para crafitar um pincel<br> Achar Ovo de Farejador com facilidade |
|**Exceção**| Jogador não consegue localizar uma ruína<br> Jogador não consegue encontrar Ovo de Farejador |

### Cenário 07

| **Título:** | Derrotar um Mob Simples (Zumbi, Esqueleto, Creeper) |
| ----------  | -----------------------------  |
|**Objetivo:**|   Derrotar um mob simples | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  | Jogador espera anoitecer<br> Jogador encontra mob<br> Jogador ataca mob até derrotá-lo |
|**Restrição:**| Utilizar armas e armadura forte |
|**Exceção**| Jogador é derrotado pelo Mob<br> Jogador perde todos os itens durante a batalha |

### Cenário 08

| **Título:** | Fazer uma Farm de Pedra |
| ----------  | -----------------------------  |
|**Objetivo:**|   Criar uma Farm automática de pedra | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, lava, água, redstone |
|**Episódios:**  | Jogador coleta materiais<br> Jogador utiliza materiais para construir a farm de pedra<br> Jogador coleta as pedras |
|**Restrição:**| Boa construção e otimização |
|**Exceção**| Não conseguir encontrar lava<br> Não utilizar corretamente a redstone<br> Farm falhar ao produzir pedra |

### Cenário 09

| **Título:** | Crafitar uma Cama |
| ----------  | -----------------------------  |
|**Objetivo:**|   Construir uma cama no minecraft utilizando a mesa de construção | 
|**Contexto:** | Jogo Inicial |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, mesa de construção|
|**Episódios:**  | Jogador encontra ovelhas<br> Jogador obtem lã de ovelhas<br> Jogador obtém madeira de qualquer árvore<br> Jogador transforma madeira bruta em tábua de madeira<br> Jogador utiliza mesa de construção para construir cama utilizando as lãs e as tábuas de madeira |
|**Restrição:**| Obter todos os itens necessários |
|**Exceção**| Jogador não encontra lãs da mesma coloração<br> Jogador não encontra ovelhas<br> Jogador não obtem recursos suficientes |

### Cenário 10

| **Título:** | Reproduzir Villagers |
| ----------  | -----------------------------  |
|**Objetivo:**|   Reproduzir villagers no jogo | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, comida, camas|
|**Episódios:**  | Jogador encontra vila<br> Jogador posiciona cama perto dos villagers<br> Jogador coloca dá comida a 2 villagers<br> Villagers se reproduzem |
|**Restrição:**| Villagers disponíveis, espaço suficiente |
|**Exceção**| Villagers não se reproduzem |

### Cenário 11

| **Título:** | Voar com Elytra |
| ----------  | -----------------------------  |
|**Objetivo:**| Voar utilizando a Elytra | 
|**Contexto:** | Jogo Avançado |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, Elytra|
|**Episódios:**  | Jogador crafita foguetes<br> Jogador equipa a Elytra<br> Jogador aciona foguete enquanto o segura  |
|**Restrição:**| Durabilidade da Elytra e número de foguetes |
|**Exceção**| Elytra quebra durante o jogo<br> Não obtém os recursos necessários para crafitar foguetes |

### Cenário 12

| **Título:** | Domar um Lobo |
| ----------  | -----------------------------  |
|**Objetivo:**|   Domar um lobo no minecraft | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher, ossos |
|**Episódios:**  | Jogador encontra Lobo<br> Jogador alimenta Lobo com ossos<br> Lobo é domado pelo Jogador |
|**Restrição:**| Ter ossos suficientes |
|**Exceção**| Lobo não é domado<br> Jogador não encontra um Lobo |

### Cenário 13

| **Título:** | Encontrar um tesouro escondido |
| ----------  | -----------------------------  |
|**Objetivo:**|   Encontrar um tesouro no minecraft | 
|**Contexto:** | Jogo Normal |
|**Atores:** |Jogador|
|**Recursos:**| Minecraft Launcher|
|**Episódios:**  | Jogador encontra Naufrágio<br> Jogador obtém mapa do tesouro<br> Jogador procura o tesouro utilizando o mapa<br> Jogador obtém tesouro escondido |
|**Restrição:**| Encontrar um mapa do tesouro<br> Encontrar um naufrágio<br> Localização precisa |
|**Exceção**| Naufrágio não produz mapa do tesouro<br> Jogador não consegue localizar o tesouro|