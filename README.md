<p align="center" ><h2>Stack de testes de unidade e integrados em um projeto .NET de Crowdfunding :bar_chart:<h2></p>


Neste módulo do BootCamp Decola Dev da Avanade, o expert Eliézer Zarpelão demonstra na prática os testes de unidade e testes integrados em um projeto de Crowdfunding (vaquinha - doação) desenvolvido por ele.


### Testes de unidade / UnitTest:

Unidade: menor parte testável de um software 

Orientação a Objetos: classe

"Ele é chamado de teste de unidade porque você divide a funcionalidade do seu programa em comportamentos discretos que podem ser testados como *unidades* individuais."

Fonte extra: https://docs.microsoft.com/pt-br/visualstudio/test/unit-test-basics?view=vs-2019




### Testes de Integração:

Encontrar falhas de integração entre as unidades, e não mais em testar as funcionalidades da mesma Integração entre unidades ou entre sistemas.

"Os testes de integração garantem que os componentes de um aplicativo funcionem corretamente em um nível que inclui a infraestrutura de suporte do aplicativo, como o banco de dados, o sistema de arquivos e a rede."

https://docs.microsoft.com/pt-br/aspnet/core/test/integration-tests?view=aspnetcore-5.0#:~:text=Os%20testes%20de%20integra%C3%A7%C3%A3o%20garantem,de%20arquivos%20e%20a%20rede.




### Testes automatizados:

“Simula” ações do usuário 

Aceitação: caixa preta 

Regressão: garante integridade de versões passadas 

Processo de automatização é caro: selecionar funcionalidades (se é viável sua aplicação para o projeto)

"Automação de testes é o uso de software para controlar a execução de testes de software através da aplicação de estratégias e ferramentas, comparando os resultados esperados com os resultados reais. Seus objetivos são a redução do envolvimento humano em atividades manuais, de tempo demandado e de custo final."

Fonte extra: https://medium.com/venturus/quais-as-raz%C3%B5es-para-automa%C3%A7%C3%A3o-de-testes-c177cbd9397




### TDD (Test Driven Development):

<p align="left">
  <img width="500" height="300" src="/imgs/TDD.jpg" alt="Imagem com o cilco do conceito de TDD ">
  </P>

TDD é o Desenvolvimento Orientado por Testes. Desenvolvemos o nosso software baseado em testes que são escritos antes do nosso código de produção.

O TDD se baseia em pequenos ciclos de repetições, onde para cada funcionalidade do sistema um teste é criado antes. Este novo teste criado inicialmente falha, já que ainda não temos a implementação da funcionalidade em questão , em seguida, implementamos a funcionalidade para fazer o teste passar, mas é preciso que esta funcionalidade que acabamos de escrever seja refatorada, ou seja, ela precisa passar por um pequeno banho de "boas práticas” de desenvolvimento de software.

Fonte: https://www.devmedia.com.br/test-driven-development-tdd-simples-e-pratico/18533











