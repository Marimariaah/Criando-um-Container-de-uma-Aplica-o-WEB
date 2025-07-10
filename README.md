# WebAppApacheContainer

Este repositório contém uma aplicação web simples rodando em um container Apache (HTTPD), desenvolvida como parte de um desafio da Digital Innovation One. O objetivo é demonstrar a implementação e execução de uma aplicação web HTML - um "Hello, World!" estilizado - em um container Docker utilizando Apache como servidor web.

## Contexto do Desafio

O desafio envolve a criação de um arquivo YML para definir um servidor Apache (httpd), especificar o local dos arquivos da aplicação no arquivo YML, e executar a aplicação web, que pode ser uma simples página "Hello World". O projeto é uma oportunidade para aplicar conhecimentos básicos em Docker (Docker Compose), Apache e HTML.

## Pré-requisitos

- Docker
- Docker Compose (opcional, mas recomendado)
- Git

## Configuração do Projeto

### Clonando o Repositório

```bash
git clone https://github.com/Marimariaah/Criando-um-Container-de-uma-Aplica-o-WEB.git

cd WebAppApacheContainer
```

### Iniciando o Container

Usando Docker Compose:

```bash
docker-compose up
```

Ou, usando Docker diretamente:

```bash
docker build -t webappapachecontainer .
docker run -p 80:80 webappapachecontainer
```

## Acesso à Aplicação

Após iniciar o container, a aplicação estará disponível em `http://localhost` ou no IP do host Docker.

## Contribuição e Desenvolvimento

Este projeto é um exemplo de como uma aplicação web pode ser executada em um container Docker com Apache. Contribuições e melhorias são bem-vindas.

## Autora

**Maria Eduarda** 
## Licença

Este projeto está aberto para uso e modificação conforme necessário.
# Criando-um-Container-de-uma-Aplica-o-WEB
