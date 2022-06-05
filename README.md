## Instruções

1. Clonar projeto

2. Renomeie o arquivo **.env.example** para **.env**

3. Instalação de dependências -->
   Abra um terminal, acesse a pasta do projeto e digite:

> composer install

(caso não tenha o composer, baixe-o aqui https://getcomposer.org/download/)

4. Ainda no terminal, e ainda dentro da pasta do projeto, digite:

> php artisan key:generate

5. Também no terminal, rode o servidor com o comando:

> php artisan serve

6. Uma mensagem como esta deverá aparecer no seu terminal:

`Starting Laravel development server: http://127.0.0.1:8000 [Mon Oct 10 22:47:42 2021] PHP 7.4.14 Development Server (http://127.0.0.1:8000)`

Acesse o endereço (neste caso, http://127.0.0.1:8000) indicado através do seu navegador.

### **ATENÇÃO**:

Se você usa o anti-vírus Avast, é muito provável que ele vai achar que o arquivo server.php é uma ameaça e colocar ele em quarentena.

Caso isso ocorra, abra o Avast, acesse a aba Proteção e depois Quarentena. Selecione o server.php na lista, clique nos três pontinhos (Mais Opções) e escolha "Restaurar e adicionar exceção".