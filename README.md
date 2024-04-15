# PlayerWebMusic

# MeuApp de Música com Angular

MeuApp de Música é um aplicativo de streaming desenvolvido em Angular, proporcionando uma experiência semelhante a players populares para descobrir e ouvir música online.

## Desafios e Soluções

Durante o desenvolvimento deste aplicativo usando Angular, enfrentamos alguns desafios interessantes:

### Gerenciamento de Estado

- **Desafio:** Gerenciar o estado global da aplicação de forma eficiente, especialmente ao lidar com a reprodução de música e a sincronização entre diferentes componentes.
  
- **Solução:** Utilizamos o padrão Redux com o NgRx para gerenciamento de estado. Isso nos permitiu ter um único estado global para controlar a reprodução, listas de reprodução e preferências do usuário.

### Integração com API de Música

- **Desafio:** Consumir e integrar uma API de música externa para obter dados de músicas, artistas e listas de reprodução.
  
- **Solução:** Criamos serviços Angular para encapsular chamadas HTTP à API de música. Utilizamos interceptadores HTTP para tratar erros e realizar pré-processamento de dados.

### Reprodução de Áudio Contínua

- **Desafio:** Implementar um player de áudio que permitisse a reprodução contínua de músicas, com controles de reprodução (play, pause, avançar, retroceder).
  
- **Solução:** Implementamos um componente de player personalizado que se comunicava com o estado global para controlar a reprodução.

### Performance e Otimizações

- **Desafio:** Garantir uma boa performance e otimização do aplicativo, especialmente ao lidar com grandes quantidades de dados de músicas e imagens.
  
- **Solução:** Implementamos estratégias de lazy loading de módulos e pré-carregamento seletivo de dados. Otimizamos o tamanho das imagens e cache de recursos estáticos para melhorar o desempenho.

## Tecnologias Utilizadas

- **Angular:** Framework principal para o desenvolvimento do front-end.
  
- **NgRx:** Gerenciamento de estado com Redux para Angular.
    
- **API de Música:** Integração com [[API utilizada]](https://developer.spotify.com/documentation/web-api) para obter dados de música.

## Licença

Este projeto está licenciado sob a [Licença]. Projeto feito de forma acadêmica, não é recomendado o uso. Consulte o arquivo `LICENSE` para obter mais detalhes.
<div align="center">
  <h4>Área de login,</h4>
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229435121027907655/image.png?ex=662fabae&is=661d36ae&hm=01cdf3b861927493f5effdcc6d3fb5bd3c4b33856241d45e6ce8233dd50298f2&" width="620">
</div>
<div align="center">
  <h4>Aréa de bibliotecas, com inteface intuitiva,</h4>
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229429365280997427/image.png?ex=662fa652&is=661d3152&hm=c5456272102d9760536d847a9e561bc9cc310b7177cb5e35580bc9646a6a3a98&" width="620">
</div>
<div align="center">
  <h4>Player suave e fluido com design minimalista!!</h4>
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229434921999798392/image.png?ex=662fab7f&is=661d367f&hm=a1b45ee8dd8e4af29fa8c2831977f59beac02e2374dc57cb0ce68b56a9d9271e&" width="620">
</div>

