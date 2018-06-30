# Teste Prático

O objetivo desta atividade é avaliar conhecimentos básicos do Javascript. Abaixo algumas instruções:

## Tecnologias a serem utilizadas:

1 - ReactJS

2 - axios (https://github.com/axios/axios)

3 - EcmaScript6 ( ES6 )

4 - redux (https://redux.js.org/) - Opcional

5 - SASS - (Opcional)

## Objetivo

Criação de componentes para listagem e manutenções de usuários através de API RestFul

## Sobre a API

Para a implementação deste teste, deverá ser usada a API de "users" que é fornecida pelo serviço https://jsonplaceholder.typicode.com. Esta API é publica e usada apenas para testes.


## Regras de implementação COMPONENTE 1 (Listagem)

![alt text](https://github.com/Deivisson/test-pratico-front/blob/master/assets/images/componente1.png)

1 - Ao montar o componente, deverá fazer requisição à API de /users para recuperar a listagem de registros. 

2 - Após recuperado os usuários, mostrar os resgistros em tabela HTML conforme imagem

3 - Para cada registro deverá conter um botão excluir. Quando excluido, o item deverá ser removido da lista que esta na tela. (Deverá fazer requisição http à API e somente depois do retorno com sucesso, remover da lista)

4 - Ao clicar sobre um usuário na tabela, deverá mostrar mais informações sobre o mesmo na área de detalhe.

5 - Ao clicar no botão "Adicionar" novo, deverá exibir o COMPONENTE 2


## Regras de implementação COMPONENTE 2 (Form)

![alt text](https://github.com/Deivisson/test-pratico-front/blob/master/assets/images/componente2.png)

1 - Implementar componente para inclusão de novos usuários conforme a imagem 2;

2 - Deverá conter os campos "Nome", "Email", "Telefone" e "Site". Todos campos são obrigatórios

3 - Ao gravar, deverá ocultar o componente form e adicionar o registro na tabela de listagem. (Obs.: Deverá chamar à API de cadastro de usuários)

4 - Se clicado no botão cancelar, o Form deverá ser fechado.

## REGRAS

1 - A implementação deverá ser entregue via este repositórios gitHub.

2 - Como estamos usando uma API de teste, operações de Criação e Exclusão dos registros, são fakes. Ou seja, o servidor irá retornar sucesso, porém os dados não serão persistidos. Para a nossa avaliação o que é importante é ver as operações sendo executadas e o reflexo disto nos componentes.

3 - Todas as operação (Listar, Excluir, Salvar) devem passar pela chamada da API.

4 - É importante que as telas estejam bem estilizadas (Css). Queremos avaliar a escrita.

5 - Dê preferência pelo uso das novas features do ES6 sempre que possível.


Bom Trabalho !!! :-)




