# AngularJS - Aula 01 - Exercício   
**user:** [dawtaylor](https://github.com/dawtaylor)  
**autor:** Adalberto Taylor

## 1 - Explique qual é a definição de MVC, MVVM e MVP

MVC ou Model View Controller é um padrão utilizado para separar as responsabilidades em camadas.
- Model -> é a camada que faz o acesso / exposição dos dados da aplicação para a view
- Controller -> é a camada que contém as regras de negócio e que recebe as requisições feitas pelo usuário através da view
- View -> é a camada de apresentação da aplicação, ela apresenta os dados recebidos da model e direciona as requisições para a camada de controller

MVVM ou Model View View Model é um padrão onde a view atualiza a model diretamente.
- Model -> direciona para a view os dados a serem apresentados
- View -> apresenta os dados para o usuário
- View -> direciona as requisições para a model
- Model -> processa as requisições e atualiza a view

MVP ou Model View Presenter é um padrão de projeto semelhante ao MVC onde o Presenter assume o papel do Controller com a diferença que nesse padrão a model não atualiza diretamente a view.
- Model -> direciona os dados a serem exibidos para a presenter
- Presenter -> intermedia a comunicação das camadas view e model
- View -> exibe os dados recebidos da presenter e encaminha as requisições para a presenter

## 2 - Crie uma aplicação com um nome e um form onde os dados colocados neles sejam mostrados logo abaixo, formatados.

Exercício resolvido no arquivo index.html