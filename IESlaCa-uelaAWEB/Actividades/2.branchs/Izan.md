¿Cómo se inicializa un repositorio local? (que comando se debe ejecutar?) git init ¿Cómo hago para que un directorio deje de ser controlado por git?

rm -rf .git (Este comando elimina todo el historial y configuración de Git en ese directorio). • Si agrego un archivo a un directorio que ya está siendo controlado por git, ¿está siendo controlado por git? No automáticamente. Debes agregarlo manualmente con git add para que Git lo controle. • ¿Qué comando se utiliza para agregar un archivo al repositorio local? Se usa:

git add • ¿Cómo determino qué archivos fueron modificados? Ejecuta:

git status • ¿Qué comando se utiliza para hacer un commit? Se usa:

git commit -m "Mensaje descriptivo" • ¿En sus propias palabras, qué es un commit? Un commit es un punto de guardado que registra los cambios realizados en los archivos del proyecto. Es como tomar una foto del estado actual del trabajo para poder volver a ella más tarde si es necesario.

EJERCICIO PRACTICO

Ejer3:que al hacer git status de estar en rojo pasa a verde(muestra el estado actual del repositorio y el archivo.

Ejer5: Antes de ejecutar git add sandwich.txt, el comando git status muestra el archivo "sandwich.txt" como "no rastreado" o "modificado pero no añadido".

Ejer7: El comando git status dice que no hay cambios,

Ejer9:Al ejecutar git log muestra los commit que hay y la información sobre ellos quien los a creado y cuando y empieza por el que se a creado mas recientemente.

Ejer10:Con el git log----online dice las acciones que se a realizadoy con git log --stat,Muestra el historial de commits con un resumen de los archivos modificados, líneas añadidas y eliminadas en cada uno.

Ejer11:Es una ventana que muestra los cambios que se producen en el repositorio del codigo en rojo:lineas eliminadas en verde:lineas añadidas en amarrillo:líneas modificadas

Ejer14:Git detecta que se ha echo una cambio de nombre del archivo y lo muestra como una una operación de renombre y despues del git status no dice que no hay cambios pendientesy el git log ---oneline aparece un nuevo commit con su hash y mensaje

Ejer15: En git status aparece el archivo pero con la palabra deleted delante y con git –log oneline aparece un nuevo commit que indica que se a eliminado.

Ejer16:Se ve las acciones que se han realizado y el cambio de nombre y cual se ha eliminado.
