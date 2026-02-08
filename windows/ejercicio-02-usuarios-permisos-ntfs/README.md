# Ejercicio 02 - Usuarios, grupos y permisos NTFS en Windows Server


## Objetivo

Gestionar usuarios y grupos locales en Windows Server y aplicar permisos
NTFS sobre carpetas para controlar el acceso a los recursos.

## Entorno

- Sistema: Windows Server 2022 Standard (Desktop Experience)
- Nombre del servidor: SERVER01
- Usuario administrador: Administrador

## Tareas realizadas

- Creación de usuarios locales
- Creación de grupos locales
- Asignación de usuarios a grupos
- Creación de carpetas compartidas
- Configuración de permisos NTFS 
- Verificación de accesos

## Prueba adicional de seguridad

Como verificación adicional, se aplicó una denegación explícita de
permisos NTFS al usuario "empleado2", impidiendo la creación de archivos
y su lectura de "C:\Datos".

El grupo "empresa" mantiene los permisos de escritura y lectura, demostrando la
prioridad de las reglas de denegación explícitas frente a permisos
heredados o de grupo en NTFS.

## Capturas

Las evidencias del ejercicio se encuentran en la carpeta 'capturas/'.


