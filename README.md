# 🌍 Agência de Viagem - API REST

Este é um projeto de uma API RESTful simples para gerenciar uma agência de viagens. O sistema permite o gerenciamento de destinos, pacotes de viagem e reservas, utilizando uma arquitetura em camadas (Controller, Service e Model).

## 🧱 Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot**
- **Maven**
- **Lombok**
- **Postman (para testes de API - opcional)** / Aquivo AgenciaViagemAPI.postman_collection.json

## 📁 Estrutura do Projeto

agencia-viagem-api/
<br>├── controller/ # Controladores (camada de entrada da API)
<br>├── service/ # Regras de negócio
<br>├── model/ # Modelos de dados
<br>├── repository/ # Repositórios (simulados em memória)
<br>├── dto/ # Objetos de transferência de dados (opcional)
<br>├── Application.java # Classe principal


📌Endpoints
<br>🧭 Destinos
- GET /destinos - Listar todos os destinos

- POST /destinos - Cadastrar um novo destino

- GET /destinos/{id} - Buscar destino por ID

- PUT /destinos/{id} - Atualizar um destino

- DELETE /destinos/{id} - Deletar um destino


✈️ Pacotes
- GET /pacotes - Listar todos os pacotes

- POST /pacotes - Cadastrar um novo pacote

- GET /pacotes/{id} - Buscar pacote por ID

- PUT /pacotes/{id} - Atualizar um pacote

- DELETE /pacotes/{id} - Deletar um pacote


📑 Reservas
- GET /reservas - Listar todas as reservas

- POST /reservas - Criar uma nova reserva

- GET /reservas/{id} - Buscar reserva por ID

- DELETE /reservas/{id} - Cancelar uma reserva

Contribuição
- Sinta-se à vontade para abrir Issues ou Pull Requests. Toda contribuição é bem-vinda!

