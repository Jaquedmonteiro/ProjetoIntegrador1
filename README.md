# ProjetoIntegrador: <This.Pizza.Club>
Projeto criado no Bloco 1 do bootcamp da Generatiom Brasil. 
<br/>
## Equipe de Desenvolvimento & Design <br/>
Ana Luiza (Nalu)<br/>
Caique Rodrigues <br/>
Fernando Porto<br/>
Igor Lima<br/>
Jaque Domingues<br/>
Jose Emerson<br/>
Luiz Henrique<br/>
Sotie Ghislain<br/>

## Ideia principal do Projeto <br/>

Desenvolver um sistema de registro e login + cardápio prático e intuitivo.
Usando o conhecimento em <strong>Orientação ao Objeto</strong>.

## Sprint
1. <strong>Registro<br/></strong>
Usuario cria uma conta no programa, fornecendo os seus dados pessoais, inclusive endereço residencial e método de pagamento.<br/>
2. <strong>Login<br/></strong>
Informar usuario e senha estabelecidos no momento do Registro.
3. <strong>Cardápio<br/></strong>
Menu de Pizza e cia. Selecionar o sabor desejado e acompanhamentos, finalizar o pedido.

## Desenvolvimento do Registro
Pessoa é a mãe do código, tendo como filha a subclasse Cliente. Em Pessoa temos os métodos, que são os dados do CLIENTE, onde foi utilizado  o Implements.

## Desenvolvimento de LOGIN
Cliente é uma subclasse de Pessoa, uma especialização, tem os atributos para criar usuário (Foram criados Getter e Setter), utilizando assim conhecimentos em Polimorfismo. Os Getters e os Setters são "ativados" na classe Cliente.

## Desenvolvimento do Cardápio da <This.Pizza.Club>.
Na elaboração do cardápio, foi utilizado um ArrayList do tipo String para apresentar as pizzas. Nesse caso, a partir das escolhas que o usuário faz o programa cria uma outra ArrayList contendo as escolhas de sabores para que no final do programa seja apresentado como uma lista. Em caso do usuário digitar um valor que não foi esperado, temos as validações e o uso do Try e Catch para tratar do mesmo.


