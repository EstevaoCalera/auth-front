# AuthFront

Tela de login desenvolvida no estudo de Angular com base nos ensinamentos e inspirações de [Dener Troquatte](https://vidafullstack.com.br/instrucoes-para-o-curso/) no [Curso de Angular 2 (v14+) Typescript do Básico ao Avançado](https://udemy.com/course/curso-de-angular/).

## Rodando a aplicação

É necessário instalar as dependências do projeto `npm install` e rodar a aplicação `ng serve`.
Além disso, é imprescindível que o servidor fake jwt seja clonado através deste [link](https://github.com/troquatte/curso-de-angular-fake-jwt) e executado `npm run start`.

## Principais funcionalidades
- Barreira de login por usuário e senha
- Rejeitar usuário ou senha errados com mensagem na tela
- Redirecionar para uma página admin caso o login seja feito corretamente
- Impedir o acesso direto à página admin sem um token válido
- Comunicação com api fake jwt

## Funcionalidades a serem criadas
- Criar página de cadastro para salvar as informações no servidor
