# The-Mentalist-automation-postman-nodeexpress-erp

## The Mentalist automation postman nodeexpress erp
Este repositório tem uma página de publicação do "report" do teste que utiliza o Github Pages para servir páginas estáticas. Esse relatório será renovado todas as vezes que o teste for realizado.


# API-QA.CODERS
# AUTOMAÇÃO BACK-END

**PROJETO QA.CODERS ACADEMY - AUTOMAÇÃO DA API'S**
# HACKATHON

## Instalação do Ambiente

* NodeJs

## Comando para instalar o Newman:
```sh default
* npm install -g newman
```
## Comando para executar apenas com a Collection:
```sh default
* newman run AutomacaoPartners.postman_collection.json
```
## Comando pra executar com as variáveis:
```sh default
* newman run AutomacaoPartners.postman_collection.json -e Partners.postman_environment.json
```
## Comando pra instalar o Report:
```sh default
* npm install -g newman-reporter-htmlextra
```
## Comando pra executar o Newman e gerar o Relatório HTML:
```sh default
* newman run AutomacaoPartners.postman_collection.json -e Partners.postman_environment.json -r htmlextra
```
