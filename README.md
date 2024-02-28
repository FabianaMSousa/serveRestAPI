# serveRestAPI
Criação de testes de API utilizando postman, newman e newman-htmlextra

# Bootcamp 001 Qualiters Club
Teste de API Rest do manual a CI/CD
## O que é
Este repositório foi criado para o bootcamp de TEste de API Rest.

## Tecnologia utilizada 
-Postman Aplicativo desktop
-node version v18.14.0
-newman version 6.1.1
-newman-repoter-html

## Documentações
- Doc da API: [Consulte Swagger](/https://serverest.dev/#/)

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](/https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
  ```
  npm install -g newman
  ```
- Terceiro: realize a intalação da depemdencia dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
  ```
  npm install -g newman-reporter-html
  ```
  npm install -g newman-reporter-html
  ...
 
## Como rodar os testes

### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman

-Abra o console linha de comando para rodar os testes
- Execute a seguinte linha de comando para rodar os testes
  ```
  newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli
  ```
- Execute o teste com relatório
  ```
  newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli,htmlextra
  ```

### Report

Se você optou por rodar os testes com htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato

email: fabi_ms028@hotmail.com

redes sociais: [linkedin.com/in/fabiana-maria-sousa-1a3527176
](https://www.linkedin.com/in/fabiana-maria-sousa-1a3527176/)

