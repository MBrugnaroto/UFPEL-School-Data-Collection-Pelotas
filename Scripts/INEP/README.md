## Estrutura dos dados inseridos no Banco de Dados (BSON):
* **INEP:**
   * InformaçõesGeraisDasEscolas:
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
       &nbsp;&nbsp;&nbsp;&nbsp;'9º Ano': ''),
       &nbsp;&nbsp;'Ensino Médio': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'1ª série': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'2ª série': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'3ª série': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'4ª série': ''}}</code>
       </pre>
  * PercentualDocentesComCursoSuperior:
       <pre>
       <code>'Percentual de funções docentes com curso superior': {
       &nbsp;&nbsp;'Última atualização': '',
       &nbsp;&nbsp;'Educação Infantil': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Total': '', 
       &nbsp;&nbsp;&nbsp;&nbsp;'Creche': '', 
       &nbsp;&nbsp;&nbsp;&nbsp;'Pré-Escola': ''},
       &nbsp;&nbsp;'Ensino Fundamental': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Total': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos Iniciais': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos Finais': ''},
       &nbsp;&nbsp;'Ensino Médio': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Educação Profissional': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Educação de Jovens e Adultos (EJA)': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Educação Especial': ''}}</code>
       </pre>
  * AdequaçãoFormacaoDocente:
       <pre>
       <code>'Percentual de docentes por grupo do indicador de adequação da formação do docente': {
       &nbsp;&nbsp;'Última atualização': '',
       &nbsp;&nbsp;'Educação Infantil': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''},
       &nbsp;&nbsp;'Ensino Fundamental': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Total': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''},
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos iniciais': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''},
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos finais': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''}},
       &nbsp;&nbsp;'Ensino Médio': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''},
       &nbsp;&nbsp;'EJA': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Ensino Fundamental': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''},
       &nbsp;&nbsp;&nbsp;&nbsp;'Ensino Médio': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': ''}}}}</code>
       </pre>
  * RegularidadeCorpoDocente:
       <pre>
       <code>'Regularidade do corpo docente': {
       &nbsp;&nbsp;'Última atualização': '',
       &nbsp;&nbsp;'Média do Indicador de Regularidade do Docente (IRD) Infantil': ''}}</code>
       </pre>
  * EsforcoDocente:
       <pre>
       <code>'Esforço docente': {
       &nbsp;&nbsp;'Última atualização': '',
       &nbsp;&nbsp;'Ensino Fundamental': {
       &nbsp;&nbsp;&nbsp;&nbsp;'Total': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 6': ''},
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos iniciais': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 6': ''},
       &nbsp;&nbsp;&nbsp;&nbsp;'Anos finais': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 6': ''}},
       &nbsp;&nbsp;&nbsp;&nbsp;'Ensino Médio': {
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 1': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 2': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 3': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 4': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 5': '',
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Grupo 6': ''}}}</code>
       </pre>
  * ComplexidadeGestaoEscola:
       <pre>
       <code>'Indicador de complexidade de gestão da escola': {
        &nbsp;&nbsp;'Última atualização': '',
        &nbsp;&nbsp;'Nível de complexidade de gestão da escola': ''}}</code>
       </pre>
  * IndicadorNivelSocioeconomico:
       <pre>
       <code>'Indicador de nível socioeconômico': {
        &nbsp;&nbsp;'Última atualização': '',
        &nbsp;&nbsp;'Quantidade de Alunos com INSE': '',
        &nbsp;&nbsp;'Média do Indicador de Nível Socioeconômico dos alunos': '',
        &nbsp;&nbsp;'Classificação do Indicador de Nível Socioeconômico': ''}}  }</code>
       </pre>
     
