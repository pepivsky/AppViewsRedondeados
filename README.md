# AppViewsRedondeados

App Android de ejemplo con implementacion de views redondeados (Botones y EditText)


## Uso | Usage 
Usa el archivo "button_rounded_background_fill.xml" como background de tu view 
```xml
<!--button_rounded_background_fill.xml-->
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="@color/colorPrimary" />

    <stroke
        android:width="3dp"
        android:color="@color/colorPrimary" />

    <padding
        android:bottom="1dp"
        android:left="1dp"
        android:right="1dp"
        android:top="1dp" />

    <corners android:radius="15px" />

</shape>
```

## Propiedades que te interesan | Interesting properties
Para crear un boton redondeado sin relleno y con borde de color modifica lo siguiente

**Solid**
```xml
 <!--solid es color del relleno que tendrá el elemento-->
<solid android:color="@color/colorPrimary" />
```
-**Stroke:** color del borde.  

-**Color:** color aplicado al elemento.  

-**Width:** ancho del elemento en dp.  

```xml
 <!--stroke color del borde del elemento
    Color : cambia el color del borde
    Width : establece el ancho del borde-->
<stroke android:width="1dp" android:color="@color/colorPrimary" />
```

**Corners:** esquinas del elemento
```xml
 <!--radius establece el radio de redondeado del elemento en píxeles -->
<corners android:radius="15px" />
```

**Para obtener un botón redondeado y sin relleno coloca la sigiente línea:**

```xml
android:background="@drawable/button_rounded_background_no_fill
```
 
![](https://i.imgur.com/JwT9ggY.jpg)

Para crear un boton redondeado con relleno establece el mismo color de **solid** y **stroke**

Para **aplicar el estilo** en el botón coloca la siguiente línea :

```xml
android:background="@drawable/button_rounded_background_fill
```
![](https://i.imgur.com/oiFWLyK.jpg)  


**Puedes hacerlo con un EditText para obtener algo similar a esto:**  

![](https://i.imgur.com/v7p7TVt.jpg)

En el EditText coloca la siguiente línea :
```xml
android:background="@drawable/edt_rounded_background"
```



### Puedes crear algo como esto:

![](https://i.imgur.com/CD3JRDW.jpg)

#### Si te fue de ayuda dale amor a este repositorio con una estrella :)
#### If it was helpful, give love to this repository with a star :)

## License
[MIT](https://choosealicense.com/licenses/mit/)
