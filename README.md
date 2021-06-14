# Projeto de Data Science - Módulo 02

Projeto elaborado para o Módulo 2 do Bootcamp de Data Science da Alura
---

No presente repositório inserimos o notebook e os dados utilizados na análise realizada para elaboração do PROJETO 2, do Módulo 2, do Bootcamp de Data Science Aplicada da Alura. Um maior detalhamento acerca do projeto poderá ser obtido a seguir.

---
## 1-Dados

Os dados utilizados neste projeto são provenientes do TABNET do Datasus, que podem ser encontrados no endereço http://tabnet.datasus.gov.br/cgi/tabcgi.exe?pni/cnv/cpniuf.def, e do IBGE, que podem ser encontrados no endereço https://sidra.ibge.gov.br/tabela/6579.
As tabelas em CSV e EXLS utilizadas foram alocadas na pasta DADOS, neste mesmo repositório do GitHub. Salientamos que os dados relativos à população foram transpostos diretamente na tabela original em Excel, o que foi realizado para que estejam em conformidade com a estrutura de dados de poliomielite previamente adquirida. 

Algumas notas acerca dos dados de POLIOMIELITE:

Doses Cáculos CV por Ano segundo Unidade da Federação

Data de atualização dos dados: 04/09/2019

Período: 1994-2019

Os dados apresentados em 2013 se referem à soma dos seguintes dados:
Até Junho de 2013: dados do API DOS;

A partir de Julho de 2013: APIWEB + SIPNI Web (exceção UFs: AC, CE, DF , GO , MS, MT, PA, PR, RJ, SE, MA e TO por digitação duplicada);

Base de dados do ano de 2013 foi encerrada em 23/03/2015;

Doses aplicadas durante o MRC (pneumo 10 e meningo C) e Multivacinação;

2014: Dados do ano de 2014 são parciais. Referem-se ao recebimento das informações do APIWEB + SIPNI até a data de 23/03/2015.

Sobre o "Sistema de Informações do Programa Nacional de Imunizações":

"O objetivo fundamental do SI-PNI é possibilitar aos gestores envolvidos no programa uma avaliação dinâmica do risco quanto à ocorrência de surtos ou epidemias, a partir do registro dos imunos aplicados e do quantitativo populacional vacinado, que são agregados por faixa etária, em determinado período de tempo, em uma área geográfica. Por outro lado, possibilita também o controle do estoque de imunos necessário aos administradores que têm a incumbência de programar sua aquisição e distribuição."

Fonte: http://pni.datasus.gov.br/

---
## 2-Projeto
O projeto tem como proposta realizar uma análise relativa às imunizações para a POLIOMIELITE no perído compreendido entre 1997 e 2018, em nível de país (Brasil), de forma ampla, e dos Estados da Região Sul, em particular, comparando com a população no mesmo período ou em certo período a ser determinado ao longo do estudo, conforme disponibilidade dos dados.
Os comentários relativos a análise dos dados são realizados ao longo do notebook, a partir do qual surgem algumas hipóteses e conclusões prévias.

O projeto baseia-se no fato de haver um indicativo de perigo de reintrodução do vírus da poliomielite no País, embora em princípio não haja casos confirmados de paralisia infantil no Brasil desde 1989. Os seguintes artigos são utilzados como fonte de pesquisa:

https://www.sbmt.org.br/portal/perigo-de-reintroducao-da-poliomielite/

https://www.sbmt.org.br/portal/rubeola-e-poliomielite-doencas-eliminadas-voltam-ameacar-o-brasil/

https://g1.globo.com/bemestar/noticia/casos-de-sarampo-e-poliomelite-aumentaram-em-todo-o-mundo-diz-relatorio-da-oms.ghtml

https://saude.abril.com.br/blog/com-a-palavra/estamos-mesmo-livres-da-poliomielite/

As informações dão conta ainda que que a cobertura vacinal no país, para este tipo de virus, tem se reduzido, o que motiva a análise dos dados relativos às doses de vacinas distribuidas aos Estados, a fim de averiguar estas afirmações.

---
**SOBRE A POLIOMIELITE**

Outras fontes de pesquisa sobre a poliomielite:

http://bvsms.saude.gov.br/dicas-em-saude/2854-poliomielite-paralisia-infantil

http://tabnet.datasus.gov.br/cgi/pni/%5Ccpnidescr.htm

https://antigo.saude.gov.br/saude-de-a-z/clamidia/965-saude-de-a-a-z/poliomielite-paralisia-flacida-aguda/13461-decricao-polio

https://portalarquivos.saude.gov.br/images/pdf/2016/abril/07/Plano-p--lio--Brasil--07-04-2016.pdf

---
## 3-Hipótese

Partiremos do pressuposto de haver um aumento de casos de poliomielite em crianças no mundo (embora não haja casos registrados no Brasil, que seja de nosso conhecimento), conforme publicações disponibilizadas por meio dos links acima, que pode ser originado pela falta de aplicação de vacinas. É possível que a causa pode surgir tanto da falta de doses para vacinação ou a partir de campanhas não abrangentes por parte dos governos. Outra possibilidade a ser considerada é a falta de adesão às campanhas por parte de pais ou responsáveis. Durante o estudo é possível que seja percebida uma diminuição na aplicação das vacinas no decorrer dos anos, restando determinar a causa deste decrécimo.

---
## 4-Conclusões

As conclusões que obtivemos a partir da análise dos dados serão apresentadas ao final do notebook, entretanto convém advertir que são parciais. Outros dados e estudos posteriores deverão ser realizados para que seja possível elucidar de forma mais ampla a questão.

---
## 5-Continuidade e Considerações Finais

O presente projeto ainda carece de análises mais profundas, que serão obitidas a partir da aquisição de outros dados em momente posterior. Também é importante mencionar que alguns ajustes ainda serão necessários, principalmente quanto à apresentação dos dados (visualização), o que esperamos seja realizado em breve. Sendo assim, manteremos este projeto em aberto para futuras alterações.





