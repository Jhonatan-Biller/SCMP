Universidade Federal do Paraná          <br>
Programa de Pós-Graduação em Matemática <br>
Álgebra Linear Aplicada                 <br>
Professor Leonardo Silva de Lima        <br>
<h2>
  Problema proposto: Redução de Dimensionalidade através da Decomposição
  por Valores Singulares e Agrupamento 
</h2>

<p>  
  &nbsp; Open Clusters são sistemas estelares que compartilham uma origem comum.
  Eles têm uso generalizado na Astronomia, pois são fundamentais para a com-
  preensão da formação e evolução estelar, bem como da dinâmica e estrutura
  das galáxias. Certas caracterı́sticas fotométricas de estrelas num aglomerado
  podem indicar que elas se formaram a partir de uma mesma nuvem primor-
  dial dentro de uma escala de tempo relativamente curta. Isto é importante,
  uma vez que todas as estrelas membros do aglomerado deveriam ter aproxi-
  madamente a mesma idade e compartilhar propriedades quı́micas. Além disso,
  estudos que compreendem vários open clusters podem ajudar-nos a compreen-
  der tanto a formação como a cinemática do disco galáctico devido à propagação
  da idade do aglomerado e às distribuições de massa. Assim, o estudo de idades,
  distâncias, massas, luminosidade e funções de massa de open clusters constituem
  importantes tópicos de pesquisa em Astronomia. Neste contexto, um dos de-
  safios mais fundamentais é o problema de descobrir quais são os membros do
  aglomerado estelar num determinado campo estelar.
</p>
<p>
  &nbsp;Este problema consiste em segregar o campo e o aglomerado de estrelas em
  um determinado campo a partir de catálogos gerados a partir de imagens de
  um telescópio. Tal procedimento é conhecido como atribuição de membros, ou
  segregação de membros (denotamos esse problema como Stellar Cluster Mem-
  bership Assignment Problem, ou SCMP). Normalmente, os dados mais difundi-
  dos disponı́veis para resolver o problema são as posições de cada estrela, bem
  como os seus parâmetros fotométricos. Esses parâmetros estão relacionados à
  medição da magnitude de cada estrela em cada banda passante de comprimento
  de onda. Veja as seguintes informações abaixo:
</p>
<ol>
  <li>
    Considere o arquivo “STARS-144.txt” disponı́vel no Teams da disciplina
    contendo as informações de aproximadamente 500 estrelas. Cada linha do ar-
    quivo corresponde a uma estrela com suas 18 caracterı́sticas: as duas primeiras
    colunas dizem respeito às coordenadas x e y de cada estrela e as restantes dizem
    respeito às caracterı́sticas fotométricas da estrela. A última coluna (coluna 19)
    apresenta valor 1 se a estrela pertence ao open cluster e 0 caso contrário.
  </li>
  <li>
    Considere padronizar (ou normalizar) os dados antes de realizar a tarefa de
    redução de dimensionalidade. Isto porque a ordem de grandeza dos dados pode
    ser muito diferente e impactar na decomposição. Exemplos de técnicas são o
    z-score e o min-max.
  </li>
  <li>
    Implemente a rotina de Decomposição por Valores Singulares. Após a
    Etapa 2, realize a decomposição por valores singulares nos dados da estrela
    para a redução de dimensionalidade. Faça testes com dimensionalidades 3, 4 e
    5 e compare os resultados obtidos.
  </li>
  <li>
    Use um algoritmo de agrupamento (clustering) já disponı́vel na literatura
    (por exemplo, o k-means) para agrupar as estrelas abaixo em dois grupos dis-
    tintos (grupo 1 do open cluster e grupo 2 fora do open cluster). Na sequência,
    verifique o percentual de assertividade do método com a classificação dada na
    última coluna do arquivo “STARS-144.txt”.
  </li>
  <li>
    Faça uma tabela contendo os percentuais de assertividade para cada redução
    de dimensionalidade realizada.
  </li>
</ol>
