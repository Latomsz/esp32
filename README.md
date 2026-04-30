Projet esp32 LED + BUZZER
Un projet pour contrôler une LED et un buzzer avec un ESP32, et afficher les données sur un site web hébergé sur une machine virtuelle Ubuntu.

Matériel
ESP32
1 LED 
1 buzzer 

1. Machine virtuelle Ubuntu
Installe VirtualBox ou VMware.

Crée une machine virtuelle avec Ubuntu Server.

2. Serveur Web (Apache + PHP)
Ouvre un terminal dans Ubuntu et exécute :
sudo apt update  sudo apt install apache2 php libapache2-mod-php

3. Site Web
Place ce fichier dans /var/www/html/index.php :
Remplace [IP_ESP32] par l'adresse IP de ton ESP32.

Code ESP32
Télécharge ce code sur ton ESP32 :
ESP32.ino

Utilisation
1. Accède au site web via l'IP de ta machine virtuelle Ubuntu.

2. Clique sur "Allumer LED" ou "Allumer Buzzer" pour contrôler l'ESP32.


