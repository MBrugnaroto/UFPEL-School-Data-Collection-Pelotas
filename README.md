# Coleção de dados das escolas de Pelotas
Dados coletados do INEP e do Portal Transparência da cidade de Pelotas contendo informações sobre as escolas da cidade de Pelotas-RS. Esse projeto tem como o intuito de realizar, posteriormente a coleta dos dados, análises sobre o ensino nas escolas e disponibiliza-las de forma estruturada, visível e clara. 

## Fontes dos *datasets*:

* **INEP:** 
    * [Oracle BI Interactive Dashboards](https://inepdata.inep.gov.br/analytics/saw.dll?dashboard&NQUser=inepdata&NQPassword=Inep2014&PortalPath=%2Fshared%2FCenso%20da%20Educa%C3%A7%C3%A3o%20B%C3%A1sica%2F_portal%2FCat%C3%A1logo%20de%20Escolas)<br>
    * [Indicadores Educacionais](http://inep.gov.br/web/guest/indicadores-educacionais)
* **Portal Pelotas:** 
    * [Portal de dados de Pelotas](http://www.pelotas.com.br/portal-de-dados)

## *Datasets*:
* **INEP:**
   * InformaçõesGeraisDasEscolas:
       * **OBS:** Através da ferramenta Oracle BI do INEP, foi filtrado as escolas de Pelotas e realizado o *download* do *dataset*, assim, não sendo necessário o *download* do *dataset* completo contendo todas as escolas registradadas.
       * Número de escolas registradas: 302.
       * Quantidade de informações de cada escola: 19.
       * Descrição: dados das escolas de pelotas, contendo informações como endereço, localização, nome da escola, código da escola, entre outros.
        
    * MediaDeAlunosPorTurma:
        * Número de escolas registradas: 176.386.
        * Número de escolas de Pelotas registradas: 228.
        * Quantidade de informações de cada escola: 31.
        * Descrição: média de alunos por cada turma em cada escola no ano expecífico.

    * MediaHorasAulaDiarias:
        * Número de escolas registradas: 152.509.
        * Número de escolas de Pelotas registradas: 224.
        * Quantidade de informações de cada escola: 30.
        * Descrição: número médio de horas aula diário por cada turma em cada escola no ano expecífico.

   * TaxaDistorcaoIdadeSerie:
        * Número de escolas registradas: 132.428.
        * Número de escolas de Pelotas registradas: 135.
        * Quantidade de informações de cada escola: 26.
        * Descrição: taxa de distorção idade serie por cada turma em cada escola no ano expecífico.

   * TaxaRendimento:
        * Número de escolas registradas: 134.457.
        * Número de escolas de Pelotas registradas: 136.
        * Quantidade de informações de cada escola: 63.
        * Descrição: percentual de rendimento (aprovação, reprovação e abandono) por cada turma em cada escola no ano expecífico.

   * TaxaDeNaoResposta:
        * Número de escolas registradas: 134.457.
        * Número de escolas de Pelotas registradas: 136.
        * Quantidade de informações de cada escola: 27.
        * Descrição: percentual de matrículas que não tiveram as informações de rendimento/movimentação computadas na situação do aluno por falta de informação ou por incosistência por cada turma em cada escola no ano expecífico.
   
   * PercentualDocentesComCursoSuperior:
        * Número de escolas registradas: 180.331.
        * Número de escolas de Pelotas registradas: 236.
        * Quantidade de informações de cada escola: 19.
        * Descrição: percentual de funções docentes com curso superior por etapa/modalidade de ensino em cada escola no ano expecífico.
   
   * AdequaçãoFormacaoDocente:
        * Número de escolas registradas: 177.714.
        * Número de escolas de Pelotas registradas: 224.
        * Quantidade de informações de cada escola: 44.
        * Descrição: percentual de docentes por grupo de adequação da formação á disciplina que leciona em cada escola no ano expecífico. O docente é contabilizado em cada turma e disciplina que leciona. Inclui os professores responsáveis pela regência de classe e os professores responsáveis pela regência de módulo ou disciplina de turma desenvolvida em curso de modalidade de educação a distância. O indicador classifica o docente segundo a adequação de sua formação inicial a cada disciplina que leciona na educação básica, levando-se em conta as normatizações legais vigentes (nacionais). A tabela apresenta o percentual de docências na respectiva unidade da agregação classificadas em cada uma das categorias do indicador. Categorias de adequação da formação dos docentes em relação à disciplina que leciona:
            * Grupo 1 - Docentes com formação superior de licenciatura (ou bacharelado com complementação pedagógica) na mesma área da disciplina que leciona.
            * Grupo 2 - Docentes com formação superior de bacharelado (sem complementação pedagógica) na mesma área da disciplina que leciona.
            * Grupo 3 - Docentes com formação superior de licenciatura (ou bacharelado com complementação pedagógica) em área diferente daquela que leciona.
            * Grupo 4 - Docentes com formação superior não considerada nas categorias anteriores.
            * Grupo 5 - Docentes sem formação superior.
            
   * RegularidadeCorpoDocente:
        * Número de escolas registradas: 166.177.
        * Número de escolas de Pelotas registradas: 208.
        * Quantidade de informações de cada escola: 10.
        * Descrição: o indicador tem por objetivo avaliar a regularidade do corpo docente nas escolas de educação básica a partir da observação da permanência dos professores nas escolas nos últimos cinco anos (2015 a 2019). Para cada docente em cada escola foi atribuída uma pontuação de forma que fosse valorizado: o total de anos em que o docente atuou na escola nos últimos 5 anos, a atuação do docente na escola em anos mais recentese a atuação em anos consecutivos. O Indicador de Regularidade do Docente varia de 0 a 5, quanto mais próximo de 0, mais irregular é o vínculo do docente com a escola e quanto mais próximo de 5, mais regular é esse vínculo. O indicador de regularidade de cada escola é obtido a partir da média do indicador de regularidade de seus docentes, e representa assim, a regularidade média do corpo docente da escola. Inclui os professores responsáveis pela regência de classe e os professores responsáveis pela regência de módulo ou disciplina de turma desenvolvida em curso de modalidade de educação a distância.
    
   * EsforcoDocente:
        * Número de escolas registradas: 134.152.
        * Número de escolas de Pelotas registradas: 139.
        * Quantidade de informações de cada escola: 33.
        * Descrição: o indicador classifica o docente em níveis de 1 a 6 de acordo com o esforço empreendido no exercício da profissão, níveis elevados indicam maior esforço. A partir dos dados disponíveis no Censo da Educação Básica, considerou-se que o esforço docente está relacionado às seguintes características da docência: número de escolas em que atua, número de turnos de trabalho, número de alunos atendidos e número de etapas nas quais leciona. A tabela apresenta o percentual de docentes que lecionam na respectiva agregação em cada um dos níveis da escala do indicador. Como o horário de início das turmas com mediação didático-pedagógica semipresencial ou a distância (EAD) não é coletado no Censo Escolar, os docentes que atuam em uma ou mais turmas nessas mediações têm o número de turnos de trabalho (definido pelo horário de início das turmas) tratado como ausente. Os níveis do indicador são descritos abaixo de acordo com as características usuais dos docentes pertencentes a cada um deles:
             * Nível 1 - Docente que, em geral, tem até 25 alunos e atua em um único turno, escola e etapa.
             * Nível 2 - Docente que, em geral, tem entre 25 e 150 alunos e atua em um único turno, escola e etapa.
             * Nível 3 - Docente que, em geral, tem entre 25 e 300 alunos e atua em um ou dois turnos em uma única escola e etapa.
             * Nível 4 - Docente que, em geral, tem entre 50 e 400 alunos e atua em dois turnos, em uma ou duas escolas e em duas etapas.
             * Nível 5 - Docente que, em geral, tem mais de 300 alunos e atua nos três turnos, em duas ou três escolas e em duas etapas ou três etapas.
             * Nível 5 - Docente que, em geral, tem mais de 300 alunos e atua nos três turnos, em duas ou três escolas e em duas etapas ou três etapas.
             * Nível 6 - Docente que, em geral, tem mais de 400 alunos e atua nos três turnos, em duas ou três escolas e em duas etapas ou três etapas.
        
   * ComplexidadeGestaoEscola:
        * Número de escolas registradas: 180.610.
        * Número de escolas de Pelotas registradas: 236.
        * Quantidade de informações de cada escola: 10.
        * Descrição: O indicador classifica as escolas em níveis de 1 a 6 de acordo com sua complexidade de gestão, níveis elevados indicam maior complexidade. Com base nos dados disponíveis do Censo da Educação Básica, considerou-se que a complexidade de gestão está relacionada às seguintes características: porte da escola, número de turnos de funcionamento, quantidade e complexidade de modalidades/etapas oferecidas. Como o horário de início das turmas com mediação didático-pedagógica semipresencial ou a distância (EAD) não é coletado no Censo Escolar, as escolas que ofertam uma ou mais turmas nessas mediações têm o número de turnos de funcionamento (definido pelo horário de início das turmas) tratado como ausente. Os níveis de complexidade de gestão são descritos abaixo de acordo com as características predominantes das escolas pertencentes a cada um deles:
            * Nível 1 -  Escolas que, em geral, possuem porte inferior a 50 matrículas, funcionam em único turno, ofertam uma única etapa de ensino e apresentam a Educação Infantil ou os Anos Iniciais como etapa mais elevada*.
            * Nível 2 -  Escolas que, em geral, possuem porte entre 50 e 300 matrículas, funcionam em 2 turnos, com oferta de até 2 etapas de ensino e apresentam a Educação Infantil ou os Anos Iniciais como etapa mais elevada*.
             * Nível 3 -  Escolas que, em geral, possuem porte entre 50 e 500 matrículas, funcionam em 2 turnos, com oferta de 2 ou 3 etapas de ensino e apresentam os Anos Finais como etapa mais elevada*.
             * Nível 4 -  Escolas que, em geral, possuem porte entre 150 e 1000 matrículas, funcionam em 2 ou 3 turnos, com oferta de 2 ou 3 etapas de ensino e apresentam o Ensino Médio, a Educação Profissional ou a EJA como etapa mais elevada*.
             * Nível 5 -  Escolas que, em geral, possuem porte entre 150 e 1000 matrículas, funcionam em 3 turnos, com oferta de 2 ou 3 etapas de ensino e apresentam a EJA como etapa mais elevada*.
             * Nível 6 -  Escolas que, em geral, possuem porte superior a 500 matrículas, funcionam em 3 turnos, com oferta de 4 ou mais etapas de ensino e apresentam a EJA como etapa mais elevada*.
             * Considerou-se como a etapa mais elevada ofertada pela escola aquela que atenderia, teoricamente, alunos com idade mais elevada.
        
   * IndicadorNivelSocioeconomico:
        * Número de escolas registradas: 63.258.
        * Número de escolas de Pelotas registradas: 94.
        * Quantidade de informações de cada escola: 10.
        * Descrição: [Informações gerais sobre o indicador de nível socioeconomico](http://download.inep.gov.br/informacoes_estatisticas/indicadores_educacionais/2015/nota_tecnica/nota_tecnica_inep_inse_2015.pdf)
        
## Conexão com o BD:
O BD foi hospedado na plataforma da [mLab](https://mlab.com/) (*Database-as-a-Service for MongoDB*) por conta da navegabilidade, segurança, automatização em núvem e disponibilidade de 500mb de armazenamento grátis.

Comando para conexão com o *client*:
- Os seguintes bancos de dados estão disponíveis nessa conexão: *schoolData* (utilizado para armazenar informações sobre as escolas de Pelotas)
<pre>
client = pymongo.MongoClient("mongodb://USUARIO:PASSWORD@criedata-shard-00-00.urzuu.mongodb.net:27017,criedata-shard-00-01.urzuu.mongodb.net:27017,criedata-shard-00-02.urzuu.mongodb.net:27017/<dbname>?ssl=true&replicaSet=atlas-6db9id-shard-0&authSource=admin&retryWrites=true&w=majority");
</pre>

Comando para acesso as *collections*:
- As seguintes *collections* estão disponíveis: *dataINEPSchools* (dados provindos do banco de dados do INEP)
<pre>
<code>db = client.schoolData;</code>
<code>collection = db.dataINEPSchools;</code>
<code>collection.find_one();</code>
</pre>


