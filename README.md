# Analisis FODA

## Agregando una imágen a nuestro archivo index.html
Si quiero agregar una imágen, voy a usar el elemento:
```sh
<img src="public/images/Analisis_FODA.webp" alt="nombre de la imágen">
```
NOTA:(public/images/Analisis_FODA.webp) es el paso correcto para que se pueda acceder a la imagen y luego mostrarla en nuestra página, entonces:
* 1er paso: accedo a la carpeta public.
* 2do paso: accedo a la carpeta images.
* 3er paso: escribimos el nombre de la imagen que queremos mostrar.

## Editando la imágen
Para poder editar la imágen, al elemento img le agregé una clase "imagen".
```sh
<img class="imagen" src="public/images/Analisis_FODA.webp" alt="imágen analisis FODA">
```
Gracias a esto, voy a poder editar la imágen del archivo index.html en un archivo style.css:
```sh
.imagen{
    width: 400px; # será el ancho de la imágen
    height: auto; # la altura de la imágen
}
```
Esto lo hice con el fin de poer achicar un poco la imágen, ya que era algo grande a la vista de uno.


