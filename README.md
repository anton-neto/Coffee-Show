# Coffee Show

<h1>Sistema de Gestão de Cafeteria Desenvolvido em PHP com PDO</h1>

<h1>Para rodar este projeto em PHP, siga estas etapas:</h1> <h2>1. Clone o Repositório</h2>
No seu terminal, execute o seguinte comando para clonar o repositório:
https://github.com/anton-neto/Coffee-Show

<h2>2. Configure o Servidor Local (XAMPP ou WAMP)</h2>
Certifique-se de que você tem o XAMPP ou WAMP instalado no seu computador para rodar o projeto em PHP.
Inicie o servidor Apache e o MySQL no XAMPP ou WAMP.

<h2>3. Importe o Banco de Dados</h2>
Acesse o phpMyAdmin em http://localhost/phpmyadmin.
Crie um banco de dados com o nome cafeteria_db.
Importe o arquivo SQL localizado na pasta /database do repositório clonado.
<h2>4. Configure o Arquivo de Conexão com o Banco de Dados</h2>
Abra o arquivo config.php localizado na pasta principal do projeto e configure as credenciais do banco de dados:
define('DB_HOST', 'localhost');
define('DB_NAME', 'cafeteria_db');
define('DB_USER', 'root');
define('DB_PASS', '');

<h2>5. Instale as Dependências do Projeto</h2>
Verifique se todas as dependências necessárias estão configuradas, como o PDO (PHP Data Objects).
Não é necessário instalar pacotes adicionais, pois o PDO já é embutido no PHP.

<h2>6. Execute o Projeto</h2>
Copie a pasta do projeto para o diretório htdocs do XAMPP ou www do WAMP.
No navegador, acesse o projeto através de http://localhost/sistema-cafeteria.

<h2>7. Teste o Sistema</h2>
Navegue pelo sistema de gestão de cafeteria e teste todas as funcionalidades.