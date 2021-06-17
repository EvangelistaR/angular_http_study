# AngularHttp
Esse é um projeto de estudos de front-end e foi gerado com [Angular CLI](https://github.com/angular/angular-cli) na versão 11.2.11

## Development server
Após baixar o repositório é necessário rodar o comando `npm install` para instalar a aplicação. Para rodar o projeto é preciso rodar o comando `ng serve`. O mesmo será acessado pelo endereço `http://localhost:4200/` no seu navegador. A aplicação será automaticamente recagarregada após cada alteração efetuada no código

## Json web server
Esse projeto conta com uma base local para exibir os dados na tabela.
Inicialmente será preciso instalar o json web server localmente `npm install -D json-server`, após isso você poderá subir o servidor JSON através do comando `json-server --watch src/assets/data/db.json`, no caso está sendo utilizado o arquivo .json que está armazenado em src -> assets -> data -> arquivo.json, mas você pode inserir o seu .json em qualquer diretório
