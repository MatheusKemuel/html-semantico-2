Café Aurora — Projeto de HTML Semântico e CSS

O Café Aurora é um site fictício de uma cafeteria e restaurante, desenvolvido para demonstrar o uso prático das principais tags semânticas do HTML5. A página contém cabeçalho e navegação, apresentação do estabelecimento, história do café, horários de funcionamento, cardápio semanal, perguntas frequentes, formulário de reserva, informações de contato e rodapé.

Tags e elementos utilizados

<!-- <!DOCTYPE html> -->

A declaração ``<!DOCTYPE html>` informa ao navegador que o documento utiliza o padrão HTML5. Ela evita que a página seja interpretada em modos antigos de compatibilidade e ajuda a manter uma renderização consistente entre navegadores.

`<header>`

O `<header>` representa o cabeçalho principal do site e foi usado para agrupar a identidade visual do Café Aurora e a navegação. Essa separação facilita a manutenção e permite que tecnologias assistivas reconheçam rapidamente o início da página.

`<nav>`

A tag `<nav>` identifica um conjunto importante de links de navegação. No projeto, ela contém uma lista com links para Início, Sobre, Cardápio e Reservas, permitindo que usuários e leitores de tela naveguem diretamente entre as principais seções.

`<main>`

O `<main>` envolve o conteúdo principal e exclusivo da página, deixando de fora o cabeçalho e o rodapé. Ele ajuda leitores de tela a saltarem diretamente para o conteúdo mais importante e facilita a identificação do assunto central pelos mecanismos de busca.

`<section>`

A tag `<section>` divide a página em blocos temáticos, como apresentação, história, cardápio, perguntas frequentes e reservas. Cada seção reúne conteúdos relacionados, tornando a estrutura mais organizada, compreensível e fácil de manter.

`<article>`

O `<article>` representa uma composição com conteúdo próprio e compreensível dentro da página. Ele foi utilizado para agrupar a apresentação do café, a história do estabelecimento e o conteúdo relacionado à reserva.

`<aside>`

A tag `<aside>` representa informações complementares ao conteúdo principal ao redor. No site, ela foi utilizada nos blocos de horários e localização, que acrescentam informações úteis sem fazer parte do texto principal da história ou do cardápio.

`<footer>`

O `<footer>` representa o rodapé da página e contém a identidade do café, um link para voltar ao início e as informações de direitos autorais. Essa tag permite que navegadores e tecnologias assistivas reconheçam semanticamente o encerramento do documento.

`<h1>`, `<h2>` e `<h3>`

Os títulos organizam o conteúdo em uma hierarquia lógica. O `<h1>` identifica o tema principal da página, os elementos `<h2>` apresentam as grandes seções e os elementos `<h3>` identificam subtópicos, como horários e dados da reserva; essa ordem melhora a leitura, a navegação por leitores de tela e a compreensão do conteúdo por mecanismos de busca.

`<p>`

A tag `<p>` representa um parágrafo e foi usada nos textos de apresentação, história, horários, confirmação e contato. Seu uso separa corretamente os blocos textuais e torna o conteúdo mais legível e previsível.

`<strong>`

O `<strong>` indica que uma parte do texto possui forte importância semântica. Ele foi aplicado ao nome “Café Aurora” no texto sobre a história, destacando uma informação relevante também para leitores de tela, e não apenas visualmente.

`<em>`

A tag `<em>` atribui ênfase semântica a uma palavra ou trecho. No projeto, ela enfatiza a característica “acolhedor”, ajudando a transmitir a intenção da frase e podendo alterar a entonação usada por leitores de tela.

`<figure>`

O `<figure>` agrupa conteúdos autocontidos, como a logo e as fotografias do café. Na seção sobre o estabelecimento, ele relaciona semanticamente a imagem da fachada com sua respectiva legenda.

`<figcaption>`

A tag `<figcaption>` fornece uma legenda ligada diretamente ao conteúdo de um <figure>. Ela foi usada para explicar que a fotografia mostra a fachada onde a história do Café Aurora começou, oferecendo contexto adicional para todos os usuários.

`<img>` e o atributo alt

A tag `<img>` insere as imagens da logo, da apresentação e da fachada. O atributo alt descreve o conteúdo ou a função das imagens para pessoas que não conseguem visualizá-las, além de ser exibido quando o arquivo não pode ser carregado.

`<time datetime="">`

O `<time>` representa uma data ou horário de forma semanticamente identificável. O atributo datetime="2026-09-12T19:00" fornece uma versão padronizada da data do próximo evento, permitindo que navegadores, buscadores e ferramentas de calendário interpretem essa informação corretamente.

`<address>`

A tag `<address>` agrupa informações de contato relacionadas ao Café Aurora. Ela foi utilizada para reunir endereço, telefone, e-mail e rede social, facilitando a identificação desses dados por tecnologias assistivas e mecanismos de busca.

`<table>`

A tag `<table>` organiza dados que possuem relação entre linhas e colunas. No cardápio semanal, ela permite comparar de maneira clara o nome de cada item, sua descrição e seu preço.

`<caption>`

O `<caption>` define o título ou a descrição geral de uma tabela. Ele informa que os dados apresentados correspondem aos pratos disponíveis e seus respectivos preços, ajudando principalmente usuários de leitores de tela a compreenderem a finalidade da tabela antes de percorrê-la.

`<thead>`

A tag `<thead>` agrupa o cabeçalho da tabela. No cardápio, ela contém os títulos “Item”, “Descrição” e “Preço”, estabelecendo o significado das colunas e melhorando a leitura dos dados.

`<tbody>`
O `<tbody>` reúne as linhas principais de dados da tabela. Ele foi utilizado para organizar os pratos, as descrições e os preços do cardápio, separando o conteúdo do cabeçalho e do rodapé.

`<tfoot>`

A tag `<tfoot>` representa o rodapé da tabela e deve conter um resumo ou uma informação final sobre os dados apresentados. No cardápio, ela pode ser usada para informar a quantidade de itens disponíveis ou uma observação geral sobre preços e disponibilidade.

`<details>`

O `<details>` cria um componente interativo nativo que pode ser aberto e fechado sem JavaScript. Ele foi utilizado na seção de perguntas frequentes para esconder inicialmente as respostas e manter a página mais compacta e organizada.

`<summary>`

A tag `<summary>` fornece o título clicável de um elemento `<details>`. Cada pergunta da seção de dúvidas funciona como um resumo que informa ao usuário qual resposta será exibida ao abrir o conteúdo.

`<mark>`

O `<mark>` indica um trecho relevante ou destacado no contexto atual. Ele foi utilizado nos preços do cardápio para chamar a atenção do usuário para uma informação importante sem depender apenas de uma classe visual.

`<abbr title="">`

A tag `<abbr>` representa uma abreviação ou sigla. No projeto, ela identifica a sigla ABIC, enquanto o atributo title="Associação Brasileira da Indústria de Café" disponibiliza seu significado completo ao usuário.

`<form>`

O `<form>` representa uma área destinada à coleta e ao envio de dados do usuário. No Café Aurora, ele reúne as informações necessárias para solicitar uma reserva, como nome, e-mail, telefone, data, horário e quantidade de pessoas.

`<fieldset>`

O `<fieldset>` agrupa campos relacionados dentro de um formulário. Ele foi usado para reunir os campos pertencentes à reserva, melhorando a organização visual e semântica do formulário.

`<legend>`

A tag `<legend>` fornece um título acessível para o grupo de campos de um <fieldset>. No formulário, ela deve identificar o conjunto como “Dados da reserva”, permitindo que usuários de leitores de tela entendam a relação entre os campos.

`<input>`

O `<input>` cria campos para entrada de diferentes tipos de dados. Foram utilizados tipos como text, email, date, time e number, permitindo que o navegador ofereça validações e controles adequados para cada informação.

`<dialog>`

O `<dialog>` representa uma caixa de diálogo ou janela modal. No projeto, ele mostra a mensagem de confirmação da reserva; sua exibição foi demonstrada com CSS e o seletor :target, embora o comportamento modal nativo completo dependa do método JavaScript showModal().




Acessibilidade e atributos ARIA

aria-label="Navegação principal"

O atributo foi aplicado ao `<nav>` para fornecer um nome acessível à região de navegação. Assim, usuários de leitores de tela conseguem diferenciar essa área de outras possíveis navegações da página.

aria-describedby="descricao-cardapio"

O atributo relaciona a tabela a um texto explicativo identificado por id="descricao-cardapio". Essa associação oferece uma descrição adicional do cardápio antes de o leitor de tela percorrer suas linhas e colunas.

aria-label="Fechar mensagem"

O atributo foi aplicado ao controle de fechamento do diálogo para descrever claramente sua função. Isso evita que o leitor de tela anuncie apenas um símbolo ou um texto pouco informativo e ajuda o usuário a entender que a ação fechará a mensagem.

aria-labelledby e aria-describedby no diálogo

O dialog pode usar aria-labelledby para se associar ao título “Reserva recebida!” e aria-describedby para se associar ao texto de confirmação. Essas relações fornecem contexto imediato quando a janela recebe foco e tornam sua finalidade mais clara para usuários de tecnologias assistivas.