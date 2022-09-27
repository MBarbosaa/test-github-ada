
# PROTOCOLO #
El protocolo en informática es un conjunto formal de estándares y normas.
Estos rigen tanto el formato como el control de la interacción entre los distintos dispositivos
dentro de una red o sistema de comunicación. La meta es que puedan transmitir datos entre ellos.

# PROTOCOLO HTTP #
El HTTP o HyperText Transfer Protocol es un protocolo de transferencia sobre el que se basa la red informática mundial (WWW). Funciona como base para los intercambios de datos realizados en la web, y mantiene una estructura basadas en los clientes y servidores y orientada a transacciones.

La arquitectura del protocolo HTTP, implica que programas clientes como Firefox, Chrome, Opera y Robots, establezcan conexión y realicen peticiones de datos a programas servidores como Apache, Nginx, entre otros. Estas peticiones son gestionadas y contestadas por los servidores, a través de intermediarios denominados proxies.

El protocolo HTTP está apoyado sobre los servidores de conexión TCP/IP, donde el protocolo TCP es el encargado de mantener la comunicación y garantizar que el proceso de intercambio de datos se realice sin errores luego de que se haya establecido la conexión.

# METODOS HTTP #
Este protocolo implementa varios métodos de peticiones que cumplen con diferentes funciones, como por ejemplo

GET
Este método solicita una representación de un recurso determinado. Las peticiones que utilicen el método GET, solo deben ser usadas para la recuperación de información, por lo que no pueden incluir datos.

POST
Tiene la función de enviar datos para que sean procesados en un recurso especificado, lo que usualmente trae como consecuencia efectos secundarios en el servidor, como por ejemplos, cambios en su estado.

PUT
El método PUT se encarga de reemplazar las representaciones que tenga el recurso de destino con la carga útil de la petición realizada.

CONNECT
Tiene la función de establecer un túnel hacia el servidor que haya sido identificado con el recurso.

DELETE
El método DELETE en HTTP estará a cargo de eliminar un recurso especificado por el usuario.

OPTIONS
Este modo es usado con el fin de describir las opciones de comunicación que tiene el recurso de destino.

# CODIGOS DE RESPUESTA #
Para cada petición el servidor devuelve un código de respuesta con la información del recurso que haya sido solicitado. Así pues, puedes obtener códigos divididos por centenas como:

1xx: son respuestas informativas.
2xx: refiere a la respuesta correcta.
3xx: respuesta de redirección.
4xx: supone algún error causado por el cliente.
5xx: se refiere a un error ocasionado por el servidor.

Además, en cada transacción se envían ciertas cabeceras que permiten ampliar las funciones de este protocolo como por ejemplo User-Agent, Allow, Content-Type y otras cabeceras para el control de cookies.
