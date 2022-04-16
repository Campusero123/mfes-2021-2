<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Métodos e Ferramentas de Engenharia de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 13/04/2022</p>

Matrícula:<font color="red">??????????</font>
Nome:<font color="red">??????????</font>

<font color="green">Nota 8,3</font>

1. (**2.00 Pontos**) Descrever pelo menos três modelos de Persistência de dados, criados e utilizados pela computação ao longo da sua história.

Resposta:
  * Modelo Relacional: Seguem um paradigma de orientação a conjuntos, no qual os dados se relacionam e são organizados em estruturas de tabelas, que têm em sua composição  colunas, tuplas e registros.

  Esses tipos de bancos proporcionam mais facilidade de inserção e recuperação dos dados e são mais indicados para sistemas que necessitem de uma grande consistência de dados. Oracle, SQL Server e MySQL são exemplos.

  * Modelo Não Relacional: soluções para casos em que não é possível organizar os dados de forma relacional — quando temos dados mistos como imagens e tabelas, por exemplo, que tornam inviáveis a organização no sistema de linhas e colunas. Esses bancos também são conhecidos como NoSQL. MongoDB, Redis e Cassandra. <font color="red">Nota 1,3</font>

2. (**2.00 Pontos**) Descreva um comparativo entre os modelos de dados relacional (SQL) e Não Relacional. Destacar as vantagens/desvantagens de um sobre o outro. Identificar em quais domínios de aplicações em que são utilizados.

Resposta:
O banco de dados relacional sempre irá fornecer dados íntegros e imutáveis, garantindo um controle transacional consistente. Além disso, seu esquema é rígido, sendo possível atribuir campos e estabelecer se o dado de uma coluna é nulo ou não nulo.

Já o banco de dados não relacional, que representa diversos tipos de bancos de dados, não exige a rigidez de esquemas para armazenar os dados, ou seja, ele não limita os campos, diferente das colunas do SQL. Além disso, é possível adicionar novas propriedades, sem a preocupação com o impacto nas demais informações já armazenadas.

Caso sua empresa esteja aplicando metodologias ágeis modernas, um banco de dados relacional provavelmente não seria uma boa opção nesse contexto, pois ela requer um nível maior de preparação.<font color="red">????????</font>
<font color="red">Nota 1,5</font>

3. (**1.50 Pontos**) Defina a arquitetura de desenvolvimento orientada a serviços.

Resposta: Arquitetura orientada a serviços (SOA) é um tipo de design de software que torna os componentes reutilizáveis usando interfaces de serviços com uma linguagem de comunicação comum em uma rede.

Um serviço é uma unidade ou conjunto de funcionalidades de software independente, que foi desenvolvido para concluir uma tarefa específica, como recuperar determinadas informações ou executar uma operação. Ele contém as integrações de dados e o código necessários para executar uma função de negócios completa. Esses serviços podem ser acessados remotamente e é possível interagir com eles e atualizá-los de maneira independente.

Em outras palavras, a SOA integra os componentes de software que foram implantados e são mantidos separadamente, permitindo que eles se comuniquem e trabalhem juntos para formar aplicações que funcionam em sistemas diferentes.
<font color="red">Nota 1,5</font>

4. (**1.50**) Apresentar cenários de utilização da arquitetura de desenvolvimento orientado a serviços e descrever quais as vantagens obtidas ao se adotar este modelo.

Resposta:
A Cisco adotou o SOA para garantir que a experiência de encomenda de seus produtos fosse consistente por todos os seus produtos e através de todos os seus canais, expondo os processos de encomenda como serviços que as divisões, aquisições e parceiros de negócios poderiam incorporar em seus websites.

Outro exemplo é o da Delaware Electric, que escolheu o SOA para integrar sistemas que antes não se comunicavam, resultando em uma maior eficiência de desenvolvimento que ajudou a organização a se manter no verde durante os 5 anos em que o governo congelou as taxas de eletricidade.

Algumas vantagens são:
Facilidade de Manutenção: mudanças na lógica de negócios (implementação) não afetam aplicações existentes;
Reuso: novas aplicações e processos (consumidores de serviços) podem reaproveitar mais facilmente as funcionalidades existentes;
Flexibilidade: sistemas de back-end e infraestrutura podem ser substituídos com menor impacto;
Resultado: agilidade e redução de custos;
Qualidade: garantia de homogeneidade de processos;
Menor tempo: agilidade na análise de impacto e no desenvolvimento evolutivo de seus sistemas;
Menor custo: redução do custo de manutenção das aplicações;
Controle: conhecimento dos ativos existentes.
Em breve vamos continuar a tratar desse assunto em outros artigos, trazendo a definição de serviço e como escolher bons serviços candidatos.
<font color="red">Nota 1,5</font>

5. (**1.50**) Descreva, na sua opinião quais são os maiores entraves para se implantar uma cultura de desenvolvimento orientada a testes, nas empresas de desenvolvimento de software.

Resposta:
Alto Custo: Como é necessário testar tudo antes, obviamente o seu projeto vai levar mais tempo ou usar mais desenvolvedores, o que elevará o custo. Além disso, todo projeto de software está sujeito a falhas, o que significa que gastar ao escrever testes com antecedência pode fazer com que o seu projeto seja abortado antes de oferecer qualquer valor àqueles que estão pagando.
Duração do Projeto Estendida: Escrever testes antes de começar vai fazer com que seu projeto demore mais para ser lançado.
Mudanças no Código Tornam Testes Escritos Obsoletos: É bem frequente que projetos tenham seus objetivos alterados porque as empresas por trás deles percebem que algumas mudanças são necessárias, de forma que o negócio seja mais viável. Quando os objetivos de um projeto mudam, ao menos uma parte do código se torna inútil, já que não será mais usado. Se você escreveu testes extensivos para o código que será deixado de lado, os testes também se tornarão inúteis.
<font color="red">Nota 1,5</font>

6. (**1.50**) Estabeleça um paralelo entre as abordagens de testes (tradicional x ágil). Destaque quais as vantagens/desvantagens de uma sobre a outra.

Resposta: Em termos de hierarquia, nas metodologias tradicionais, há uma figura central no monitoramento das demandas. Normalmente, é o líder da área quem responde por todo o processo e delega as atividades. Nas metodologias ágeis, a macroestrutura é dividida em equipes multidisciplinares que possuem autonomia para a tomada de certas decisões, se assemelhando mais a um “organismo vivo” do que uma “pirâmide”.
Em termos de documentação, a metodologia tradicional se baseia em uma estratégia essencialmente documentada, na qual o planejamento define toda a ordem do desenvolvimento do projeto. Apesar disso, não pense que o método ágil não demanda um planejamento. A grande diferença é que, conforme as etapas se cumprem, é possível revisar e reformular as tarefas, desde que isso contribua para que a entrega prevista no projeto se cumpra de maneira mais prática.
<font color="red">Nota 1,0</font>
INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Responder e entregar este mesmo arquivo, renomeado para **prova_p2_mat.md**, onde mat é o número da sua matrícula.
3. Data da Entrega: 13/04/2022, as 22h.
4. Critério de Aceitação: arquivos entregues, conforme solicitado.
