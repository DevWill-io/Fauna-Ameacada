# Fauna Ameaçada

## Tema
Animais brasileiros em extinção. O projeto aborda a riqueza da biodiversidade brasileira, as principais ameaças que colocam diversas espécies em risco e a importância da preservação ambiental.

## Integrantes
- Williams
- Aparecida
- Joaquim
- Kamile

## Descrição
O site é um projeto acadêmico focado em conscientizar sobre a preservação da fauna brasileira. Ele apresenta informações sobre espécies ameaçadas, dados populacionais, status de conservação, curiosidades e dicas de como a população pode ajudar a proteger o meio ambiente.

## Páginas
- `index.html`: Apresentação geral do tema e chamada para as outras páginas.
- `sobre.html`: Explicação principal sobre a fauna ameaçada e suas causas.
- `galeria.html`: Imagens, cartões e informações sobre 8 animais em risco.
- `curiosidades.html`: Fatos curiosos, ameaças específicas de cada espécie e dicas práticas.
- `componentes.html`: Página extra apresentando os integrantes do grupo e suas funções.

## Divisão de tarefas
- Williams: `galeria.html` (e CSS da galeria) + `componentes.html` (e CSS dos componentes)
- Aparecida: `index.html` (e CSS da página inicial)
- Joaquim: `sobre.html` (e CSS da página sobre)
- Kamile: `curiosidades.html` (e CSS da página de curiosidades)

## Uso do Flexbox
O Flexbox foi aplicado de forma estrutural em todo o site, garantindo a responsividade e o alinhamento dos elementos. As principais propriedades utilizadas foram:
- **`display: flex`**: Aplicado no `body` (para fixar o footer no fundo), no cabeçalho (`.site-header`), no menu de navegação (`.menu ul`), nas seções hero (`.hero`), nas grades de cartões (`.cards`), na galeria (`.galeria`) e no rodapé.
- **`justify-content` e `align-items`**: Usados no cabeçalho para separar a logo do menu (`space-between`) e alinhar os itens ao centro (`center`), além de centralizar o conteúdo das seções e do rodapé.
- **`flex-wrap`**: Usado no menu de navegação, nos cartões e na galeria para permitir que os itens quebrem de linha em telas menores.
- **`gap`**: Aplicado em quase todos os contêineres flexíveis para criar um espaçamento uniforme entre os itens (ex: 12px no menu, 20px nos cards e galeria).
- **Contêineres e itens flexíveis**: Os contêineres são as tags `header`, `nav`, `section` e o `body`. Os itens flexíveis são os links do menu (`<li>`), os cartões (`<article>`), as imagens e os textos.

## Uso de IA
O grupo utilizou IA para auxiliar nas ideias e em alguns tópicos de pesquisa e desenvolvimento de conteúdo.
