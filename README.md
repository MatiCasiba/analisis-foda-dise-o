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

## Agregando elementos de anclaje
Para crear hipervínculos que nos permita navegar a otra pág, con el objetivo de saber más del tema, usaré el siguiente elemento:
```sh
<a href="https://raulloaiza.com/ventajas-y-desventajas-del-foda/blog/" target="_blank">ventajas y desventajas</a>
```
* En el href irá la dirección de la página
* La función de tareget="_blank", es que abrirá otra pestaña al momento de navegar, entonces con esto logro que siga la pestaña de mi página.

### Agregando un elemento anclaje al elemento imágen
La imágen que agrego estará identada a un elemento de anclaje, con la finalidad de que se amplie más la imágen, pero en otra pestaña ( utilizando nuevamente el target="_blank"):
```sh
<a href="https://assets.asana.biz/transform/485b5890-ad68-4914-bace-de38f4d2a650/inline-project-management-SWOT-analysis-4-es-2x?io=transform:fill,width:1680&format=webp" target="_blank"><img class="imagen" src="public/images/ejemplos-analisis-foda.webp" alt="imágen ejemplos de FODA"></a>
```

