## DIU - Practica2, entregables

### Ideación 
* Malla receptora de información 
* Mapa de empatía
* Point of View 


### PROPUESTA DE VALOR
* ScopeCanvas


### TASK ANALYSIS

* User Task Matrix 
* User/Task flow


### ARQUITECTURA DE INFORMACIÓN

* Sitemap 
* Labelling 


### Prototipo Lo-FI Wireframe 


### Conclusiones  
(incluye valoración de esta etapa)

>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica

# Ideación

## Malla receptora de información

A partir de nuestra experiencia usando la página web de Sibuya y la de las personas que hemos creado, hemos creado esta [Malla receptora de información](feedbackCaptureGrid.png)

Podemos observar que la estructura de la página es muy profesional y que todo está muy bien explicado, pero podemos ver varias deficiencias, por ejemplo al buscar y en ciertas opciones que se encuentran "ocultas", de donde hemos obtenido varias ideas para crear una página mejor, tales como poner un buscador tolerante a fallos ortográficos comunes.

## Mapa de empatía

Hemos creado un [Mapa de empatía](EmpathyCustomerMapShibuya.png) poniéndonos en los zapatos de las personas que hemos creado.

Las personas escuchan que la comida japonesa es exquisita y navegando por Internet descubren la página de Sibuya. Miran sus redes sociales y deciden darle una oportunidad. Se dan cuenta de que es un restaurante moderno con comida de calidad pero no pueden reservar para ir con toda su familia o amigos y que en la carta normal no aparecen los precios de las cosas que quieren, tienen que crear un pedido para poder verlos.

## Point of View
El análisis de la página de Sibuya ha mostrado que tiene varias deficiencias que pueden resultar molestas al usuario, sobre todo si es alguien a quién le gusta que todo se vea de primeras en la página principal.

El primer punto que hemos detectado es que la opción para acceder a la carta no se muestra en la página principal, sino que se encuentra en el menú lateral desplegable. Siendo un apartado muy importante, sobre todo si es la primera vez que el usuario va a Sibuya, debería de estar a la vista para que el usuario sepa donde acceder de primeras y no se ponga a buscar por la página.

Siguiendo con la carta, no podemos ver los precios de los platos en ella. Si queremos consultarlos, debemos inicar un pedido, introducir los datos necesarios y ya se nos abrirá una carta alternativa donde podemos ver los precios de cada plato. Un usuario normal no sabe esto de primeras, por tanto puede que decida no reservar en el restaurante por el desconocimiento del precio de los platos.

Para terminar con la carta, tenemos un buscador bastante deficiente que no detecta errores ortográficos simples, como una letra equivocada, por tanto un usuario que sepa qué quiere buscar pero no sepa como escribirlo del todo bien no verá resultados.

Otro punto negativo que hemos considerado es el límite de personas al realizar una reserva. Normalmente, si realizamos una reserva, es porque vamos con un gran número de personas y queremos aasegurar que entremos todos, pero solo podemos reservar hasta 6 personas. Esto es problema si, por ejemplo, queremos ir a comer con la familia.

Para finalizar, los datos que introducimos en la página no se quedan guardados en caso de error, tenemos que introducirlos de nuevo.

Después de realizar estas observaciones nos enfocaremos en que nuestra página:
- Tenga un diseño simple pero llamativo
- Todas las posibles acciones del usuario estarán a la vista en todo momento
- La carta contendrá los precios de cada plato
- El buscador estará preparado para solucionar fallos ortográficos simples
- El número máximo de personas para reservar será de 20
- En caso de error mantendremos la información

# Propuesta de valor

Nuestra propuesta consiste en crear una página web para Inazuma Ramen de forma que sea lo más sencilla de utilizar para el usuario. Nos centraremos en que toda la infomarción importante se muestre en todo momento y que las instrucciones para reservar y para realizar pedidos sean lo más claras posibles. Nos basaremos sobre todo en el número de reservas y de pedidos para comprobar si vamos por buen camino. Además tendremos en cuenta los puntos mencionados en el punto anterior. Con todo esto, hemos modelado nuestra [Propuesta de valor](ScopeCanvas.png)

# Task analysis

## User Task Matrix

En nuestra página web podemos realizar las siguientes acciones:

Acción | Administrador | Cliente
|-------|------------|---------
Consultar la carta | Bajo | Alto
Realizar un pedido | Bajo | Medio
Realizar una reserva | Bajo | Alto
Contactar con el restaurante | Bajo | Medio

## User Task Flow

Hemos modelado un par de acciones que pueden realizar los clientes, siguiendo paso a paso cómo empiezan desde la página principal hasta que terminan la acción.

El [Primer Task Flow](FlowmapReserva.png) sigue los pasos de un cliente que quiere realizar una reserva desde nuestra página web. Una vez dentro de la página el usuario seleccionará la fecha, hora y número de personas de la reserva. Si es posible realizar la reserva se mostrará un mensaje de éxito, en caso contrario se mostrará un mensaje de error con el motivo para que el usuario rectifique.

En el [Segundo Task Flow](FlowmapPedido.png), el usuario quiere realizar un pedido, para ello entra en la sección de pedidos donde introducirá sus datos y comprobaremos si son válidos. Tras esto recorrerá la carta añadiendo los platos que quiere pedir y, una vez finalizado, en la página depagos seleccionará el método que prefiera. Si selecciona el pago con tarjeta se comprobará que los datos introducidos son correctos.

# Arquitectura de información

## Sitemap

Con todo lo explicado en los puntos anteriores hemos creado nuestro [Sitemap](SiteMap.png).

## Labelling

Término | Significado
| ------------- | -------
Pagina Principal | Página de inicio de Inazuma Ramen con acceso a las distintas secciones
Carta | Página para consular la carta
Pedido | Sección para realizar un pedido
Carta-Pedido| Página para consular la carta cuando el cliente vaya a realizar un pedido. 
Delanteros | Sección de la carta donde se encuentran los entrantes
Mediocentros | Sección de la carta donde se encuentran los platos principales
Defensas | Sección de la carta donde se encuentran los postres
Porteros | Sección de la carta donde se encuentran las bebidas
Pagos | Página para llevar a cabo el pago del pedido
Reserva | Página para realizar una reserva
Contacto | Sección donde se encuentra el correo y numero de teléfono de la empresa

## Prototipo Lo-FI Wireframe 
Hemos diseñado las siguientes pantallas de la interfaz: Pagina Principal, Carta, Reservas, Pago, Contacto y Pedido. Lo hemos hecho tanto con posiciones fijas absolutas y elementos en jerarquía de frames [Wireframe fijos](Wireframefijo.fig) como con un GRID LAYOUT con ajustes de diseño RESPONSIVE [Wireframe dinámico](Wireframedinámico.fig). Referente al diseño Responsive, hemos realizado las versiones en ordenador, tablet y móvil. Teniendo en cuenta la forma de utilización de la tablet tanto en vertical como horizontal y la aparición del teclado en tablet y móvil a la hora de rellenar los campos pertinentes.

#Wireframe dinámico
Pagina Principal



