# Interface de listagem de filmes em Angular consumindo uma API REST simulado com JSON Server 

## Utilização da Interface de listagem de filmes (Angular)

Para instalar o Angular em seu sistema local, você precisa do seguinte:
Node.js

Angular requer um LTS ativo ou LTS de manutenção versão do Node.js.
Os downloads estão disponíveis aqui: [Instalador](https://nodejs.org/en/)

Instale o Angular CLI
Você usa a CLI Angular para criar projetos, gerar código de aplicativo e biblioteca e executar uma variedade de tarefas de desenvolvimento contínuas, como teste, empacotamento e implantação.

Para instalar o Angular CLI, abra uma janela de terminal e execute o seguinte comando:

```php
npm install -g @angular/cli
```

Certifique-se que tenha permissão de admim para toda instalação via terminal!

Você precisará do Git Bash para o versionamento de código.
Os downloads estão disponíveis aqui: [Instalador](https://git-scm.com/downloads/)

Abra um novo terminal em uma pasta de sua escolha e faça o clone do projeto:

```php
git clone https://github.com/rodolfodiego/test-innolevels
```

Abra um novo terminal na pasta "test-innolevels" do projeto após a instalação do NodeJs e o Angular Cli e instale as dependências da aplicação:

```php
npm install
```
Abra um novo terminal na pasta "test-innolevels" do projeto após a instalação das depednêcias do projetoe e instale o json-server:

```php
npm install -g json-server
```
Abra um novo terminal na pasta "test-innolevels" do projeto após a instalação das depednêcias do projeto, rode a simulação da API REST com JSON Server:

```php
json-server --watch FILMES.json
```
Certifique-se se o JSON Server subiu na porta padrão http://localhost:3000.

Abra um novo terminal na pasta "test-innolevels" do projeto após a instalação de subir o JSON Server, rode a aplicação usando o comando:

```php
ng serve 
```
A aplicação irá subir na porta padrão http://localhost:4200.
