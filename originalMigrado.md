<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 13

Conversion time: 6.987 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Mon Sep 11 2023 03:09:27 GMT-0700 (PDT)
* Source doc: Arquitetura de Referência da INDBio
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 10 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 1; ALERTS: 13.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Arquitetura de Referência da Infraestrutura Nacional de Dados sobre Biodiversidade


# INDBio

**Marco Conceitual**

Organização: 

Eduardo Dalcin


# 


# Índice


[TOC]



# 


# Sumario executivo {#sumario-executivo}

Este documento propõe uma Arquitetura de Referência para a instalação de uma Infraestrutura Nacional de Dados sobre Biodiversidade (INDBio). '''Esta arquitetura consiste identificação e descrição de um conjunto de elementos e suas interações, em forma de rede, que, juntamente com instrumentos próprios, possibilitam o fluxo de informação de sobre biodiversidade'''.

Esta rede de elementos e suas interações permitem, em sua essência, que dados sobre biodiversidade sejam qualificados, organizados, preservados, selecionados, integrados e colocados à disposição de ferramentas de análise e síntese que, dentro de um contexto agregado por especialistas, oferece aos tomadores de decisão e formuladores de políticas públicas as informações gerenciais necessárias para a conservação da biodiversidade e seu uso sustentado e socialmente justo. 

Em essência, o propósito desta arquitetura é viabilizar a catalogação, integração e harmonização de dados existentes sobre biodiversidade, de maneira que possam ser facilmente localizados, acessados e explorados para os mais diversos usos, por qualquer cliente que tenha acesso à Internet.


# Motivação e Justificativa {#motivação-e-justificativa}

Em 29 de novembro de 2011 foi realizada a “Reunião de Peritos em Sistemas de Informação sobre Biodiversidade – SIBBr”, em Brasília – DF, no qual o objetivo era apresentar aos presentes o “Projeto SiBBr” e a “Coleta de subsídios para a definição da estratégia de elaboração, implementação e consolidação do SIBBr (“Road map”)” [^1]. Na mesma ocasião, foram apresentadas, na dinâmica do evento, várias questões à serem respondidas pelos grupos de trabalho, entre elas a questão “Qual deve ser a estrutura (arquitetura) geral do sistema?”. Desde então, esta pergunta não obteve uma resposta clara, objetiva e acordada, nem mesmo no seio do “Comitê Técnico Científico do SiBBr” (CTC), cuja gênese remonta à mesma reunião.

Na primeira reunião do CTC, em dezembro de 2011, foi demandada a criação de um “GT de arquitetura” cuja proposta era a “Revisão da arquitetura do Sistema”, no escopo de uma “prova de conceito”, com o intuito de “analisar, definir e documentar os processos que serão adotados, apontar os gargalos e impedimentos que devem ser mitigados, e levantar quais as demandas das instituições.” [^2].

Em 15 de fevereiro de 2012, a primeira reunião do GT de arquitetura cobriu, em suas discussões, uma série de aspectos relacionados à arquitetura sem, entretanto, apresentar um modelo conceitual que, na verdade, começou a ser discutido e amadurecido naquela reunião [^3] . Na reunião seguinte do CTC, em 5 de março do mesmo ano, foram relatados os avanços das discussões no âmbito do GT de arquitetura, assim como a definição de novas atividades relacionadas [^4] .

Desde então, por diversas razões, o foco no amadurecimento e consolidação de uma arquitetura para “o SiBBr” se dispersou, juntamente com o próprio GT de arquitetura, criado para este fim.

Assim sendo, consideramos ser fundamental o amadurecimento e consolidação de uma visão conceitual de uma Arquitetura, que incorpore não só um “Sistema de Informação sobre a Biodiversidade Brasileira (SiBBr)”, mas uma toda uma Infraestrutura Nacional de Informações sobre Biodiversidade, capaz de suportar e garantir o funcionamento adequado e sustentável deste sistema.


# Visão Geral {#visão-geral}

A organização de uma Infraestrutura Nacional de Dados sobre Biodiversidade (INDBio) pode ter diferentes abordagens. Neste documento consideramos uma visão em geral, em seu mais alto nível de abstração, onde elementos básicos interagem entre si na forma de uma rede (Figura 1).



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.jpg "image_tooltip")


**Figura 1** – Visão Geral da Infraestrutura Nacional de Dados sobre Biodiversidade (INDBio) com exemplos de elementos e suas relações, não necessariamente representando todas as suas possibilidades

Esta visão geral, aqui descrita, não substitui, muito menos descarta uma documentação que prevê uma abordagem global ao design, planejamento, implementação e governança de uma arquitetura formal, modelada em níveis ou domínios, como: Negócios (''Business''), Aplicação (''Application''), Dados (''Data'') e Tecnologia (''Technology''). Para tal, um framework apropriado deve ser utilizado como o TOGAF [^5] (Figura 2).



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


**Figura 2** - Ciclo de Desenvolvimento de Arquitetura segundo o framework TOGAF 9.1 (Haren, 2011)


# Missão e Objetivos {#missão-e-objetivos}


## Declaração de Missão {#declaração-de-missão}

**_“Proporcionar melhor tomada de decisão na conservação e no uso sustentado e socialmente justo da biodiversidade por meio de uma iniciativa governamental interdisciplinar voltada para qualificação, integração e publicação de dados.”_**


## Objetivos {#objetivos}



* Assegurar ampla colaboração entre instituições, especialistas e grupos temáticos;
* Assegurar o acesso aberto e público a dados de qualidade;
* Evitar a duplicação de esforços e fontes de informação inconsistentes;
* Garantir que o melhor conhecimento disponível e o rigor científico sejam preponderantes na tomada de decisão.


## Princípios da Arquitetura {#princípios-da-arquitetura}



* A INDBio possui uma organização em forma de rede, não linear, não hierárquica, formada de elementos e interações [^6], e centrada em Instituições;


* Os elementos da arquitetura podem se agregar em Unidades Funcionais (Figura 3);



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.jpg "image_tooltip")


**Figura 3** – Exemplo de Unidade Funcional provedora de dados primários



* A arquitetura é baseada no compartilhamento e reutilização de dados e componentes entre as aplicações, e orientada a serviços, com a adoção de padrões e protocolos abertos, largamente utilizados (Figura 4);



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


**Figura 4** – Arquitetura orientada a serviços



* Todo o dado sobre biodiversidade disponível na INDBio deve ter um conjunto de metadados associado, em formato aberto, padronizado e também digitalmente acessível;
* Todo o dado sobre biodiversidade disponível na INDBio deve ter um responsável pela sua qualidade, consistência e integridade;
* Todo o dado sobre biodiversidade que trafega na INDBio é considerado público, e seu uso é definido pela licença citada nos metadados correspondentes;


# Elementos da Arquitetura {#elementos-da-arquitetura}


## Instituições[^7]

As instituições são consideradas os elementos fundamentais desta arquitetura, uma vez que se apresentam como agregadores de outros elementos da arquitetura (Figura 5). Além disto, conferem à arquitetura solidez institucional, que pode ainda ser promovida por instrumentos jurídicos e normativos apropriados.



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.jpg "image_tooltip")


**Figura 5** – Visão geral da arquitetura centrada nas instituições, como agregadoras de recursos.

Além das relações entre os elementos da arquitetura nacional em si, esta se relaciona com iniciativas e organizações internacionais e intergovernamentais, que agem como consumidoras e demandadoras de produtos e serviços gerados pela infraestrutura (Figura 6).



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.jpg "image_tooltip")


**Figura 6** – Relação da INDBio com alguns exemplos de iniciativas nacionais, internacionais e intergovernamentais

O cenário nacional apresenta uma enorme diversidade de instituições com vocação e potencial para compor a INDBio. Apesar da diversidade, e diferente realidade de cada uma delas, podemos organizá-las nas seguintes vocações, ou potenciais, não mutuamente excludentes:



* Provedora de Dados
* Qualificadora de Dados
* Provedora de Infraestrutura
* Provedora de Ferramentas e Sistemas 
* Provedora de Análise e Síntese
* Capacitadora


### 


### Instituições Provedoras de Dados Mestres e de Referência

---
 {#instituições-provedoras-de-dados-mestres-e-de-referência}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>


Dados Mestres e de Referência são aqueles que são requeridos por diferentes grupos, processos e sistemas da INDBio, e provêm contexto para os dados transacionais [^8].

Em dados sobre biodiversidade, o “nome do táxon” constitui uma referência que agrega diferentes recursos de informação dispersos pela Infraestrutura, como amostras de coleção biológica, dados ecológicos e recursos de produção intelectual (referências, dissertações, teses, etc.).

Além dos Dados de Referência Taxonômica e Nomenclatural, podemos considerar também como dados de referência aqueles formados por conjuntos de termos, vocabulários e ontologias sobre biodiversidade, controlados e padronizados – com domínio bem definido - por toda a Infraestrutura, como por exemplo, o [Banco de Nomes Geográficos do Brasil (BNGB)](http://www.bngb.ibge.gov.br/bngb.php) oferecido pelo IBGE.

Dados Mestres e de Referência, mais do que prover contexto para dados transacionais, possibilitam que dados sobre uma mesma entidade, dispersos pela Infraestrutura, se agreguem em torno de um domínio, possibilitando análise e síntese dentro de um contexto taxonômico, espacial ou temporal completo, baseado em todo o conhecimento disponível produzido.

Um exemplo de Instituição Provedora de Dados Mestres e de Referência para a INDBio é o Instituto de Pesquisas Jardim Botânico do Rio de Janeiro (JBRJ), provendo um “backbone” nomenclatural e taxonômico com a Lista de Espécies da Flora do Brasil (Figura X), tanto na opção “human readable” (http://floradobrasil.jbrj.gov.br/) quanto “machine readable” (ou M2M – machine to machine) ([http://ipt.jbrj.gov.br/](http://ipt.jbrj.gov.br/) e [http://reflora.jbrj.gov.br/tapirlink/](http://reflora.jbrj.gov.br/tapirlink/)).



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.jpg "image_tooltip")


**Figura 7** – Exemplo de Instituição Provedora de Dados Mestres e de Referência


### 


### Instituições Provedoras de Dados sobre Ocorrências

---
 {#instituições-provedoras-de-dados-sobre-ocorrências}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>


Instituições Provedoras de Dados de Ocorrências são aqui consideradas instituições, das esferas federais e estaduais, que detêm coleções biológicas devidamente curadas. As informações associadas aos itens destas coleções representam os Dados de Ocorrência – dados associados à amostra ou registro da ocorrência (imagem ou som) que compõem uma coleção cientificamente documentada.

Coleções biológicas são, notoriamente, de importância fundamental no contexto da informação sobre biodiversidade [^9] [^10], e a publicação de seus dados, metadados e imagens em formato digital, uma prioridade [^11] [^12] [^13].

As instituições detentoras de coleções biológicas são um dos pilares fundamentares da INDBio, oferecendo dados sobre ocorrência para serem, no escopo da INDBio:



* Consumidos por outros sistemas de integração, análise e síntese (_machine readable_ ou _M2M_);
* Consumidos por especialistas e utilizados em processos de produção intelectual e análise e síntese (_human readable_);
* Expostos à crítica visando à melhoria de qualidade por especialistas e ferramentas automatizadas ou assistidas (_machine_ and _human readable_);

Em uma visão geral, para prover dados de suas coleções, e de outros recursos de informação que por ventura a instituição possa ter sob sua guarda, há uma demanda de um conjunto de elementos que devem estar integrados e funcionais, de modo a permitir o fluxo de dados de qualidade para a infraestrutura. Este conjunto de elementos, integrados e funcionais, compõem o que chamaremos aqui Unidade Funcional.

Estes elementos, componentes destas Unidades Funcionais, entretanto, não necessitam estar, necessariamente, inteiramente sob a responsabilidade da IPDO. Acordos de cooperação técnica e parcerias podem viabilizar, por exemplo, infraestrutura computacional e participação de especialistas externos na qualificação das coleções (Figura X).



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.jpg "image_tooltip")


**Figura 8** – Exemplo de Unidade Funcional Multi-institucional

Da mesma forma, Unidades Funcionais podem compartilhar recursos da mesma instituição, conforme visto na Figura 8. Tal configuração é especialmente útil no compartilhamento de recursos de infraestrutura computacional, como armazenagem, processamento e operação.



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.jpg "image_tooltip")


**Figura 9** – Unidades Funcionais compartilhando recursos de diferentes instituições

As Unidades Funcionais Provedoras de Dados de Ocorrência oferecem uma interface que, além de atender a INDBio, pode permitir o acesso de especialistas e do público em geral, através de um portal oferecendo consulta aos dados de suas coleções biológicas (Figura X).



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.jpg "image_tooltip")


**Figura 10** – Exemplo de interface de Unidade Funcional com a INDBio e consumidores


### Instituições Provedoras de Dados Ecológicos

---
 {#instituições-provedoras-de-dados-ecológicos}

<p style="text-align: right">
Editor: Debora Drucker</p>


Dados ecológicos, obtidos por observações diretas do campo e por estudos baseados em experimentos representam valioso recurso de informação sobre nossas espécies e ecossistemas [^14].


### Instituições com repositórios institucionais de produção intelectual

---
 {#instituições-com-repositórios-institucionais-de-produção-intelectual}

<p style="text-align: right">
Editor: </p>


Um repositório institucional de acesso aberto constitui um serviço de informação científica - em ambiente digital e interoperável - dedicado ao gerenciamento da produção científica e/ou acadêmica de uma instituição (universidades ou institutos de pesquisa). Contempla a reunião, armazenamento, organização, preservação, recuperação e, sobretudo, a ampla disseminação da informação científica produzida na instituição [^15].



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.jpg "image_tooltip")


**Figura 11** - Repositório Institucional do MPEG

Repositórios institucionais bem estruturados constituem importante fonte de conhecimento sistematizado sobre a biodiversidade. Uma vez que são baseados em padrões e protocolos abertos, como o padrão [http://dublincore.org/ Dublin Core] e o protocolo [http://www.openarchives.org/pmh/ Open Archives Initiative Protocol for Metadata Harvesting], podem oferecer conteúdo indexado relevante para integração a INDBio.


### Instituições Provedoras de Dados Genéticos

---


<p style="text-align: right">
Editor: Maristerra Rodrigues Lemes</p>


Exemplos à considerar:

* http://brbol.org/

* https://www.ncbi.nlm.nih.gov/taxonomy/

* https://www.ncbi.nlm.nih.gov/genbank/collab

* http://www.ggbn.org/


### Instituições provedoras de dados de Germoplasma

---
 {#instituições-provedoras-de-dados-de-germoplasma}

<p style="text-align: right">
Editor: Maria Lúcia Nova da Costa</p>


O termo germoplasma é definido como “a base física do cabedal genético, que reúne o conjunto de materiais hereditários de uma espécie” [^16] . Diversas instituições são detentoras de coleções de germoplasma, compostas geralmente por material de origem vegetal, animal ou microbiana, tais como os jardins botânicos, jardins zoológicos [^17] , institutos de pesquisas [^18] [^19], empresas agrícolas [^20] e outros. Essas coleções guardam também um conjunto de dados associados aos espécimes ou amostras mantidos, que dizem respeito a sua classificação taxonômica, nomes vulgares, forma de obtenção, dados de coleta e informações sobre o ambiente onde foi coletado, caracterização morfológica, química e molecular, além de outros de acordo com a especificidade do material. Dados desse tipo são de extrema relevância para apoiar ações e pesquisas científicas e tecnológicas que tratam de elaboração de fármacos, controle biológico de pragas, diagnóstico de doenças, melhoramento vegetal e caracterização e restauração ambiental, dentre outros temas que visam a melhoria da saúde pública, segurança alimentar e conservação e uso sustentável dos componentes da biodiversidade. 


## Atores {#atores}

<p style="text-align: right">
Editor: </p>


A literatura tem apresentado várias abordagens para definir e descrever “atores” que possuem relação com dados e informações sobre biodiversidade [^21] [^22] [^23] [^24] [^25] [^26] [^27].  Além destas abordagens focadas na informação sobre biodiversidade, a INDE, como uma iniciativa análoga a INDBio, reconhece grandes grupos, ou setores, partícipes da Infraestrutura; e ainda, atores que devem estar envolvidos na construção da INDE [^28].

Neste documento, reconhecemos dois grandes grupos de atores: aqueles relacionados com o conteúdo – dados e informações, e aqueles relacionados com a infraestrutura, física e lógica, que os suportam.

Em relação aos atores relacionados com o conteúdo, podemos ainda agrupá-los em três grupos, à saber: Produtor, Transformador e Consumidor (Figura X).



<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.jpg "image_tooltip")


**Figura X** – Principais classes de atores relacionados com conteúdo da INDBio

As classes de atores relacionados ao conteúdo não são mutuamente excludentes. Com frequência encontramos pesquisadores, técnicos, analistas e especialistas atuando, em diferentes intensidades e momentos, em cada um destes três papéis. 

Atuando como produtor de dados, encontramos atores pertencentes ao setor público, setor privado, academia e sociedade civil organizada (terceiro setor). Entretanto, mais recentemente, a chamada “Ciência Cidadão” ("''Citizen Science''") tem causado significativo impacto na coleta ou geração de dados sobre biodiversidade [^29] [^30] [^31]. 

Como transformador de dados, consideramos aqui aqueles capazes de agregar valor ao dado, seja pela sua qualificação, seja pela capacidade de integração para análise e síntese, na maioria das vezes voltadas para a produção de artigos acadêmicos ou relatórios. Neste caso, o papel de transformador se confunde como o de consumidor, visto que não há como transformar o dado sem consumi-lo. Porém, o Consumidor se apresenta aqui como um “usuário” dos produtos e serviços oferecidos pela INDBio e seus componentes, no sentido de utilizar estes produtos e serviços “'_as it is_'”, transformando-os apenas na sua forma, e não no conteúdo.


### Organizações de Atores

---
 {#organizações-de-atores}


#### Sociedades Científicas {#sociedades-científicas}


#### Redes temáticas e de especialistas {#redes-temáticas-e-de-especialistas}


## Recursos {#recursos}


### Recursos de Infraestrutura Computacional {#recursos-de-infraestrutura-computacional}

<p style="text-align: right">
Editor: Wagner Leo</p>



#### Armazenagem {#armazenagem}


#### Processamento {#processamento}


#### Conectividade {#conectividade}


#### Plataformas, ferramentas e aplicativos {#plataformas-ferramentas-e-aplicativos}

<p style="text-align: right">
Editor: Diogo Silva</p>



### Recursos de Dados {#recursos-de-dados}


#### Dados sobre Espécies e suas Características {#dados-sobre-espécies-e-suas-características}

<p style="text-align: right">
Editores: Eduardo Dalcin, Rogério Gribel</p>



#### Dados sobre testemunhos, ocorrências e registros de espécimes {#dados-sobre-testemunhos-ocorrências-e-registros-de-espécimes}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>



#### Dados Ecológicos {#dados-ecológicos}

<p style="text-align: right">
Editor: Debora Drucker</p>



#### Dados sobre interações entre espécies {#dados-sobre-interações-entre-espécies}

<p style="text-align: right">
Editor: </p>



#### Dados sobre Ameaças {#dados-sobre-ameaças}

<p style="text-align: right">
Editor: </p>



# Instrumentos {#instrumentos}


## Normas e Políticas {#normas-e-políticas}

<p style="text-align: right">
Editores: Rodrigo Silva Pinto Jorge, Keila Macfadem Juarez</p>



## Padrões, Vocabulários e Ontologias {#padrões-vocabulários-e-ontologias}

<p style="text-align: right">
Editores: AnaMaria Moura, Laurindo Campos e Daniele Palazzi</p>


Padrões, vocabulários e ontologias são elementos fundamentais da interoperabilidade entre sistemas de informação e, em última instância, são elementos que possibilitam que a INDBio funcione como uma rede.

Segundo o [Documento de Referência da e-PING – Versão 2014](http://www.governoeletronico.gov.br/biblioteca/arquivos/documento-da-e-ping-versao-2014/), para o governo brasileiro, interoperabilidade é:



* “Intercâmbio coerente de informações e serviços entre sistemas. Deve possibilitar a substituição de qualquer componente ou produto usado nos pontos de interligação por outro de especificação similar, sem comprometimento das funcionalidades do sistema.” (governo do Reino Unido);
* “Habilidade de transferir e utilizar informações de maneira uniforme e eficiente entre várias organizações e sistemas de informação.” (governo da Austrália); 
* “Habilidade de dois ou mais sistemas (computadores, meios de comunicação, redes, software e outros componentes de tecnologia da informação) de interagir e de intercambiar dados de acordo com um método definido, de forma a obter os resultados esperados.” (ISO);
* “Interoperabilidade define se dois componentes de um sistema, desenvolvidos com ferramentas diferentes, de fornecedores diferentes, podem ou não atuar em conjunto.” (Lichun Wang, Instituto Europeu de Informática – CORBA Workshops);

Interoperabilidade não é somente Integração de Sistemas, não é somente Integração de Redes. Não referencia unicamente troca de dados entre sistemas. Não contempla simplesmente definição de tecnologia. É, na verdade, a soma de todos esses fatores, considerando, também, a existência de um legado de sistemas, de plataformas de Hardware e Software instaladas. Parte de princípios que tratam da diversidade de componentes, com a utilização de produtos diversos de fornecedores distintos. Tem por meta a consideração de todos os fatores para que os sistemas possam atuar cooperativamente, fixando as normas, as políticas e os padrões necessários para consecução desses objetivos.

Para que se conquiste a interoperabilidade, as pessoas devem estar engajadas num esforço contínuo para assegurar que sistemas, processos e culturas de uma organização sejam gerenciados e direcionados para maximizar oportunidades de troca e reuso de informações.

Desta forma, a instalação da INDBIo como uma iniciativa do Governo Federal, centrada em instituições do Governo Federa, a adoção dos padrões e políticas contidos na e-PING é obrigatória (Portaria SLTI/MP nº 5, de 14 de julho de 2005).

A interoperabilidade possui ainda dois domínios principais: o sintático, que trata da capacidade de comunicação e troca de dados entre sistemas (formatos, padrões e protocolos), chamada de Interoperabilidade Sintática; e a semântica, que trata da capacidade de interpretar automaticamente a informação trocada, de forma significativa e precisa.

O [Padrão de Metadados do Governo Eletrônico Brasileiro (e-PMG)](http://www.governoeletronico.gov.br/acoes-e-projetos/e-ping-padroes-de-interoperabilidade/padrao-de-metadados-do-governo-eletronico-e-pmg), desenvolvido com base no padrão Dublin Core, propõe o [http://vocab.e.gov.br/ Vocabulário Controlado do Governo Eletrônico], parte do Repositório de Vocabulários e Ontologias do Governo Eletrônico Brasileiro, onde o termo “Biodiversidade” se faz presente. Entretanto, para que a proposta da INDBIo se concretize, termos, vocabulários e ontologias específicos do domínio da biodiversidade e conservação necessitam ser definidos e acordados, além dos existentes, que contemplam apenas parte das demandas [^32].

No cenário nacional, vale destacar a iniciativa do grupo de pesquisas do Instituto Nacional de Pesquisas da Amazônia – INPA, na definição de uma ontologia voltada para a biodiversidade [^33] [^34], registrada e disponível no agregador de ontologias bio-médicas Bioportal.

Além dos padrões relacionados ao Governo Eletrônico Brasileiro, a necessidade de interoperar com sistemas de abrangência global, demanda a compatibilidade da INDBio com termos, vocabulários e ontologias de abrangência global, como o proposto pelo  [Biodiversity Information Standards](http://www.tdwg.org/) .


### Padrões {#padrões}


#### Darwin Core e Darwing Core Archive {#darwin-core-e-darwing-core-archive}


#### EML {#eml}

O EML - Ecological Metadata Language [^35] é uma especificação de metadados  apropriada para documentar dados tabulares. É implementada em módulos estruturados em XML (eXtensible Markup Language) que descrevem um aspecto da documentação de um conjunto de dados, como o módulo de descrição de métodos de coleta ou o de abrangência geográfica, taxonômica e temporal do conjunto de dados [^36] . A Tabela 1 contém os módulos e a explicação do que descrevem. Essa especificação vem sendo adotada por diversas redes de grupos de pesquisa, como o LTER norte-americano (Long Term Ecological Research) [^37], o SAEON (South African Environmental Observatory Network) e o TEAM (Tropical Ecosystem Assessment and Monitoring), da Conservation International, e instituições como o NCEAS (National Center for Ecological Analysis and Synthesis) [^38] e o TFRI (Taiwan Forestry Research Institute). 

No Brasil, o Projeto Temático Gradiente Funcional, do Programa BIOTA-FAPESP (Composição florística, estrutura e funcionamento da Floresta Ombrófila Densa dos Núcleos Picinguaba e Santa Virgínia do Parque Estadual da Serra do Mar) [^39], o PPBio Amazônia Ocidental (Programa de Pesquisa em Biodiversidade, MCT) [^40] e o PELD (Programa de Pesquisas Ecológicas de Longa Duração, CNPq) adotaram o protocolo EML para documentar os dados coletados. Um dos módulos do EML é a descrição da tabela de dados, o que permite a interpretação de tabelas avulsas.

Tabela 1. Módulos da especificação de metadados EML e suas descrições [^41] &lt;ref>&lt;/ref>


<table>
  <tr>
   <td><strong>Módulo</strong>
   </td>
   <td><strong>Conteúdo</strong>
   </td>
  </tr>
  <tr>
   <td>EML-resource
   </td>
   <td>Informação geral sobre os metadados, como quem os criou, título e palavras-chave
   </td>
  </tr>
  <tr>
   <td>EML-party
   </td>
   <td>Informação detalhada sobre pessoas e organizações envolvidas
   </td>
  </tr>
  <tr>
   <td>EML-coverage
   </td>
   <td>Abrangência temporal, geográfica e temporal do conjunto de dados
   </td>
  </tr>
  <tr>
   <td>EML-project
   </td>
   <td>Contexto da pesquisa que originou o conjunto de dados, por exemplo objetivos e financiamento
   </td>
  </tr>
  <tr>
   <td>EML-methods
   </td>
   <td>Procedimentos de campo e de laboratório usados para criar o conjunto de dados e procedimentos de controle de qualidade dos dados
   </td>
  </tr>
  <tr>
   <td>EML-attribute
   </td>
   <td>Nome, definição, unidade e domínio das varáveis
   </td>
  </tr>
  <tr>
   <td>EML-access
   </td>
   <td>Níveis de acesso permitidos para usuários ou grupos de usuários
   </td>
  </tr>
</table>



#### Perfil MGB {#perfil-mgb}


#### LOD {#lod}


#### RDF {#rdf}


#### SPARQL {#sparql}


#### Plinian Core {#plinian-core}


#### Dublin Core {#dublin-core}

Metadados são comumente definidos como “dados sobre dados”. São informações que caracterizam os dados e informam sobre sua natureza, propósito, formato, autoria [^42]. São informações que possibilitam organizar, classificar, relacionar e inferir novos dados sobre o conjunto de dados. A quantidade e a qualidade dos metadados de um conjunto de dados podem determinar a utilidade daquele conjunto de dados [^43] .

Dublin Core é um esquema de metadados que visa descrever objetos digitais, tais como, vídeos, sons, imagens, textos e sites na web [^44]. Esse modelo permite descrever a identificação, direitos, licenças, responsabilidades, autoria, contribuição, formatação, cobertura espacial e temporal além de relações e referências a outros recursos.

Tendo  o principal objetivo de possibilitar a interoperabilidade de metadados, os sistemas podem ser classificados em quatro níveis de interoperabilidade:

Level 1: Shared term definitions

Level 2: Formal semantic interoperability

Level 3: Description Set syntactic interoperability

Level 4: Description Set Profile interoperability

Os termos  atualmente recomendados pelo Dublin Core Metadata Initiative (DCMI) incluem o modelo Simples (DCMES), o Qualificado(Qualified) e mais termos incorporados ao longo do desenvolvimento da iniciativa, estando disponíveis no portal do DCMI (http://dublincore.org/documents/dcmi-terms/).

O modelo de metadados permite ainda ser estendido com vocabulários próprios a necessidade utilizando "Application Profiles".


#### Audubon Core {#audubon-core}

http://www.tdwg.org/homepage-news-item/article/audubon-core-public-review/


## Estratégia Nacional de Informação Sobre Biodiversidade {#estratégia-nacional-de-informação-sobre-biodiversidade}

<p style="text-align: right">
Editores: Eduardo Dalcin</p>


A Estratégia Nacional de Informação sobre Biodiversidade é um documento que estabelece diretrizes que irão orientar e priorizar as ações nacionais e regionais para a instalação da Infraestrutura Nacional de Informação sobre Biodiversidade, seu funcionamento, evolução e sustentabilidade.


### Eixos Prioritários {#eixos-prioritários}



* Capacitação
* Comunicação
* Infraestrutura


### Ações Estruturantes {#ações-estruturantes}



* Oferta de capacitação em Informática na Biodiversidade, qualificação e governança de dados, análise e síntese, Taxonomia, etc.
* Promoção da geração de produtos oriundos dos produtos e serviços oferecidos pelo SiBBr, e da utilização destes produtos no apoio à decisão.
* Oferta de infraestrutura de armazenagem e gestão de recursos computacionais, infraestrutura adequada ao crescimento e dinamização das coleções biológicas.


## 


## Sistema de Informação sobre a Biodiversidade Brasileira - SiBBr {#sistema-de-informação-sobre-a-biodiversidade-brasileira-sibbr}

<p style="text-align: right">
Editores: Luiz Gadelha Jr.</p>


A instalação de uma infraestrutura como a INDBio demanda um conjunto de ferramentas, produtos e serviços que, pelas suas características estruturais e transversais, atuam um “núcleo” operacional desta Infraestrutura. Este núcleo auxilia na implementação, propagação e consolidação destas ferramentas, produtos e serviços, no momento inicial de instalação da INDBio, onde esta estrutura é precária ou inexistente. Além disso, funciona como articulador central entre a demanda e a oferta de informações sobre biodiversidade pelos diferentes atores, define e homologa padrões e protocolos de interoperabilidade entre os sistemas e garante um fluxo contínuo de dados e informações de qualidade pela rede.

No cenário nacional, o Sistema de Informação sobre a Biodiversidade Brasileira – SiBBr assume este papel de núcleo operacional da Infraestrutura, distribuindo sua operação e gestão por instituições-chave do cenário técnico-científico nacional ligadas a computação científica e a biodiversidade.



<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.jpg "image_tooltip")


**Figura X** – SiBBr como núcleo operacional da INDBio


### Ferramentas, Produtos e Serviços {#ferramentas-produtos-e-serviços}


#### Portal agregador de produtos e serviços {#portal-agregador-de-produtos-e-serviços}

<p style="text-align: right">
Editor: </p>



#### Cadastro Nacional de Coleções Biológicas {#cadastro-nacional-de-coleções-biológicas}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>


Coleções Biológicas desempenham um papel central, fundamental e crítico em qualquer iniciativa relacionada com a informação sobre biodiversidade, e sua importância estratégica foi suficientemente explorada e enaltecida na literatura [^45] [^46]. Além disto, a [Deliberação nº 53 da Comissão Nacional de Biodiversidade – CONABIO, de 26 de agosto de 2008](http://www.mma.gov.br/estruturas/conabio/_arquivos/deliberaao_53_ctpcoleoes_15.pdf), além de reforçar este papel, apresenta um conjunto de recomendações e proposições, entre elas, criando uma Câmara Técnica Permanente de Coleções Biológicas Com algumas relevantes competências. Entretanto, não existe um Diretório Nacional de Coleções Biológicas, nem como proposição em nenhum dos documentos acima, capaz de servir de referência quantitativa e qualitativa das coleções biológicas nacionais.

No contexto da INDBio, um diretório nacional destes repositórios da biodiversidade, seria capaz de fornecer um Identificador Persistente Único para estas coleções que, associado ao Identificador Persistente Único do testemunho do espécime (voucher) depositado na coleção, cria uma forma inequívoca de se referenciar à este testemunho depositado em uma coleção, facilitando a integração e interoperabilidades destes dados [^47]. Como exemplo, podemos citar o [Global Registry of Biorepositories (GRBio)](http://grbio.org), que possui registros de coleções brasileiras, incorporadas de diversas fontes.

Da mesma forma que o GRBio, um diretório nacional, funcionando também como um “registrador” e, no contexto da arquitetura,  pode servir como uma “Base de Dados Mestre e de Referência”, sobre as coleções biológicas nacionais, oferecendo não só acesso à consulta pública, mas um conjunto de “Web Services” que seriam consumidos pelos sistemas distribuídos pela infraestrutura.


#### Agregador de dados de coleções biológicas {#agregador-de-dados-de-coleções-biológicas}

<p style="text-align: right">
Editor: </p>


Agregadores de dados primários sobre biodiversidade são ferramentas baseadas na Internet que possibilitam a consulta integrada a diferentes coleções biológicas através de uma única interface. Como exemplos, podemos citar o agregador do Global Biodiversity Information Facility – GBIF, a instituição intergovernamental, do qual o Brasil é signatário, com a missão de “...tornar os dados mundiais sobre biodiversidade livremente acessíveis, de forma aberta, pela Internet.” [^48]; e ainda a iniciativa brasileira SpeciesLink, desenvolvida e mantida pelo Centro de Referência em Informação Ambiental – CRIA, como “...um sistema distribuído de Informação que integra em tempo real, dados primários de coleções biológicas.” [^49].


#### Serviço de imagem em alta resolução {#serviço-de-imagem-em-alta-resolução}

Serviço de armazenagem, processamento e incorporação (via código) de imagens de alta resolução sejam estáticas (ex.foto) ou dinâmicas (ex.filmes).

Serviço de armazenagem, processamento e incorporação (via código) de arquivos de sons.


#### Serviço de Mapeamento {#serviço-de-mapeamento}

<p style="text-align: right">
Editor: Hesley Py</p>



#### Serviço de Modelagem {#serviço-de-modelagem}

<p style="text-align: right">
Editores: Marinez Siqueira, Katia Ferraz, Rafael Loyola</p>



#### Repositório de Produção Intelectual {#repositório-de-produção-intelectual}

Agregador de produção intelectual indexada sobre biodiversidade


#### Repositório de Dados Ecológicos {#repositório-de-dados-ecológicos}

<p style="text-align: right">
Editor: Debora Pignatari Drucker</p>



#### Resolvedor de nomes científicos {#resolvedor-de-nomes-científicos}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>



#### Serviço de Qualidade de Dados {#serviço-de-qualidade-de-dados}

<p style="text-align: right">
Editores: Luís Alexandre e Allan Koch Veiga</p>




* Importância da Qualidade de Dados (QD) nas pesquisas.
* Serviços de Limpeza de Dados
    * Definições
    * Objetivo
    * Métodos / Abordagens
    * Exemplos de Serviços de Limpeza de Dados de Biodiversidade


#### Serviço de Mineração de Dados {#serviço-de-mineração-de-dados}

<p style="text-align: right">
Editores: Luís Alexandre e Allan Koch Veiga</p>



##### Uso de Serviços de Mineração de Dados na Geração de Conhecimento sobre a Biodiversidade.


##### Uso de Serviços de Mineração de Dados como Mecanismos de QD.


##### Serviços de Mineração de Dados

A mineração de dados é o processo de descoberta de correlações significativas, padrões e tendências de repositórios de dados, usando tecnologias de reconhecimento de padrões e estatística, ou simplesmente, “a extração ou mineração de conhecimento a partir de grandes quantidades de dados” [^50]. 

O processo de extração de conhecimento de bancos de dados (KDD - Knowledge Discovery in Databases) envolve diversas etapas para sua total aplicação. Nesse processo, somente depois da etapa de limpeza de dados, realizada na fase de pré-processamento, é que as técnicas de mineração de dados são usadas para extrair as regras e padrões. Ela é uma das principais fases deste processo de geração de conhecimento e tem por objetivo realizar a descoberta automática de informações úteis em grandes depósitos de dados [^51]. 

Na INDBio pode ser usada tanto para a extração de conhecimentos quanto para a melhorar na qualidade de dados. Na extração de conhecimento podem ser usadas técnicas para a mineração de dados espaciais, a análise de co-ocorrência de espécies em dados, ...


#### Serviço de anotações {#serviço-de-anotações}

<p style="text-align: right">
Editor: Eduardo Dalcin</p>


As anotações em dados científicos disponíveis na Internet, como em material de coleção biológica, tem surgido na literatura como uma funcionalidade nova e requerida pelos usuários de dados sobre biodiversidade [^52]. Neste cenário, dois projetos se destacam:  [FilteredPush](http://wiki.filteredpush.org/wiki/FilteredPush) [^53] e [AnnoSys](http://wiki.bgbm.org/annosys/index.php/Main_Page) [^54]. Em ambos os projetos existe a visão de um repositório central de anotações que é compatível com a visão do SiBBr atuando como um “núcleo operacional” da INDBio.


#### Serviço de identificador único persistente {#serviço-de-identificador-único-persistente}

<p style="text-align: right">
Editor: </p>


Um identificador é a associação entre uma série de caracteres e um objeto. Objetos podem ser arquivos, parte de arquivos, nomes, etc. Um identificador persistente é um identificador que esta disponível e é gerido ao longo do tempo. Ele não deve mudar se um item é renomeado ou movido. Um identificador único é um identificador que não permite conflito e que não se repete.

Identificadores persistentes (únicos) são importante por serem não-ambigos. Na biologia, nos lidamos com informações sobre muitos objetos diferentes (...), e temos muitas formas diferentes de nos referir a esses objetos [^55].

Alguns tipos de identificadores:



* DOI

    Digital Object Identifier (DOI) são identificadores originários da área de publicações e tem amplo uso em artigos [^56]. O DOI para um documento se mantém fixo durante a existência deste, enquanto sua localização e metadados podem mudar [^57].



* ARK

    Archival Resource Key (ARK) são um tipo de identificadores originários de bibliotecas, arquivos e museus [^58]. Funcionam na forma de URLs com um schema bem definido.



* EZID

    EZID é um serviço que permite acesso e gestão de identificadores persistentes para datasets, arquivos e outros recursos. Está disponível via "machine-to-machine APIs" e como uma interface web. O serviço permite adquirir DOIs e ARKs [^59].



* LSID

    O Life Sciences Identifier (LSID) é uma especificação de Uniform Resource Name (URN) [ou URI] cujo conceito introduz uma forma de nomear e identificar recursos armazenados em multiplos bancos de dados distribuídos [^60].



* PURL

    PURLs (Persistent Uniform Resource Locators) are Web addresses that act as permanent identifiers in the face of a dynamic and changing Web infrastructure. Instead of resolving directly to Web resources, PURLs provide a level of indirection that allows the underlying Web addresses of resources to change over time without negatively affecting systems that depend on them. This capability provides continuity of references to network resources that may migrate from machine to machine for business, social or technical reasons [^61]. 



* UUID

    Universally Unique IDentifier (UUID) é um tipo de identificador criado por algoritmos que garantem virtualmente que não serão gerados dois identificadores iguals em qualquer momento ou lugar. Assim evitam a necessidade de verificação por identificadores idênticos e ajudam a garantir que futuros mecanismos de busca e resolução encontraram a instância correta e não retornaram múltiplas possíveis interpretações [^62].


#### Repositório de códigos-fonte {#repositório-de-códigos-fonte}

<p style="text-align: right">
Editor: </p>



#### Repositório de “workflow” científico {#repositório-de-“workflow”-científico}

<p style="text-align: right">
Editor: Luiz Gadelha Jr.</p>


Diversos autores propõem que a análise dos dados destes experimentos computacionais possa ser considerada um quarto paradigma científico [^63], em adição aos tradicionais paradigmas experimental, analítico e de simulações computacionais. Gray [^64], observa que não existem ferramentas que permitam apoiar, de forma integrada, todas as etapas envolvidas nestes experimentos, como a coleta de dados brutos nos sensores, a curadoria dos mesmos, a execução de análises, a estruturação de dados para consultas, a visualização, e a publicação científica em formato que permita que leitores e revisores acessem os dados utilizados e reproduzam os experimentos computacionais de forma automatizada. O termo e-Ciência [^65] é frequentemente utilizado para denotar atividades deste tipo.

A gerência manual de experimentos científicos computacionais em larga escala [^66] é trabalhosa e sujeita a erros, já que diversos aspectos devem ser levados em consideração, por exemplo: 



* As atividades podem ter dependências de dados entre si, de modo que algumas atividades só podem iniciar sua execução quando seus dados de entrada, produzidos por outras atividades que as precedem, estiverem disponíveis; 
* Eventualmente, o fluxo de execução do experimento pode sofrer uma bifurcação para a execução de diversas atividades independentes entre si, tornando interessante a execução paralela das mesmas por questões de eficiência; 
* O início da execução de uma atividade pode depender do fim da execução de diversas atividades disparadas após uma bifurcação, requerendo uma sincronização da execução do experimento, onde é necessário garantir que todas as atividades geradas pela bifurcação de fato terminaram a sua execução; 
* Caso o experimento utilize diversos recursos computacionais remotos, é necessário gerenciar a transferência de dados e monitorar a execução de atividades remotas. 

Como observado por Davidson [^67], esses aspectos são de difícil controle quando são utilizadas linguagens de scripting genéricas como Perl ou Python. A automatização destes experimentos pode ser apoiada por sistemas de gerência de workflows científicos (SGWCs) [^68] que permitem projetar, executar e analisar experimentos dados pela composição de diversas aplicações científicas, possivelmente distintas, que são encadeadas através da produção e consumo de dados. De acordo com Deelman et al. [^69], a utilização de SGWCs permite que os cientistas se concentrem no experimento científico ao invés de dedicarem uma parcela do seu tempo à gerência de aspectos computacionais.

SGWCs já foram aplicados de forma bem-sucedida, por exemplo, à modelagem de distribuição de espécies [^70] [^71] [^72] [^73] [^74], permitindo um gerenciamento integrado das diversas atividades que compõem tais estudos. No contexto do SiBBr, é interessante que sejam disponibilizadas ferramentas de gerenciamento de workflows científicos para suporte a atividades de análise e síntese que sejam dadas pela composição de diferentes atividades computacionais. No SiBBr, há um trabalho preliminar [^75] [^76] que enfatiza a questão da escalabilidade e o registro de informações de proveniência de workflows científicos para modelagem de distribuição de espécies. Finalmente, a disponibilização de tais ferramentas através de portais científicos na web [^77] [^78] as tornaria mais acessíveis e permitiria a utilização eficiente de recursos computacionais disponíveis em infraestruturas distribuídas como o SINAPAD [^79]. Algumas iniciativas têm disponibilizado workflows científicos através de repositórios na web [^80] [^81] [^82].


#### Registrador de Serviços {#registrador-de-serviços}

Editor: 


#### Sistema de Suporte à Decisão {#sistema-de-suporte-à-decisão}

<p style="text-align: right">
Editor: George Porto Ferreira</p>


Sistema de Suporte à Decisão (SAD) é um sistema ou subsistema interativo, baseado em computador, destinado a ajudar os tomadores de decisão a utilizarem tecnologias de comunicação, dados, documentos, conhecimento e / ou modelos para identificar e resolver problemas, concluir tarefas do processo de tomada de decisão, e tomar decisões. “Sistema de Suporte à Decisão” é um termo geral para qualquer aplicação de computador que melhora a capacidade de uma pessoa ou grupo para tomar decisões [^83]. 

No nível conceitual, Power (2002) apud (Hättenschwiler & Gachet) enumera cinco tipos de Sistemas de Suporte à Decisão: Os dirigidos à comunicação (Communication-Driven DSS), os dirigidos à dados (Data-Driven DSS), Os dirigidos à documentos (Document-Driven DSS), os dirigidos à conhecimento (Knowledge-Driven DSS) e os dirigidos à modelos (Model-Driven DSS).

O SAD orientado a modelos enfatiza o acesso e manipulação de modelos estatísticos, financeiros, de otimização ou simulação. Estes sistemas orientados à modelos usam dados e parâmetros fornecidos pelos seus usuários para auxiliar os tomadores de decisão na análise de uma situação. Porém, estes sistemas não necessariamente usam dados de forma intensiva. SADs orientados a comunicação suportam mais de uma pessoa trabalhando em uma tarefa, de forma compartilhada. SADs orientados a dados enfatizam o acesso e manipulação de uma série temporal de dados internos de uma empresa e, algumas vezes, dados externos. SADs orientados a documentos gerenciam, recuperam e manipulam informações em formato eletrônico não estruturadas, em uma variedade de formatos. Por fim, SADs orientados ao conhecimento oferecem expertise especializada na solução de problemas, armazenada como fatos, regras e procedimentos, ou em estruturas similares [^84].

O Documento do Projeto [^85] cita que “_...Pelo menos quatro produtos (aplicativos de software) - para tomadores de decisão - serão discutidos e definidos no Produto 3.1. Possíveis produtos / ferramentas incluem: Sistema dinâmico de Lista Vermelha (Red List), Sistema de inventário da biodiversidade, Sistema de alerta precoce e Ferramenta de “inteligência empresarial” da biodiversidade._”

Ainda segundo o Documento do Projeto, “_Os produtos assumirão a forma de aplicativos novos ou melhorados que ofereçam ferramentas para facilitar a tomada de decisões sobre recursos naturais e ordenamento do território,  desenvolvimento das infraestruturas de conservação do projeto, decisões judiciais e legislativas, implementação de políticas públicas, bem como em qualquer outro setor público ou privado que intervêm em áreas naturais e que se beneficiarão do acesso a dados de biodiversidade._”


### Gestão {#gestão}

<p style="text-align: right">
Editor: </p>



# Referências {#referências}


<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     MCT - SEPED - CGEC. (2011, Setembro 29). Ajuda Memória de Reunião de Peritos em Sistemas de Informação sobre Biodibersidade. Brasília - DF.

[^2]:
     MCT - SEPED - CGEC. (2011, Dezembro 15 e 16). Ajuda Memória da 1a Reunião do Conitê Técnico Científico do SiBBr. Brasília - DF.

[^3]:
     MCTI - SEPED - CGEC. (2012, Fevereiro 15). Ajuda Memória da Primeira Reunião do Grupo de Trabalho de Arquitetura do SiBBr. Brasília - DF.

[^4]:
     MCTI - SEPED - CGEC. (2012, Março 5). Ajuda Memória da Reunião (Videoconferência) do CTC do SiBBr.

[^5]:
     Haren, V. (2011). The Open Group Architecture Framework (TOGAF) 9.1. Van Haren Publishing.

[^6]:

     Martinho, C., Costa, L., Junqueira, V., & Fecuri, J. (2003). Redes: Uma introdução às dinâmicas da conectividade e da auto-organização. (R. Kritsch, Ed.) Brasília-DF: WWF - Brasil.

[^7]:
     Consideramos neste documento como “instituições”, organizações governamentais, das esferas federal, estadual e municipal; e sociais de direito privado, sem fins lucrativos (Lei nº 9.637, de 15 de maio de 1998; e Lei nº 9.790, de 23 de março de 1999).

[^8]:
     DAMA International. (2012). O Guia da DAMA para o corpo de conhecimento em gestão de dados DAMA-DMBOK. (M. Mosley, Ed., & C. B. International, Trans.) São Paulo: Technics publications.

[^9]:
     Balke, M., Schmidt, S., Hausmann, A., Toussaint, E., Bergsten, J., Buffington, M., Hobern, D. (2013). Biodiversity into your hands - A call for a virtual global natural history ‘metacollection’. Frontiers in Zoology, 10(55).

[^10]:
     Zaher, H., & Young, P. S. (2003, Sept). As coleções zoológicas brasileiras: panorama e desafios. Retrieved Feb 28, 2014, from Ciência e Cultura: http://cienciaecultura.bvs.br/scielo.php?script=sci_arttext&pid=S0009-67252003000300017&lng=en&nrm=iso

[^11]:
     Baird, R. (2010). Leveraging the fullest potential of scientific collections through digitization. Biodiversity Informatics, pp. 130 - 136.

[^12]:
     Hobern, D., Apostolico, A., Bello, J. C., Canhos, D., Dubois, G., Field, D., Willoughby, S. (2013). Global Biodiversity Informatics Outlook: Delivering Biodiversity Knowledge in the Information Age.

[^13]:
     Cellinese, N., & Beaman, R. S. (2012). Mass digitization of scientific collections: New opportunities to transform the use of biological specimens and underwrite biodiversity science. ZooKeys, pp. 7-17.

[^14]:
     Drucker, D. P. (2011, Julho). Avanços na Integração e Gerenciamento de Dados Ecológicos. Natureza & Conservação, 9(1), pp. 115-120.

[^15]:
     Leite, F., Amaro, B., Batista, T., & Costa, M. (2012). Boas práticas para a construção de repositórios institucionais da produção científica. Cartilha, Ibict, Brasília.

[^16]:
     Valois, A.C.C.; Salomão, A.N.; Allem, A.C. Glossário de recursos genéticos vegetais. Brasília: Embrapa, 1996. Doc. No. 22, 62p.

[^17]:
     http://www.szb.org.br

[^18]:
     http://portal.fiocruz.br/pt-br/content/cole%C3%A7%C3%B5es-biol%C3%B3gicas

[^19]:
     https://www.inpa.gov.br/colecoes/colecoes2.php

[^20]:
     http://plataformarg.cenargen.embrapa.br

[^21]:
     Abbot, L., Bisby, F., & Rogers, D. (1985). Taxonomic Analysis in Biology - Computers, Models and Databases. New York, U.S.A.: Columbia University Press

[^22]:
     Bisby, F., & Allkin, R. (Eds.). (1984). Databases in Systematics (Vol. The Systematics Association Special Volume No. 26). London, UK: Academic Press.

[^23]:
     Bisby, F., Russel, G., & Pankhurst, R. (Eds.). (1993). Designs for a Global Plant Species Information System (Vol. The Systematics Association Special Volune No. 48). Oxford: Claredon Press.

[^24]:
     Fortuner, R. (Ed.). (1993). Advances in Computer Methods for Systematic Biology: Artificial Intelligence, Databases, Computer Vision. London: The Johns Hopkins University Press.

[^25]:
     Hawksworth, D., Kirk, P., & Clarke, S. (Eds.). (1997). Biodiversity Information Needs and Options. Wallingford, Oxon, UK: CAB International.

[^26]:
     Curry, G., & Humphries, C. J. (Eds.). (2007). Biodiversity Databases - Techniques, Politics and Applications (Vol. Thje Systematics Association Special Volume Series 73). London, UK: CRC Press.

[^27]:
     Davis, M. L., Tenopir, C., Allard, S., & Frame, M. T. (2014, January 17). Facilitating Access to Biodiversity Information: A Survey of Users' Needs and Practices. Environmental Management.

[^28]:
     CINDE - Comitê de Planejamento da Infraestrutura Nacional de Dados Espaciais. (2010). Plano de Ação para Implantação da Infraestrutura Nacional de Dados Espaciais - INDE. Rio de Janeiro, Brasil.

[^29]:
     Silvertown, J. (2009, September). A new dawn for citizen science. Trends in Ecology and Evolution, pp. 467-471.

[^30]:
     Bonney, R., Cooper, C. B., Dickinson, J., Kelling, S., Pjillips, T., Rosenberg, K. V., & Shirk, J. (2009, December). Citizen Science: A Developing Tool for Expanding Science Knowledge and Scientific Literacy. Bioscience, 59(11), pp. 977-984.

[^31]:
     Snaddon, J., Petrokofsky, G., Jepson, P., & Willis, K. J. (2013, February 23). Biodiversity technologies: tools as change agents. Biol. Lett., 9, pp. 1-3.

[^32]:
     Walls, R. L., Deck, J., Guralnick, R., Baskauf, S., Beaman, R., Blum, S., Wooley, J. (2014, March). Semantics in Support of Biodiversity Knowledge Discovery: An Introduction to the Biological Collections Ontology and Related Ontologies. PLOS ONE, 9(3).

[^33]:
     Amanqui, F. K., Serique, K. J., Lamping, F., Santos, J. C., Albuquerque, A. C., & Moreira, D. d. (2013). Implementing an Architecture for Semantic Search Systems for Retrieving Information in Biodiversity Repositories. Simpósio Brasileiro de Banco de Dados - SBBD 2013. Recife - PE.

[^34]:
     Albuquerque, A. C. (2011, Junho). Desenvolvimento de uma Ontologia de Domínio para Modelagem de Biodiversidade. Dissertação apresentada ao Curso de Pós-Graduação em Informática do Instituto de Ciências Exatas da Universidade Federal do Amazonas, como requisito parcial para a obtenção do grau de Mestre em Informática. Manaus, AM.

[^35]:
     Fegraus EH et al., 2005. Maximizing the value of ecological data with structured metadata: An introduction to ecological metadata language (EML) and principles for metadata creation. Bulletin of the Ecological Society of America, 86:158-168. http://dx.doi.org/10.1890/0012-9623(2005)86[158:MTVOED]2.0.CO;2

[^36]:
     Drucker, D. P. (2011, Julho). Avanços na Integração e Gerenciamento de Dados Ecológicos. Natureza & Conservação, 9(1), pp. 115-120.

[^37]:
     Michener WK et al., 2011. Long term ecological research and information management. Ecological Informatics, 6(1):13-24. http://dx.doi.org/10.1016/j.ecoinf.2010.11.005

[^38]:
     Jones MB et al., 2006. The new bioinformatics: integrating ecological data from the gene to the biosphere. Annual Review of Ecology, Evolution, and Systematics, 37:519-44. http://dx.doi.org/10.1146/annurev.ecolsys.37.091305.110031

[^39]:
     Joly CA et al., 2008. As parcelas permanentes do Projeto Temático BIOTA Gradiente Funcional: Composição florística, estrutura e funcionamento da Floresta Ombrófila Densa dos Núcleos Picinguaba e Santa Virgínia do Parque Estadual da Serra do Mar, São Paulo, Brasil. In: Sanquetta CA, editor. Experiências de monitoramento no bioma Mata Atlântica com uso de parcelas permanentes. Curitiba: Programa PELD-CNPq & Multigraph. p. 109-148.

[^40]:
     Costa FRC & Magnusson WE, 2010. The need for large-scale, integrated studies of biodiversity - the experience of the Program for Biodiversity Research in Brazilian Amazonia. Natureza & Conservação, 8(1):3-12.

[^41]:
     Michener WK et al., 2011. Long term ecological research and information management. Ecological Informatics, 6(1):13-24. http://dx.doi.org/10.1016/j.ecoinf.2010.11.005

[^42]:
     http://www.w3c.br/pub/Materiais/PublicacoesW3C/manual_dados_abertos_desenvolvedores_web.pdf

[^43]:
     http://dados.gov.br/cartilha-publicacao-dados-abertos

[^44]:
     http://pt.wikipedia.org/wiki/Dublin_Core

[^45]:
     Peixoto, A. L., Barbosa, M. d., Menezes, M., & Maia, L. C. (Eds.). (2006). Diretrizes e Estratégias para a Modernização de Coleções Biológicas Brasileiras e a Consolidação de Sistemas Integrados de Informação sobre Biodiversidade. Brasília - DF, Brasil: Centro de Gestão e Estudos Estratégicos - Ministério da Ciência e Tecnologia.

[^46]:
     Peixoto, A. L. (Ed.). (2003). Coleções Biológicas de Apoio ao Inventário, Uso Sustentável e Conservação da Biodiversidade. Rio de Janeiro, RJ, Brasil: Instituto de Pesquisas Jardim Botânico do Rio de Janeiro.

[^47]:
     GBIF. (2011). A Beginner's Guide to Persitent Identifiers - Version 1.0. Global Biodiversity Information Facility, Copenhagen.

[^48]:
     Gilman, E., King, N., Peterson, A. T., Chavan, V., & Hahn, A. (2009). Building the biodiversity data commons—the global biodiversity. In L. Maurer (Ed.), ICT for agriculture and biodiversity conservation (pp. 79-99). Graz: ICT Ensure, Graz University of Technology.

[^49]:
     CRIA. (2014, abril 1). SpeciesLink. Retrieved abril 1, 2014, from SpeciesLink: http://splink.cria.org.br/

[^50]:
     HAN, J., KAMBER, M., PEI, J. Data Mining: Concepts and Techniques. 3. ed. San Francisco: Morgan Kaufmann, 2011

[^51]:
     ELMASRI, R., NAVATHE, S. B. Sistemas de banco de dados. 6. ed. São Paulo: Editora Pearson Addison Wesley, 2011

[^52]:
     Page, R. D. (2014, abril 01). Rethinking annotating biodiversity data. (R. D. Page, Ed.) Retrieved 04 01, 2014, from iPhylo: http://iphylo.blogspot.com.br/2014/03/rethinking-annotating-biodiversity-data.html

[^53]:
     Morri, R. A., Dou, L., Hanken, J., Kelly, M., Lowery, D. B., Ludäscher, B., Morris, P. J. (2013, November 4). Semantic Annotation of Mutable Data. PLoS ONE, 11.

[^54]:
     Tschöpe, O., Macklin, J. A., Morris, R. A., Suhrbier, L., & Berendsohn, W. G. (2013, December). Annotating biodiversity data via the Internet. Taxon, 6, pp. 1248-1258.

[^55]:
     http://www.gbif.org/resources/2575

[^56]:

     http://ezid.cdlib.org/home/understanding

[^57]:
     http://en.wikipedia.org/wiki/Digital_object_identifier

[^58]:

     http://ezid.cdlib.org/home/understanding

[^59]:

     http://www.datacite.org/cdl_launch_ezid

[^60]:

     http://wiki.tdwg.org/twiki/bin/view/GUID/LSID

[^61]:

     http://purl.oclc.org/docs/index.html

[^62]:

     http://www.gbif.org/resources/2669

[^63]:
     Hey, T., Tansley, S., Tolle, K. (Eds.). The Fourth Paradigm: Data-Intensive Scientific Discovery. Microsoft Research, 2009. http://research.microsoft.com/en-us/UM/redmond/about/collaboration/fourthparadigm/4th_PARADIGM_BOOK_complete_HR.pdf

[^64]:
     Gray, J. et al. Scientific Data Management in the Coming Decade. SIGMOD Record 34, 41 (2005).

[^65]:
     Hey, T. e Trefethen, A. Cyberinfrastructure for e-Science. Science 308, 821 (2005).

[^66]:
     Mattoso, M. et al. Gerenciando Experimentos Científicos em Larga Escala. SEMISH - Seminário Integrado de Hardware e Software. Anais do XXVIII Congresso da SBC (2008). http://www.lbd.dcc.ufmg.br/colecoes/semish/2008/009.pdf

[^67]:
     Davidson, S., Freire, J. Provenance and Scientific Workflows: Challenges and Opportunities. In: Proc. 2008 ACM SIGMOD International Conference on Management of Data (SIGMOD’08), pp. 1345–1350, 2008.

[^68]:
     Cuevas-Vicenttín, Víctor, et al. Scientific workflows and provenance: Introduction and research opportunities. Datenbank-Spektrum 12.3 (2012): 193-203.

[^69]:
     Deelman, E. et al. Workflows and e-Science: An overview of workflow system features and capabilities,
    Future Generation Computer Systems, v. 25, n. 5, pp. 528 – 540, 2009.

[^70]:
     Pennington, D. D., Higgins, D., Peterson, A. T., Jones, M. B., Ludäscher, B., & Bowers, S. (2007). Ecological Niche Modeling Using the Kepler Workflow System. In I. J. Taylor, E. Deelman, D. B. Gannon, & M. Shields (Eds.), Workflows for e-Science (pp. 91–108). Springer London.

[^71]:
     Vicario, Saverio, Alex Hardisty, and Niobe Haitas. Biovel: biodiversity virtual e-laboratory. EMBnet. journal 17.2 (2011): pp-5.

[^72]:
     Morisette, J. T. et al. (2013). VisTrails SAHM: visualization and workflow management for species habitat modeling. Ecography, 36(2), 129–135.

[^73]:
     Candela, L., Castelli, D., Coro, G., Pagano, P., & Sinibaldi, F. (2013). Species distribution modeling in the cloud. Concurrency and Computation: Practice and Experience. doi:10.1002/cpe.3030

[^74]:
     Talbert, C., Talbert, M., Morisette, J., & Koop, D. (2013). Data Management Challenges in Species Distribution Modeling. IEEE Bulletin of the Technical Committee on Data Engineering, 36(4), 31–40.

[^75]:
     L. Gadelha, S. Stanzani, P. Corrêa; E. Dalcin, C. Gomes, L. Sato, M. Siqueira. Scalable and Provenance-Enabled Scientific Workflows for Predicting Distribution of Species. Proc. 8th International Conference on Ecological Informatics (ISEI 2012), p. 222-224. Brasília, 2012.

[^76]:
     https://github.com/sibbr/sdm-workflows

[^77]:
     Amaral, R. et al. (2014). Supporting biodiversity studies with the EUBrazilOpenBio Hybrid Data Infrastructure. Concurrency and Computation: Practice and Experience. doi:10.1002/cpe.3238

[^78]:
     Gomes, A. T. A., Bastos, B. F., Medeiros, V., & Moreira, V. M. (2014). Experiences of the Brazilian national high-performance computing network on the rapid prototyping of science gateways. Concurrency and Computation: Practice and Experience. doi:10.1002/cpe.3258

[^79]:
     https://www.lncc.br/sinapad/

[^80]:
     https://wiki.biovel.eu/display/doc/BioVeL+Workflows

[^81]:
     http://sciencepipes.org/

[^82]:
     http://www.myexperiment.org

[^83]:
     Power, D. J., Burstein, F., & Sharda, R. (2011). Reflections on the Past and Future of Decision Support Systems: Perspective of Eleven Pioneers. In D. Schuff, D. Paradice, F. Burstein, D. J. Power, & R. Sharda (Eds.), Decision Support - An examination of the DSS discipline (Vol. Annals of Information System 14, pp. 25-48). Springer.

[^84]:
     Hättenschwiler, P., & Gachet, A. (n.d.). Decision Support Systems. Retrieved abril 03, 2014, from Department of Informatics at the University of Fribourg: http://diuf.unifr.ch/ds/courses/dss2002/pdf/DSS.pdf

[^85]:
     Ministério da Ciência e Tecnologia. (2008). Documento do Projeto: Gerenciamento e uso de informações para ampliar a capacidade brasileira em conservar e utilizar a biodiversidade. Brasília - DF.
