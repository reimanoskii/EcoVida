# EcoVida
# trabalho desenvolvido pelos aluno - Afonso - Eduarda - Gustavo Miranda.

Pagina sobre sustentabilidade no dia a dia, desenvolvida para a atividade de Bootstrap da disciplina de Front-end.

## Objetivo

Mostrar como pequenas atitudes, como reciclar e economizar água e energia, ajudam a preservar o meio ambiente. O projeto utiliza um dos temas da Agenda 2030 sugeridos no pelo professor.

## Tecnologias utilizadas

- HTML5: estrutura e conteúdo da página.
- CSS3: cores, bordas e apresentação das imagens.
- Bootstrap 5.3.3: componentes e organização responsiva.

## Organização da página

- **Início:** apresentação do EcoVida e do tema sustentabilidade.
- **Dicas:** três cards sobre reciclagem, economia de água e economia de energia.
- **Cadastro:** formulário com nome e e-mail.
- **Rodapé:** identificação do projeto.

## Componentes do Bootstrap

A página utiliza navbar, cards, formulário e botão. O menu recolhível usa o JavaScript do Bootstrap, importado no final do HTML.

A organização responsiva utiliza `container`, `row` e `col-md-4`. Os cards ficam lado a lado a partir de 768 px e empilhados em telas menores. As imagens utilizam `img-fluid`, e a barra de navegação recolhe o menu em telas menores que 992 px.

## Arquivos do projeto

- `index.html`: conteúdo, navegação, componentes e formulário.
- `style.css`: personalização visual.
- `README.md`: explicação do projeto e instruções de uso.

## Como executar

1. Baixe os arquivos do projeto.
2. Mantenha `index.html` e `style.css` na mesma pasta.
3. Abra o arquivo `index.html` no navegador.

É necessário acesso à internet para carregar o Bootstrap pelo CDN e as imagens hospedadas no Unsplash. Não é necessário instalar Node.js.

## Como testar

1. Abra a página e confira se as cores, imagens e cards aparecem.
2. Clique em Início, Dicas e Cadastro para verificar a navegação entre as seções.
3. Reduza a largura da janela: os cards devem ficar empilhados e o botão do menu deve aparecer.
4. Clique no botão do menu para abrir e fechar as opções.
5. Clique em Cadastrar com os campos vazios: o navegador deve solicitar o preenchimento.
6. Preencha o nome e informe um e-mail inválido, como `teste`: o navegador deve impedir o envio.
7. Informe um e-mail válido, como `teste@example.com`: os campos devem passar pela validação.

### Limitação do formulário

O formulário é demonstrativo. Ele utiliza a validação nativa do HTML (`required` e `type="email"`), mas não salva dados nem envia e-mails. Como não há configuração de envio, a submissão utiliza o comportamento padrão do navegador: navega para a própria página com os campos na URL. Utilize dados fictícios nos testes.


