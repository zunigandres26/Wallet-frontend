# wallet-app

Este es el proyecto de la clase de **Ingenieria de Sofware** Seccion **1900** para el 2 Periodo academico de la UNAH del año 2021.

Nuestra propuesta es una aplicacion de una billetera electronica para controlar las finanzas personales de nuestros usuarioas.

Las tecnologias empleadas en el desarrollo son:
- Backend: Python3 Flask
- Backend: MySQL
- Frontend: React.js

Nuestro equipo esta conformado por

| Estudiante |  Cuenta  | Correo | 
|---|---|---|
| Jose Enrique Barrientos Estrada | 20161005918 | Jose97_barrientos97@hotmail.com | 
| Jessica Alejandra Manzanares Moreno | 20151001483 |Jamanzanares@unah.hn|
|Victor Miguel Pineda | 20151030886 | vpinedaa@unah.hn |
| Roger Alfredo Molina | 20161001463 | rmolinav@unah.hn |
| Andrés Zuniga | 20161003850 | aarodriguezz@unah.hn |



# Guia para montar el Frontend en Linux-Ubuntu

Comenzamos intalando ``nodejs`` que es un entorno de JavaScript que nos permite usar la liberia de ``ReactJS`` para el desarollo del frontend con el siguiente comando.

```bash
sudo apt install nodejs
```
Seguidamente instalamos el instalador de paquetes de Node
```bash
sudo apt install npm
```
ahora nos ubicamos en la ruta ``./Frontend/`` del proyecto para instalas las dependencias que se encuentran en el archivo ``package.json`` con el siguiente comando
```bash
npm install package
sudo npm install -g serve
```
Finamente podemos correr el siguiente comando para lanzar nuestra aplicacion
```bash
npm run build
serve -s build
```