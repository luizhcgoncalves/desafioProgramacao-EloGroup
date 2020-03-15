# desafioProgramacao-EloGroup
Desafio de Programação para EloGroup feito por Luiz Henrique Carneiro Gonçalves (goncalves.luizhc@gmail.com)

## Frameworks e bibliotecas
Para a construção desse projeto foram utilizados os seguintes recursos:
- Bootstrap v3.4.1: este recurso disponibilizou recursos para formatação e ajustes de layout da página desenvolvida, implementando os elementos da página com formatação simplificada, porém eficaz e já eficiente para visualização em dispositivos móveis, além de prover recursos para validação do formulário.
- JQuery: utilizei tanto o jquery.min, que já traz a possibilidade de aplicar o JQuery na página, como também o jquery.mask, que facilitou a aplicação de máscara no número de telefone para que ficasse visualmente mais agradável durante a inserção dos dados no formulário.

## Hierarquia de arquivos
Para simplificar a visualização, análise e teste, os arquivos foram mantidos centralizados em um só: index.php. Fontes externas constam como link para a fonte.

## GUPY
Luiz Henrique Carneiro Gonçalves

## Padrão de nomes e ids
Para facilitar a leitura e compreensão do código, o código foi dividido nas seguintes seções:
* Nome
* Telefone
* Canal (Como nos conheceu)
* Outros canais (especificação quando o usuário selecionar a opção "Outros")
* Redes Sociais
* Lista de Redes Sociais

Em cada seção, o padrão de nomenclatura seguiu a seguinte regra:
- Nomes: n_<seção>
- Ids de inputs: f_<seção>
- Divisórias: d_<seção>
- Textos de ajuda: a_<seção>
- Glyphicons de validação: g_<seção>

## Arquivo util.js e AJAX
Optei por manter tudo em um local só a fim de que o código fosse facilmente lido e analizado.

JQuery foi utilizado ao mínimo, e o AJAX foi dispensado. Para uma página com conteúdo pequeno, considerei desnecessário sobrecarregar a página com funções ativas o tempo todo, sendo preferida a performance.
