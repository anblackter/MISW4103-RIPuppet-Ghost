# Pruebas Automatizadas de Ghost usando RIPpuppet 
Se construye el siguiente repositorio en el cual se almacena el código fuente utilizado para correr las pruebas automizadas de Ghost usando RIPuppet.

- Repositorio original (código base): https://github.com/TheSoftwareDesignLab/RIPuppetCoursera

## Integrantes del grupo
- Carlos Arturo Rico Salazar
- Santiago Gomez Perdomo
- Angel Yecid Henao Bedoya
- Julian Ricardo Villate Torres

## Curso
MISW4103

## Entrega
Semana 4

## Descripción
- Se utiliza la version de node v20.16.0, siguiendo las recomendaciones del tutorial.
- Para el estado coldstart antes de cada prueba, se utiliza docker con los siguientes comandos:
```
docker run --name some-ghost -e NODE_ENV=development -p 2368:2368 ghost:5.96.0
docker rm some-ghost
```
- Se varia el archivo config.json para cambiar el browser después de cada prueba, asegurando el estado coldstart.


# RIPuppet
A node js library for GUI Ripping on web applications

# Executing

First check that you are using a valid Node version. We recommend you to use Node v12.22.12.

Check the content inside config.json file.

Modify the required parameters.

To execute the testing tool use the following command:

```
node index.js

```

For example:

```
node index.js

```
