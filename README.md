![image](https://github.com/RaphaelCarvalh/PlayerWebMusic/assets/162733267/c242727c-45ab-4719-aa77-4b734a220b1c)# PlayerWebMusic

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
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229429240538337290/image.png?ex=66719134&is=66703fb4&hm=7eec855cc85b52c31de24c5d0c569f481e86e0aa200f649e75963bb4280973a0&" width="620">
</div>
<div align="center">
  <h4>Aréa de bibliotecas, com inteface intuitiva,</h4>
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229429365280997427/image.png?ex=66719152&is=66703fd2&hm=c9afdc4d4dcfea4795cca0b65a6e4096a696f57bae8cff5f71e786a709c423bf&" width="620">
</div>
<div align="center">
  <h4>Player suave e fluido com design minimalista!!</h4>
  <img src="https://cdn.discordapp.com/attachments/1177172733554065428/1229434921999798392/image.png?ex=6671967f&is=667044ff&hm=4b0ea0aea406dc56d66f0c8e2a8d8c06a440f07be2f4c56e05b7e8541f74ae56&" width="620">
</div>

