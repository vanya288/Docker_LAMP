# LAMP
_Podstawowe środowisko stosu LAMP zbudowane przy użyciu Docker Compose. Składa się z następujących elementów:_
* PHP
* Apache
* MySQL

_Serwery **PHP** i **MySQL** są przyłączone do sieci backend a **Apache** do backend oraz frontend._ 
_**Apache** ma wystawiony na świat zewnętrzy port **6666**_


# Struktura projektu
* docker-compose.yml : _Plik docker-compose w którym są opisane są związki pomiędzy poszczególnymi kontenerami_
* docker-compose.png : _Reprezentacja graficzna dla pliku docker-compose.yml_
* public
  * index.php
* .docker
  * apache
    * Dockerfile : _Plik Dockerfile dla usługi cząstkowej apache_
    * imd.apache.conf : _Plik konfiguracyjny dla usługi cząstkowej apache_
  * php
    * Dockerfile : _Plik Dockerfile dla usługi cząstkowej php_
* README.md

# Uruchomienie
'docker-compose up -d`

