<p align="center">
    <b><h1>Rotas:</h1></b>
    <table border="1">
    <tr>
        Addresss
    </tr>
    <tr>
        <td>POST</td>
        <td>http://127.0.0.1:8000/api/address</td>
        <td>Cadastra um endereço</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>http://127.0.0.1:8000/api/address</td>
        <td>Retorna todos endereços</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>http://127.0.0.1:8000/api/address/{id}</td>
        <td>Retorna endereço de id correspondente</td>
    </tr>
    <tr>
        <td>PUT</td>
        <td>http://127.0.0.1:8000/api/address/{id}</td>
        <td>Altera o endereço de id correspondente</td>
    </tr>
    <tr>
        <td>DELETE</td>
        <td>http://127.0.0.1:8000/api/address/{id}</td>
        <td>Exclui o endereço de id correspondente</td>
    </tr>
    </table>
    <b><p>Esta regra vai para cidade e estados, mas todas as rotas podem ser conferidas com o comando:</p></b>
    <p><i>php artisan route:list</i></p>
    <b><p>ATENÇÃO: Foi adicionada uma validação bem simples, para conseguir visualizar precisa adicionar Accept -> application/json no Postman.</p></b>
    ----------------------------------------------------------
    <b><h1>Como configurar a aplicação:</h1></b>
    <b><p>Depois de fazer o clone do repositório em sua maquina, pelo prompt vá até o local do projeto e execute:</p></b>
    <p><i>composer install --no-scripts</i></p>
    <b><p>Copie o arquivo env.example e renomei para .env:</p></b>
    <p><i>em linux o comando é cp .env.example .env , mas você pode fazer isto manualmente tanto no linux como no windows.<i></p>
    <b><p>Dentro do arquivo .env, configure seu banco de dados. </p></b>
    <p><i>DB_CONNECTION=mysql  (tipo do banco de dados)</p>
    <p>DB_HOST=127.0.0.1        (url do banco de dados)</p>
    <p>DB_DATABASE=address_bd     (nome da base de dados)</p>
    <p> DB_USERNAME="exemplo"   (nome do usuario da base de dados)</p>
    <p>DB_PASSWORD="exemplo"    (senha do usuario da base de dados, caso não tiver deixe vazio)</i></p>     
    <b><p>Execute as migrações</p></b>
    <p><i>php artisan migrate</i></p>
    <b><p>Iniciar a aplicação</p></b>
    <p><i>php artisan migrate</i></p>
    ---------------------------------------------------------
 </p>
