Ejercicio Teorico ¿Qué es un conflicto en Git? Un conflicto ocurre cuando Git no puede fusionar automáticamente los cambios de dos ramas porque ambas han modificado la misma parte de un archivo, y no sabe cuál versión conservar.

¿Cuándo ocurre? • Al hacer git merge o git pull, si: ? Dos personas (o ramas) cambiaron la misma línea en un archivo. ? Una rama borra un archivo que la otra modificó. ? El mismo archivo fue editado de formas incompatibles en ambas ramas.

¿Es bueno o malo? • No es malo, es normal en el trabajo colaborativo. • Es una señal de que dos partes han trabajado sobre lo mismo y hay que tomar una decisión. • Lo importante es resolverlo bien, eligiendo el contenido correcto.

¿Se puede evitar un conflicto? Sí, no siempre, pero se pueden reducir al mínimo: 1. Comunicación clara en el equipo (quién trabaja en qué). 2. Dividir tareas por archivos o módulos para que cada persona edite diferentes zonas. 3. Actualizar frecuentemente tu rama con git pull para integrar cambios antes de que se acumulen. 4. Usar ramas pequeñas y cortas, evitando cambios grandes sin sincronizar. 5. Usar herramientas de comparación y revisión antes del merge. Ejercicio Practico

Ejer10: Muestra que he quitado el pollo y lo he cambiado por lomo en el git diff master suprema y con get diffmaster bife no sale.

Ejer11:Te sale la milanesa.

Ejer12:Si pone Already up to date Ejer13:No Ejer14:Igual que el otro no va Ejer15: Que sale pan rrallado y bife

Ejer18: Da error
