- Copiar .env.example para .env

- Configurar conexão com banco de dados com variáveis DB_

- Alterar chave CSRF_KEY no arquivo .env | [IT-Tools](https://it-tools.tech/token-generator?length=32)

- Testar conexão e migração de dados

| Linux: vendor/bin/phinx migrate --dry-run

| Windows: php vendor/bin/phinx migrate --dry-run

- Rodar servidor embutido do php (utilizar url APP_URL do .env)

| php vendor/bin/phinx migrate --dry-run

- Executar migração de dados

| Linux: vendor/bin/phinx migrate

| Windows: php vendor/bin/phinx migrate

1-Routes (routes.php)
2-Controller (ProductController > CategoryController)
3-Migrations ()
4-Repository (ProductRepository > CategoryRepository)
5-Model(product > category)
6-Service (ProductService > CategoryService)
7-Duplicar (Views/admin> products > categories)
8-Controller (views)
9-Views(alterar)