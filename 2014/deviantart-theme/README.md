# Theme para Wordpress parecido al fabuloso deviantART #

      Este Theme lo desarrolle para un cliente que es fotógrafo y le propuse hacer un sitio parecido a Deviantart para que expusiera sus fotos de la mejor manera y le propuse esto al cliente porque quiera un reto ya que en aquel entonces Deviantart era uno de los mejores sitios para fotografía es que el código fuente de Deviantart es tan sublime y consume muy pocos recursos del servidor y del  Brower en este Theme use como bases del theme BigFoo de THBThemes para poder arrancar desde una plantilla acorde a este proyecto me refiero a los loop formats de los post y los stream, y es un **theme** hecho para  **Wordpress**, tiene incluido la función de offset súper útil a la hora de agregar una página a favoritos del browser esto por la opción de navegación infinita que posee  el theme, tiene una barra parecida al adobe Acrobat Reader PDF, que facilita cuando carga un bloque de imágenes con el scroll infinito se puede ir de bloque en bloque ósea pagina 1, pagina 2 etc., al igual que se puede hacer colocando directamente el número de la página si ya fue cargada va a la página solicitada y la muestra, la barra también muestra la cantidad de fotos cargadas en la página que está activa en el viewerport.

      Este theme tiene tres formas de ver los artículos y las fotos al igual que dos formas de paginación infinita y normal, posee slideshow.
      
      He utilizado la librería phpExifRW, para sacar los datos de la cámara usada para tomar las fotos por ejemplo: foco, lentes, y todas esas características lo hace solo una vez y es cuando se sube la foto al artículo o post y almacena la información sacada de la foto en la DB de WordPress para no hacer más uso de esta librería  para poder presentar la información de las fotos parecido como lo hace deviantart, presenta la leyenda de la foto cuando se va al post o articulo.
      
      Las categorías son presentadas al estilo que lo hace  deviantart si se selecciona una categoría padre muestra la categoría padre y el primer nivel de los hijos las demás categorías desaparecen y aparece un link nuevo que da la posibilidad de mostrar todas las categorías anteriores todo esto manipulando la información de la DB de WordPress objetos $wpdb (DB), $term y funciones get_category_by_slug, get_term.

      Una de las características más emblemáticas es la posibilidad de ir atrás y adelante en el browser sin que se pierda lo ya cargado en la navegación infinita teniendo así la posibilidad de seguir cargando nuevas páginas, en la navegación infinita al igual que lo hace Deviantart, tiene zoon las fotos , las páginas de los comentarios se cargan solo una vez, cuando se hace click en alguna página de los comentarios por ejemplo pag10 si ya la ha cargado simplemente muestra su contenido sin volver hacer petición al servidor o a la DB esto es muy importante para el ancho debanda al igual que la navegación infinita no la vuelve a cargar si se va a un link de contenido y se regresa.

  **>>>**  [**Codigo fuente aqui**](https://github.com/dennysjmarquez/SOURCE-CODE-theme-wordpress-cecichaparroart-deviantart-style)  **<<<**  

----------

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen1.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen2.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen3.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen4.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen6.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen7.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen9.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen11.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen13.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen14.png)

![](https://raw.githubusercontent.com/dennysjmarquez/portfolio/master/2014/deviantart-theme/Imagen15.png)
