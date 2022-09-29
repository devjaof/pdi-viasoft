# SOLID
## Single Responsibility Principle
	Uma classe deve ter apenas uma responsabilidade, apenas um motivo para ser alterada.

## Open Closed Principle
	Uma classe deve estar aberta para extensão e fechada para modificação;
	Não há necessidade de aumentar o tamanho de uma classe, ao invés disso criar uma base para a classe e caso necessite de uma feat, apenas estender a base.	

## Liskov Substitution Principle
  Subclasses podem ser substituídas pelas suas classes pai:
  A subclasse deve ter a capacidade de ser utilizada em qualquer momento no lugar da classe pai.
  Se caminha como um pato, fala como um pato e parece um pato, mas precisa de pilhas. Então não é um pato.	

## Interface Segregation Principle
	Uma classe não é obrigada a implementar interfaces que ela não irá utilizar.
	Segregue suas interfaces!

## Dependency Inversion Principle
	Dependa de abstrações e não de implementações;

  Exemplo implementação: <br>
  `const movie = new movie();`	

  Exemplo de abstração: <br>
  `class DramaCategory implements Category {}` <br>
  `const movie = new movie(“name”, new DramaCategory());`