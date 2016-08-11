:: Linhas gerais de uso
=======================

A grande maioria dos Arquivos, por limitação de recursos, têm que
estabelecer prioridades nas suas tarefas. Alguns adotam procedimentos
que, embora não sejam os mais adequados, permitem obter alguns
resultados a curto prazo. Embora o GISA seja flexível a práticas
tradicionalmente usadas pelos Arquivos, apresentam-se neste manual os
procedimentos mais adequados, de modo a tirar o máximo partido das
potencialidades oferecidas pelo software, ficando ao cargo de cada
serviço de Arquivo que via tomar. Na impossibilidade de adotar a via
mais adequada, aconselha-se sempre que possível a uma situação de
compromisso. Não sendo possível tratar todos os documentos existentes,
selecionam-se os mais pertinentes ou consultados com maior frequência,
pelo seu valor histórico, social, cultural ou jurídico.

Antes de arrancar, e principalmente se vão ser vários colaboradores a
usar a aplicação, é aconselhável que seja feito um planeamento das
tarefas as serem efetuadas no GISA. Há algumas tarefas que só podem ser
executadas após a execução de outras, há também algumas que poderão ser
feitas em simultâneo e é crucial a distribuição das responsabilidades de
acesso e utilização, por parte dos utilizadores, em função das tarefas
atribuídas a cada um.

Definição de utilizadores e perfis de utilização
------------------------------------------------

A primeira tarefa a fazer no GISA (desde que não seja monoposto) é criar
utilizadores, grupos de utilizadores e definir permissões por módulos.
Para um maior detalhe consultar `Utilizadores </docs/utilizadores>`__ ou
`Grupos de utilizadores </docs/grupos_utilizadores>`__.

Existem valores de `permissões por omissão </docs/permissoes_omissao>`__
atribuídas pelo sistema, que poderão a qualquer momento ser alterados
por um utilizador. Contudo, para que o resultado da atribuição de
permissões seja o esperado, será necessário ter um conhecimento
detalhado do `cálculo de permissões </docs/permissoes_calculo>`__.

O restante tipo de `permissões por plano de
classificação </docs/permissoes_plano>`__ e `permissões por objeto
digital </docs/permissoes_od>`__, deverá ser gerido à medida do
necessário. As `permissões por módulo </docs/permissoes_modulo>`__
também podem ser alteradas num painel específico.

Para uma melhor compreensão do mecanismo das permissões consultar
`exemplos de atribuição de permissões </docs/permissoes_exemplos>`__.

Construção do plano de classificação
------------------------------------

Teoricamente, o passo a seguir, deverá ser a construção de um `plano de
classificação </docs/introducao#plano_de_classificacao>`__, seguindo a
abordagem do GISA. Em caso de dificuldade, pode somente criar-se o nível
orgânico de topo, onde ficarão todas as estruturas documentais, e
futuramente, criar-se a estrutura orgânica, movendo as estruturas
documentais previamente criadas para as entidades produtoras adequadas.

Para a construção de um plano de classificação no GISA, seguindo um
quadro orgânico-funcional, pode seguir-se o seguinte procedimento:

   - Criar uma *entidade detentora* e, opcionalmente, grupos de arquivos.
   Mais informação em `Entidade
   Detentora </docs/descricao_ui#entidade_detentora>`__ e `Grupo de
   arquivos </docs/descricao_ui#grupo_de_arquivos>`__.

   - Criar a *estrutura orgânica*, debaixo de uma entidade detentora ou de
   um grupo de arquivo e para isso:

      + Criar uma entidade produtora no módulo *Controlo de
      autoridade/Entidade produtora*. Mais informação em `Criar uma
      entidade
      produtora </docs/entidade_produtora#criar_uma_entidade_produtora>`__.

      + Definir essa entidade produtora como o *nível de topo* da
      estrutura orgânica. Mais informação em `Definir nível de
      topo </docs/descricao_ui#definir_nivel_de_topo>`__.

      + Criar o resto das entidades produtoras (`Criar uma entidade
      produtora </docs/entidade_produtora#criar_uma_entidade_produtora>`__),
      relacionando-as (`Relações entre entidades
      produtoras </docs/entidade_produtora#relacoes>`__) entre si de
      forma a constituir a estrutura orgânica. Essas relações poderão
      ser do tipo *hierárquico*, *associativo*, *familiar* ou
      *temporal*.

   - Criar a *estrutura documental*, ou seja, unidades informacionais
   (séries, subséries, documentos ou subdocumentos) organizadas
   hierarquicamente debaixo das respetivas entidades produtoras da
   estrutura orgânica. Mais informação em `Estrutura
   documental </docs/descricao_ui#estrutura_documental>`__.

Descrição multinível
--------------------

A descrição documental é fundamental na localização de documentos. A
descrição multinível usada no GISA permite gerir as descrições de forma
a que o esforço desta tarefa possa ser reduzido, disponibilizando níveis
de descrição suficientemente genéricos, de conjuntos de documentos
preferencialmente pouco pesquisados, embora nestes casos nunca possam
ser garantidos bons resultados nas pesquisas de informação. Ao mesmo
tempo, podem existir níveis de descrição mais específicos, no limite o
próprio documento, quando a informação neles contida é suficientemente
relevante para tal.

Muitos Arquivos usam a unidade física (que pode corresponder a várias
unidades informacionais) como unidade de descrição arquivística, em vez
da unidade informacional. Embora possa facilitar o trabalho, esta
prática, como já foi dito, poderá não conduzir a grandes resultados na
pesquisa de informação.

O preenchimento dos campos de descrição pode envolver a referência a
unidades físicas que deverão ser previamente recenseadas, a conteúdos e
tipologias informacionais que deverão constar na lista de registos de
autoridade ou então a objetos digitais. Ou seja, deverá ser previsto se
será conveniente executar as tarefas de recenseamento de unidades
físicas e de construção da lista dos registos de autoridade antes da
descrição das unidades informacionais ou executá-las à medida que vão
sendo necessárias para determinada descrição.

Quaisquer outras tarefas, tais como avaliação, pesquisa, impressão de
relatórios, estatísticas, publicação na Internet, só são possíveis sobre
meta-informação introduzida anteriormente no sistema.

A descrição de cada campo e o modo de preenchimento encontra-se em
detalhe na secção `Descrição
multinível </docs/descricao_ui#descricao_multinivel>`__.

Recenseamento de unidades físicas
---------------------------------

A representação e descrição do arquivo em termos físicos é importante,
pois facilita a gestão de um arquivo. Quando a pesquisa de determinada
informação é crucial, não basta descrever a unidade física, é
indispensável a descrição das unidades informacionais que a constituem.

Para fazer o recenseamento e descrição de unidades físicas, ver
`Unidades Físicas </docs/descricao_uf>`__.

A associação de unidades físicas a unidades informacionais pode ser
feita via:

   - unidades físicas e para isso consultar `Unidades de
   descrição </docs/descricao_uf#unidades_de_descricao>`__

   - unidades informacionais e para isso consultar `Identificação -
   Dimensão e suporte </docs/ident_dim#dimensao_e_suporte>`__.

Criação de tipologias informacionais
------------------------------------

A criação de tipologias informacionais numa lista controlada e o
relacionamento entre os diferentes termos, encontra-se detalhada em
`Tipologias informacionais </docs/tipologia_informacional>`__.

Entradas no registo de autoridade deste tipo servem para o preenchimento
do campo `3.1. Âmbito e
Conteúdo </docs/ambito_conteudo#conteudo_e_estrutura_-_ambito_e_conteudo>`__
das descrições arquivísticas segundo a ISAD(G).

Criação de registos de autoridade do tipo ideográfico, geográfico e onomástico
------------------------------------------------------------------------------

A página `Conteúdos </docs/conteudo>`__ apresenta os passos necessários
à criação de registos de autoridade do tipo:

   - ``Ideográfico``,
   - ``Onomástico`` ou
   - ``Nome geográfico ou topónimo citadino``.

Estes registos são utilizados na indexação das unidades de descrição
arquivística, preenchendo a zona `\*. Indexação existente no módulo
Unidades informacionais/Descrição </docs/indexacao>`__.

Associação de objetos digitais
------------------------------

A associação de objetos digitais que não se encontrem num Repositório
digital (imagens, som, documentos de texto, etc.) às descrições
arquivísticas encontra-se detalhada na secção *Índice de imagens* da
página `Unidades informacionais </docs/descricao_ui>`__.

A associação de objetos digitais, que se encontrem num Repositório
digital, às descrições arquivísticas encontra-se detalhada na página
`Objetos digitais </docs/objetos_digitais>`__.

Avaliação documental
--------------------

Independentemente da abordagem adotada, a *avaliação documental* tem
alguns procedimentos que deverão ser tidos em conta.

Numa primeira etapa, deverá ser efetuada a *`avaliação das
séries </docs/avaliacao#avaliacao_de_um_nivel_documental>`__* ou dos
documentos que não constituam série, escolhendo qual a melhor abordagem
para chegar a um destino final adequado. Assim, se a série for para:

   - ``Conservação`` - salvo alguma exceção, a maioria dos documentos
   dessa série deverão ser conservados.

   - ``Eliminação`` - deve indicar-se o prazo ao fim do qual os seus
   documentos poderão ser eliminados, decidindo após esse prazo qual o
   verdadeiro destino de cada um.

Para o caso de séries cujo destino é ``Conservação``, pode definir-se de
imediato o destino de todos os seus documentos em bloco, pois serão na
sua maioria para conservar. Para um maior detalhe consultar `Passo 1:
Avaliação e seleção dos conteúdos da unidade de
descrição </docs/avaliacao#passo_1avaliacao_e_selecao_dos_conteudos_da_unidade_de_descricao>`__.

Periodicamente, poderão ser listados, por série para eliminar, todos os
documentos cujo *prazo de conservação está ultrapassado*. Para isso,
usar a pesquisa avançada na área de *Unidades informacionais/Pesquisa*,
detalhada em `Pesquisa na
Descrição </docs/pesquisa_ui#pesquisa_na_descricao>`__.

Como numa série cujo destino final seja ``Eliminação``, alguns dos seus
documentos poderão ser, por algum motivo, para ``Conservação``, quando
existirem documentos cujo prazo de conservação está ultrapassado, será
conveniente estabelecer o destino definitivo de cada um deles,
individualmente ou em bloco. Para se trabalhar em bloco, deverá ser
selecionada a série, que se pretende, e registar na zona `Passo 1:
Avaliação e seleção dos conteúdos da unidade de
descrição </docs/avaliacao#passo_1avaliacao_e_selecao_dos_conteudos_da_unidade_de_descricao>`__.

Para o caso dos documentos serem registados como eliminados, é
conveniente associá-los a um *auto de eliminação* ainda no painel `Passo
1: Avaliação e seleção dos conteúdos da unidade de
descrição </docs/avaliacao#passo_1avaliacao_e_selecao_dos_conteudos_da_unidade_de_descricao>`__
e incluir as correspondentes unidades físicas, que são para eliminar, no
auto de eliminação através do painel `Passo 2: Seleção das unidades
físicas </docs/avaliacao#passo_2selecao_das_unidades_fisicas>`__.

Publicação de unidades de descrição
-----------------------------------

Para publicar uma determinada unidade de descrição na Internet, ver a
secção `Publicação de um nível de
descrição </docs/avaliacao#publicacao_de_um_nivel_de_descricao>`__.

Para a publicação em lote, de todos os níveis debaixo de um determinado
nível, ver a secção `Passo 1: Avaliação e seleção dos conteúdos da
unidade de
descrição </docs/avaliacao#passo_1avaliacao_e_selecao_dos_conteudos_da_unidade_de_descricao>`__.

Pesquisa
--------

A pesquisa no GISA pode ser feita:

   - ``via aplicação``, dividindo-se em dois tipos de objetos de procura
   diferentes:

      + ``informação`` - sendo efetuada na área de *Unidades
      informacionais* e o resultado são registos de séries ou
      documentos, os quais poderão referenciar os respetivos documentos
      digitais, caso estejam acessíveis.

      + ``suportes físicos`` - neste caso a pesquisa é feita na área de
      *Unidades físicas*, devolvendo o registo das unidades físicas.

   - ``via Web``, acessível por todos através do URL do GISA Internet
   atribuído a cada arquivo (ex: http://arquivo.cm-gaia.pt/)

A pesquisa, quer via aplicação quer via Web, é “full-text”, ou seja,
recupera informação procurando palavras ou expressões de pesquisa na
meta-informação registada. Para um melhor entendimento de como construir
expressões de pesquisa consultar `Expressões de
pesquisa </docs/pesquisa>`__.

Elaboração de inventários, catálogos e outros relatórios
--------------------------------------------------------

Para elaboração de listagens necessárias ao serviço de arquivo:

   - ``Catálogos``, ``inventários`` de unidades informacionais e autos de
   eliminação, na área *Unidades informacionais/Descrição*. Para mais
   detalhe ver a secção `Geração de
   relatórios </docs/descricao_ui#geracao_de_relatorios>`__.

\* ``Listas de unidades informacionais``, resultados de pesquisas
(obedecendo a determinados critérios de pesquisa) efetuadas na área
*Unidades informacionais/Pesquisa*. Para mais detalhe ver a secção
`Relatórios de unidades
informacionais </docs/pesquisa_ui#relatorios>`__.

   - ``Listas de unidades físicas``, resultados de pesquisas (obedecendo a
   determinados critérios de pesquisa) efetuadas na área *Unidades
   físicas/Pesquisa*. Para mais detalhe ver a secção `Relatórios de
   unidades físicas </docs/pesquisa_uf#relatorios>`__.

\* ``Listas de entidades produtoras``, ver a secção `Geração de
relatório de entidades
produtoras </docs/entidade_produtora#geracao_de_relatorio_de_entidades_produtoras>`__
da página `Entidades produtoras </docs/entidade_produtora>`__.

   - ``Listas de registos de autoridade do tipo Conteúdo``, ver a secção
   `Geração de relatório de
   conteúdos </docs/conteudo#geracao_de_relatorio_de_conteudos>`__.

\* ``Listas de registos de autoridade do tipo Tipologias informacional``,
ver a secção `Geração de relatório de tipologias
informacionais </docs/tipologia_informacional#geracao_de_relatorio_de_tipologias_informacionais>`__.

Análise estatística e controlo de desempenho
--------------------------------------------

A análise estatística que pode ser feita no GISA, encontra-se detalhada
na página `Estatísticas </docs/estatisticas>`__.

Gestão de requisições
---------------------

Quando se fazem pesquisas de documentos, pode ser importante saber se
determinado documento se encontra em depósito ou se foi requisitado.
Para se ter esta informação será necessário registar no sistema todas as
requisições de documentos (ver `Requisições </docs/requisicoes>`__), bem
como todas as devoluções (ver `Devoluções </docs/devolucoes>`__).

Periodicamente, poderá ser necessário saber qual a lista de todos os
documentos requisitados e ainda não devolvidos. Ver o procedimento em
`Imprimir Lista de
requisitados </docs/requisicoes#imprimir_lista_de_requisitados>`__.

Controlo da ocupação do depósito
--------------------------------

O controlo da taxa de ocupação do depósito torna-se crítico quando o
espaço livre é escasso. Para se efetuar este controlo (ver com detalhe
em `Gestão de depósitos </docs/gestao_depositos>`__) de forma eficaz,
será necessário registar:

   - todas as unidades físicas existentes no depósito, não esquecendo o
   preenchimento da sua dimensão. Para isso consultar `Unidades
   Físicas </docs/descricao_uf>`__;

\* todas as entradas de unidades físicas no depósito, não esquecendo o
preenchimento da sua dimensão. Para isso consultar `Unidades
Físicas </docs/descricao_uf>`__;

   - o destino de todos os documentos para eliminar, criando os respetivos
   autos de eliminação quando o prazo de conservação for ultrapassado.
   Este processo de avaliação é feito na área de *Unidades
   informacionais/Descrição* e para um maior detalhe consultar `Conteúdo
   e estrutura - Avaliação, seleção e eliminação </docs/avaliacao>`__;

\* o abate (eliminação física) dos documentos que constam nos autos de
eliminação. Para isso consultar `Abate de Unidades
físicas </docs/gestao_depositos#unidades_fisicas_associadas>`__.

Registo do abate de unidades físicas
------------------------------------

O registo da eliminação física de documentos é feito na área de
*Unidades físicas/Gestão de depósitos* e encontra-se explicada com
detalhe em `Abate de Unidades
físicas </docs/gestao_depositos#unidades_fisicas_associadas>`__.

Exportação de dados do GISA
---------------------------

Para *exportar* dados do GISA:

   - *para ficheiro*, usando o formato **EAD**, consultar a secção
   `Exportação para EAD </docs/descricao_ui#exportacao_para_ead>`__;

\* *para servidores agregadores*, que reconheçam o protocolo
**OAI-PMH**, basta ter o GISA Internet instalado e na instalação ser
configurada essa opção.

Importação de dados para o GISA
-------------------------------

Para *importar* dados para o GISA, estes devem estar num ficheiro Excel,
obedecendo a um formato e a um procedimento detalhados em `Importação de
dados em Excel </docs/descricao_ui#importacao_de_dados_em_excel>`__.
