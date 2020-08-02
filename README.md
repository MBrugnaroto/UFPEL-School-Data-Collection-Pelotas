# Coleção de dados das escolas de Pelotas
Dados coletados do INEP e do Portal Transparência da cidade de Pelotas contendo informações sobre as escolas da cidade de Pelotas-RS. Esse projeto tem como o intuito de realizar, posteriormente a coleta dos dados, análises sobre o ensino nas escolas e disponibiliza-las de forma estruturada, visível e clara. 

## Fontes dos *datasets*:

* **INEP:** 
    * [Oracle BI Interactive Dashboards](https://inepdata.inep.gov.br/analytics/saw.dll?dashboard&NQUser=inepdata&NQPassword=Inep2014&PortalPath=%2Fshared%2FCenso%20da%20Educa%C3%A7%C3%A3o%20B%C3%A1sica%2F_portal%2FCat%C3%A1logo%20de%20Escolas)<br>
    * [Indicadores Educacionais](http://inep.gov.br/web/guest/indicadores-educacionais)
* **Portal Pelotas:** [Portal de dados de Pelotas](http://www.pelotas.com.br/portal-de-dados)

## *Datasets*:
* **INEP:**
   * InformaçõesGeraisDasEscolas:
       * **OBS:** Através da ferramenta Oracle BI do INEP, foi filtrado as escolas de Pelotas e realizado o *download* do *dataset*, assim, não sendo necessário o *download* do *dataset* completo contendo todas as escolas registradadas.
       * Número de escolas registradas: 302.
       * Quantidade de informações de cada escola: 19.
       * Estrutura dos dados inseridos no Banco de Dados (BSON):
         <pre>
         <code>{'_id': ObjectId(''),
          'Restrição de Atendimento': '',
          'Escola': '',
          'Código INEP': ,
          'UF': '',
          'Município': '',
          'Localização': '',
          'Localidade Diferenciada': '',
          'Categoria Administrativa': '',
          'Endereço': '',
          'Telefone': '',
          'Dependência Administrativa': '',
          'Categoria Escola Privada': '',
          'Conveniada Poder Público': '',
          'Regulamentação pelo Conselho de Educação': '',
          'Porte da Escola': '',
          'Etapas e Modalidade de Ensino Oferecidas': '',
          'Outras Ofertas Educacionais': '',
          'Latitude': '',
          'Longitude': ''}</code>
          </pre>
    * MediaDeAlunosPorTurma:
        * Número de escolas registradas: 176.386.
        * Número de escolas de Pelotas registradas: 228.
        * Quantidade de informações de cada escola: 31
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
         <pre>
         <code>'Média de Alunos por Turma': {
               &nbsp;&nbsp;'Última atualização': '',
               &nbsp;&nbsp;'Educação Infantil': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '', 
               &nbsp;&nbsp;&nbsp;&nbsp;'Creche': '', 
               &nbsp;&nbsp;&nbsp;&nbsp;'Pré-Escola': ''},
               &nbsp;&nbsp;'Ensino Fundamental 8 e 9 anos': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'9º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Turmas Multietapa, Multi ou Correção de Fluxo 2': ''},
               &nbsp;&nbsp;'Ensino Médio': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Não-Seriado': ''}}</code>
               </pre>
    * MediaHorasAulaDiarias:
        * Número de escolas registradas: 152.509.
        * Número de escolas de Pelotas registradas: 224.
        * Quantidade de informações de cada escola: 30.
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
        <pre>
         <code>'Média Horas-Aula diárias': {
               &nbsp;&nbsp;'Última atualização': '',
               &nbsp;&nbsp;'Educação Infantil': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '', 
               &nbsp;&nbsp;&nbsp;&nbsp;'Creche': '', 
               &nbsp;&nbsp;&nbsp;&nbsp;'Pré-Escola': ''},
               &nbsp;&nbsp;'Ensino Fundamental 8 e 9 anos': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'9º Ano': '',
               &nbsp;&nbsp;'Ensino Médio': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Não-Seriado': ''}}</code>
               </pre>
   * TaxaDistorcaoIdadeSerie:
        * Número de escolas registradas: 132.428.
        * Número de escolas de Pelotas registradas: 135.
        * Quantidade de informações de cada escola: 26.
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
        <pre>
         <code>'Taxa de distorção de idade-série por turma': {
               &nbsp;&nbsp;'Última atualização': '',
               &nbsp;&nbsp;'Ensino Fundamental 8 e 9 anos': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'9º Ano': '',
               &nbsp;&nbsp;'Ensino Médio': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4ª série': ''}}</code>
               </pre>
   * TaxaRendimento:
        * Número de escolas registradas: 134.457.
        * Número de escolas de Pelotas registradas: 136.
        * Quantidade de informações de cada escola: 63.
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
        <pre>
         <code>'Taxa de rendimento escolar': {
               &nbsp;&nbsp;'Última atualização': '',
               &nbsp;&nbsp;'Ensino Fundamental 8 e 9 anos': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de aprovação': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&'9º Ano': ''},
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de reprovação': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&'9º Ano': ''}},
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de abandono': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&'9º Ano': ''}},
               &nbsp;&nbsp;'Ensino Médio': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de aprovação': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Não-Seriado': ''},
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de reprovação': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4ª série': '--',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Não-Seriado': '--'},
               &nbsp;&nbsp;&nbsp;&nbsp;'Taxa de abandono': {
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'4ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Não-Seriado': ''}}
               }</code>
               </pre>
   * TaxaDeNaoResposta:
        * Número de escolas registradas: 134.457.
        * Número de escolas de Pelotas registradas: 136.
        * Quantidade de informações de cada escola: 27.
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
        <pre>
         <code>'Taxa de distorção de idade-série por turma': {
               &nbsp;&nbsp;'Última atualização': '',
               &nbsp;&nbsp;'Ensino Fundamental 8 e 9 anos': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'5º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'6º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'7º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'8º Ano': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'9º Ano': '',
               &nbsp;&nbsp;'Ensino Médio': {
               &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
               &nbsp;&nbsp;&nbsp;&nbsp;'4ª série': ''}}</code>
               </pre>
        
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


