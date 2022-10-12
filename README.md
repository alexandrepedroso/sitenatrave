<div align="start">
 <img src="https://user-images.githubusercontent.com/101142042/195394799-de11ed12-202f-4bb0-a031-10c387021f2e.png" width=350px />
</div>
## Aplicação/Site Natrave
Site de palpites para jogos da Copa do Mundo de 2022 desenvolvido em React
<br/>Arquivos dentro da branch **master**


## Objetivo do projeto e Estrutura
Este projeto de estudo foi realizado durante o evento __Full Stack Challenge__, promovido pela plataforma/curso Codar.me <br />
A aplicação tem as seguintes páginas: <br />
- Home: Página de primeira visita, onde é apresentada a marca e encaminhado para login ou novo cadastro;
- Cadastro: Tela de signup para novos usuários, onde será registrado o user no banco de dados;
- Login: Após registro, o usuário poderá entrar de forma fácil e rápida de acordo com o cadastro já feito;
- Dashboard: É onde é feito os palpites dos jogos da Fase de Grupos da Copa do Mundo do Catar, de acordo com o dia específico <br />
selecionado. Sendo os jogos também armazenados em um banco de dados (tabela);
- Profile: Página de perfil do usuário que mostra os palpites já realizados pelo mesmo, obtendo informações da página de Dashboard;<br />
<br/>
##Aprendizado
Decidi upar o projeto para o Github como forma de mostrar o estudo realizado durante o evento que ocorreu durante os dias 03 a 07 de Outubro, onde tive meu primeiro contato com React, utilização de banco de dados e construção do back-end de uma 

## Tecnologias
* Back-end
  * __Node__ e__Koa__ 
  * __Prisma ORM__ - (Banco de dados)
* Front-end
  * __Axios__ 
  * __React e Vite__
  * __Tailwind CSS__ 
  * __React-Use__ 
  * __Date-Fns__ 
  * __Formik / Yup__ 
  
<br />

## :car: Utilizando a aplicação
Baixe o repositório com git clone e entre na pasta do projeto.<br/>
Renomeie os arquivos _.env.example_ para _.env_ e informe as URLs e o JWT secret.<br/>
```bash
$ git clone https://github.com/alexandrepedroso/sitenatrave.git
```
* Para baixar as ferramentas de Back-end necessárias:
```bash
$ cd api
$ npm install
$ npm run start
```
Para iniciar servidor de banco de dados:
```bash
$ cd api
$ npm run start
```
* Para baixar as ferramentas de Front-end necessárias:
```bash
$ cd ..
$ cd web
$ npm install
```
Para iniciar servidor
```bash
$ cd ..
$ cd web
$ npm run dev
```
## Exemplo da aplicação executando:
<p align="center">
  <kbd>
 <img width="auto" style="border-radius: 10px" height="auto" 
 src="https://github.com/alexandrepedroso/sitenatrave/blob/master/public/imgs/GifPreview.gif" alt="Intro">
  </kbd>
  </br>
</p>
