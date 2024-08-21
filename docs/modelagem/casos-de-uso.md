# Casos de uso

<script src="https://kit.fontawesome.com/c221e013ed.js" crossorigin="anonymous"></script>

**Histórico de Revisão**

| Data   | Versão  | Descrição | Autor(es)|
| --- | --- | --- | --- |
| 18/08/2024 | 0.1 | Criação do documento inicial com diagrama e tabelas da especificação suplementar| Carlos Eduardo |
| 19/08/2024 | 0.2 | Linkagens com os termos do [léxico](lexico.md) | Carlos Eduardo |
| 20/08/2024 | 0.3 | Adição do diagrama de criação de [mundos](lexico.md#l05-overworld) e [realms](lexico.md#l45-realms) | Carlos Eduardo |

## Introdução
Este documento contém a especificação dos casos de uso, onde o principal objetivo é detalhar as interações entre os [usuários](lexico.md#l42-usuario) e o sistema, uma das melhores formas para a elicitação dos requisitos funcionais.

## Diagramas dos Casos de Uso
### Caso de uso geral
![Casos de uso](../assets/imgs/Caso%20de%20uso.jpg)
<p style="text-align: center"> <i class="fa-solid fa-circle-info"></i> Versão 1 - Autor: Carlos Eduardo</p>

### Criação de [mundos](lexico.md#l05-overworld) e [realms](lexico.md#l45-realms)
![Casos de uso](../assets/imgs/criar_mundo.jpg)
<p style="text-align: center"> <i class="fa-solid fa-circle-info"></i> Versão 1 - Autor: Carlos Eduardo</p>

## Especificação do caso de uso


### UC01 [Criar mundo](../modelagem/lexico.md#l25-criar-mundo)
| [Criar mundo](../modelagem/lexico.md#l25-criar-mundo) | |
|---|---|	
|**Descrição:**|Criar um novo [mundo](lexico.md/#l05-overworld) no Minecraft. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar no menu principal do jogo. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu "[Criar Mundo](../modelagem/lexico.md#l25-criar-mundo)". <br> 2. [Usuário](lexico.md#l42-usuario) configura as opções desejadas para o [mundo](lexico.md/#l05-overworld) (nome, tipo de [mundo](lexico.md/#l05-overworld), etc.). <br> 3. [Usuário](lexico.md#l42-usuario) confirma a criação do [mundo](lexico.md/#l05-overworld). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide cancelar a criação do [mundo](lexico.md/#l05-overworld) antes de confirmar. <br> 2. [Usuário](lexico.md#l42-usuario) retorna ao menu principal. |
|**Fluxo de Exceção:**| 1. Ocorre um erro durante a criação do [mundo](lexico.md/#l05-overworld). <br> 2. [Usuário](lexico.md#l42-usuario) recebe uma mensagem de erro e é redirecionado ao menu principal. |
|**Pós-condições:**| Um novo [mundo](lexico.md/#l05-overworld) é criado e carregado para o [usuário](lexico.md#l42-usuario) [explorar](lexico.md/#l21-exploracao). |

### UC02 Selecionar modo de jogo e dificuldade
| Selecionar modo de jogo e dificuldade | |
|---|---|	
|**Descrição:**|Selecionar o modo de jogo e a dificuldade para o [mundo](lexico.md/#l05-overworld). |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar no menu de criação ou edição de um [mundo](lexico.md/#l05-overworld). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa as configurações de modo de jogo e dificuldade. <br> 2. [Usuário](lexico.md#l42-usuario) seleciona o modo de jogo desejado ([Sobrevivência](lexico.md/#l09-sobrevivencia), [Criativo](lexico.md/#l07-criativo), [Aventura](lexico.md/#l08-aventura), [Espectador](lexico.md/#l06-espectador), [Hardcore](lexico.md/#l10-hardcore)). <br> 3. [Usuário](lexico.md#l42-usuario) escolhe o nível de dificuldade (Fácil, Médio, Difícil...). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide manter as configurações padrão. |
|**Fluxo de Exceção:**| 1. Erro ao salvar as configurações. <br> 2. [Usuário](lexico.md#l42-usuario) é notificado e tenta novamente. |
|**Pós-condições:**| Configurações de modo de jogo e dificuldade aplicadas ao [mundo](lexico.md/#l05-overworld). |

### UC03 Carregar [mundo](lexico.md/#l05-overworld)
| Carregar [mundo](lexico.md/#l05-overworld) | |
|---|---|	
|**Descrição:**|Carregar um [mundo](lexico.md/#l05-overworld) existente. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar no menu principal do jogo. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa a lista de [mundo](lexico.md/#l05-overworld)s salvos. <br> 2. [Usuário](lexico.md#l42-usuario) seleciona o [mundo](lexico.md/#l05-overworld) desejado. <br> 3. [Mundo](lexico.md/#l05-overworld) é carregado e o [jogador](lexico.md#l42-usuario) pode jogar. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não carregar nenhum [mundo](lexico.md/#l05-overworld) e retorna ao menu principal. |
|**Fluxo de Exceção:**| 1. Ocorre um erro ao carregar o [mundo](lexico.md/#l05-overworld). <br> 2. [Usuário](lexico.md#l42-usuario) é notificado e redirecionado ao menu principal. |
|**Pós-condições:**| [Mundo](lexico.md/#l05-overworld) existente é carregado para o [jogador](lexico.md#l42-usuario). |

### UC04 [Explorar](lexico.md/#l21-exploracao) [mundo](lexico.md/#l05-overworld)
| [Explorar](lexico.md/#l21-exploracao) [mundo](lexico.md/#l05-overworld) | |
|---|---|	
|**Descrição:**|[Explorar](lexico.md/#l21-exploracao) o [mundo](lexico.md/#l05-overworld) do Minecraft. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Mundo](lexico.md/#l05-overworld) deve estar carregado e pronto para [exploração](lexico.md/#l21-exploracao). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) move o personagem pelo [mundo](lexico.md/#l05-overworld). <br> 2. [Usuário](lexico.md#l42-usuario) interage com o ambiente. <br> 3. [Usuário](lexico.md#l42-usuario) coleta [recursos](lexico.md/#l31-recursos) ou enfrenta inimigos. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide construir ou modificar o ambiente durante a [exploração](lexico.md/#l21-exploracao). |
|**Fluxo de Exceção:**| 1. Ocorre um erro no jogo durante a [exploração](lexico.md/#l21-exploracao). <br> 2. [Usuário](lexico.md#l42-usuario) é notificado e o jogo pode reiniciar. |
|**Pós-condições:**| O [mundo](lexico.md/#l05-overworld) é explorado. |

### UC05 Combater inimigos
| Combater inimigos | |
|---|---|	
|**Descrição:**|Combater inimigos no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar em modo de [sobrevivência](lexico.md/#l09-sobrevivencia) ou similar. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) encontra inimigos durante a [exploração](lexico.md/#l21-exploracao). <br> 2. [Usuário](lexico.md#l42-usuario) usa armas ou [ferramentas](lexico.md/#l18-ferramentas) para atacar os inimigos. <br> 3. Inimigos são derrotados ou o [jogador](lexico.md#l42-usuario) é derrotado. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide evitar o combate e foge ou se esconde dos inimigos. |
|**Fluxo de Exceção:**| 1. Jogo trava durante o combate. <br> 2. O jogo é reiniciado. |
|**Pós-condições:**| Inimigos derrotados ou [jogador](lexico.md#l42-usuario) recomeça após a derrota. |

### UC06 Proteger território
| Proteger território | |
|---|---|	
|**Descrição:**|Proteger o território no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve ter estabelecido uma base ou local de interesse. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) constrói defesas ao redor do território. <br> 2. [Usuário](lexico.md#l42-usuario) protege o território de ataques inimigos. <br> 3. Território permanece seguro ou é invadido. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide abandonar o território e mudar para um novo local. |
|**Fluxo de Exceção:**| 1. Defesas falham e território é invadido. <br> 2. [Usuário](lexico.md#l42-usuario) deve reconstruir sua base ou procurar outro local. |
|**Pós-condições:**| Território protegido, abandonado ou há a necessidade de reconstrução. |

### UC07 Construir [blocos](lexico.md#l44-blocos)
| Construir [blocos](lexico.md#l44-blocos) | |
|---|---|	
|**Descrição:**|Construir [blocos](lexico.md#l44-blocos) no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve possuir [blocos](lexico.md#l44-blocos) no [inventário](lexico.md#l43-inventario). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) seleciona os [blocos](lexico.md#l44-blocos) no [inventário](lexico.md#l43-inventario). <br> 2. [Usuário](lexico.md#l42-usuario) posiciona os [blocos](lexico.md#l44-blocos) no [mundo](lexico.md/#l05-overworld) conforme desejado. <br> 3. Construção é realizada. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não construir o [bloco](lexico.md#l44-blocos). |
|**Fluxo de Exceção:**| 1. Ocorre um erro ao posicionar os [blocos](lexico.md#l44-blocos). <br> 2. [Usuário](lexico.md#l42-usuario) tenta novamente ou usa outro tipo de [bloco](lexico.md#l44-blocos). |
|**Pós-condições:**| [Blocos](lexico.md#l44-blocos) construídos. |

### UC08 Quebrar [blocos](lexico.md#l44-blocos)
| Quebrar [blocos](lexico.md#l44-blocos) | |
|---|---|	
|**Descrição:**|Quebrar [blocos](lexico.md#l44-blocos) no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar equipado com uma ferramenta ou à mão livre. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) seleciona o [bloco](lexico.md#l44-blocos) que deseja quebrar. <br> 2. [Usuário](lexico.md#l42-usuario) utiliza a ferramenta adequada ou à mão livre para quebrar o [bloco](lexico.md#l44-blocos). <br> 3. [Bloco](lexico.md#l44-blocos) é quebrado e, se for possível, coletado para o [inventário](lexico.md#l43-inventario). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não coletar o [bloco](lexico.md#l44-blocos) quebrado e o deixa no chão. |
|**Fluxo de Exceção:**| 1. [Bloco](lexico.md#l44-blocos) não pode ser quebrado por estar protegido ou ser indestrutível. <br> 2. [Usuário](lexico.md#l42-usuario) desiste de quebrar o [bloco](lexico.md#l44-blocos) ou procura outra ferramenta. |
|**Pós-condições:**| [Bloco](lexico.md#l44-blocos) é quebrado ou permanece intacto. |

### UC09 Coletar [recursos](lexico.md/#l31-recursos)
| Coletar [recursos](lexico.md/#l31-recursos) | |
|---|---|	
|**Descrição:**|Coletar [recursos](lexico.md/#l31-recursos) no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| [Usuário](lexico.md#l42-usuario) deve [explorar](lexico.md/#l21-exploracao) o [mundo](lexico.md/#l05-overworld). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) encontra [recursos](lexico.md/#l31-recursos) durante a [exploração](lexico.md/#l21-exploracao). <br> 2. [Usuário](lexico.md#l42-usuario) utiliza [ferramentas](lexico.md/#l18-ferramentas) ou à mão livre para coletar os [recursos](lexico.md/#l31-recursos). <br> 3. [Recursos](lexico.md/#l31-recursos) são adicionados ao [inventário](lexico.md#l43-inventario). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não coletar os [recursos](lexico.md/#l31-recursos) e continua a [exploração](lexico.md/#l21-exploracao). |
|**Fluxo de Exceção:**| 1. [Recursos](lexico.md/#l31-recursos) são destruídos acidentalmente durante a coleta. <br> 2. [Usuário](lexico.md#l42-usuario) procura por mais [recursos](lexico.md/#l31-recursos) no [mundo](lexico.md/#l05-overworld). |
|**Pós-condições:**| [Recursos](lexico.md/#l31-recursos) coletados e armazenados no [inventário](lexico.md#l43-inventario). |

### UC10 Adicionar e gerenciar amigos
| Adicionar e gerenciar amigos | |
|---|---|	
|**Descrição:**|Adicionar e gerenciar amigos no jogo. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve estar conectado a uma rede e ter uma conta microsoft. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa a lista de amigos. <br> 2. [Usuário](lexico.md#l42-usuario) adiciona novos amigos ou gerencia os existentes. <br> 3. Amizades são atualizadas junto ao [servidor](lexico.md#l14-servidores) do jogo. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide remover ou bloquear um amigo da lista. |
|**Fluxo de Exceção:**| 1. Erro ao atualizar a lista de amigos. <br> 2. [Usuário](lexico.md#l42-usuario) tenta novamente ou entra em contato com o suporte. |
|**Pós-condições:**| Amigos adicionados ou lista de amigos gerenciada. |

### UC11 [Criar](lexico.md/#l11-craft) [Itens](lexico.md/#l32-itens)
| [Criar](lexico.md/#l11-craft) [Itens](lexico.md/#l32-itens) | |
|---|---|	
|**Descrição:**|[Criar](lexico.md/#l11-craft) [itens](lexico.md/#l32-itens) no jogo usando [recursos](lexico.md/#l31-recursos) coletados. |
|**Ator(es):**|[Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**|[Usuário](lexico.md#l42-usuario) deve possuir os [recursos](lexico.md/#l31-recursos) necessários no [inventário](lexico.md#l43-inventario). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa a mesa de trabalho ou o menu de criação. <br> 2. [Usuário](lexico.md#l42-usuario) seleciona o item a ser criado. <br> 3. Item é criado e adicionado ao [inventário](lexico.md#l43-inventario). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não [criar](lexico.md/#l11-craft) o item e fecha o menu de criação. |
|**Fluxo de Exceção:**| 1. [Recursos](lexico.md/#l31-recursos) insuficientes para [criar](lexico.md/#l11-craft) o item. <br> 2. [Usuário](lexico.md#l42-usuario) coleta mais [recursos](lexico.md/#l31-recursos) e tenta novamente. |
|**Pós-condições:**| Item criado e adicionado ao [inventário](lexico.md#l43-inventario) do [usuário](lexico.md#l42-usuario). |

### UC12 Jogar no modo [multiplayer](lexico.md/#l41-multiplayer)
| Jogar no modo [multiplayer](lexico.md/#l41-multiplayer) | |
|---|---|	
|**Descrição:**| Jogar no modo [multiplayer](lexico.md/#l41-multiplayer) com outros [usuários](lexico.md#l42-usuario). |
|**Ator(es):**| [Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| [Usuário](lexico.md#l42-usuario) deve estar conectado à internet e ter uma conta no Minecraft. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu [multiplayer](lexico.md/#l41-multiplayer). <br> 2. [Usuário](lexico.md#l42-usuario) escolhe um [servidor](lexico.md#l14-servidores) ou insere o IP de um [servidor](lexico.md#l14-servidores) específico. <br> 3. [Usuário](lexico.md#l42-usuario) conecta-se ao [servidor](lexico.md#l14-servidores) e começa a jogar com outros [jogadores](lexico.md#l42-usuario). |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide jogar em modo singleplayer e retorna ao menu principal. |
|**Fluxo de Exceção:**| 1. Erro de conexão com o [servidor](lexico.md#l14-servidores). <br> 2. [Usuário](lexico.md#l42-usuario) tenta conectar novamente ou escolhe outro [servidor](lexico.md#l14-servidores). |
|**Pós-condições:**| [Usuário](lexico.md#l42-usuario) conectado ao [servidor](lexico.md#l14-servidores) e jogando com outros [jogadores](lexico.md#l42-usuario). |

### UC13 Entrar ou criar conta
| Entrar ou criar conta | |
|---|---|	
|**Descrição:**| Entrar ou criar uma conta no Minecraft. |
|**Ator(es):**| [Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| [Usuário](lexico.md#l42-usuario) deve ter acesso à internet. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu de login. <br> 2. [Usuário](lexico.md#l42-usuario) acessa a página de login da microsoft e insere as credenciais ou cria uma nova conta. <br> 3. [Usuário](lexico.md#l42-usuario) é autenticado e pode acessar o jogo. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide jogar sem se conectar a sua conta |
|**Fluxo de Exceção:**| 1. Erro ao criar ou entrar na conta. <br> 2. [Usuário](lexico.md#l42-usuario) verifica as credenciais e tenta novamente. |
|**Pós-condições:**| [Usuário](lexico.md#l42-usuario) autenticado. |

### UC14 Conectar ou adicionar um [servidor](lexico.md/#l14-servidores)
| Conectar ou adicionar um [servidor](lexico.md#l14-servidores) | |
|---|---|	
|**Descrição:**| Conectar-se a um [servidor](lexico.md/#l14-servidores) existente ou adicionar um novo. |
|**Ator(es):**| [Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| [Usuário](lexico.md#l42-usuario) deve estar conectado à internet. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu de [servidores](lexico.md/#l14-servidores). <br> 2. [Usuário](lexico.md#l42-usuario) seleciona um [servidor](lexico.md/#l14-servidores) existente ou insere o IP de um novo [servidor](lexico.md/#l14-servidores). <br> 3. [Usuário](lexico.md#l42-usuario) conecta-se ao [servidor](lexico.md/#l14-servidores) escolhido. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não se conectar a nenhum [servidor](lexico.md/#l14-servidores) e retorna ao menu principal. |
|**Fluxo de Exceção:**| 1. Erro ao conectar-se ao [servidor](lexico.md/#l14-servidores). <br> 2. [Usuário](lexico.md#l42-usuario) tenta novamente ou escolhe outro [servidor](lexico.md/#l14-servidores). |
|**Pós-condições:**| [Usuário](lexico.md#l42-usuario) conectado ao [servidor](lexico.md/#l14-servidores). |

### UC15 Sair do jogo
| Sair do jogo | |
|---|---|	
|**Descrição:**| Sair do jogo e retornar ao sistema operacional. |
|**Ator(es):**| [Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| Jogo deve estar em execução. |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu de pausa ou o principal. <br> 2. [Usuário](lexico.md#l42-usuario) seleciona a opção de sair do jogo. <br> 3. Jogo é fechado e [usuário](lexico.md#l42-usuario) retorna ao SO. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide continuar jogando e fecha o menu. |
|**Fluxo de Exceção:**| 1. Jogo trava ao tentar sair. <br> 2. [Usuário](lexico.md#l42-usuario) força o fechamento do jogo via sistema operacional. |
|**Pós-condições:**| Jogo fechado e retorno ao sistema operacional. |

### UC16 Salvar [mundo](lexico.md/#l05-overworld)
| Salvar [mundo](lexico.md/#l05-overworld) | |
|---|---|	
|**Descrição:**| Salvar o progresso do [mundo](lexico.md/#l05-overworld) em que está jogando. |
|**Ator(es):**| [Usuário](lexico.md#l42-usuario) |
|**Pré-Requisitos:**| [Usuário](lexico.md#l42-usuario) deve estar jogando em um [mundo](lexico.md/#l05-overworld). |
|**Fluxo Principal:**| 1. [Usuário](lexico.md#l42-usuario) acessa o menu de pausa. <br> 2. [Usuário](lexico.md#l42-usuario) seleciona a opção de salvar. <br> 3. Progresso do [mundo](lexico.md/#l05-overworld) é salvo. |
|**Fluxo Alternativo:**| 1. [Usuário](lexico.md#l42-usuario) decide não salvar e continua jogando. |
|**Fluxo de Exceção:**| 1. Erro ao salvar o [mundo](lexico.md/#l05-overworld). <br> 2. [Usuário](lexico.md#l42-usuario) tenta novamente ou verifica espaço disponível. |
|**Pós-condições:**| [mundo](lexico.md/#l05-overworld) salvo e progresso garantido. |

### UC17 Configurações gerais
| Configurações gerais | |
|---|---|
| **Descrição:** | Permite ao [jogador](lexico.md#l42-usuario) ajustar configurações gerais do mundo, como modo de jogo e dificuldade. |
| **Ator(es):** | [Jogador](lexico.md#l42-usuario) |
| **Pré-Requisitos:** | O [jogador](lexico.md#l42-usuario) deve estar na tela de configuração do mundo. |
| **Fluxo Principal:** | 1. O [jogador](lexico.md#l42-usuario) acessa a seção de configurações gerais.<br>2. O [jogador](lexico.md#l42-usuario) ajusta as opções de modo de jogo e dificuldade.<br>3. O [jogador](lexico.md#l42-usuario) confirma as configurações e prossegue para a próxima etapa. |
| **Fluxo Alternativo:** | 1. O [jogador](lexico.md#l42-usuario) decide manter as configurações padrão.<br>2. O [jogador](lexico.md#l42-usuario) confirma as configurações e prossegue para a próxima etapa. |
| **Fluxo de Exceção:** | 1. Falha ao aplicar as configurações.<br>2. O jogo solicita que o [jogador](lexico.md#l42-usuario) ajuste as configurações novamente. |
| **Pós-condições:** | As configurações gerais são aplicadas e o [jogador](lexico.md#l42-usuario) pode continuar a configuração do mundo. |

### UC18 Criar no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms)
| Criar no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms) | |
|---|---|
| **Descrição:** | Permite ao [jogador](lexico.md#l42-usuario) criar um mundo no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms). |
| **Ator(es):** | [Jogador](lexico.md#l42-usuario) |
| **Pré-Requisitos:** | O [jogador](lexico.md#l42-usuario) deve estar logado em sua conta da Microsoft e ter uma assinatura ativa do [Realms](lexico.md#l45-realms). |
| **Fluxo Principal:** | 1. O [jogador](lexico.md#l42-usuario) seleciona a opção para criar no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms).<br>2. O [jogador](lexico.md#l42-usuario) escolhe um nome e configuracões para o [Realms](lexico.md#l45-realms).<br>3. O [jogador](lexico.md#l42-usuario) confirma e o mundo é criado no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms). |
| **Fluxo Alternativo:** | 1. O [jogador](lexico.md#l42-usuario) decide criar o mundo localmente em vez de usar o [Realms](lexico.md#l45-realms).<br>2. O [jogador](lexico.md#l42-usuario) retorna à opção de criação de mundo local. |
| **Fluxo de Exceção:** | 1. Falha ao conectar ao [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms).<br>2. O jogo notifica o [jogador](lexico.md#l42-usuario) e permite tentar novamente ou retornar ao menu principal. |
| **Pós-condições:** | O mundo é criado no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms) e fica disponível para o [jogador](lexico.md#l42-usuario) e seus amigos convidados. |

### UC19 Selecionar grupamento
| Selecionar grupamento | |
|---|---|
| **Descrição:** | Permite ao [jogador](lexico.md#l42-usuario) escolher a quantidade de [jogadores](lexico.md#l42-usuario) que poderão jogar simultaneamente no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms) (2 ou 10). |
| **Ator(es):** | [Jogador](lexico.md#l42-usuario) |
| **Pré-Requisitos:** | O [jogador](lexico.md#l42-usuario) deve estar na etapa de criação no [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms). |
| **Fluxo Principal:** | 1. O [jogador](lexico.md#l42-usuario) acessa a opção de seleção de grupamento.<br>2. O [jogador](lexico.md#l42-usuario) escolhe entre as opções de 2 ou 10 [jogadores](lexico.md#l42-usuario).<br>3. O [jogador](lexico.md#l42-usuario) confirma a escolha e prossegue com a criação. |
| **Fluxo Alternativo:** | 1. O [jogador](lexico.md#l42-usuario) é direcionado à escolha padrão ou retorna à tela anterior. |
| **Fluxo de Exceção:** | 1. O [jogador](lexico.md#l42-usuario) encontra problemas ao selecionar o grupamento.<br>2. O jogo notifica o [jogador](lexico.md#l42-usuario) para tentar novamente ou escolher outra opção. |
| **Pós-condições:** | O grupamento é selecionado, permitindo a criação do mundo com o número especificado de [jogadores](lexico.md#l42-usuario) simultâneos. |

### UC20 Selecionar nome do [realm](lexico.md#l45-realms)
| Selecionar nome do [realm](lexico.md#l45-realms) | |
|---|---|
| **Descrição:** | Permite ao [jogador](lexico.md#l42-usuario) escolher o nome do [Realm](lexico.md#l45-realms) onde o mundo será criado. |
| **Ator(es):** | [Jogador](lexico.md#l42-usuario) |
| **Pré-Requisitos:** | O [jogador](lexico.md#l42-usuario) deve estar na etapa de criação do mundo no [Realms](lexico.md#l45-realms). O [jogador](lexico.md#l42-usuario) deve estar conectado à internet. |
| **Fluxo Principal:** | 1. O [jogador](lexico.md#l42-usuario) acessa a opção para nomear o [Realm](lexico.md#l45-realms).<br>2. O [jogador](lexico.md#l42-usuario) digita o nome desejado.<br>3. O [jogador](lexico.md#l42-usuario) confirma o nome e prossegue com a criação do mundo. |
| **Fluxo Alternativo:** | 1. O [jogador](lexico.md#l42-usuario) decide utilizar um nome sugerido automaticamente pelo jogo.<br>2. O [jogador](lexico.md#l42-usuario) confirma o nome sugerido e prossegue. |
| **Fluxo de Exceção:** | 1. O nome escolhido já está em uso ou é inválido.<br>2. O jogo solicita que o [jogador](lexico.md#l42-usuario) escolha outro nome. |
| **Pós-condições:** | O nome do [Realm](lexico.md#l45-realms) é registrado e o [jogador](lexico.md#l42-usuario) pode continuar com a criação do mundo. |

### UC21 Aceitar termos e condições [realms](lexico.md#l45-realms)
| Aceitar termos e condições [realms](lexico.md#l45-realms) | |
|---|---|
| **Descrição:** | Requer que o [jogador](lexico.md#l42-usuario) aceite os termos e condições para utilizar o [servidor](lexico.md#l14-servidores) [Realms](lexico.md#l45-realms). |
| **Ator(es):** | [Jogador](lexico.md#l42-usuario) |
| **Pré-Requisitos:** | O [jogador](lexico.md#l42-usuario) deve estar na etapa de criação do mundo no [Realms](lexico.md#l45-realms). O [jogador](lexico.md#l42-usuario) deve estar conectado à internet. |
| **Fluxo Principal:** | 1. O [jogador](lexico.md#l42-usuario) é apresentado aos termos e condições.<br>2. O [jogador](lexico.md#l42-usuario) lê e aceita os termos e condições.<br>3. O [jogador](lexico.md#l42-usuario) prossegue com a criação do [servidor](lexico.md#l14-servidores) [realms](lexico.md#l45-realms). |
| **Fluxo Alternativo:** | 1. O [jogador](lexico.md#l42-usuario) decide não aceitar os termos e condições.<br>2. O [jogador](lexico.md#l42-usuario) é impedido de prosseguir com a criação do mundo no [Realms](lexico.md#l45-realms). |
| **Fluxo de Exceção:** | 1. Falha ao registrar a aceitação dos termos e condições.<br>2. O jogo solicita que o [jogador](lexico.md#l42-usuario) tente aceitar os termos novamente. |
| **Pós-condições:** | Os termos e condições são aceitos e o [jogador](lexico.md#l42-usuario) pode continuar a criação do mundo no [Realms](lexico.md#l45-realms). |
