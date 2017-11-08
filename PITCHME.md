@title[HTTP]

# <h1>¿Qué es?</h1>

#### Es un protocolo que nos permite realizar una 
#### peticion de datos y recursos 
#### (Documentos HTML).*
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

#### <h1>En los protocolos basados en el modelo cliente-servidor, como es el caso del HTTP, una sesión consta de tres fases: </h1>

#### 1.-El cliente establece una conexión TCP (o la conexión correspondiente si la capa de transporte corresponde a otro protocolo).
#### 2.-El cliente manda su petición, y espera por la respuesta. 
#### 3.-El servidor procesa la petición, y responde con un código de estado y los datos correspondientes.
<br>

---

@title[Cabeceras Comunes]

####<li>Server: indica el tipo de servidor HTTP empleado.</li>
####<li>Age: indica el tiempo que ha estado el objeto servidor almacenado en un proxy cache (en segundos)</li>
####<li>Cache-control: lo usa el servidor para decirle al navegador que objetos cachear, durante cuanto tiempo, etc..</li>
####<li>Content-Encoding: se indica el tipo de codificación empleado en la respuesta</li>
####<li>Expires: indica una fecha y hora a partir del cual la respuesta HTTP se considera obsoleta. Usado para gestionar caché.</li>
####<li>Location: usado para especificar una nueva ubicación en casos de redirecciones.
####<li>P3P: se usa para especificar el tipo de política de privacidad empleado en la web. No está muy extendido.</li>
####<li>Set-Cookie: sirve para crear cookies. Las famosos cookies viajan entre el servidor y el navegador a través de estas cabeceras HTTP.</li>

<br>

---

@title[Peticiones]

####<li>GET
####El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.</li>
####<li>HEAD
####El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.</li>
####<li>POST
####El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.</li>
####<li>PUT
####El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.</li>
####<li>DELETE
####El método DELETE borra un recurso en específico.</li>
####<li>CONNECT
####El método CONNECT establece un tunel hacia el servidor identificado por el recurso.</li>
####<li>OPTIONS
####El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.</li>
####<li>TRACE
#### El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.</li>

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
#<span>Cookie: PHPSESSID=298zf09hf012fh2; csrftoken=u32t4o3tb3gg43; _gat=1;</span>
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

####<li>Una única conexión.</li>
####<li>Eliminación de información redundante.</li>
####<li>Multiplexación.</li>
####<li>HTTP 2.0 es un protocolo binario.</li>
####<li>Servicio 'server push'</li>
####<li>Compresión de cabeceras para transmitir menos información.</li>
####<li>Priorización de flujos.</li>
####<li>No requiere cifrado TLS.</li>

<br>

---

