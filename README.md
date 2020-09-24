# AppViewsRedondeados

App Android de ejemplo con implementacion de views redondeados (Botones y EditText)


## Uso | Usage 
Usa este archivo como background de tu view 
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

**<solid android:color="@color/colorPrimary" />** color del relleno que tendrá el elemento

**<stroke android:width="1dp" android:color="@color/colorPrimary" />**
stroke color del borde del elemento
Color : cambia el color del borde
Width : establece el ancho del borde

**<corners android:radius="15px" />** radius establece el radio de redondeado del elemento

En el boton solo coloca la siguiente linea :

android:background="@drawable/button_rounded_background_no_fill"
 


![](https://i.imgur.com/JwT9ggY.jpg)

Para crear un boton redondeado con relleno solo establece el mismo color de solid y stroke

En el boton solo coloca la siguiente linea :

android:background="@drawable/button_rounded_background_fill"

![](https://i.imgur.com/oiFWLyK.jpg)

Puedes hacerlo con un EditText para obtener algo similar

En el EditText solo coloca la siguiente linea :

android:background="@drawable/edt_rounded_background"

![](https://i.imgur.com/v7p7TVt.jpg)

### Puedes crear algo como esto:

![](https://i.imgur.com/CD3JRDW.jpg)

#### Si te fue de ayuda dale amor a este repositorio con una estrella :)
#### If it was helpful, give love to this repository with a star :)

## License
[MIT](https://choosealicense.com/licenses/mit/)
