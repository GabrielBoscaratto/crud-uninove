---

# Documentação do Projeto Uninove CRUD PHP - Gabriel Boscaratto

## Introdução

Este projeto é um sistema de CRUD desenvolvido em PHP utilizando o framework Laravel. O sistema faz uso da biblioteca Filament para fornecer uma interface de usuário moderna e responsiva.

## Pré-requisitos

Antes de iniciar o projeto, certifique-se de ter os seguintes itens instalados em sua máquina:

- PHP (versão 8.1 ou superior)
- Composer
- MySQL (ou outro banco de dados suportado)
- Laravel (instalação via Composer)
- Filament (instalação via Composer)

## Instalação

### Clonando o Repositório

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_DIRETORIO>
   ```

### Instalando Dependências

Execute o comando abaixo para instalar as dependências do projeto:

```bash
composer install
```

### Configurando o Ambiente

Copie o arquivo `.env.example` para `.env`:

```bash
cp .env.example .env
```

Em seguida, configure as variáveis de ambiente no arquivo `.env` de acordo com suas configurações de banco de dados.

### Migrando o Banco de Dados

Antes de iniciar o servidor, você deve criar as tabelas necessárias no banco de dados. Execute o seguinte comando:

```bash
php artisan migrate
```

### Iniciando o Servidor

Para iniciar o ambiente de desenvolvimento, utilize o seguinte comando:

```bash
php artisan serve --port=8002
```

O projeto estará acessível em: [http://127.0.0.1:8002/admin/login](http://127.0.0.1:8002/admin/login) (ou `localhost` se preferir).

## Acessando o Sistema

Para acessar a interface de administração, abra o navegador e vá para a URL:

[http://127.0.0.1:8002/admin/login](http://127.0.0.1:8002/admin/login) (ou `localhost` se preferir).

### Credenciais Iniciais

- **Email:** admin@admin.com
- **Senha:** admin

## Funcionalidades

- **Criar:** Adicionar novos registros ao banco de dados.
- **Ler:** Visualizar registros existentes.
- **Atualizar:** Editar registros existentes.
- **Deletar:** Remover registros do banco de dados.

*Observação: O Filament não tem suporte para o idioma em seu template, mas foi essencial para utilizar o layout visual do projeto.*

## Telas do Sistema

### Tela de Login

![Tela de Login](https://github.com/user-attachments/assets/8da989d6-2419-4091-92b7-bdd2d785ffa5)

### Dashboard

![Dashboard](https://github.com/user-attachments/assets/2f269f26-81b3-4f60-bdc4-69d463e346f2)

### Tela de Usuários

![Tela de Usuários](https://github.com/user-attachments/assets/674bc80c-9845-4647-9c28-48297402cf8d)

### Tela de Edição

![Tela de Edição](https://github.com/user-attachments/assets/23ddbb7d-be82-4268-8ea1-20cfe5aaf410)

---
