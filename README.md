# UniSocial
```
Tecnologias: 
PHP 8.2
Laravel 10
MySQL 8+;
React JS 17.0.2
```

```
Utilizei o Create React APP então deixei em repositórios separados, para ter controle dos fluxo da aplicação e dos commits, segue os links do PHP e React.Mas esses links são apenas para visualizar o histórico de commits. Os arquivos PHP e React estão combinados em um único repositório. OBS: Modifique os nomes das pastas para minúsculas para evitar conflitos.
UniPHP: https://github.com/educcarnn/UniPHP
UniReact: https://github.com/educcarnn/UniReact
```


Para executar o projeto, entre em cada pasta de arquivo, conforme a execução do projeto, primeiro do Laravel e depois o React


**Entre no diretório do react e siga os passos**
```
(Laravel)
1 - Entre no arquivo em PHP, certifique-se de ter o PHP versão 8.2 instalado e o composer
2 - Após isso, entre no terminal de projeto, e execute a série de comandos a seguir
```
**Rodar o Laravel**
```
# Instale as dependências do Composer
composer install

# Gere o link simbólico para armazenar imagens
php artisan storage:link

# Se necessário for, execute para ter permissões necessárias
chmod -R 755 public/storage

# Copie o arquivo de configuração do ambiente
cp .env.example .env

O comando a seguir não é necessário, somente em caso do import estiver com erro, mas nesse caso deve se importar o dump gerado que está neste repo
php artisan migrate

# Rodar o servidor
php artisan serve

Dcoumentaçao para auxílio:
https://laravel.com/docs/10.x/filesystem
```
**Entre no diretório do react e siga os passos**
```
(React)
1 - Entre no arquivo em react, certifique-se de ter o Node LTS, yarn instalado
2 - Após isso, entre no terminal de projeto, e execute a série de comandos a seguir
```


**Rodar o React**
```
# Instale as dependências do projeto
yarn

# Execute o servidor
yarn start
```
**Pacotes externos**
```
Pacotes Externos (Node.js):
react-bootstrap: Versão mais recente
DraftJS: Versão mais recente
axios: Versão mais recente
react-fontawesome: Versão mais recente
```