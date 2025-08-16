# 🛒 Catálogo de Produtos e Pedidos - Microsserviços (DIO)

Projeto desenvolvido como parte do desafio da **Digital Innovation One (DIO)**, focado na criação de um sistema simples de catálogo de produtos e simulação de pedidos.

## 📌 Objetivo
Reforçar os conceitos de **microsserviços** com **Spring Boot** e **Spring Cloud**, utilizando:
- API Gateway
- Service Discovery (Eureka)
- Comunicação entre microsserviços via HTTP

## 🏗️ Arquitetura
O sistema é composto por dois microsserviços principais:

1. **Catálogo de Produtos**  
   - CRUD de produtos (nome, descrição, preço, estoque).

2. **Simulação de Pedidos**  
   - Criação de pedidos com base nos produtos cadastrados.

Além disso:
- **Eureka Server**: responsável pelo Service Discovery.  
- **API Gateway**: responsável por rotear as requisições para os microsserviços corretos.  

## 🚀 Tecnologias
- Java 17
- Spring Boot
- Spring Cloud (Eureka, Gateway)
- Maven

## ▶️ Como Executar
Clone o repositório:
```bash
git https://github.com/DavidMartony/dio-desafio-microsservicos
