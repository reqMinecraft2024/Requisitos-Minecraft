# Observação dos Requisitos não funcionais 

**Histórico de Revisão**

| Data       | Versão | Descrição            | Autor(es)                                    |
| ---------- | ------ | -------------------- | -------------------------------------------- |
| 21/08/2024 | 0.1    | Criação do documento | Carlos Eduardo |
| 08/09/2024 | 0.2    | Atualizando a tabela | Danilo Melo |

## Introdução
Abaixo estão reunidos os requisitos que foram observados no minecraft a respeito da qualidade do sistema, como desempenho, segurança e usabilidade. Estes requisitos ajudam a garantir que o jogo ofereça uma experiência de usuário satisfatória. 

## Requisitos Elicitados
| **Categoria**     | **Código** | **Requisito**  |
|-------------------|------------|----------------|
| **Desempenho**    | RNF1       | O jogo deve ter um tempo de resposta rápido para ações dos [jogadores](../modelagem/lexico.md#l42-usuario), como movimentação e interação com [blocos](../modelagem/lexico.md#l44-blocos). |
|  **Desempenho**                 | RNF2       | O jogo deve minimizar a latência de rede para garantir uma experiência de jogo suave em modos [multiplayer](../modelagem/lexico.md#l41-multiplayer). |
|   **Desempenho**                | RNF3       | O [chat](../modelagem/lexico.md#l23-chat) deve funcionar de forma fluida e sem atrasos perceptíveis. |
|  **Desempenho**                 | RNF4       | Deve haver opções para ajustar a qualidade gráfica, incluindo resolução, distância de renderização e efeitos visuais. |
| **Segurança**     | RNF5       | O jogo deve ter mecanismos para proteger as contas dos [jogadores](../modelagem/lexico.md#l42-usuario) contra acessos não autorizados. |
| **Usabilidade**   | RNF6       | A interface do [usuário](../modelagem/lexico.md#l42-usuario) deve ser intuitiva e fácil de navegar. |
|  **Usabilidade**                  | RNF7       | O jogo deve fornecer feedback visual e auditivo claro para as ações dos [jogadores](../modelagem/lexico.md#l42-usuario). |
|    **Usabilidade**                | RNF8       | O [jogador](../modelagem/lexico.md#l42-usuario) deve ser capaz de personalizar atalhos de teclado e controles. |
|      **Usabilidade**              | RNF9       | O jogo deve incluir um sistema de ajuda relevante durante a gameplay. |
| **Compatibilidade**| RNF10      | O jogo deve ser compatível com diferentes plataformas como PC, consoles e dispositivos móveis. |
|    **Compatibilidade**               | RNF11      | Deve haver suporte para diferentes resoluções e configurações de gráficos. |
|  **Compatibilidade**                 | RNF12      | O jogo deve oferecer suporte a [mods](../modelagem/lexico.md#l16-mods) e plugins em diferentes plataformas. |
| **Requisitos Adicionais** | RNF13  | O jogo deve suportar múltiplos idiomas. |
|   **Requisitos Adicionais**                | RNF14      | O jogo deve permitir a personalização de [skins](../modelagem/lexico.md#l15-skins) e pacotes de textura. |
|    **Requisitos Adicionais**               | RNF15      | O menu de pausa deve ser acessível durante o jogo e deve permitir que os [jogadores](../modelagem/lexico.md#l42-usuario) acessem as configurações ou saiam do jogo facilmente. |
|     **Requisitos Adicionais**              | RNF16      | O jogo deve permitir que os [jogadores](../modelagem/lexico.md#l42-usuario) personalizem os controles de entrada de acordo com suas preferências. |
|      **Requisitos Adicionais**             | RNF17      | O jogo deve permitir aos [jogadores](../modelagem/lexico.md#l42-usuario) ajustar o volume do som e da música separadamente. |
|     **Requisitos Adicionais**              | RNF18      | O jogo deve ter um sistema de salvamento automático para evitar perda de progresso. |