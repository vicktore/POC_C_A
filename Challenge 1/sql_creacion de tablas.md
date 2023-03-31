Pasos

Craer Base de Datos Mysql

ip: 212.1.208.201
DB: u156469157_poc_ca
User: u156469157_poc_ca
Contraseña: Poc_ca2023%

Creamos el usuario, con acceso remoto
CREATE USER 'u156469157_poc_ca'@'%' IDENTIFIED BY 'Poc_ca2023%';

CREATE DATABASE u156469157_poc_ca;

damos permisos
GRANT ALL PRIVILEGES ON u156469157_poc_ca.* TO 'u156469157_poc_ca'@'%';

comprobamos
SHOW GRANTS FOR 'u156469157_poc_ca'@'%';

469157_poc_ca'@'%' IDENTIFIED 


revisamos los csv y validamos los encabezados.

ajustamos los archivos con sus encabezados.

creamos las tabla con datos u156469157_poc_ca.sql

