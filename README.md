# Projeto Configurações De Micro Serviços

Informações gerais sobre as configurações de Micro Serviços.

## 📋 Sobre

Este projeto tem como finalidade a centralização das configurações da rede de Micro Serviços `Neuro Philip`, desta forma todos os arquivos de configuração dos Micro Serviços estarão em um repositório Git.

## ⚙️ Serviços Configurados

Atualmente temos os seguintes Micro Serviços configurados:

#### Example Configuration App: 

Arquivo de configuração utilizado como exemplo para testes do projeto neuro-philip-config-server.

```
http://localhost:9090/sample-config-app/default
```

#### Eureka Server

Projeto utilizado para localizar serviços com o objetivo de balanceamento de carga e failover dos servidores.

```
http://localhost:9091/
```

#### Permission Server

Projeto utilizado para controlar a autenticação/autorização de nossos recursos. 

```
http://localhost:9092/oauth/token
```

#### Auth Server

Projeto utilizado para fornecer funcionalidades de CRUD para Usuários, Perfis, Controle de Acesso, Notificações e Menu. 

```
http://localhost:9093/
```

#### Organization Server

Projeto utilizado para fornecer funcionalidades de CRUD para Grupo Empresarial e Empresa. 

```
http://localhost:9093/
```
