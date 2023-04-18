<h1 align="center">
	Filmes - Movies 
</h1>

<p align="center">Drupal - PHP</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/PHP-purple">
  <img alt="License" src="https://img.shields.io/badge/Drupal-purple">
  <img alt="License" src="https://img.shields.io/badge/SQLite-blue">
  <img alt="License" src="https://img.shields.io/badge/HTML-orange">
  <img alt="License" src="https://img.shields.io/badge/Bootstrap-blue">
  <img alt="License" src="https://img.shields.io/badge/CSS-blue">

  <a href="https://beacons.ai/dscostat7/" target="_blank">
    <img alt="by Diego Souza" src="https://img.shields.io/badge/Made%20by-Diego%20Souza-blue">
  </a>

  <a href="https://www.linkedin.com/in/dscostat7/" target="_blank">
    <img alt="Follow me Linkedin" src="https://img.shields.io/badge/Follow%20up-Diego%20Souza-2ecc71?style=social&logo=linkedin">
  </a>
</p>


## 🚀 Projeto

Projeto contempla uma página (Home) com dez filmes em destaque, cada filme possui três atores/atrizes em seu elenco.
Cada filme possui sua página específica, com a sinopse e composição do elenco. Cada ator/atriz, possui uma página com
sua biografia e informações de filmes estrelados na plataforma.

Na sequencia deste documento, você encontrará informações de módulos para a construção dessa aplicação e um passo
a passo de como clonar e rodar localmente a mesma aplicação!

## 🔧 Tecnologias

- PHP
- Drupal
- HTML
- CSS
- Bootstrap
- SQLite

## 🚧 Módulos instalados e comandos utilizados

- Breadcumb, com o comando `composer require 'drupal/easy_breadcrumb:^2.0'`
- Gerando tema padrão `php core/scripts/drupal generate-theme movies`

## 💻 Passo a passo para rodar local

- Comece realizando o clone do repositório `git clone https://github.com/dscostat7/drupalMovies`
- Copie o arquivo `.sqlite.bkp` que se encontra na raiz do projeto, e cole em `web\sites\default\files`
- Instalando e atualizando as depencias `composer install` e `composer update`
- Feito todo o processo com sucesso, acesse o diretório `web` via terminal e execute o comando abaixo
- `php -S localhost:8888 .ht.router.php` O projeto estará disponível em seu computador no endereço `localhost:8888`

## 🎮 Quer ficar no controle?

Sem problemas, basta ir diretamente para a rota `/user` e acessar com os seguintes dados:
`usuario: admin`
`senha: teste123`


---

Developed by <a href="https://beacons.ai/dscostat7/" target="_blank">Diego Souza</a>

---
