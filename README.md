# Desafio Docker - Full Cycle 3.0

Este é o repositório da resolução do Desafio do Curso Full Cycle 3.0 - Módulo Docker Desafio Go.

## Descrição

O desafio consiste em criar um programa em Go que imprime "Full Cycle Rocks!" no console e depois containerizá-lo em um contêiner Docker.

## Como rodar

Para executar este programa, você precisa ter o Go e o Docker instalados em sua máquina.

### Executando diretamente com o Go

```bash
go run main.go
```

Isso irá compilar e executar o programa, que deve imprimir "Full Cycle Rocks!" no console.

### Executando com Docker

```bash
docker build -t desafio-go .
docker run desafio-go
```

Isso irá criar uma imagem Docker a partir do Dockerfile fornecido e executar um contêiner a partir dessa imagem. O programa dentro do contêiner irá imprimir "Full Cycle Rocks!" no console.

## Autor

Este desafio foi resolvido por Phillip Eduardo Pimenta Forte.
