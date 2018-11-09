# lenguajesIAW-CGI
Script para saber el lenguaje que mas te guste.

Nuestro script tiene la siguiente funcionalidad:

    Gracias al curso de ASIR, hemos aprendido varios sistemas operativos e incluso ejecutado alguno de ellos.
    En el, tendremos que elegir el lenguaje que más nos guste, lo hayamos dado o no.

Lo que vamos a necesitar para nuestra ejecución:

    Servidor Apache2
    Activar CGI-BIN en apache (#a2enmod cgi)
    Transferir nuestro .cgi a la ruta /usr/lib/cgi-bin/

Para su ejecución debemos hacerlo de la siguiente manera:
    
    -localhost/cgi-bin/lenguaje.cgi
        Ejecutariamos nuestro cgi el cual nos pedira primeramente que escribamos un lenguaje, el que más nos guste, una vez lo escribimos, vamos a pasar a poner una nota a ese lenguaje.
   
    -Una vez enviamos ese formulario, pasaremos al segundo el cual tendra como primera lìnea...
        El lenguaje elegido es: (lenguaje) y le das una nota de: (nota)
    -Lo siguiente que nos saldra sera una breve pregunta en la cual pide que expliques porque te gusta más el lenguaje que has escogido anteriormente.
