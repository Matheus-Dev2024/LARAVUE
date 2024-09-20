
quando baixar o repositorio esse são os seguintes comando que vai colocar pra baixar as dependencias 

caso use o php so no containe do docker entre no containe ( docker compose exec -it nome_do_containe bash )

caso ja tenha o php instalado apenas jogue esses comandos direto no terminal da sua ide 
{
composer clear-cache
composer install
composer update
}

ainda dentro do containe do php vai colocar o seguinte comando ( php artisan key:generate ) para que chave de criptografia da aplicação seja baixada quando vc baixar diretamente da documentação do laravel não vai precisar se preucupar com isso de pois que executar o comando vc vai no seu .env e vai vereficar na linha que conatem APP_KEY=base64:xxxxxx se  ela estive vazia APP_KEY= preucure outro comando no navegador ou diretamente na documentação do laravel 10


quando baixar o laravel vc vai no terminal e vai coloca o comando { npm install vue@latest } para baixar a ultima versão do vue 

apos fazer isso aind no terminal vai colocar o comando { npm install @vitejs/plugin-vue } para baixar as depedencias
