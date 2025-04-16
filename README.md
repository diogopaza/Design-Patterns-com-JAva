# Design-Patterns-com-Java

<h3>Orientação a Objetos - Noções</h3>
<p>
  <strong>Revisando modificadores de metodos</strong><br/>
  <ul>
    <li>abstract: somente pode ser usado em classes abstratas no Java, esse tipo de metodo nao contem um corpo, ou seja, nao tem uma implementacao. Metodos abstratos obrigam subclasses a implementa-los, atraves da sobreescrita de metodos (um dos usos de Polimorfismo - <emph>overriding</emph>).</li>
    <li>final:</li>
    <li>private:</li>
    <li>protect ou public:</li>
  </ul>

  
</p>


<h3>Strategy</h3>
<p>Objetivo: encapsular um algoritmo dentro de uma classe.</p>
<p>O padrao Strategy necessita de diversas variacoes de um algoritmo. </p>
<p>Exercicio: Implemente o padrao Strategy onde um passageiro possa definir uma das tres formas de viagem: carro, onibus ou aviao:</p>

<h3>Null Object</h3>
<p>Este padrao ilustra como com o uso de heranca e possivel enganar o codigo que utiliza a classe, introduzindo um novo comportamento que ira eliminar a necessidade do uso de condicionais. </p>
<p>O padrao Null Object propoe a criacao de uma classe para representar objetos nulos em uma aplicacao. Essa classe deve estender (tambem e possivel usar interfaces) a classe original e implementar seus metodos de forma a executar o comportamento esperado da aplicacao quando um valor nulo for recebido. Dessa forma, em vez de retornar um valor nulo, retorna-se uma istancia dessa nova classe.</p>




<h4>Referencias</h4>
<sub>
<p>Este repositorio e um estudo e implementacao do livro Design Patterns com Java, Projeto orientado a objetos guiado por padroes.</p>
  <p>O livro serve como um guia e implementacoes e pesquisas sao realizadas em conjunto com o estudo do livro, resultando em codigo proprios do proprietario deste repositorio.</p>
</sub>
