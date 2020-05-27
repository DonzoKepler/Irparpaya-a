...............................
#Nombre del script: dk029
...............................
#Significado: Acompañar a uno hasta ponerlo en camino 
#Lengua: french - France
..............................
.........................
#NAME SCRIPT: dk029
.........................
#dk029 meaning = Accompany one to put it on the road.
#Language: French - France 
.........................

#Domingo 15/03/2020
#Martes 29/12/2020
#by: real strategy / rwam

#Script diseñado para la extracción de url de páginas web, Mostrar los estatus que arrojan cada uno de dichos host y analizar los servicios que brinda con un scan usando nmap 

PASO N°1

#Instalar paquetes para el buen inicio del script

apt update && apt upgrade -y

pkg install nmap

pkg install wget

pkg install curl

pkg install git


PASO N°2

#Instalar el script host-extractor-v2

git clone https://github.com/DonzoKepler/dk029.git

cd dk029

chmod +x real-host-v2.sh

bash real-host-v2.sh



PRESIONA UNA ENTER PARA CONTINUAR...
