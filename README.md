# Projeto de Configura��es Micro Servi�os


## Sobre

Este projeto tem como finalidade a centraliza��o das configura��es da rede de Microservices `Neuro Philip`, desta forma todos os arquivos de configura��o dos micro servi�os estar�o em um reposit�rio git.


## Servi�os Configurados

Atualmente est�o configurados os seguintes micro servi�os:

### Exemplo Configuration App

Arquivo de configura��o utilizado como exemplo para testes do projeto neuro-philip-config-server.

- Url 
	- http://localhost:9090/sample-config-app/default

### Eureka Server

Projeto utilizado para localizar servi�os com o objetivo de balanceamento de carga e failover de servidores.

- Url
	- http://localhost:9091/

### Auth Server

Projeto utilizado para ser um servidor de autoriza��o que vai ser respons�vel por controlar a autentica��o e autoriza��o de nossos recursos. 

- Url
	- http://localhost:9092/oauth/token