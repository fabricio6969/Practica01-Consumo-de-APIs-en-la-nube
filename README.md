# appdis
Este repositorio pertenece a la materia de aplicaciones distribuidas.

 	
PRÁCTICA DE LABORATORIO
CARRERA: ING. DE SISTEMAS	ASIGNATURA: APLICACIONES DISRTIBUIDAS
NRO. PRÁCTICA:	1	TÍTULO PRÁCTICA: Consumo de APIs web (plataformas en la nube)
OBJETIVOS
•	Conocer las arquitecturas y patrones arquitectónicos web para el diseño de aplicaciones web
•	Interactuar con servicios web de plataformas en la nube






INSTRUCCIONES	
Desarrollar una aplicación web usando una de las API gratuitas de API List Fun. Tener en cuenta que se deben aplicar buenas prácticas para el desarrollo de la interfaz gráfica de usuario, para la cuál se permite utilizar plantilla de Bootstrap.

Requisitos:
•	La aplicación Web debe permitir buscar la información a través de un nombre.
•	Además, se deberá visualizar toda la información disponible de la base de datos.

ACTIVIDADES POR DESARROLLAR
1.	Identificar gráficamente la arquitectura web de la aplicación a desarrollar.

Este modelo de arquitectura pertenece al modelo con servidor de aplicaciones, ya que la función que realiza un servidor de aplicaciones es diferente, ya que los recursos que va a manipular no son archivos estáticos, sino que contienen el código que tiene que ejecutar. Es decir, un servidor web en solitario eviaría al cliente el recurso solicitado tal cual, mientras que el servidor de aplicaciones lo ejecuta y envía al cliente el resultado a través del servidor web.

El servidor web y el servidor de aplicaciones pueden residir en una misma máquina como se refleja en el siguiente esquema. El servidor web recibe la petición de un recurso, y si éste corresponde a un recurso dinámico, transfiere la parte correspondiente al servidor de aplicaciones el cual devolverá de nuevo al servidor web el recurso ejecutado. Finalmente será el servidor web el que envíe al cliente el resultado final.
 
Fig.1. Diagrama modelo cliente con servidor de aplicaciones.








2.	Generar una llave para consumir los servicios web de la API (opcional, depende de la API seleccionada).



La siguiente API, nos entrega información sobre cocteles.
https://www.thecocktaildb.com/api/json/v1/1/search.php?f=a

La siguiente API, nos visualiza de forma aleatoria perros de diferentes razas.
https://www.thecocktaildb.com/api/json/v1/1/search.php?f=a


3.	Crear un repositorio en GitHub con el nombre “Practica01 – Consumo de APIs en la nube”

https://github.com/fabricio6969/Practica01-Consumo-de-APIs-en-la-nube.git



4. Desarrollar una aplicación con HTML + CSS + Javascript + Web Services para buscar información y visualizar
toda la información disponible a través de la API.

 

Fig.2. Conumo de la primera APP 

 
Fig.3. Consumo de la segunda API.


5. Realizar varios commits en la herramienta GitHub que demuestren el desarrollo de la aplicación.
6. Generar el informe de la práctica con el desarrollo de cada uno de los puntos descritos anteriormente.
7. Implementar el README del repositorio del proyecto con la misma información del informe de la práctica
8. Subir al AVAC el informe del proyecto en formato *.pdf. El informe debe contar con conclusiones apropiadas
y la firma de cada estudiante
RESULTADO(S) OBTENIDO(S):
•	Identifica las diferentes arquitecturas Web para el desarrollo de aplicaciones.

Una aplicación Web es  proporcionada  por  un  servidor  Web  y  utilizada  por  usuarios  que  se Conectan desde cualquier punto vía clientes Web (browsers o navegadores). La arquitectura de un Sitio Web tiene tres componentes principales:

  Un servidor Web
  Una conexión de red
  Uno o más clientes
El servidor Web distribuye páginas de información formateada a los clientes que las solicitan. Los requerimientos son hechos a través de una conexión de red, y para ello se usa el protocolo HTTP. Una vez que se solicita esta petición mediante el protocolo HTTP y la recibe el servidor Web, éste localiza la página Web en su sistema de archivos y la envía de vuelta al navegador que la solicitó.

CONCLUSIONES:
•	Los estudiantes podrán identificar arquitecturas web utilizando servicios en la nube. Así como también, podrán consumir APIs y manipular objetos JSON.

•	El presente trabajo se enfocó en el aprovechamiento de las nuevas tecnologías Web, en particular dentro del protocolo HTTP, con la intención de proporcionar herramientas para el consumo de APIS.

•	Identificamos muy bien el funcionamiento de las APIS y su buen funcionamiento para la integración de las diferentes aplicaciones en un solo sistema.
RECOMENDACIONES:

•	Conocimiento básico de programación.
•	Buenas prácticas de programación.
•	Investigación e interés por parte del desarrollador.
 

 

Estudiante: Fabricio Gómez Ávila.


Firma:	
 
Fabricio Gomez Avila
