# Respostas das atividades

## Atividade 1
**Resposta:** O arquivo `index.html` é responsável pela estruturação semântica e hierárquica do conteúdo da página web, enquanto o arquivo `style.css` é responsável pela estilização visual, apresentação e layout. Essa divisão aplica o princípio de separação de responsabilidades (estrutura vs. apresentação), facilitando a manutenção, escalabilidade e legibilidade do código.

## Atividade 2
**Resposta:** A declaração `<!DOCTYPE html>` informa ao navegador que o documento em questão deve ser interpretado de acordo com a especificação do HTML5. Sua presença ativa o modo padrão de renderização (*Standards Mode*), evitando que o navegador entre em modo de compatibilidade (*Quirks Mode*), o qual gera inconsistências visuais e comportamentais.

## Atividade 3
**Resposta:** A tag `<html>` representa o elemento raiz (*root*) de toda a árvore DOM de um documento HTML. O atributo `lang="pt-BR"` define que o idioma principal do documento é o Português do Brasil, o que é fundamental para a correta pronúncia por tecnologias assistivas (leitores de tela), funcionamento de corretores ortográficos e otimização para motores de busca (SEO).

## Atividade 4
**Resposta:** A tag `<head>` armazena os metadados, links para recursos externos e configurações gerais da página que não são renderizados diretamente no corpo visível do documento. A tag `<meta charset="UTF-8">` especifica o conjunto de caracteres Unicode UTF-8, garantindo que acentos, caracteres especiais e símbolos da língua portuguesa sejam exibidos corretamente sem corrupção de texto.

## Atividade 5
**Resposta:** A tag `<title>` define o título do documento HTML. Ele é exibido na aba ou na barra de título do navegador, é utilizado ao salvar a página nos favoritos (*bookmarks*) e serve como o título principal exibido nas páginas de resultados dos motores de busca (SERPs).

## Atividade 6
**Resposta:** A tag `<link rel="stylesheet" href="style.css">` é utilizada no `<head>` para importar e conectar uma folha de estilos CSS externa ao documento HTML. O atributo `rel="stylesheet"` especifica a relação do arquivo importado como folha de estilo, e o atributo `href` indica o caminho relativo ou absoluto para o arquivo `.css`.

## Atividade 7
**Resposta:** A tag `<body>` contém todo o conteúdo visível da página web (textos, imagens, tabelas, formulários, menus). A aplicação da regra CSS `font-family: Arial, sans-serif;` no seletor `body` define a tipografia padrão para todo o documento, aplicando o conceito de herança CSS para que todos os elementos filhos adotem essa fonte.

## Atividade 8
**Resposta:** A tag `<nav>` é um elemento semântico do HTML5 destinado especificamente a agrupar blocos de navegação e menus contendo links essenciais para outras páginas ou para seções internas do próprio site, auxiliando na compreensão da estrutura da página por leitores de tela e robôs de busca.

## Atividade 9
**Resposta:** Os links âncora internos utilizam a tag `<a>` com o atributo `href` referenciando um identificador antecedido por cerquilha (ex: `href="#inicio"`, `href="#sobre"`, `href="#contato"`). Ao serem clicados, o navegador desloca a barra de rolagem diretamente até a posição do elemento cujo atributo `id` seja correspondente.

## Atividade 10
**Resposta:** A tag `<main>` delimita o bloco de conteúdo principal e exclusivo da página web. Deve existir apenas uma tag `<main>` visível por documento, excluindo conteúdos que se repetem em várias páginas (como barras de navegação globais, cabeçalhos de topo e rodapés), sendo essencial para a acessibilidade e navegação via teclado por leitores de tela.

## Atividade 11
**Resposta:** A tag `<h1>` representa o cabeçalho de nível 1, ou seja, o título hierárquico mais importante da página, devendo resumir o tema principal do documento. No CSS, as propriedades `color: #003366;` e `text-align: center;` definem sua cor em azul-escuro e alinham o texto no centro horizontal do elemento.

## Atividade 12
**Resposta:** A tag `<p>` é usada para estruturar parágrafos de texto no HTML. O uso de uma classe personalizada, como `.destaque`, permite aplicar regras de estilo reutilizáveis a elementos específicos — tais como `font-size: 18px;` (aumento no tamanho da fonte) e `font-weight: bold;` (texto em negrito) — sem alterar globalmente todas as outras tags de parágrafo da página.

## Atividade 13
**Resposta:** A tag `<section>` agrupa conteúdos semanticamente relacionados em seções temáticas autônomas do documento. O atributo `id` (como `id="sobre"` e `id="contato"`) confere um identificador exclusivo a cada seção, permitindo aplicar estilizações específicas via CSS (seletor `#id`) e viabilizar a navegação por links âncora.

## Atividade 14
**Resposta:** As tags `<h2>` e `<h3>` definem subtítulos de segundo e terceiro nível na hierarquia do documento, organizando o conteúdo em tópicos e subtópicos lógicos. No CSS, a regra `h2, h3 { color: #006400; }` utiliza um seletor agrupado para padronizar a cor verde-escuro em ambos os níveis de subtítulo de forma concisa.

## Atividade 15
**Resposta:** A tag `<img>` é utilizada para inserir imagens na página através do atributo `src`, que indica o caminho do arquivo. O atributo `alt` fornece uma descrição textual alternativa da imagem, indispensável para garantir a acessibilidade de pessoas com deficiência visual (por meio de leitores de tela), além de ser exibido caso a imagem não carregue e auxiliar na indexação em mecanismos de busca.

## Atividade 16
**Resposta:** A tag `<figure>` é um elemento semântico que encapsula um conteúdo ilustrativo autônomo (como imagens, diagramas, ilustrações ou códigos), e a tag `<figcaption>` fornece a legenda explicativa ou título diretamente vinculado a esse conteúdo dentro da mesma figura.

## Atividade 17
**Resposta:** Os links externos utilizam a tag `<a>` com o atributo `href` apontando para uma URL absoluta completa (como `https://developer.mozilla.org/pt-BR/docs/Web/HTML`). Eles direcionam o usuário para páginas ou domínios fora da aplicação web atual.

## Atividade 18
**Resposta:** Os links internos utilizam a tag `<a>` com caminhos relativos (como `contato.html` ou `index.html`) para conectar diferentes páginas pertencentes ao mesmo projeto ou estrutura de diretórios local, permitindo a navegação contínua entre os arquivos do site.

## Atividade 19
**Resposta:** Uma tabela em HTML5 é estruturada através da tag `<table>`. O bloco `<thead>` agrupa o cabeçalho da tabela contendo a linha `<tr>` com as células de título `<th>` (renderizadas por padrão em negrito e centralizadas). O bloco `<tbody>` agrupa o corpo da tabela contendo as linhas de dados `<tr>` preenchidas pelas células de dados `<td>`.

## Atividade 20
**Resposta:** No CSS para tabelas, `width: 100%;` faz com que a tabela preencha 100% da largura do seu elemento pai; `border-collapse: collapse;` une as bordas adjacentes das células em uma linha única e contínua, eliminando o espaçamento duplo padrão do navegador; `border: 1px solid #cccccc;` adiciona um contorno sólido; e `padding: 10px;` em `<th>` e `<td>` insere espaçamento interno para melhorar a legibilidade dos dados.

## Atividade 21
**Resposta:** O link com esquema `mailto:` (ex: `href="mailto:contato@exemplo.com"`) utiliza o manipulador de protocolo padrão do sistema operacional para acionar automaticamente o cliente de e-mail do usuário (como Thunderbird, Outlook ou Apple Mail), pré-preenchendo o campo de destinatário com o endereço informado.

## Atividade 22
**Resposta:** A tag `<footer>` define a seção de rodapé de um documento ou seção. É semanticamente adequada para abrigar informações de direitos autorais, créditos, autoria, links para políticas de privacidade, termos de uso e dados institucionais complementares.

## Atividade 23
**Resposta:** A propriedade CSS `float: left;` remove o elemento do fluxo normal e o posiciona à esquerda, permitindo que textos e elementos adjacentes fluam em torno dele pelo lado direito. A propriedade `margin-right: 20px;` adiciona um espaçamento à direita da imagem, impedindo que o texto adjacente fique encostado na borda da figura.

## Atividade 24
**Resposta:** A propriedade `padding` define o espaçamento interno do elemento (a distância entre o conteúdo e a sua própria borda), como aplicado em `<main>`, `<nav>`, `<th>` e `<td>`. Já a propriedade `margin` define o espaçamento externo (a distância entre a borda do elemento e os elementos vizinhos ao seu redor), como a margem vertical (`margin: 20px 0;`) aplicada nas seções `<section>`.

## Atividade 25
**Resposta:** Os seletores CSS determinam quais elementos receberão as regras de estilo:
1. **Seletor de Tipo/Tag** (ex: `body`, `h1`, `table`): seleciona todos os elementos daquela tag no documento.
2. **Seletor de Classe** (ex: `.destaque`): indicado pelo ponto (`.`), seleciona qualquer elemento que possua a classe informada, permitindo reutilização em múltiplos elementos.
3. **Seletor de ID** (ex: `#sobre`, `#contato`): indicado pela cerquilha (`#`), possui maior especificidade e seleciona um único elemento com o identificador correspondente.

## Atividade 26
**Resposta:** Na estilização de menus de navegação (`<nav>`), o `background-color: #003366;` cria uma barra de destaque com cor de fundo, o `padding: 15px;` gera espaçamento interno, o `color: #ffffff;` nos links (`<a>`) proporciona alto contraste e legibilidade, e o `text-decoration: none;` remove o sublinhado padrão dos hiperlinks para conferir um aspecto visual moderno de botões ou itens de menu.

## Atividade 27
**Resposta:** As boas práticas de desenvolvimento em HTML5 e CSS3 envolvem o uso de tags semânticas apropriadas (melhorando acessibilidade para leitores de tela e otimização para SEO), correta estruturação hierárquica de títulos (`<h1>` a `<h6>`), separação estrita entre conteúdo/estrutura (HTML) e apresentação (CSS), validação de código nos padrões da W3C, código limpo e indentado, e garantia de contraste adequado de cores.
