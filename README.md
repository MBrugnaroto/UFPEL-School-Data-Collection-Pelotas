# Coleção de dados das escolas de Pelotas
Modelagem de um Banco de Dados (BD) MongoDB contendo as escolas de Pelotas-RS. Objetivo desse trabalho é modelar um BD com todas as informações sobre as escolas
da cidade de Pelotas com finalidade de melhorar a disponibilidade dessas informações para aplicações futuras.

## Fontes dos *datasets*:

* **INEP:** [Oracle BI Interactive Dashboards](https://inepdata.inep.gov.br/analytics/saw.dll?dashboard&NQUser=inepdata&NQPassword=Inep2014&PortalPath=%2Fshared%2FCenso%20da%20Educa%C3%A7%C3%A3o%20B%C3%A1sica%2F_portal%2FCat%C3%A1logo%20de%20Escolas)<br>

* **Portal Pelotas:** [Portal de dados de Pelotas](http://www.pelotas.com.br/portal-de-dados)

## *Datasets*:
 * dataINEP:
    * Número de escolas registradas: 302
    * Quantidade de informações de cada escola: 19
      * | Informação        | Número de registros não nulos        | Número de registros nulos        |
        | ------------- |:-------------:|:-------------:|
        | Restrição de Atendimento | 302 | 0 |
        | Escola  | 302 | 0 |
        | Código INEP  | 302 | 0 |
        | UF  | 302 | 0 |
        | Município  | 302 | 0 |
        | Localização  | 302 | 0 |
        | Localidade Diferenciada  | 302 | 0 |
        | Categoria Administrativa  | 302 | 0 |
        | Endereço  | 302 | 0 |
        | Telefone  | 292 | 10 |
        | Dependência Administrativa | 302 | 0 |
        | Categoria Escola Privada  | 302 | 0 |
        | Conveniada Poder Público  | 302 | 0 |
        | Regulamentação pelo Conselho de Educação  | 239 | 63 |
        | Porte da Escola  | 239 | 63 |
        | Etapas e Modalidade de Ensino Oferecidas  | 236 | 66 |
        | Outras Ofertas Educacionais  | 90 | 212 |
        | Latitude  | 198 | 104 |
        | Longitude  | 198 | 104 |

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
db = client.schoolData;
collection = db.dataINEPSchools;
collection.find_one();
</pre>
