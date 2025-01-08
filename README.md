# Dir-Back
Utilidad en bash para retrocer directorios en la terminal sin usar los odiosos ../../../../

### Como usar

Es recomendable poner el directorio dentro del PATH o incluir el archivo en alguna ruta que este dentro del PATH  como por ejemplo "/usr/bin" para que su uso sea mas absesible.


Una vez que se pueda acceder al archivo desde cualquier directorio este seria el modo de usar la utilidad.

```
. db 1
```

+  **"."** Punto para usar la utilidad desde el directorio actual.
+  **"db"** llama a la utilidad para retroceder directorios.
+ **"1"** numero de directorios a retroceder (variable)

![pwd](/imagenes/pwd.png)

Como podemos ver, se retrocede el numero de directorios dependiendo del numero que pasamos como parametros.

![pwd2](/imagenes/pwd2.png)

**NOTA:** EL limite es **10** y si el numero es mayor que 10 se cerrara la terminal y no se por que xd. 
Cualquier contribucion comunicarse. Saludos. 
                                                 
