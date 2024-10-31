# Instalación y configuración de Git

Vamos a instalar y configurar Git en nuestro equipo local

* [**Instalación**](#instalación)
* [**Configuración**](#configuración)

----

## Instalación

Para instalar git en nuestro equipo (kali linux) lo primero es actualizar los paquetes:
```sudo apt-get update```

Después con ```sudo apt-get install git``` ya se instala git.


----

## Configuración

Ahora vamos a configurar git con nuestro datos, primero para configurar el nombre hacemos
```git config --global user.name "nombre ejemplo"```

Y para configurar nuestro correo electrónico ponemos
```git config --global user.email alvaro@ejemplo.com```