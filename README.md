# CURSO ALURA - Angular: Começando com o framework

> Curso realizado no dia 02-11-2021.


## 
- [x] Escutar o evento de submit do formulário através de event binding;
- [x] Two-way data binding;
- [x] Capturar as informações de um formulário;
- [x] Utilizar o metadata @Output() para criar um evento para o seu componente;
- [x] Emitir eventos dentro do seu componente;
- [x] Utilizar o event binding para capturar o evento propagando pelo componente;
- [x] Utilizar o metadata @Input() para receber valores em um componente;
- [x] Exibir uma lista de dados através da diretiva *ngFor;
- [x] Configurar o formato de horas na aplicação;
- [x] Utilizar a diretiva *ngIf;
- [x] Trabalhar com Service;
- [x] Como construir um mock de uma API REST com o json-server;
- [x] Importar e utilizar o módulo HttpClient;
- [x] Como enviar os dados de um formulário para a API;
- [x] Como exibir em tela os dados obtidos de uma API;
- [x] Importar e utilizar o módulo RouterModule;
- [x] Adicionar rotas aos componentes transformando-os em páginas;
- [x] Utilizar o RouterLink para melhorar a usabilidade de nossa aplicação.

## Estrutura básica do projeto
``` bash
  /
  |__ tsconfig.json # confugurações do TypeScript
  |__ src/
      |__ stules.scss # CSS global da aplicação
      |__ assets/ # imagens que serão utilizadas na aplicação
      |__ app/ # pasta principal do projeto
           |__ app.component.html # arquivo com o html do componente
           |__ app.component.scss # arquivo com o css do componente
           |__ app.component.ts # arquivo com as classes e métodos do componente
           |__ app.module.ts # arquivo que contém a importação dos módulos
           |__ nova-transferencia/ # para principal do projeto
               |__ app.nova-transferencia.html # arquivo com o html do componente
               |__ app.nova-transferencia.scss # arquivo com o css do componente
               |__ app.nova-transferencia.ts # arquivo com as classes e métodos do componente
```


# Ferramentas Utilizadas:

## NodeJS:
https://nodejs.org/en/download/

## Git:
https://git-scm.com/downloads



# Comandos para Rodar o Projeto Localmente:

## Instalação do Angular
``` bash

Ctrl + Ponto: Sugestão de IMPORT do VS Code

# Rodar a Instalação
npm install -g @angular/cli

# Verificar a versão do Angular
ng version

# Criar o projeto chamado bytebank.
ng new bytebank

# Iniciar o servidor
ng serve --open
ng s --o

# Gerar um Componente
ng generate component extrato

# Fake API - JsonServer
npm install -g json-server

# Subir o servidor fake do JsonServer
json-server --watch db.json
```
