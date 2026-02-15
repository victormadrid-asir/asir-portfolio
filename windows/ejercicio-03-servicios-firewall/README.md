# Ejercicio 03 - Servicios y Firewall en Windows Server


## Objetivo

Administrar servicios en Windows Server y configurar reglas básicas
del firewall para permitir y denegar conexiones.

## Entorno

- Sistema: Windows Server 2022 Standard (Desktop Experience)
- Nombre del servidor: SERVER01
- Usuario administrador: Administrador

## Tareas realizadas

- Comprobación y gestión de servicios
- Instalación de un servicio web (IIS)
- Configuración del firewall de Windows
- Verificación de accesos permitidos y denegados

## Verificación del Firewall

Para comprobar el funcionamiento del Firewall de Windows, se configuró
una redirección de puertos (port forwarding) en VirtualBox, permitiendo
el acceso desde el host al servicio IIS del servidor.

Con la regla HTTP habilitada, el acceso desde el host fue bloqueado, demostrando
el correcto funcionamiento del firewall a nivel de red.


## Capturas

Las evidencias del ejercicio se encuentran en la carpeta 'capturas/'.


