# Theme para Wordpress parecido al fabuloso deviantART #

      Este Theme lo desarrolle para un cliente que es fotógrafo y le propuse hacer un sitio parecido a Deviantart para que expusiera sus fotos de la mejor manera posible , le propuse esto al cliente porque quiera un reto ya que en mi parecer Deviantart es uno de los mejores sitios para fotografía es que el código fuente de Deviantart es tan sublime y consume muy pocos recursos del servidor y del Brower usa técnicas increíbles me encanta como está programado y quise hacer algo parecido es tanto así que llegue a medir los recursos que utilizaba mi theme al mostrar las fotos para comparar los resultados con Deviantart, cuando revisen el código fuente de mi theme los JavaScript se darán dé cuenta de mi esfuerzo para hacerlo lo más parecido al grande Deviantart, bueno sigamos, es un theme hecho para WordPress, tiene incluido la función de offset súper útil a la hora de agregar una página a favoritos del browser esto por la opción de navegación infinita que posee el theme, tiene una barra parecida al adobe Acrobat Reader PDF, que facilita cuando carga un bloque de imágenes con el scroll infinito se puede ir de bloque en bloque ósea página 1, página 2 etc., al igual que se puede hacer colocando directamente el número de la página si ya fue cargada va a la página solicitada y la muestra, la barra también muestra la cantidad de fotos cargadas en la página que está activa en el viewerport.
      
      Este theme tiene tres formas de ver los artículos y las fotos al igual que dos formas de paginación infinita y normal, posee slideshow.
      
      He utilizado la librería phpExifRW, para sacar los datos de la cámara usada para tomar las fotos por ejemplo: foco, lentes, y todas esas características lo hace solo una vez y es cuando se sube la foto al artículo o post y almacena la información sacada de la foto en la DB de WordPress para no hacer más uso de esta librería para poder presentar la información de las fotos parecido como lo hace deviantart, presenta la leyenda de la foto cuando se va al post o artículo.
      
      Le hice un sistema de emoticones al estilo de Taringa.net como los emoticones de washapp para la caja de comentarios de los post y con la particularidad de que carga  los emoticones al hacer clic en las diferentes categorías no los carga todos de una vez y usando la característica de html5 localStorage logre almacenar en memoria los emoticones más usados   y que aparece en una pestaña que lo indica los más usados al igual que lo hace washapp.      
      
      Las categorías son presentadas al estilo que lo hace deviantart si se selecciona una categoría padre muestra la categoría padre y el primer nivel de los hijos las demás categorías desaparecen y aparece un link nuevo que da la posibilidad de mostrar todas las categorías anteriores todo esto manipulando la información de la DB de WordPress objetos $wpdb (DB), $term y funciones get_category_by_slug, get_term.
      
      Una de las características más emblemáticas es la posibilidad de ir atrás y adelante en el browser sin que se pierda lo ya cargado en la navegación infinita teniendo así la posibilidad de seguir cargando nuevas páginas, en la navegación infinita al igual que lo hace Deviantart, tiene zoon las fotos , las páginas de los comentarios se cargan solo una vez, cuando se hace click en alguna página de los comentarios por ejemplo pag10 si ya la ha cargado simplemente muestra su contenido sin volver hacer petición al servidor o a la DB esto es muy importante para el ancho debanda al igual que la navegación infinita no la vuelve a cargar si se va a un link de contenido y se regresa.
      
      En este Theme use como bases del Theme BigFoo de THBThemes que es un theme free, para poder arrancar desde una plantilla acorde a este proyecto me refiero a los loop formats de los post (image – text – video - etc) y para poder ahórrame un poquito de trabajo ;)



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
