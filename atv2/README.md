
---

### **README da Atividade 2 (atv2/README.md)**

```markdown
# Atividade 2 - Implementar Wiki.js com Docker

### Objetivo
A segunda atividade é configurar e implementar a plataforma **Wiki.js** usando Docker, com um container PostgreSQL para persistência de dados.

### Requisitos:
- **Docker** e **Docker Compose** instalados.
- O container **PostgreSQL** deve ser configurado com as credenciais de acesso necessárias para o Wiki.js.
- O **Wiki.js** deve ser configurado para usar o banco de dados **PostgreSQL**.
- As portas 3000 e 5432 devem ser expostas para a comunicação.

### Como rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafio-modulo-docker-stackx.git

2. Navegue até a pasta atividade2

    cd desafio-modulo-docker-stackx/atv2

3. Inicie os containers utilizando 
    o Docker Compose:

    docker-compose up -d

4. Acesse a aplicação Wiki.js
    no    navegador:

    http://localhost:3000
    
