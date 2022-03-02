<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Métodos e Ferramentas de Engenharia de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula:
Nome:

1. (**2.00**) Você é o encarregado da área de desenvolvimento de software da sua empresa e foi convidado para coordenar os trabalhos necessários para migrar o banco de dados do _Oracle_ para o _Postgresql_. Sob a perspectiva das "Técnicas para a Resolução de Problemas", descreva pelo menos cinco atividades imprescindíveis neste trabalho.
**Resposta**: Entre as atividades que podemos realizar para migrar o banco sem grandes impactos podemos citar:
  2.1. a boa prática de evitar funções e extensões específicas de um SGBD, uma vez que existem facilidades em alguns SGBDs que fogem muito ao padrão SQL ou aos recursos normalmente oferecidos pelos demais SGBDs.
  2.2 Outra atividade que podemos fazer para evitar conflitos é utilizar identificadores para tabelas, colunas e outros objetos do seu banco de dados apenas com letras minúsculas, uma vez que alguns SGBDs como o Oracle e o SQL Server são case insentitive, enquanto outros como PostgreSQL e o MySQL são case sensitive.
  2.3 Outro detalhe ao qual devemos nos atentar é com relação à diferenças de codificação, uma vez que o Oracle utiliza o padrão unicode UTF-16 enquanto o PostgreSQL utiliza o padrão UTF-8, por exemplo.
  2.4 Outro detalhe muito importante nessa migração específica entre Oracle e Postgresql é que os tipos de dados diferem entre esses SGBDs. Ex.: Enquanto um número de tamanho variável é representado pelo tipo NUMBER no Oracle, o seu equivalente no Postgresql é o tipo NUMERIC.
  2.5 Outro exemplo de diferenças entre os dois SGBDs é que existem diferenças entre as consultas. Ex.: Não é possível substituir um LEFT JOIN ou um RIGHT JOIN por uma cláusula WHERE utilizando a sintaxe (+) do Oracle no PostgreSQL. É preciso declarar explicitamente o seu JOIN no PostgreSQL.

  Com essas 5 atividades descritas(que são apenas algumas das muitas que devemos estudar para realizar uma migração), podemos ter uma noção do quão importante e crítica pode ser uma migração de banco.

  **Focou apenas na perspectiva técnica. Existem várias questões gerenciais associadas a este problema, por exemplo planejamento, definição do cronograma, homologação, etc.**

  Nota = 1,0

2. (**2.00**) Seguindo os preceitos da Orientação a Objetos, solicita-se a implementação das classes constantes do diagrama de classes abaixo.
<div align=center>
  <img src="../../../definicao/oo.png">
</div>

**Não entregue**, Nota = 0,0

3. (**2.00**) Explique porque, em geral, é preferível a **composição** a **herança** nos projetos atuais de desenvolvimento de software.
**Resposta**: É preferível utilizar a composição à herança pois a Composição se baseia na ideia de "ter" ao invés de "ser". No caso da herança, a classe filha herda as características da pai, e é nomeada como a pai. Ex.: O gato e o cachorro são classes filhas da classe pai animal. Ambos são filhos da classe pai, e portanto, são animais. Já no caso da composição, a classe pode se apropriar de características de outra classe, sem necessariamente ser uma classe "filha" da classe original. Ex.: Supondo que temos a classe "dedo". Essa classe terá as características de um dedo. Agora ao criarmos uma classe "mão", podemos usar a Composição para utilizar as características dos dedos, o que não seria correto nesse caso para a herança, uma vez que uma mão não pode ser filha de um dedo. Além de tudo isso, na Composição, o comportamento pode ser escolhido em tempo de execução em vez de estar amarrado em tempo de compilação.

**Ateve-se somente ao quê da questão e não ao porque. Por exemplo explicar que com a composição fica mais fácil tanto a reutilização, promove o desacoplamento, etc.**

Nota = 1.0

4. (**2.00**) Considerando Linguagens de Programação compiladas e interpretadas, descreva vantagens e desvantagens de um modelo sobre o outro e em que cenários estas vantangens e desvantagens se apresentam.
**Resposta**: O processo de compilação envolve converter o nosso código para linguagem de máquina através de um programa chamado compilador. O compilador seleciona o código inteiro, converte ele inteiro para binário e guarda o resultado em um único “pacote”, que já vai para o cliente final pronto para ser executado. Entre as vantagens do código compilado, podemos ressaltar o nível de proteção maior do mesmo, uma vez que o cliente não tem acesso ao código-fonte, recebendo apenas o código binário executável. A segunda maior vantagem é a performance, uma vez  que já temos à mão tudo aquilo que é necessário para a execução, o que aumenta muito a velocidade deste processo. A desvantagem, é que nesse modelo o código tem que ser compilado manualmente. Você precisa "remontar" o programa sempre que precisar fazer uma alteração.
No caso do código interpretado, um programa chamado interpretador converte nosso código para linguagem de máquina. Contudo, esse processo irá ocorrer aos poucos, pois o interpretador irá realizar a conversão analisando linha por linha, e não o programa inteiro, diferentemente do que ocorre com o compilador. Entre as maiores vantagens desse modelo, podemos apontar a maior facilidade de realizar o debug do código, uma vez que a interpretação ocorre aos poucos, e por isso podemos visualizar com mais facilidade os erros que podem aparecer, e se identificarmos problemas, poderemos resolvê-los imediatamente. Entretanto, temos a desvantagem de ser um processo mais lento, uma vez que o processo de interpretação será mais lento, pois será executado de maneira repetida. Isso não é muito percebido pelo usuário, uma vez que ambos modelos não são executados "por debaixo dos panos". Porém, com o número crescente de linhas de código, a diferença de tempo se torna evidente para os desenvolvedores.

Nota = 2.0

5. (**2.00**) Sob a perspectiva do usuário/cliente, qual a vantagem de se empregar o paradigma de desenvolvimento orientado a objetos ao invés do paradigma estruturado?
**Resposta**: Os dois paradigmas são bem diferentes, sendo o estruturado um paradigma onde se desenvolve em sequência, com pouca reutilização de código, enquanto o orientado a objetos já é possível executar o sistema de forma modularizada através das classes, e o encapsulamento e reuso de dados também é possível. A nível de cliente, podemos dizer que o conceito de Abstração, que faz parte do paradigma orientado a objetos é uma vantagem do mesmo, uma vez que é uma forma de abstrair o quão complexo é um método ou rotina de um sistema, ou seja, o usuário não necessita saber todos os detalhes de como sua implementação foi realizada, apenas para que serve determinada rotina e qual o resultado esperado da mesma. Sendo assim, podemos também dividir internamente problemas complexos em problemas menores, onde resolvemos cada um deles até encontrarmos a solução do problema inteiro. Outra vantagem do paradigma é a confiabilidade do sistema que o utiliza, uma vez que ao alterar parte do código, o programa deve continuar funcionando, diferentemente do paradigma estruturado, que precisa seguir uma sequência de execução. Podemos ressaltar também que por ser um paradigma mais complexo, o mesmo favorece a escalabilidade de software.

Nota = 2.0


INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega:
   1. As questões discursivas devem ser respondidas neste mesmo arquivo, logo abaixo da sua definição.
   2. Quanto a questão 2, deverá ser implementada na Linguagem de Programação e IDE de sua preferência. Terminando a implementação, junte todo o código fonte, com este arquivo **prova_p1.md** e crie um arquivo compactado chamado **prova_p1_mat.md**, onde mat é o número da sua matrícula. Este arquivo compactado é que deverá ser submetido.
3. Data da Entrega: 16/02/2022, as 23h59min.
4. Critério de Aceitação: arquivos entregues, conforme solicitado.
