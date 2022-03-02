<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: 201700281

Nome: Virgínia de Fernandes Souza

<p><font color=green>Nota: 9,1.</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software?

   || Revelar a presença de defeitos nos softwares. <font color=green>Certo.</font>

   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário?

   || Os softwares podem nao funcionar corretamente, podendo levar a muitos problemas como prejuízos financeiros, risco em relação a integridade física da pessoa, multas e outros. <font color=red>Errado.</font>

2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível.

   || É o teste no qual todas as possibilidades são testadas, o que quer dizer que testa-se todos os possíveis dados de entrada. Consiste então numa completa validação do programa.Se cada instância for bem-sucedida, o programa foi verificado; senão, um erro foi encontrado. É a única técnica de testes que garantiria a validade do programa. Esta técnica não é viável pois, na maior parte dos casos, o domínio da função (conjunto de dados de entrada possíveis) é infinito, ou quando finito, grande o bastante para fazer o número de testes requeridos inviável. <font color=green>Certo.</font>

3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural.

   || Desvantagens do teste funcional - caixa preta:

   Para encontrar todos os defeitos utilizando teste caixa preta é necessário o teste exaustivo. <font color=red>(???)</font>

   Depende de uma boa especificação de requisitos o que, geralmente , não é bem feito.

   || Desvantagens teste estrutural - caixa branca.

   Pode consumir tempo e recursos significativos para suaaplicação.

   Exigem habilidades de programação do testador para
compreender o fluxo de controle do programa.

<font color=orange>Parcialmente correto. Nota 0,8.</font>


4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada.

   || Os níveis de teste são teste de unidade, teste de integração, teste de sistema e testde aceitação.

    Testes de unidade: são testes automatizados de pequenas unidades de código, normalmente classes, as quais são testadas de forma isolada do restante do sistema. A maior parte dos testes estão nessa categoria. Testes de unidade são simples, mais fáceis de implementar e executam rapidamente. Um teste de unidade é um programa que chama métodos de uma classe e verifica se eles retornam os resultados esperados. Assim, quando se usa testes de unidades, o código de um sistema pode ser dividido em dois grupos: um conjunto de classes — que implementam os requisitos do sistema — e um conjunto de testes. <font color=green>Certo.</font>

5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivalência.

|| É uma técnica de testes com base em requisitos - caixa preta- ao utilizar essa técnica o testador passa a ter noção de cobertura de testes a partir de requisitos e especificações. Ou seja ela é usada para reduzir o número de casos de teste a um nível gerenciável, mas preservando uma cobertura razoável do teste. <font color=orange>Parcialmente correto. Nota 0,8.</font>


6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados.

|| Sim.

Nível 0:  qualquer valor de cobertura menor que 100% da cobertura de todos os comandos.

Nível 1: 100% de cobertura de comandos.__Todos-nós__ (cobertura de nós) corresponde ao requisito mínimo de teste, mas, mesmo assim, pode ser difícil de ser atingida.

Nível 2: 100% de cobertura de decisões, também chamado de cobertura de arcos/arestas - critério __todos-arcos__.  Aqui o objetivo é fazer cada comando de decisão assumir os valores true e false.

Nível 3: 100% de cobertura de condições.

Nível 4: 100% de cobertura decisões/condições. Esse critério requer que
todas as combinações sejam testadas.

Nível 5: 100% de cobertura de condições múltiplas. Consiste em utilizar o conhecimento de como o compilador avalia condições múltiplas de determinado comando de decisão
e utilizar essa informação na geraçãoao de casos de testes.

Nível 6: cobertura de loop -  quando o programa possui loops, o número de caminhos pode ser infinito.
 <font color=green>Certo.</font>

Nível 7: 100% de cobertura de caminhos. Também conhecido como critério __todos-caminhos__. Para programas sem loop o número de caminhos pode ser pequeno o suficiente e casos de testes podem ser contruídos para cobri-los. Em relação aos programas com loop o número de caminhos pode ser muito grande ou infinito, tornando impossível cobrir todos os caminhos de execução.



7. Considere a especificação, a seguir, de um hipotético programa que objetiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A).
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida
         • Equilátero = quando todos os lados tem a mesma medida;
         quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).


7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.


| |Regra1|Regra2|Regra3|Regra4|Regra5|Regra6|Regra7|Regra8|Regra9|Regra10|Regra11|
|---|---|---|---|---|---|---|---|---|---|---|---|
|**Condições**| | | | | | | | | | | | | | | | |
|A < B + C|F|V|V|V|V|V|V|V|V|V|V|
|B < A + C|-|F|V|V|V|F|V|V|V|V|V|
|C < A + B|-|-|F|V|V|V|V|V|V|V|V|
|A = B = C|-|-|-|V|V|V|V|F|F|F|F|
|A = C    |-|-|-|V|V|F|F|V|V|F|F|
|B = C    |-|-|-|V|F|T|F|V|F|T|F|
|**Ações**| | | | | | | | |
|Não É triângulo|X|X|X||X|X||X|||||
|Triângulo escaleno|||||||||||X|
|Triângulo isósceles|||||||X||X|X|||
|Triângulo equilátero||||X|||||


<font color=green>Certo.</font>



7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
| 01  | 4   | 1  | 2  |Não é triangulo   |
| 02  | 1   | 4  | 2  |Não é triangulo   |
| 03  | 1   | 2  | 4  |Não é triangulo   |
| 04  | 5   | 5  | 5  |Triangulo Equilátero   |
| 05  | 1   | 2  | -1  |Não é triangulo   |
| 06  | 101   | 2  | 3  |Não é triangulo  |
| 07  | 2   | 2  | 3  |Triangulo Isosceles   |
| 08  | 0   | 2  | 3  |Não é triangulo  |
| 09  | 2   | 3  | 2  |Triangulo Isosceles   |
| 10  | 3   | 2  | 2  |Triangulo Isosceles   |
| 11  | 3   | 4  | 5  |Triangulo Escaleno  |

<font color=green>Certo.</font>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
