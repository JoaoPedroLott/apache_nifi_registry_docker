# Projeto Apache NiFi Registry Docker

Este repositório contém um projeto Docker para criar uma imagem do [Apache NiFi Registry](https://nifi.apache.org/registry.html) na versão xxxx. Utilizamos um Dockerfile para construir a imagem e um docker-compose para facilitar a execução do contêiner.

## Pré-requisitos

Certifique-se de ter o Docker instalado em sua máquina antes de começar.

- Docker: [Instalação do Docker](https://docs.docker.com/get-docker/)

## Como usar

1. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/JoaoPedroLott/apache_nifi_registry_docker.git
```

2. Inicie o contêiner usando o docker-compose:

```bash
docker compose up
```

O Apache NiFi Registry estará acessível em http://localhost:18080/nifi-registry

## Configuração Adicional

- O diretório conf/ contém arquivos de configuração do NiFi Registry que podem ser ajustados conforme necessário.
- Certifique-se de revisar e personalizar o Dockerfile para atender aos requisitos específicos do seu projeto.

## Contribuindo

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos. Abra uma issue ou envie um pull request!