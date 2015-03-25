lexml-slides
------------

**Colaboração** e **reutilização** de apresentações e trechos de apresentações relativas ao [Projeto LexML](http://projeto.lexml.gov.br/).
Projeto `lexml-slides` para a centralizar fontes e organizar sequências de *slides*, para fins de reuso em apresentações diversas.

## Objetivo ##
Concentrar em só repositório os *slides* de todas as [apresentaçoes públicas interessantes](http://educacaoaberta.org/wiki/index.php?title=Defini%C3%A7%C3%A3o) (na visão dos curadores/colaboradores) do LexML, possibilitando a sua atualização, correção e principalmente reutilização.

## Organização das pastas deste projeto ##
No presente README são listadas as apresentações e as fontes de onde foram obtidas.
As apresentações precisam ter minimamente:

 * link para GoogleDocs da apresentação (rotulada com convenções deste README)
 * link ou indicação da fonte do original
 * arquivo formato `.pptx` baixado do GoogleDocs para espelho neste git.

Opcionalmente, para controle de versões (acompanhamento em diff) um segundo formato: 
 * arquivo formato `.txt` para apenas acompanhar histórico de grandes modificações textuais.
 * versão "explodida" do formato `.pptx.zip` (basta renomear original e explodir), que garante controle de versão em todos os componentes.

### modulos ###
Sequências de slides de um mesmo tema ou abordagem, no presente projeto, quando devidamente isoladas e controladas, são denominadas **módulos**.

O conteúdo dos módulos pode ser extraído de apresentações originais (controladas) ou de outros módulos.

Cada *módulo* deve ter sua origem no GoogleDocs, com nome fixado neste README (ver "Rótulos e links"). Cada módulo deve apresentar também uma pasta com mesmo nome, contendo o "`.pptx` explodido" &mdash; corresponde ao arquivo `nome.pptx` exportado do GoogleDocs com nome `nome.pptx.zip` e então explodido pelo `unzip`.

### originais ###
Recipiente centralizado das apresentações originais realizadas. Cada apresentação, quando originada em outro aplicativo, deve ser importada para o GoogleDocs e renomeada para o padrão fixado neste README. O arquivo `.pptx` é o arquivo exportado do GoogleDocs, não pode ter outra origem. Sugere-se também exportar o `.txt` para ajudar no controle/verificação de eventuais atualizações da apresentação.

Nota: são considerados "originais" todas as apresentações efetivamente realizadas, independente de sua redação ter ou não reutilizado módulos. Créditos dos *slides*, apresentador e data de apresentação precisam vir grafados no primeiro slide (modificar caso o original não indique).

## Rótulos e links ##

Apresentações parciais (sequências de *slides*) organizadas em módulos para reuso:

|rotulo|Notas|
|---|---|
|[mdl-pesqTipica1](https://docs.google.com/presentation/d/1OC9JlEfIbGNr1VfbMTnrg6pE7_feD2t89QS2pVoH8GU/)|Uso do Portal LexML em pesquisas típicas, proposta-1. Fonte: recorde de *apres-PAraujo2014*.|
|[mdl-fatosVigencia1](https://docs.google.com/presentation/d/10lu5MAzsZMjFrLVy4Z2c3wWE7s_qAG-8fN8Wa5s6re4/)|Análise Jurídica dos Fatos, e vigência das normas.  Fonte: recorde de *apres-JLima2011*. |
|[mdl-cmpGoogle1](https://docs.google.com/presentation/d/10abTfZinIBwEas4OWXc1r1ud0cpFXlAjuAeyCVksBcs/)|LexML vs Google, comparação. Fonte: ppkrauss2015.|
|[mdl-naConst1](https://docs.google.com/presentation/d/19pRX_X1ffPupFtQAnKT0TIa-IG-wxrmu3E1MUI_zz6c/)|LexML responde à Constituição. Fonte: ppkrauss2015.|

Originais (com eventuais atualizações) das apresentações completas:

|rotulo|Nome original|Link Original|Notas|
|---|---|---|---|
|[apres-JLima2011](https://docs.google.com/presentation/d/1-t7cnK_BACAWB02gk_gr8pSuMpbt8A1LNfuInB_USMI/)|LexML e Processo Legislativo ENIAL GITEC.pptx | [interlegis.leg.br](https://colab.interlegis.leg.br/raw-attachment/wiki/IIIEncontroGitec/LexML%20e%20Processo%20Legislativo%20ENIAL%20GITEC.ppt)|[by-sa](https://creativecommons.org/licenses/by-sa/4.0/)|
|[apres-PAraujo2014](https://docs.google.com/presentation/d/13s7ZVK7U8-1tYL3GOZlzfaZaHTWCfrfnFPq8UbJzCbo/)|FONTES DE INFORMAÇÃO JURÍDICAS.pptx|[bibjuufpr.blogspot.com.br/2014/02/lexml](http://bibjuufpr.blogspot.com.br/2014/02/lexml-rede-de-informacao-legislativa-e.html)|<small>Material cedido por e-mail (em 2015-03-03 e 2015-03-12), permissão [by-nc-sa](https://creativecommons.org/licenses/by-nc-sa/4.0/).|
|[apres-PKrauss2015](https://docs.google.com/presentation/d/1qxuGx6ROwWAgEAtOQ0PYgzSUabYy22j2a5Kn4-Zh4h0/)|LexML-apresPUC-SP-sys-2015-03-24.pptx|-|Permissão [by-nc-sa](https://creativecommons.org/licenses/by-nc-sa/4.0/).|


## Videos correspondentes ##

 * [apres-JLima2011](https://www.youtube.com/watch?v=AgHZd4LX9gg)
 * ...

## Créditos, licenças e permissões ##

Os créditos dos originais devem ser indicados no primeiro ou ultimo slides da apresentação &ndash; um colaborador pode tomar a liberdade de acrescentar caso o autor já tenha cedido anteriormente para o dominio publico. Em geral o apresentador (e autor/colaborador principal dos slides) é indicado no primeiro slide e os créditos no final. Da mesma forma o tipo de licença cedida deve ser indicada.

O presente projeto não tem "espelhos", sendo distribuído apenas por um único repositório designado pelo [lexml.gov.br](http://www.lexml.gov.br), atualmente o [github.com/lexml](https://github.com/lexml).

As apresentações registradas no presente projeto são consideradas [Recurso Educacional Aberto](http://educacaoaberta.org/wiki/index.php?title=Defini%C3%A7%C3%A3o), e estarão sob uma das seguintes licenças, com permissão de adaptação (remix): [by-sa](https://creativecommons.org/licenses/by-sa/4.0/) ou [by-nc-sa](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Referências ##

 * ...

Outras iniciativas vinculadas ao presente projeto:

 * http://projeto.lexml.gov.br/gt-lexml/workshop-zero/slides 
 * https://www.youtube.com/channel/UCcPQHqAz2s6wa6cYgbnnLxQ
 * ...

