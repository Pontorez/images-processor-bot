1. ```git clone https://github.com/Pontorez/images-processor-bot```
2. ```cd images-processor-bot```
3. ```php -r "readfile('https://getcomposer.org/installer');" | php```
4. ```./composer.phar update```
5. Import dump.sql into MySQL database
6. Set MySQL connection params in bot:19
7. ```./bot schedule urls.txt```
8. ```./bot download```
