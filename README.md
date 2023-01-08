![ProContactoLogo](https://user-images.githubusercontent.com/121767595/211174228-9907b7f7-8057-447d-ab3d-690eecbdb2ff.png)

# Evaluación Práctica :computer:

#### Edgar Juan Pablo Pichardo Barragan

## Lista de ejercicios:

- [x] :small_blue_diamond: [**Ejercicio 1**](#ejercicio-1) 
- [x] :small_blue_diamond: [**Ejercicio 2**](#ejercicio-2) 
- [x] :small_blue_diamond: [**Ejercicio 3**](#ejercicio-3) 
- [x] :small_blue_diamond: [**Ejercicio 4**](#ejercicio-4) 
- [x] :small_blue_diamond: [**Ejercicio 5**](#ejercicio-5) 
- [x] :small_blue_diamond: [**Ejercicio 6**](#ejercicio-6) 
- [x] :small_blue_diamond: [**Ejercicio 7**](#ejercicio-7) 


## Ejercicio 1

1. Instalar el IDE Visual Studio Code

<img width="90" alt="visual" src="https://user-images.githubusercontent.com/121767595/211175815-c116b12c-7730-46fc-8c60-9f6376270afe.png">

2. Instalar GIT y GIT Bash

<img width="90" alt="visual" src="https://user-images.githubusercontent.com/121767595/211175847-cdf75ef8-5485-44bc-902d-c38e64684fbf.png">


## Ejercicio 2

1. **¿Qué es un servidor HTTP?**</br>
Es el protocolo de transmisión de información, es cual se establece para que un computador solicitante y otro que contiene la información puedan comunicarse de         manera correcta a la hora de transmitir información por la red.

2. **¿Qué son los verbos HTTP? Mencionar los más conocidos** </br>
Son peticiones que usamos para indicar que queremos realizar sobre el servidor, y las mas conocidas son get, post, patch, put y delete.

3. **¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?** </br>
Un request es la petición que el cliente hace y esta llegara al servidor. </br>
Un response es la solución que da el servidor después de hacer lo que necesita para brindarle una respuesta.</br>
Los headers son la parte central de los request y response y contienen información de autentificación de seguridad, el agente que se esta utilizando y metadatos de control del cache.

4. **¿Qué es un queryString? (En el contexto de una url)** </br>
Es la parte de una URL que contiene los datos que deben pasar a aplicaciones web como los programas CGI.

5. **¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?** </br>
Indican si se ha completado satisfactoriamente una solicitud HTTP específica. Como la respuesta satisfactoria 200 que es uno de los HTTP responseCode. Son el tipo de comunicación web que se utiliza para indicar situaciones o problemas de los sitios y páginas que se dan por parte del cliente o del servidor.

6. **¿Cómo se envía la data en un Get y cómo en un POST?** </br>
El método get envía la información codificada del usuario en el header del HTTP request, directamente en la url. </br>
Un ejemplo es:</br>
www.ejercicio2.com/index.htm?key1=value1&key2=value2&key3=value3 </br>
En el método HTTP post también se codifica la información, pero ésta se envía a través del body del HTTP request, entonces no aparece en la URL.

7. **¿Qué verbo http utiliza el navegador cuando accedemos a una página?** </br>
Utiliza el verbo get.

8. **Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.** </br>
En XML la estructura de datos estándar esta basada en texto para representar información estructurada como: datos, listas, configuración, documentos, etc. </br>
Aquí un ejemplo muy simple de una estructura en XML: </br>

```XML
<nota>
<para>Procontacto</para>
<de>Edgar</de>
<titulo>Ejercicio2</titulo>
<contenido>Estructura de datos</contenido>
</nota>
```
En JSON el formato de intercambio de información es mas legible y por lo tanto mas entendible por el ser humano y de igual manera es igual de eficiente que XML. </br>
Aquí el mismo ejemplo de XML pero en JSON: </br>

```JSON
{
    "nota": {
        "para": "Procontacto",
        "de": "Edgar",
        "titulo": "Ejercicio2",
        "contenido": "Estructura de datos"
    }
}
```
9. **Explicar brevemente el estándar SOAP** </br>
El estándar SOAP está basado en XML y sirve  para la transmisión de mensajes en HTTP y otros protocolos de Internet.

10.	**Explicar brevemente el estándar REST Full**</br>
Es una técnica de la arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear APIs.

11.	**¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**</br>
Los headers transmiten información acerca del navegador del cliente a la página solicitada. </br>
El key Content-type indica el media type del recurso y dice al cliente que tipo de contenido será retornado. </br>


## Ejercicio 3

**Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:** </br>

1. **Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json** </br>

![image](https://user-images.githubusercontent.com/121767595/211177893-d555368a-ad31-431f-bd74-8f76d58caa95.png)

2. **Realizar un request POST a la URL anterior, y con body:** </br>

```
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
```
Tip: (Marcar la opción “raw” como body)

![image](https://user-images.githubusercontent.com/121767595/211177951-24eea36d-889f-43b9-86bb-306977e7dea6.png)

3. **Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json**

![image](https://user-images.githubusercontent.com/121767595/211177964-87a81d5d-d33a-47a0-9c58-bb85cfec13a7.png)

4. **¿Qué diferencias se observan entre las llamadas el punto 1 y 3?** </br></br>
En el primer GET nos arrojó los datos que se encuentran en la URL, en cambio en el segundo GET podemos observar los datos de la URL más los datos que se dieron de alta en el POST del punto 2. 


## Ejercicio 4

**Realizar los siguientes módulos de Trailhead:** </br>

https://trailhead.salesforce.com/users/norozco3/trailmixes/introduccion </br> 

![Ejercicio4](https://user-images.githubusercontent.com/121767595/211182868-4bf68bfe-3246-4978-b4de-9f811aef1521.PNG)


:mag_right: [**Perfil de Trailhead**](https://trailblazer.me/id/edgarp) :mag:


## Ejercicio 5

**Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto </br>
(algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:** </br>

| N° | Objeto   | Explicación  |
| ------------ | ------------ |------------ |
| 1 | Lead          | Representa un cliente potencial que demostró interés en un producto o servicio ofrecido por la marca por medio de la interacción con contenidos y otros materiales. Este objeto tiene como característica guardar los datos de las personas que deseas como clientes.|
| 2 | Account       | Representa una cuenta individual, que es una organización o persona involucrada con su negocio. Este objeto guarda datos como clientes, competidores y socios.|
| 3 | Contact       | Representa un contacto, que es una persona asociada a una cuenta. Este objeto guarda como bien lo dice datos del contacto.|
| 4 | Opportunity   | Representa una oportunidad, que es una venta o trato pendiente. Este objeto guarda datos para la administración sobre una venta o trato pendiente también se puede sincronizar este objeto con una cotización.|
| 5 | Product       | Representa un servicio o artículo que la empresa vende a los clientes. Este objeto guardar los datos de varios campos que se usan solo para programaciones de cantidad e ingresos.|
| 6  | PriceBook    | Representa la lista de productos y sus precios por unidad. Este objeto guarda los datos de precios que contiene la lista de productos que vende la organización.|
| 7 | Quote         | Representa un artículo de valor comercial, como un producto vendido por su empresa o un competidor, que ha comprado un cliente. Este objeto guarda los datos para realizar un seguimiento de los productos vendidos a los clientes.|
| 8  | Asset       | Representa un artículo de valor comercial, como un producto vendido por su empresa o un competidor, que ha comprado un cliente. Este objeto guarda los datos para realizar un seguimiento de los productos vendidos a los clientes.|
| 9  | Case         | Representa un caso, que es un asunto o problema del cliente. Este objeto guarda asuntos o problemas del cliente.|
| 10  | Article     | Este objeto se puede utilizar para asociar un artículo con categorías de datos o para consultar las selecciones de categoría de un artículo.|

**Diagrama**

![Ejercicio5 drawio](https://user-images.githubusercontent.com/121767595/211181297-fb719152-3717-4cf5-9b96-310e079dd38c.png)


## Ejercicio 6

**Responder las siguientes preguntas brevemente sobre:** </br>

:ballot_box_with_check: **Soluciones de Salesforce** </br>

1.	**¿Qué es Salesforce?**</br>
Es una plataforma para le gestión de relaciones con clientes.

2.	**¿Qué es Sales Cloud?**</br>
Es una plataforma para dar seguimiento a los procesos de ventas de inicio a fin.

3.	**¿Qué es Service Cloud?**</br>
Es una solución completa de atención al cliente creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar.

4.	**¿Qué es Health Cloud?**</br>
Es una plataforma diseñada para la gestión clínica de pacientes por medio de tecnologías on-cloud

5.	**¿Qué es Marketing Cloud?**</br>
Es un proveedor de software y servicios de análisis y automatización de marketing digital.

:ballot_box_with_check: **Funcionalidades de Salesforce** </br>

1.  **¿Qué es un RecordType?**</br>
Es aquel que se define por defecto en un perfil de Salesforce.

2.  **¿Qué es un ReportType?**</br>
Define el conjunto de registros y campos disponibles para un informe en función de las relaciones entre un objeto principal y sus objetos relacionados.

3.  **¿Qué es un Page Layout?**</br>
Los diseños de página controlan el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos.

4.  **¿Qué es un Compact Layout?**</br>
Este muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

5.  **¿Qué es un Perfil?**</br>
Definen como acceden los usuarios a objetos y datos y que pueden hacer en la aplicación.

6.  **¿Qué es un Rol?**</br>
Controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización.

7.  **¿Qué es un Validation Rule?**</br>
verifican que los datos ingresados por usuarios en registros cumplen los estándares que especifica antes de poder guardarlos

8.  **¿Qué diferencia hay entre una relación Master Detail y Lookup?**</br>
Hay diferencias fundamentales en el comportamiento y el uso compartido de registros, el valor del campo de relación master detail es obligatorio, mientras en el lookup no, en el master detail si el registro principal se elimina automáticamente los registros secundarios se eliminan y en el lookup no, así que la diferencia clave es que el master detail tiene una dependencia directa entre los objetos mientras la otra no.

9.  **¿Qué es un Sandbox?**</br>
Es una copia de la organización en un entorno aislado que podemos usar para distintos fines, como pruebas y capacitación.

10.  **¿Qué es un ChangeSet?**</br>
Es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión.

11.  **¿Para qué sirve el import Wizard de Salesforce?**</br>
Sirve para importar datos en Salesforce.

12.  **¿Para qué sirve la funcionalidad Web to Lead?**</br>
Sirve para diseñar un formulario para cada tipo de negocio con el objetivo de insertarlo en un blog o una web corporativa.

13.  **¿Para qué sirve la funcionalidad Web to Case?**</br>
Sirve para ayudar a las organizaciones a responder a los clientes más rápido.

14.  **¿Para qué sirve la funcionalidad Omnichannel?**</br>
Es una solución integral de servicio al cliente, esta herramienta enruta en tiempo real, el trabajo correcto a los agentes adecuados, proporcionando un perfil completo de las interacciones de un cliente.

15.  **¿Para qué sirve la funcionalidad Chatter?**</br>
Sirve para ver noticias en tiempo real, perfiles, grupos y para compartir información y colaborar.

:ballot_box_with_check: **Conceptos generales* </br>

1.	**¿Qué significa SaaS?**</br>
Software as a Service, es una forma de poner a disposición softwares y soluciones de tecnología por medio de internet, como un servicio.

2.	**¿Salesforce es Saas?**</br>
Si ya que pone a disposición softwares y soluciones de tecnología por medio de internet como un servicio.

3.	**¿Qué significa que una solución sea Cloud?**</br>
Quiere decir que permite el acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de internet.

4.	**¿Qué significa que una solución sea On-Premise?**</br>
Quiere decir que la organización mantiene sus propios servidores y hardware, y compra la licencia del software o lo desarrolla internamente.

5.	**¿Qué es un pipeline de ventas?**</br>
Este se refiere a cada uno de los pasos de un proceso de ventas que sigue un representante de ventas para llevar una venta desde el principio hasta el final.

6.	**¿Qué es un funnel de ventas?**</br>
Es el esquema que representa las etapas del proceso de decisión de compra de un usuario hasta convertirse en cliente.

7.	**¿Qué significa Customer Experience?**</br>
Es cómo se relaciona una empresa con sus clientes en todos los aspectos del recorrido de compra.

8.	**¿Qué significa omnicanalidad?**</br>
Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc).

9.	**¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?**</br>
A. Significa que tienen un modelo de negocio en el que se realizan transacciones comerciales entre empresas.</br>
B. Significa que tienen un modelo de negocio en el cual las empresas ofrecen productos y servicios al público general, con el objetivo de obtener un porcentaje de rentabilidad durante la transacción.</br>
C. Es una medida del nivel del rendimiento de un proceso.

10.	**¿Qué es una API y en qué se diferencia de una Rest API?**</br>
Una API es el conjunto de protocolos y definiciones que se usan para integrar y desarrollar el software de las apps y se diferencian principalmente en la estructura, el formato de intercambio de mensajes y en la flexibilidad.

11.	**¿Qué es un Proceso Batch?**</br>
Es el proceso mediante el cual una computadora completa lotes de trabajos, a menudo simultáneamente, en orden secuencial y sin parar.

12.	**¿Qué es Kanban?**</br>
Es un método Lean, muy popular de gestión del flujo de trabajo para definir, gestionar y mejorar los servicios que proporciona el trabajo de conocimiento.

13.	**¿Qué es un ERP?**</br>
Es un tipo de software que las organizaciones utilizan para gestionar las actividades empresariales diarias.

14.	**¿Salesforce es un ERP?**</br>
No, pero Salesforce Billing puede complementar las plataformas de planificación de recursos de negocio o ERP.


## Ejercicio 7

**Importar el archivo CSV proporcionado por laura.lejarza@procontacto.com.mx, utilizando Dataloader y agregar los siguientes screenshots a GitHub.**

**_Paso a paso del proceso para mostrar cómo fue realizado_**

**importación de cuentas**

1. Se analizo el archivo para ver que campos faltaban en el objeto account para después agregarlos.
2. Se limpio el documento y se guardó como archivo csv para la importación.
3. Se inicio sesión en Dataloader.

![image](https://user-images.githubusercontent.com/121767595/211183590-84487490-8320-4888-bbf3-34b61573c39f.png)

4. Seleccionamos el objeto al cual realizaremos la importación de datos que en este caso será Account y así mismo el archivo de importación.

![image](https://user-images.githubusercontent.com/121767595/211183611-ba6177cb-262d-4c07-96f6-32e4556cb9e4.png)

5. Vemos que se leyeron los datos correctamente.

![image](https://user-images.githubusercontent.com/121767595/211183649-3f3a1aba-0866-4168-86a6-2462ca315108.png)

6. Procedemos a hacer el mapeo, seleccionamos create or edit map, despues auto match y esto nos relacionara las columnas del archivo csv con los objetos que creamos en Salesforce. (Industria no lo cree, por que ya estaba el objeto Industry y solo lo relacione manualmente)

![image](https://user-images.githubusercontent.com/121767595/211183723-8c203589-09d9-4c28-b955-0cc8935ae4eb.png)

7. Nos arroja que la importación fue exitosa, así como también los documentos de error y success que muestra la importación exitosa.

![image](https://user-images.githubusercontent.com/121767595/211183849-a897a4dc-9f72-46f6-be7a-c160b183defc.png)

8.Aquí se muestra la lista de cuentas con las columnas que se solicitaron, falto un campo, pero solo permite 15 campos, también para que solo se mostraran las cuentas que se importaron se agregó un filtro donde el campo que filtramos fue cualquier campo personalizado que se agregó, de esta manera nos arrojó solo las cuentas recién importadas.

![image](https://user-images.githubusercontent.com/121767595/211184127-a1f1d8a4-9386-42e9-9e51-a2bc0cecb039.png)

**importación de oportunidades**

1. Como en el anterior proceso analizamos, limpiamos el archivo y se guardó como csv.
2. Para la importación primero necesitamos los id de las cuentas que importamos, así que exportamos las cuentas.

![image](https://user-images.githubusercontent.com/121767595/211184367-9d8f2fd7-9c96-43c3-9c7e-b50c9122932e.png)

3. Una vez teniendo el archivo, me doy cuenta que no todas las cuentas de oportunidades están registradas, así que procedo a encontrar las cuentas que si están registradas haciendo la comparación de datos y separando los datos para la importacion.

![image](https://user-images.githubusercontent.com/121767595/211184527-bb283d07-c413-4ac9-84c8-22641bf0d969.png)

4. Ya con esto procedemos a importar, seleccionamos opportunities y seleccionamos el documento csv.

![image](https://user-images.githubusercontent.com/121767595/211184757-952ce38b-84bb-4958-83f6-4c3d386f38ad.png)


6. Ahora procedemos a hacer el mapeo de las columnas y objetos.

![image](https://user-images.githubusercontent.com/121767595/211184699-2736b17d-d46e-4034-a609-bbf6ff527e3a.png)

5. De nuevo aparece que la importación fue exitosa y se generan los archivos correspondientes.
6. Y ya por ultimo podemos observar las oportunidades de las cuentas que fueron importadas en nuestro Playground.

![image](https://user-images.githubusercontent.com/121767595/211184834-e24a1ec2-5df6-416a-abf3-d0df84930f7c.png)

