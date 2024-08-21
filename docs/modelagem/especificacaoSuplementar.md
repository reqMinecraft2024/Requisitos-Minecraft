# Especificações Suplementares

**Histórico de Revisão**

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 20/08/2024 |  0.1   | Criação das Especificações | [Samara Letícia](https://github.com/samarawwleticia)|

# Introdução

A especificação suplementar garante que todos os requisitos do sistema, incluindo aqueles relacionados à qualidade e desempenho, sejam devidamente considerados.

### 1. **Desempenho**
- **Taxa de Quadros (FPS)**: O jogo deve manter uma taxa mínima de 30 FPS em dispositivos que atendam às especificações recomendadas.
- **Uso de Memória**: O jogo pede no mínimo 4GB de RAM para uma experiência agradável em dispositivos com as configurações mínimas.

### 2. **Requisitos de Segurança**
- **Autenticação**: Todos os jogadores devem autenticar-se através de uma conta Microsoft para acessar [servidores](../modelagem/lexico.md#l14-servidores) online.
- **Criptografia**: As comunicações entre o cliente e o servidor devem ser criptografadas utilizando TLS 1.2 ou superior.
- **Proteção contra Exploits**: Medidas devem ser implementadas para proteger o jogo contra exploits conhecidos, como manipulação de pacotes ou modding não autorizado.

### 3. **Requisitos de Usabilidade**
- **Interface do Usuário**: A interface deve ser responsiva e adaptável a diferentes resoluções de tela, incluindo dispositivos móveis.
- **Acessibilidade**: O jogo deve incluir opções de acessibilidade, como suporte a leitores de tela e modos de alto contraste.
- **Documentação**: Deve haver documentação clara e acessível para novos jogadores explicando as funcionalidades básicas do jogo.

### 4. **Requisitos de Compatibilidade**
- **Compatibilidade Multiplataforma**: O jogo deve ser compatível com Windows, Xbox, PlayStation, Nintendo Switch, iOS e Android.
- **Suporte a Versionamento**: Deve ser possível jogar em servidores que suportam múltiplas versões do jogo, ou pelo menos a versão mais recente.

### 5. **Requisitos de Manutenção**
- **Atualizações**: O jogo deve permitir atualizações regulares sem a necessidade de reinstalação completa.
- **Backup de Dados**: O jogo deve permitir a realização de backups automáticos dos dados dos jogadores.
