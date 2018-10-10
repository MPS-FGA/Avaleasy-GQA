| Data       | Versão | Descrição            |         Autor             |
|:----------:|:------:|:--------------------:|:-------------------------:|
| 02/10/2018 | 0.1 | Criação do Documento  | [Arthur Diniz](https://github.com/arthurbdiniz) e [Victor Moura](https://github.com/victorcmoura) |

## 1. Resultado do Ciclo
<p align="justify">O Resultado do Ciclo é um relatório gerado após a realização das auditorias, contendo uma análise mais consolidada dos dados obtidos após a realização das auditorias.Em outras palavras, este resultado contém um resumo do que foi encontrado por todos auditores assim como o que aconteceu durante o processo de auditoria.

## 2. Template para o Resultado do Ciclo

### 2.1 Informações iniciais

<p align="justify">Inicialmente o Resultado do Ciclo deve possuir informações básicas relacionadas ao mesmo, sendo estas: Código da Auditoria, Data de Planejamento,Data de Execução,Data da Finalização.Estes são registrados em uma tabela no seguinte formato:

<table>
  <tr>
    <th>Código da Auditoria</th>
    <td>XXX</td>
  </tr>
  <tr>
    <th>Data de Planejamento</th>
    <td>XX/XX/XXXX</td>
  </tr>
  <tr>
    <th>Data de Execução</th>
    <td>XX/XX/XXXX</td>
  </tr>
  <tr>
    <th>Data da Finalização</th>
    <td>XX/XX/XXXX</td>
  </tr>
  <tr>
    <th>Revisor do Documento:</th>
    <td>Fulano de Tal</td>
  </tr>
</table>

### 2.2 Objetos auditados

<p align="justify">O segundo tópico do documento deve conter uma lista de todos os objetos que foram auditados, assim como uma explicação do porque este objeto ter sido escolhido para auditoria neste momento.Essa informação deve ser registrada em uma tabela neste formato:

<table>
  <tr>
    <th>Código Objeto</th>
    <th>Objeto</th>
    <th>Atividade relacionada a este objeto no processo</th>
  </tr>
  <tr>
    <th>XXX</th>
    <td>Artefato X</td>
    <td>Atividade X</td>
  </tr>
</table>

### 2.3 Técnicas Utilizadas

<p align="justify">Após a lista de objetos de auditoria, deverá existir uma tabela contendo as técnicas utilizadas para objeto de auditoria, assim como um link para o template padrão utilizado para cada técnica durante a auditoria.Essa tabela será no seguinte formato:

<table>
  <tr>
    <th>Issue</th>
    <th>Objeto</th>
    <th>Técnica Utilizada</tH>
    <th>Template</tH>
  </tr>
  <tr>
    <td>#123</td>
    <td>Objeto X</td>
    <td>Técnica X</td>
    <td>Template X</td>
  </tr>

</table>

### 2.4 Auditores

<p align="justify">Este tópico deve conter a lista de todos os auditores alocados para a realização das auditorias nos objetos selecionados, e um link para o Resultado Bruto gerado por cada um dos mesmos.
O link para o resultado bruto é importante pois este vai conter as não conformidades encontradas por cada um dos auditores, assim como a definição de prazos para resolução e propostas de melhoria.

<p align="justify">Essas informações devem ser apresentadas por meio de uma tabela no seguinte formato:

<table>
  <tr>
    <th>Nome do Auditor</th>
    <th>Objeto de Auditoria</th>
    <th>Resultado Bruto</th>
  </tr>
  <tr>
    <td>Fulano</td>
    <td>Objeto de Auditoria</th>
    <td>Link para resultado</td>
  </tr>
  <tr>
    <td>Ciclano</td>
    <td>Objeto de Auditoria</th>
    <td>Link para resultado</td>
  </tr>
</table>

### 2.5 Resumo das Não Conformidades
<p align="justify">Este tópico irá conter todas as não conformidades levantadas pelos auditores sendo apresentadas de forma resumida e clara.As mesmas devem ser disponibilizadas no seguinte formato:

<table>
  <tr>
    <th>Código Objeto</th>
    <th>Não Conformidade</th>
    <th>Complexidade</th>
    <th>Responsável</th>
    <th>Proposta de Solução</th>
  </tr>
  <tr>
    <th>XXX</th>
    <td>Não conformidade X</td>
    <td>Grave</td>
    <td>Equipe X </td>
    <td>Isto pode ser resolvido realizando tal atividade de tal maneira.</td>
  </tr>
</table>

### 2.6 Não conformidades não solucionadas

<p align="justify">Durante o processo de auditorias, as não conformidades encontradas são identificadas e sugestões de solução são apresentadas.Este tópico contém as não conformidades levantadas que não foram solucionadas no prazo determinado.

Estas serão apresentadas no seguinte formato:

<table>
  <tr>
    <th>Código Objeto</th>
    <th>Não Conformidade</th>
    <th>Complexidade</th>
    <th>Responsável</th>
    <th>Proposta de Solução</th>
  </tr>
  <tr>
    <th>XXX</th>
    <td>Não conformidade X</td>
    <td>Grave</td>
    <td>Equipe X </td>
    <td>Isto pode ser resolvido realizando tal atividade de tal maneira.</td>
  </tr>
</table>

### 2.7 Anexos

Anexos considerados importantes.

### 2.8 Análise de Causa Efeito

Utilizar uma técnica para fazer a análise de Causa-Efeito de acordo com a análise das não conformidades do Ciclo.

### 2.9 Propostas de Melhoria levantadas pela equipe de qualidade

<p align="justify">A equipe de garantia da qualidade possui um conhecimento a cerca da organização que permite realizar propostas de melhorias em alguns pontos que forem observados.Essas propostas podem ser relacionadas a atividades,artefatos gerados pelo processo, práticas adotadas pelas outras equipes, assim como propostas gerais para bom andamento do projeto.

Esse tópico conterá essas sugestões da equipe de garantia da qualidade para as outras equipes da organização.
