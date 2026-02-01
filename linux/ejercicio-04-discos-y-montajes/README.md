# Ejercicio 04 - Discos, particiones y montajes en Linux


## Objetivo

Aprender a gestionar discos en Linux, crear particiones, formatearlas
y configurar montajes persistentes.

## Entorno

- Sistema: Ubuntu Server
- Virtualización: VirtualBox
- Usuario administrador: asir

## Tareas realizadas

- Identifiación de discos
- Creación de particiones
- Formateo de sistemas de archivos
- Montaje manual de discos
- Configuración de montaje persistente (/etc/fstab)

## Capturas

Las evidencias del ejercicio se encuentran en la carpeta "capturas/".

## Incidencia resuelta durante el ejercicio

Durante la realización del ejercicio se detectó que el sistema tenía
una entrada previa en el fichero "/etc/fstab" correspondiente a un
UUID de una práctica anterior.

Esta configuración impedía que el nuevo disco se montara
correctamente tras el reinicio.

Para resolverlo se realizaron los siguiente pasos:
- Revisión del fichero "/etc/fstab"
- Eliminación de la entrada antigua con el UUID obsoleto
- Obtención del UUID correcto del nuevo disco
- Configuracíon del punto de montaje adecuado ("/datos")
- Verificación del montaje persistente tras el reinicio

Tras la correción, el sistema monta el disco correctamente de forma
automática.



