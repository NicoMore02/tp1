[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/kl-E8VQf)
# Respuestas

## ¿Porque es conveniente incluirlo?
_El archivo .gitignore es útil en proyectos bajo control de versiones con Git porque evita que ciertos archivos innecesarios o no deseados sean rastreados y versionados. Algunas razones para usarlo son :
* Evitar archivos temporales.
* Proteger datos sensibles.
* Optimizar el repositorio.
* Mantener el repositorio limpio.

## ¿Cómo se debe hacer?
_Para crear un archivo .gitignore local, se crea un archivo de texto y se le asigna el nombre ".gitignore". Luego, edita este archivo según se necesario. Cada nueva línea debe incluir un archivo o carpeta adicional que quieras que Git lo ignore.
_Las entradas de este archivo también pueden seguir un patrón coincidente:
* "*" se utiliza como una coincidencia comodín.
* "/" se usa para ignorar las rutas relativas al archivo .gitignore.
* "#" es usado para agregar comentarios.

## ¿Cómo configurar el archivo .gitignore correctamente?
_1- Usar reglas generales y específicas:
* Las reglas generales deben ir al inicio del archivo.
* Si hay excepciones, agrégalas después con !.

_2- Agrupar archivos similares:
* Ordenar por tipo de archivo o propósito (ayuda a la organización).

_3- Usar comentarios:
* Explicar por qué ciertos archivos se están ignorando.

_4- Revisar archivos ignorados en GitHub o plantillas.

_Siguiendo estos pasos, se evitará problemas de control de versiones y se mantendra el repositorio más eficiente y limpio.