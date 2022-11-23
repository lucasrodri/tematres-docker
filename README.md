# Apache + PHP 7 + MySQL + phpMyAdmin
> Ambiente local de desenvolvimento com Docker

Este repositório contém configurações Docker para a montagem de ambiente de desenvolvimento local com Apache, PHP 7, MySQL e phpMyAdmin.

**Pré requisitos:** Docker e Docker Compose

```bash
# Criar e levantar os containers
docker-compose up -d

# Iniciar o container Docker
docker-compose start

# Parar o container Docker
docker-compose stop

# Parar e remover containers da máquina
docker-compose down
```

**Acesso localhost**
```txt
http://localhost:8080
```

**Acesso phpMyAdmin**
```txt
http://localhost:8081

login: root
senha: 123mudar
```

**Passos para executar tematres**
- Criar db tematres via phpMyAdmin
- Abrir o link http://localhost:8080
- Configurar o tematres 
