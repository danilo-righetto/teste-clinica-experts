<h1 align="center">
  <p align="center">Teste Laravel - Clinica Experts</p>
  <img src="https://imgur.com/Qd1TADO.jpg" alt="Clinica Experts">
</h1>

<p align="center">
  <a href="#license"><img src="https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000"></a>
  <a href="https://imgur.com/fbwPu3A.jpg"><img src="https://img.shields.io/badge/cardapio-working-brightgreen?color=green" alt="Clinica Experts"></a>
  <a href="CONTRIBUTING.md#pull-requests"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome with Admins"></a>
</p>

## Introduction/Introdução

O projeto se baseia-se no teste `Laravel + Vue` da [Clinica Consig](https://clinicaexperts.com.br/) onde **Soluções integradas que automatizam a sua clínica de estética**.

## Installation/Instalação

1. Verifique se o Docker e o Docker Composer estão instalados na sua maquina.
2. Execute o comando `cp .env.example .env` para gerar o arquivo contendo as variáveis de ambiente.
3. Execute o comando `docker-compose build` para gerar os containers.
4. Execute o comando `docker-compose up -d` para subir a estrutura da aplicação.
5. Execute o comando `docker exec clinica-laravel composer install` para instalar as dependências da aplicação.
6. Execute o comando `docker exec clinica-laravel php artisan key:generate` para gerar a chave da aplicação.
7. Execute o comando `docker exec clinica-laravel php artisan migrate:fresh --seed` para criar as tabelas necessárias e popular os dados do banco de dados.
8. Execute o comando `docker exec clinica-laravel php artisan test` para executar todos os testes implementados pela aplicação.
9. Acesse: [localhost:80](http://localhost/).

Para acessar o container principal do projeto utilize o comando: `docker exec -it clinica-laravel bash`.

## Versioning/Versionamento

O projeto está sendo versionado utilizando o padrão [Git Flow](https://medium.com/trainingcenter/utilizando-o-fluxo-git-flow-e63d5e0d5e04).

## Contributing/Contribuir

Quer contribuir com o projeto? [Veja como contribuir por aqui](./CONTRIBUTING.md).

## Code of Conduct/Código de Conduta

Veja o nosso [Código de Conduta](./CODE_OF_CONDUCT.md).

## License/Licença do Projeto

[MIT License](./LICENSE.md).
