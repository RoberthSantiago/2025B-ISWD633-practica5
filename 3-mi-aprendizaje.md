# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Lo que aprendi en esta practica 

En esta práctica aprendí cómo Docker Compose facilita enormemente el manejo de aplicaciones con múltiples contenedores. Antes pensaba que levantar varios servicios (como una base de datos y un servidor web) era un proceso complicado y manual, pero al trabajar con el archivo compose.yaml, entendí que se puede definir toda la estructura de la aplicación en un solo archivo y ejecutarla con un simple comando.

También aprendí la importancia de usar correctamente la indentación en YAML, ya que un error mínimo en los espacios puede causar fallos en la configuración. Otro punto clave fue comprender cómo funcionan las dependencias entre servicios mediante depends_on, especialmente con la condición service_healthy, que permite que un servicio (como WordPress) se inicie solo cuando otro (como MySQL) esté completamente listo.

Además, me pareció muy útil la parte de los Healthchecks, ya que permiten que Docker Compose supervise la salud de los servicios y garantice que todo esté funcionando correctamente. Finalmente, comprendí por qué definir una buena política de reinicio es esencial para asegurar la disponibilidad continua de los contenedores, especialmente en entornos donde el servicio debe mantenerse activo todo el tiempo.

En resumen, esta práctica me ayudó a ver cómo Docker Compose automatiza, organiza y da robustez al despliegue de aplicaciones complejas, algo fundamental para el trabajo en entornos reales.
