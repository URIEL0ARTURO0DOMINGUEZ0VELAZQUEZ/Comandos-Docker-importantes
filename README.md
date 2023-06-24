#### Comandos-Docker-importantes
comandos que se utilizan regularmente

## primer comando sirve para saber el la dirreccion para nuestro Broker
**nslookup broker.hivemq.com**         o tambien
**nslookup public.mqtthq.com**

## segundo comando es para encendeer nuestros contenedores
**docker start $(docker ps -a -q)**

## tercer comando es para apagarlos
**docker stop $(docker ps -a -q)**

## cuarto comando es para consultar el estado de nuestros contenedores
docker compose
**docker container ls -a**

## quito comando es para consultar nuetro tcp
**netstat -an | grep 1880**

## sexto comando: este comando se utiliza ppara mandar señales
**docker exec -it id-contenedor mosquitto_pub -h ip-broker -t (name-broker) -m "texto"**
ejemplo 
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/Comandos-Docker-importantes/assets/136390705/edb122bb-48af-4297-af13-219e9b899ac0)

lo que hace en Node-RED
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/Comandos-Docker-importantes/assets/136390705/07a58614-57be-4449-80ad-6ba8108e8f76)

## septimo punto 
el **JSON** convertirlo siempre en JaveScrip 

## url para dashboard consultar
*http://localhost:1880/ui*

## octavo comando para realizar mysql
**docker exec -it 9acdac6f354a mysql -p**
## noveno comando para bases de datos 
mysql>**show databases**


