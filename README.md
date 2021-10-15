# SSOO-tarea02
##### Autor: Carlos Alexis Escobedo Román
##### Correo: carlos.escobedo@alumnos.uv.cl
El problema que nos fue dado consiste en investigar algunos comandos de linux (**jq** y **curl**), con lo cuales deberiamos resolver el problema planteado.
La solución encontrada fue llamar el archivo JSON usando **curl** y además escondemos la tabla de descarga con el parametro -s, continuando utilizando **jq** para
dar el formato al archivo JSON y tambien aplicar filtros para entregrarlo de la manera que fue pedido, para finalizar se envia el contenido ya filtrado al nuevo archivo
mediante al redireccionamiento(**>>**) y mostrar un mensaje de finalizado.
