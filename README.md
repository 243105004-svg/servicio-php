## Explicación del funcionamiento

El sistema está compuesto por una página web alojada en GitHub Pages y un servicio web desarrollado en PHP, alojado en Render.

El usuario accede a la página web desde su navegador y presiona un botón para solicitar el nombre del estudiante.

Mediante JavaScript, la página realiza una petición HTTP utilizando la función fetch hacia el servicio PHP.

El servicio PHP procesa la solicitud y devuelve el nombre del estudiante en formato JSON.

Finalmente, el navegador recibe la respuesta y muestra el nombre del estudiante en un cuadro de diálogo.
