# Vamos falar de condicionais: if, else if, switch

## Declarações condicionais 

Muitas vezes, qunado você escrece um código, deseja executar diferentes ações para diferentes decisões. 

Você pode usar instruções condicionais em seu código para fazer isso.

Em JavaScript, temos as seguintes declarações condicionais:

      - Use if para especificar um bloco de código a ser executado, se uma condição especificada for verdadeira. 
      - Use else para especificar um bloco de codigo a ser executado, se a mesma condição for falsa. 
      - Use else if para especificar uma nova condição para testar, se a primeira condição for falsa. 
      - Use o switch para especificar muitos blocos alternativos de codigo a serem executados. 


## A declaração if

Use a if para instrução para especificar um bloco de código JavaScript a ser executado se uma condição for verdadeira. 

      Exemplo de sintaxe:

      if (condição) {
            // Bloco de codigo a ser executado!
      }

## A declaração else

Use a else instrução para especificar um bloco de código a ser executado se a condição for falsa. 

      Exemplo de sintaxe:

      if (condição) {
            // Bloco de código a ser executado se a condição for verdadeira.
      } else {
            // Bloco de código a ser executado se a condição for falsa.
      }

## A declaração else if 

      Exemplo de sintaxe:

      if (condição1) {
            // Bloco de codigo a ser executado se a condição for verdadeira.
      } else if (condição2){
            // Bloco de codigo a ser executado se a condição1 for falsa e a segunda for verdadeira. 
      } else {
            // bloco de codigo a ser executado se todas as condições forem falsas. 
      }

## A instrução switch do JavaScript 

      Exemplo de sintaxe:

      switch(expression){
            case x:
                  // Bloco de codigo
                  break;
            case y:
                  // Bloco de código
                  break;
            default:
                  // Bloco de código
      }

É assim que funciona:

      - A expressão switch é avaliada uma vez. 
      - O valor da expressão é comparado com os valores de cada caso. 
      - Se houver uma correspodência, o bloco de código associados será executado. 
      - Se não houver correspondência, o bloco de código padrão será executado. 

  