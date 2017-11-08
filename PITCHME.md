@title[HTTP]

# ¿Qué<span class="gold">es?</span>

#### Es un protocolo que nos permite realizar una 
#### peticion de datos y recursos (Documentos HTML).*
<br>

---

@title[Caracteristicas]

#### 1.-Http es <span class="gold"> sencillo </span>.
#### 2.-Http es <span class="gold">extensible</span>.
#### 3.-Http es <span class="gold"> un protocolo en sesiones, pero sin estados</span>.
#### 4.-Http y <span class="gold"> conexiones</span>.
<br>

---

@title[Tipica Sesion]

#### En los protocolos basados en el modelo cliente-servidor, como es el caso del HTTP, una sesión consta de tres fases:

#### 1.-El cliente establece una conexión TCP (o la conexión correspondiente si la capa de transporte corresponde a otro protocolo).
#### 2.-El cliente manda su petición, y espera por la respuesta. 
#### 3.-El servidor procesa la petición, y responde con un código de estado y los datos correspondientes.

####A partir del protocolo HTTP/1.1 la conexión, no se cierra al finalizar la tercera fase, y el cliente puede continuar realizando peticiones. Esto significa que la segunda y tercera fase, pueden repetirse cualquier número de veces.
<br>

---

@title[Cabeceras Comunes]

####.-Server: indica el tipo de servidor HTTP empleado.
####.-Age: indica el tiempo que ha estado el objeto servidor almacenado en un proxy cache (en segundos)
####.-Cache-control: lo usa el servidor para decirle al navegador que objetos cachear, durante cuanto tiempo, etc..
####.-Content-Encoding: se indica el tipo de codificación empleado en la respuesta
####.-Expires: indica una fecha y hora a partir del cual la respuesta HTTP se considera obsoleta. Usado para gestionar caché.
####.-Location: usado para especificar una nueva ubicación en casos de redirecciones.
####.-P3P: se usa para especificar el tipo de política de privacidad empleado en la web. No está muy extendido.
####.-Set-Cookie: sirve para crear cookies. Las famosos cookies viajan entre el servidor y el navegador a través de estas cabeceras HTTP.

<br>

---

@title[Peticiones]

####.-GET
####El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.
####.-HEAD
####El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.
####.-POST
####El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.
####.-PUT
####El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.
####.-DELETE
####El método DELETE borra un recurso en específico.
####.-CONNECT
####El método CONNECT establece un tunel hacia el servidor identificado por el recurso.
####.-OPTIONS
####El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.
####.-TRACE
#### El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.

<br>

---

@title[Respuestas]

####HTTP/1.1 400 Bad Request
####Date: Sun, 18 Oct 2012 10:36:20 GMT
####Server: Apache/2.2.14 (Win32)
####Content-Length: 230
####Content-Type: text/html; charset=iso-8859-1
####Connection: Closed
<br>

---

@title[Cookie]

####El encabezado Cookie de una solicitud HTTP contiene cookies HTTP almacenadas y enviadas previamente por el servidor con el encabezado 
#Cookie: PHPSESSID=298zf09hf012fh2; csrftoken=u32t4o3tb3gg43; _gat=1;
<br>

---

@title[Evolucion]

####HTTP es el protocolo en el que se basa la Web. Fue inventado por Tim Berners-Lee entre los años 1989-1991
####Invención de la World Wide Web
####El protocolo de una sola línea
####Desarrollando expansibilidad
####El protocolo estándar.
####El uso de HTTP para transmisiones seguras
####Uso de HTTP para aplicaciones complejas
####HTTP/2 – Un protocolo para un mayor rendimiento
####Post-evolución del HTTP/2
<br>

---

@title[Evolucion HTPP 2.0]

####.-Una única conexión.
####.-Eliminación de información redundante.
####.-Multiplexación.
####.-HTTP 2.0 es un protocolo binario.
####.-Servicio 'server push'
####.-Compresión de cabeceras para transmitir menos información.
####.-Priorización de flujos.
####.-No requiere cifrado TLS.

<br>

---

