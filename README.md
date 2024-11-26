# Testes

Aqui listo os tipos de testes mais comuns utilizados

## Testes de Integração

Este tipo de teste validam componentes isolados

- Exemplo em API:
  Validar que a o GET na api retornou o status 201.
- Exemplo em um componente React:
  Validar que o evento onClick foi disparado ao clicar em um botão

## Testes End to End (E2E)

Validam oque acontece após a integração. Ele valida o fluxo do usuário e oque sua interação alterou no estado da entidade.

- Exemplo em API:
  Validar que o GET na api retornou o status 201.
  Validar que na listagem da api o registro feito está nesta listagem
- Exemplo no Frontend:
  Valida que o componente é renderizado após o clique e contem o texto e a classe css

## Testes Unitários

Este tipo de teste faz a validação do ponto de vista do cliente não importando a implementação. Validam o comportamento do seu código sem depender de iteração externa. Ele parte da premissa que a interação externa funciona. seja ela api , banco de dados, 
arquivos externos.
Eles são utilizados para testar funções individuais , diferente do teste E2E que testa o fluxo completo.
