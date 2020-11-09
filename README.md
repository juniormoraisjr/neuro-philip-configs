# Projeto de Configurações Micro Serviços


## Sobre

Este projeto tem como finalidade a centralização das configurações da rede de Microservices `Neuro Philip`, desta forma todos os arquivos de configuração dos micro serviços estarão em um repositório git.


## Serviços Configurados

Atualmente estão configurados os seguintes micro serviços:

### Exemplo Configuration App

Arquivo de configuração utilizado como exemplo para testes do projeto neuro-philip-config-server.

- Url 
	- http://localhost:9090/sample-config-app/default

### Eureka Server

Projeto utilizado para localizar serviços com o objetivo de balanceamento de carga e failover de servidores.

- Url
	- http://localhost:9091/

### Auth Server

Projeto utilizado para ser um servidor de autorização que vai ser responsável por controlar a autenticação e autorização de nossos recursos. 

- Url
	- http://localhost:9092/oauth/token