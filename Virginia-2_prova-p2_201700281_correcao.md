<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>

#### <p style="text-align: center;">Instituto de Informática</p>

#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>

#### <p style="text-align: center;">Teste de Software - 2021/2</p>

#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>

#### <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: 201700281

Nome: Virgínia de Fernandes Souza

<font color="red">Nota 5,5</font>

1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware.

   * Processo de Teste de Software - estrutura as etapas, as atividades, os artefatos, os papéis e as responsabilidades do teste, permitindo organização e controle de todo o ciclo do teste, minimizando os riscos e agregando valor ao software.
   * Projeto de Teste de Software - É um documento que especifica detalhes da abordagem de teste para um requisito (ou uma combinação deles) do software e identifica os casos de teste associados.
   * Plano de Teste de Software - é um documento que funciona como um norteador, visando planejar as atividades a serem realizadas, definir os métodos a serem empregados, planejar a capacidade necessária, estabelecer métricas e formas de acompanhamento do processo. <font color="red">Nota 0,5</font>

   ---

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.

   Um Processo de Teste de Software tem como objetivo estruturar as etapas, as atividades, os artefatos, os papéis e as responsabilidades do teste, permitindo organização e controle de todo o ciclo do teste, minimizando os riscos e agregando valor ao software. O processo de software abrange o projeto de teste uma vez que apresenta como uma de suas etapas a conclusão do projeto de teste. Já o plano de teste é um dos documentos produzidos na condução de um projeto, ele funciona como um integrador entre as atividades de testes no projeto, além de ser um mecanismo de comunicação para as partes interessadas e um guia para a execução e controle das atividades de teste. <font color="red">Nota 0,5</font>

---

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.

* A atividade de testes ágeis ocorre durante o desenvolvimento em ciclos  frequentes e contínuos.
* Em um ambiente ágil, os bugs são identificados, relatados e corrigidos em um curto espaço de tempo, pelo fato do foco estar na prevenção e não na remediação dos mesmos.
* Nesse tipo de ambiente, os testes podem ser realizados por todos os membros do time.Em ambiente ágil, a tendência é que as entregas sejam feitas mais rápidas, em curtas iterações. A gestão de defeitos tende a ser, também, mais dinâmica, pois passa a ser executada diretamente pelo próprio desenvolvedor, sem o relato de inconformidades e intervenção do testador.
* É realizado com maior ênfase por meios automáticos, possibilitando a realização de ciclos enxutos e cada vez mais rápidos, além de garantir a validação regressiva das funcionalidades, e de forma econômica.
* Possui enfoque em testes de caixa preta e caixa branca em todas as camadas da arquitetura.
Os testes são usados como complementação dos requisitos e documentação do código.
* Maior ênfase em testes exploratórios, abordagem usada em situações nas quais o prazo para os testes é curto.
<font color="red">Nota 1,0</font>
---

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório.

Teste exploratório é uma abordagem que oferece uma liberdade maior ao testador, permitindo que interagir com a aplicação do modo que considerar mais adequado e utilizar as informações obtidas que provê para direcionar os testes dentro do cenário existente, e assim, realizar as combinações que acreditar necessárias.

O teste exploratório é um processo orientado a resultados, no qual o conhecimento sobre o produto e seus requisitos e regras cresce ao longo da sua exploração, uma vez obtidos resultados que atendam aos requisitos, termina.

É um método frequentemente usado em situações em que não existe um conhecimento sobre o sistema a ser testado, não há documentação e/ou requisitos (como acontece em metodologias ágeis) e situações em que o prazo para os testes é curto.

A abordagem exploratória é a melhor maneira de testar um produto rapidamente para tentar garantir o mínimo de qualidade possível, quando o tempo não permite um teste planejado.
<font color="red">Nota 1,0</font>
---

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:

---

   4.1 (**2.0 Pontos**) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

      **CT01:** Testar número do Banco < 3 digitos.
      **CT02:** Testar número do Banco > 3 digitos.
      **CT03:** Testar número do Banco < 0.
      **CT04:** Testar número do Banco certo.
      **CT05:** Testar comprimento do nome do Banco < 5.
      **CT06:** Testar nome do Banco > 100.
      **CT07:** Testar nome do Banco com caractere especial.
      **CT08:** Testar nome do Banco certo.
      **CT09:** Testar número da Agência < 3 digitos.
      **CT10:** Testar número da Agência > 5 digitos.
      **CT11:** Testar número da Agência com letra.
      **CT12:** Testar número da Agência certo.
      **CT13:** Testar nome da Agência, < 5 caracteres.
      **CT14:** Testar nome da Agência, > 100 caracteres.
      **CT15:** Testar nome da Agência com caractere especial.
      **CT16:** Testar o nome da Agência certo.
      **CT17:** Testar nome da cidade da Agência, < 5 dígitos.
      **CT18:** Testar nome da cidade da Agência, > 100 caracteres.
      **CT19:** Testar nome da cidade da Agência com caractere especial.
      **CT20:** Testar o nome da cidade da Agência certo.
      **CT21:** Testar número da Conta, < 6 dígitos.
      **CT22:** Testar número da Conta, > 6 dígitos.
      **CT23:** Testar número da Conta, com letra entre os digitos.
      **CT24:** Testar tipo da Conta, Corrente.
      **CT25:** Testar tipo da Conta, Poupança.
      **CT26:** Testar tipo da Conta, Outro.
      **CT27:** Testar saldo da Conta < 0.
      **CT28:** Testar saldo  da Conta > 0.
      **CT29:** Testar transferir da Conta, sendo valor certo.
      **CT30:** Testar transferir da Conta, sendo valor < 0.
      **CT31:** Testar depositar da Conta, sendo valor certo.
      **CT32:** Testar depositar da Conta, sendo valor < 0.
      **CT33:** Testar sacar da Conta, sendo valor certo.
      **CT34:** Testar sacar da Conta, sendo valor < 0.

      <font color="red">Nota 1,0</font>
---

   4.2 (**2.0 Pontos) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

   |CT|Valores de Entrada|Resultado esperado|
   |---|---|---|
   |CT01|90, Inter|"Valor inválido"|
   |CT02|193213, Inter|"Valor inválido"|
   |CT03|-156, Inter|"Valor inválido"|
   |CT04|897, Inter|"Banco Cadastrado"|
   |CT05|897, Int|"Valor inválido"|
   |CT06|897, IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII|"Valor inválido"|
   |CT07|897, uff&g|"Valor inválido"|
   |CT08|123, Inter|"Banco Cadastrado"|
   |CT09|87, Campus, Goiania, banco| "Valor inválido"|
   |CT10|987456321, Campus, Goiania, banco| "Valor inválido"|
   |CT11|1sdf3, Campus, Goiania, banco| "Valor inválido"|
   |CT12|12345, Campus, Goiania, banco| "Agencia Cadastrada"|
   |CT13|12345, UFG, Goiania, banco|"Valor inválido"|
   |CT14|12345, ugggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggg, Goiania, banco|"Valor inválido"|
   |CT15|12345, UF&%#, Goiania, banco|"Valor inválido"|
   |CT16|12345, Campus, Goiania, banco|"Agencia Cadastrada"|
   |CT17|12345, Campus, Goi, banco|"Valor inválido"|
   |CT18|12345, Campus, Cidddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddaaaaaaaaaaade, banco|"Valor inválido"|
   |CT19|12345, Campus, Goi&ania, banco|"Valor inválido"|
   |CT20|12345, Campus, Goiania, banco|"Agencia Cadastrada"|
   |CT21|1236, Corrente, Campus|"Valor inválido"|
   |CT22|1234567, Corrente, Campus|"Valor inválido"|
   |CT23|12f456, Crrente, Campus|"Valor inválido"|
   |CT24|123456, orrente, Campus|"Conta cadastrada"|
   |CT25|123456, Poupanca, Campus|"Conta cadastrada"|
   |CT26|123456, BLABLABLA, Campus|"Valor inválido"|
   |CT27|59000|"Saldo atualizado"|
   |CT28|-10|"Valor inválido"|
   |CT29|origem, destino, 5000|"Transferência feita com sucesso"|
   |CT30|origem, destino, -5000|"Valor inválido"|
   |CT32|conta, 4589|"Deposito feito com sucesso"|
   |CT31|conta, -1000|"Valor inválido"|
   |CT34|conta, 1450|"Valor inválido"|
   |CT33|conta, -1450|"Valor inválido"|
---
  <font color="red">Nota 1,5</font>
   4.3 (**3.0 Pontos**) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.

<font color="red">Nota 0,0, sem entregas.</font>

INSTRUÇÕES:

1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
