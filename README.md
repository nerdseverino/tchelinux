# Tchelinux 2019

Contatos: 

**Linkedin: https://linkedin.com/in/fabriciomachado**

**Telegram: @systemcrashpoa**

**Blog: https://nerdseverino.com.br**

Requisitos:
- Docker: 

**``curl - fsSL "get.docker.com" | bash``** 

- Docker Compose:

**``curl -L https://github.com/docker/compose/releases/download/1.18.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose``**

**``chmod +x /usr/local/bin/docker-compose``**

**``docker-compose --version``**

Obs.: Caso não seja root não esqueça do sudo! :D

**Como usar:**

- Use o git clone ou faça download do repositório
- Entre na pasta onde está o arquivo e execute o **``docker-compose up -d``**

Para verificar os containers rodando:
**``docker ps``**

**Obs.: Para usar o traefik o mesmo está no momento sem segurança e é indicado para uso interno da rede, para uso exerno consulte a documentação do software para uso com SSL.**

**https://docs.traefik.io/**
