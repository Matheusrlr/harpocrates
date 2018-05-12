# harpocrates
Sistema de votação eletrônica Harpocrates

Sistema de votação desenvolvido para a disciplina de segurança de urnas eletrônicas.

- Carlos Magno
- Lucas Geraldo
- Matheus Reis

UFSJ 2018

# Requisitos

- Obrigatorios
* python3
* eel
* mysql

- Opcional
* phpmyadmin

Para instalar as dependências execute:
> python3 -m pip install eel

# Banco de dados

O módulo de mesário do harpocrates está utilizando um banco de dados mysql para completar as suas funcionalidades, portanto é necessário a criação de um banco e uma tabela.

Configurando o Banco:

- Crie um novo banco importado o banco_de_dados.sql disponível na pasta banco de dados. Será criada um banco chamado eleitores.

- Agora importe os dados do arquivo eleitores.sql que contém a população do banco.

- Agora configure os dados de conexão com o mesmo no arquivo conector_bd.

# Para Executar

Execute:
> python3 mesario.py
