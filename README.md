Documentação do Projeto Uninove

Introdução

Este projeto é um sistema de CRUD (Create, Read, Update, Delete) desenvolvido em PHP com o framework Laravel. O sistema utiliza a biblioteca Filament para fornecer uma interface de usuário moderna e responsiva.

Pré-requisitos

Antes de iniciar o projeto, certifique-se de ter o seguinte instalado em sua máquina:

PHP (versão 8.1 ou superior)
Composer
MySQL (ou outro banco de dados suportado)
Laravel (instalação via Composer)
Filament (instalação via Composer)
Instalação

Clonando o Repositório

git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_DIRETORIO>
Instalando Dependências
Execute o comando abaixo para instalar as dependências do projeto:


composer install
Configurando o Ambiente
Copie o arquivo .env.example para .env:

cp .env.example .env
Configure as variáveis de ambiente no arquivo .env de acordo com suas configurações de banco de dados.
Migrando o Banco de Dados
Antes de iniciar o servidor, você deve criar as tabelas necessárias no banco de dados. Execute o seguinte comando:


php artisan migrate
Iniciando o Servidor

Para iniciar o ambiente de desenvolvimento, utilize o seguinte comando:


php artisan serve --port=8002
O projeto estará acessível em: http://127.0.0.1:8002/admin/login (ou localhost se preferir)

Acessando o Sistema

Para acessar a interface de administração, abra o navegador e vá para a URL:

http://127.0.0.1:8002/admin/login (ou localhost se preferir)

Credenciais Iniciais
Email: admin@admin.com
Senha: admin
Funcionalidades

Criar: Adicionar novos registros ao banco de dados.
Ler: Visualizar registros existentes.
Atualizar: Editar registros existentes.
Deletar: Remover registros do banco de dados.


(Filament não tem suporte para lingua no seu template infelizmente, porem foi essencial para utilizar o template visual do projeto)
