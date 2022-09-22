
# Teste FrontEnd Jr - Ignis Digital

O teste consiste na reprodução de um protótipo utilizando
o framework Nextjs.

A aplicação consiste em um aplicativo de listagem de filmes, 
com login e paginação.

Que pode ser acessada nesta url:
https://www.figma.com/file/auVNLJhsiVs7wPvonfRhPe/Ignis---teste-entrevista?node-id=0%3A1

Todos os dados devem ser consumidos da api que está hospedada no endereço: https://teste.ignisdigital.tec.br/

Cujo a documentação pode ser encontrada em: 
https://app.swaggerhub.com/apis/Ignis-Digital/ignis-teste/1.0.0

##  Informações sobre o teste

- Seu login e senha, está no e-mail que foi enviado juntamente com este teste
- Deve ser enviado para o e-mail contato@ignisdigital.tec.br o link do repositório no github contendo o código e instruções de como rodar.
- É obrigatório que todas as telas sejam desenvolvidas.
- Caso tenha dificuldade em realizar algum detalhe ou desenvolver alguma funcionalidade. É permitido entregar sem ela, mas acarretará na perda de pontos.

### Detalhes sobre o projeto
- Na tela de Listagem de filmes, ao clicar em um filme específico deve ser exibido os seus detalhes.
- Na listagem de filmes a imagem a ser exibida para cada card, é obtida através da propriedade "poster_path", porém ao clicar para ver mais detalhes, deve ser exibida a imagem da propriedade backdrop_path
- Caso o filme não possua imagem, deve ser exibida uma imagem de placeholder a sua escolha.
- Ao clicar para visualizar um filme, sua caixa deve ser expandida para ocupar mais colunas (conforme protótipo), e a listagem de filmes deve continuar imediatamente abaixo


### Requisitos Obrigatórios
- Desenvolver todas as telas
- Realizar a autenticação no projeto, de forma que ao reiniciar a página ou fecha-la e abri-la novamente a sessão seja mantida.
- Realizar busca de filmes
- Adicionar mais filmes a listagem através do botão ver mais
- Subir o projeto no github com um readme.md, explicando como fazer para roda-lo
- Utilizar Styled-components para a estilização do projeto

### Diferenciais
- Utilizar alguma estratégia de Cache
- Utilizar Cookies para salvar o token de autenticação
- Desenvolver a partir da sua criatividade a versão responsiva para desktop
- Realizar o deploy da aplicação em alguma plataforma de hospedagem como Vercel ou Netlify
- Ter todos os detalhes de layout aplicados de acordo com o protótipo
- Colocar animações nas transições de tela e exibição de componentes


# Boa Sorte!