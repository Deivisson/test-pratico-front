# Teste Prático

O objetivo desta atividade é avaliar conhecimentos básicos do Javascript. Abaixo as intruções:

## Tecnologias a serem utilizadas:

1 - ReactJS

2 - axios (https://github.com/axios/axios)

3 - EcmaScript6 ( ES6 )

4 - redux (https://redux.js.org/) - Opcional

## Objetivo

Criação de componente conforme imagem abaixo:

![alt text](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

## Regras de implementação COMPONENTE 1 (Listagem)

1 - Ao montar o componente, deverá fazer requisição à API de /users para recuperar a listagem de registros. 

2 - Após recuperado os usuários, mostrar os resgistros em tabela HTML conforme imagem

3 - Para cada registro deverá conter um botão excluir. Quando excluido, o item deverá ser removido da lista que esta na tela. (Deverá fazer requisição http à API e somente depois do retorno com sucesso, remover da lista)

4 - Ao clicar sobre um usuário na tabela, deverá mostrar mais informações sobre o mesmo na área de detalhe.

5 - Ao clicar no botão "Adicionar" novo, deverá exibir o COMPONENTE 2


## Regras de implementação COMPONENTE 2 (Form)

1 - Implementar componente para inclusão de novos usuários conforme a imagem 2;

2 - Deverá conter os campos "Nome", "Email", "Telefone" e "Site". Todos campos são obrigatórios

3 - Ao gravar, deverá ocultar o componente form e adicionar o registro na tabela de listagem. (Obs.: Deverá chamar à API de cadastro de usuários)

4 - Se clicado no botão cancelar, o Form deverá ser fechado.
