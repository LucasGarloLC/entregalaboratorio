# Pasos para completar el «Laboratorio Git»

He abierto la terminal en VSC mediante «Ctrl + Shift + ñ» y he navegado hasta la carpeta en la que quería crear el repositorio en local mediante «cd C:\Lemoncode».
He creado la carpeta «entregalaboratorio» y he accedido a la carpeta desde la terminal mediante «cd entregalaboratorio».
He inicializado el repositorio git mediante «git init».

He creado el repositorio «entregalaboratorio» en GitHub y he copiado la URL: https://github.com/LucasGarloLC/entregalaboratorio.git
En mi terminal, he conectado el repositorio en local con el repositorio en GitHub mediante «git remote add origin https://github.com/LucasGarloLC/entregalaboratorio.git» + «git push -u origin master».


En local, he creado el archivo «README.md» con el botón «New file...» para añadir el archivo al proyecto.
He añadido el archivo a staging mediante «git add .» y he hecho un commit mediante «git commit -m "Nuevo archivo README"».
He subido los cambios a GitHub mediante «git push».

De vuelta a la terminal de VSC, en el README.md, he añadido el siguiente texto:
    # Aceituneros
    Andaluces de Jaén,
    aceituneros altivos,
    decidme en el alma:
    ¿quién, quién levantó los olivos?
He añadido el archivo a staging mediante «git add .» y he hecho un commit del archivo mediante «git commit -m "Cambio en el README».
He subido los cambios a GitHub mediante «git push».

Después, he creado una nueva rama llamada «development» mediante el comando «git branch development».
He cambiado a la nueva rama mediante «git switch development", y he añadido el siguiente texto al final del README.md: «No lo sé.»
He añadido el archivo a staging mediante «git add .» y he hecho un commit mediante «git commit -m "Cambios de la rama development"»
He subido los cambios a GitHub mediante «git push».

A mitad de camino, se me ha ocurrido la genial idea de cambiar el texto que había escrito —por alguna razón que no recuerdo— y he borrado el texto «No lo sé» y he añadido el texto «Probablemente los romanos.»
He añadido el archivo a staging mediante «git add .»

He vuelto a la rama principal mediante «git switch main».
En la rama principal, he hecho un merge con la rama development mediante «git merge development» y he visto que se ha añadido la nueva frase.
He añadido el archivo a staging mediante «git add .» y he hecho un commit mediante «git commit -m "Algunos cambios de última hora"»
Para terminar, he hecho un push de los cambios a GitHub mediante «git push».