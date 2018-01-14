## Как добавить еще одну версию PHP?

Скачать отсюда http://windows.php.net/downloads/releases/ 5 файлов с нужной версией PHP,
например (для 7.2.1):

http://windows.php.net/downloads/releases/php-7.2.1-nts-Win32-VC15-x64.zip
http://windows.php.net/downloads/releases/php-7.2.1-nts-Win32-VC15-x86.zip
http://windows.php.net/downloads/releases/php-7.2.1-Win32-VC15-x64.zip
http://windows.php.net/downloads/releases/php-7.2.1-Win32-VC15-x86.zip
http://windows.php.net/downloads/releases/php-7.2.1-src.zip

Из первых четырех извлечь файлы /dev/php7(ts).lib и положить в папку libs этого репозитория, 
переименовав по аналогии с:

php-VC15-7.2.0-nts-x64.lib
php-VC15-7.2.0-nts-x86.lib
php-VC15-7.2.0-ts-x64.lib
php-VC15-7.2.0-ts-x86.lib

Исходники (php-7.2.1-src.zip) распаковать в папку src. Удалить из нее все файлы `*.c`, `*.cpp`.
