# k6-performance-test
Neste projeto executo testes de perfomance com K6 em um ambiente local usando uma API real.

![image](https://github.com/user-attachments/assets/b16e9c95-1627-4b5b-9ec0-a81b74dcd3b5)


## Pré condições / Instalações

Acesse https://grafana.com/docs/k6/latest/set-up/install-k6/ e faça o download do K6.

Para subir a API que vamos testar a performance, necessitamos fazer o git clone do [projeto](https://github.com/weareqacademy/curso-k6-basico)      
Ter uma conta no MongoDB com um banco de dados criado para fazer a conexão com a API, através do arquivo .env que está no diretorio `curso-k6-basico/api/src/`

É necessário ter instalado o Node.js para colocar a API no ar.

> Eu usei a versão `v18.20.7` do Node.js, use esta ou superior.

Execute os comandos abaixo para instalar das dependências do projeto:
`cd curso-k6-basico/api`
`yarn install`
`yarn dev`


## Creditos

Projeto criado a partir dos conhecimentos aprendidos durante o curso Introdução aos testes de perfomance com K6, ministrado pelo [Fernando Papito](https://www.udemy.com/user/fernando-papito/)
