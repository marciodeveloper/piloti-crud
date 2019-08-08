# Sistema de CRUD em Laravel 5.8

### Primeiros Passos 

Faça um clone do repositório em sua máquina:

```
git clone https://github.com/marciodeveloper/piloti-crud
```

### Instalação

Execute o comando em seu terminal, para instalar o pacote de permissões:

```
composer require spatie/laravel-permission
```
Para migrar as tabelas, execute o seguinte comando:

```
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider" --tag="migrations"
```
Em seguida, crie o banco de dados e atualize o .env para incluir as informações do banco de dados.

Para construir as tabelas, execute:

```
php artisan migrate
```
Para publicar o arquivo de configuração do pacote de permissões, execute:

```
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider" --tag="config"
```
### Laravel Collective Form

Execute o comando abaixo para instalar o controlador:

```
composer require laravelcollective/html
```
### Controlador de Autenticação

Execute este commando em seu terminal:

```
php artisan make:auth
```
### Controlador de Posts

Execute o comando em seu terminal:

```
php artisan make:model Post -m
```
Por último, faça uma nova migração das tabelas em seu terminal:

```
php artisan migrate
```
## Autor

**José Márcio Barthem**
