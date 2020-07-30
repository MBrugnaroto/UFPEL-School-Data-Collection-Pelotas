# Coleção de dados das escolas de Pelotas
Dados coletados do INEP e do Portal Transparência da cidade de Pelotas contendo informações sobre as escolas da cidade de Pelotas-RS. Esse projeto tem como o intuito de realizar, posteriormente a coleta dos dados, análises sobre o ensino nas escolas e disponibiliza-las de forma estruturada, visível e clara. 

## Fontes dos *datasets*:

* **INEP:** [Oracle BI Interactive Dashboards](https://inepdata.inep.gov.br/analytics/saw.dll?dashboard&NQUser=inepdata&NQPassword=Inep2014&PortalPath=%2Fshared%2FCenso%20da%20Educa%C3%A7%C3%A3o%20B%C3%A1sica%2F_portal%2FCat%C3%A1logo%20de%20Escolas)<br>

* **Portal Pelotas:** [Portal de dados de Pelotas](http://www.pelotas.com.br/portal-de-dados)

## *Datasets*:
* **INEP:**
   * InformaçõesGeraisDasEscolas:
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
          'Outras Ofertas Educacionais': ,
          'Latitude': ,
          'Longitude': }</code>
          </pre>
   * MediaDeAlunosPorTurma:
        * Número de escolas registradas: 222
        * Quantidade de informações de cada escola: 23
        * Estrutura dos dados inseridos no Banco de Dados (BSON):
         <pre>
         <code>'Média de Alunos por Turma': 
            {
               'Última atualização': 2019.0,
               'Educação Infantil': 
                  {
                     'Total': '--', 
                     'Creche': '--', 
                     'Pré-Escola': '--'
                  },
               'Ensino Fundamental 8 e 9 anos': 
                  {
                     'Total': '--',
                     'Anos Iniciais': '--',
                     'Anos Finais': '--',
                     '1º Ano': '--',
                     '2º Ano': '--',
                     '3º Ano': '--',
                     '4º Ano': '--',
                     '5º Ano': '--',
                     '6º Ano': '--',
                     '7º Ano': '--',
                     '8º Ano': '--',
                     '9º Ano': '--',
                     'Turmas Multietapa, Multi ou Correção de Fluxo 2': '--'
                   },
               'Ensino Médio': 
                  {
                     'Total': 26.6,
                     '1ª série': 25,
                     '2ª série': 26,
                     '3ª série': 30,
                     '4ª série': '--',
                     'Não-Seriado': '--'}}
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


