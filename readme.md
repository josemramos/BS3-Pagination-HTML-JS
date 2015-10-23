# Bootstrap 3 pagination

HTML y JS para hacer funcionar el paginador de Bootstrap 3

Tu contenido a mostrar debe ir dentro del ul id="page-content", cada contenido debe ir dentro de una etiqueta con clase ".content", de eta manera, pagination.js podrá leer la cantidad de contenido que hay y distribuirla según la cantidad de contenido a mostrar por página.

Para cambiar la cantidad de contenido a mostrar por página, debes ir al archivo "/js/pagination.js", y en la linea 4, cambiar el valor de "pageSize" (por defecto está en 2).

El resto se hace de forma automática.

Código pagination.js cortesía de [Arthur Filipiak] (http://bit.ly/1XnkO14)
[Stackoverflow issue] (http://bit.ly/1kxEn8Q)