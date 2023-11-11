## 2 Catálogo General de Activos

Identificar y clasificar los activos es imprescindible para documentar el estado de la empresa, y también para entender las posibles amenazas y las medidas de seguridad adecuadas. A continuación explico como funciona e incluyo algunos de los posibles activos y puede cambiar con el tiempo dependendiendo del desarrollo de la empresa con el tiempo. 

La implementación de la metodología MAGERIT consiste en la creación de un catálogo de activos. Este proceso, esencial antes de tomar decisiones sobre seguridad, implica la identificación precisa de los activos de la empresa. Según la norma UNE 71504:2008 [6] (pdf de referencia), un activo se define como cualquier componente o funcionalidad en un sistema de información vulnerable a ataques deliberados o accidentales con consecuencias para la organización. Estos abarcan información, datos, servicios, aplicaciones (software), equipos (hardware), comunicaciones, recursos administrativos, recursos físicos y recursos humanos.

Dentro de un sistema de información, identificamos dos categorías principales de activos: la información y los servicios que proporciona. Subordinados a estos, encontramos otros elementos clave, desde datos y servicios auxiliares hasta aplicaciones informáticas, equipos informáticos, soportes de información, equipamiento auxiliar, redes de comunicaciones, instalaciones y el personal operativo.

Cada activo tiene un valor, que no se refiere simplemente al costo, sino a la importancia que tiene para la empresa. Esta valoración se realiza considerando dimensiones críticas de seguridad, tales como la confidencialidad, integridad y disponibilidad del activo.

En el ámbito de los servicios digitales, se añaden dos dimensiones adicionales relacionadas con el conocimiento de los actores involucrados: la autenticidad de los usuarios y la trazabilidad del uso del servicio (más en su respectiva parte mas adelante).

Para evaluar los activos, se usan escalas de valores que permitan una comparación efectiva de riesgos. Es crucial emplear una escala común para todas las dimensiones, preferiblemente logarítmica y centrada en diferencias relativas de valor. MAGERIT ofrece dos escalas, una más sencilla y otra más detallada. La elección de una escala sencilla de diez valores, adaptada a la envergadura del despacho y sus activos, facilita la identificación de elementos despreciables y aquellos irremplazables.

Este proceso de catalogar activos y asignarles valor no solo establece una base sólida para la seguridad, sino que también proporciona un marco homogéneo para analizar riesgos de manera efectiva y tomar decisiones informadas.

Los puntos de la siguiente tabla, organizan los activos en una jerarquía, asignándoles un código que muestra su posición en la jerarquía, un nombre y una breve descripción de lo que representa cada tipo de activo. Los activos No tienen que ser estrictamente como tal, y perfectamente pueden pertenecer a diferentes categorias.

## Valoración de Activos

La valoración es una forma de asignar un puntaje o evaluación a cada activo en diferentes dimensiones de seguridad. Generalmente se utiliza para indicar cuánto valor tiene cada activo para la organización en términos de:

- D (Disponibilidad): ¿Qué tan importante es que este activo esté siempre disponible?
- I (Integridad): ¿Qué tan crítico es mantener la integridad o exactitud de este activo?
- C (Confidencialidad): ¿Qué tan sensible o confidencial es la información contenida en este activo?
- A (Autenticidad): ¿Cuán importante es asegurar que este activo sea auténtico y provenga de una fuente confiable?
- T (Trazabilidad): ¿Cuánta importancia se le da al seguimiento y registro de las acciones relacionadas con este activo?
- "-" (No valorable): Aquellos activos los cuales no puedo valorarlos por lo que son, o lo que representan.

La valoración se realiza utilizando una escala, que puede ser numérica (por ejemplo, del 1 al 10) o cualitativa (baja, media, alta). En los siguientes activos, utilizaré una escala cualitativa para representar la valoración en cada activo. Lo idóneo y perfecto es poner todos los valores como "Alta" para tener un entorno laboral definitivo en término de seguridad, pero para hacerlo más real, le he dado menos valor como "Media" a algunos activos que podrían llevar Alta perfectamente, y lo mismo para Baja, porque si no como he dicho seria practicamente todo en Alta.

## 2.1 Inventario de activos (sin terminar)

| Número | Tipo de Activo                            | Descripción                                      |
|--------|------------------------------------------|--------------------------------------------------|
| 1      | [I] Activos Esenciales                   | Activos críticos para la operación del bufete    |
| 2      | [D] Datos / Información                   | Casos legales en curso                           |
| 3      | [K] Claves Criptográficas                 | Claves de acceso a información sensible          |
| 4      | [S] Servicios                             | Servicios de investigación legal                 |
| 5      | [SW] Software - Aplicaciones informáticas | Sistema de gestión de casos                       |
| 6      | [HW] Equipamiento informático (hardware)  | Computadoras y servidores                        |
| 7      | [COM] Redes de comunicaciones             | Red interna del bufete                           |
| 8      | [Media] Soportes de información           | Copias de seguridad en la nube                   |
| 9      | [AUX] Equipamiento auxiliar               | Sistemas de seguridad física                     |
| 10     | [L] Instalaciones                         | Oficinas y salas de reuniones                    |
| 11     | [P] Personal                              | Abogados y personal legal                        |


### 2.2 Fichas detalle archivo

Las fichas son documentos o formularios que contienen información detallada sobre un elemento específico. En la metodología MAGERIT para la gestión de riesgos en sistemas de información, las fichas de detalle de activos son registros detallados para cada tipo de activo identificado en el catálogo. Cada ficha proporciona información específica sobre el activo, como su código de identificación, nombre, descripción, y cualquier otra información relevante que facilite su gestión y evaluación de riesgos.

Estas fichas (mas bien herramientas prácticas) ayudan a documentar y organizar la información sobre los activos del bufete en este caso. Además, son fundamentales para llevar a cabo evaluaciones de riesgos, ya que proporcionan datos detallados de cada activo, así como sus posibles amenazas y las salvaguardas aplicadas.



### 2.2.1 [I] Activos esenciales

Los activos esenciales forman el núcleo de la infraestructura, comprendiendo elementos vitales para el funcionamiento del bufete. Estos pueden incluir información crítica, servicios fundamentales, y cualquier otro componente que sea indispensable para la operatividad diaria.

| Código | Nombre                            | Descripción                                                  | D     | I     | C     | A     | T     |
|--------|-----------------------------------|--------------------------------------------------------------|-------|-------|-------|-------|-------|
| AE001  | Archivo Digital de Casos           | Almacena información crítica de casos, indispensable para la práctica legal diaria. | Alta  | Alta  | Alta  | Alta  | Media |
| AE002  | Sistema de Comunicaciones          | Facilita la comunicación interna y externa, siendo vital para la colaboración y la prestación de servicios. | Alta  | Media | Alta  | Alta  | Alta  |
| AE003  | Base de datos de clientes          | Almacena información detallada sobre los clientes, incluyendo historial legal, preferencias y contactos. | Alta  | Alta  | Alta  | Alta  | Media |
| AE004  | Sistema de gestión financiera      | Herramienta que facilita la gestión financiera del bufete, incluyendo facturación, ingresos y gastos. | Alta  | Alta  | Alta  | Alta  | Media |
| AE005  | Plataforma de colaboración interna | Espacio digital que permite la colaboración eficiente entre los miembros del bufete en documentos y proyectos. | Alta  | Media | Alta  | Alta  | Alta  |


Estos activos no solo son esenciales para la operación interna, sino que también contribuyen a mejorar la eficiencia, la toma de decisiones y la prestación de servicios de calidad a los clientes.



### 2.2.2 [A] Arquitectura del sistema

La arquitectura del sistema engloba los elementos que sustentan la infraestructura tecnológica del bufete. Estos pueden abarcar desde servidores y redes hasta la disposición física de los equipos.

| Código | Nombre                        | Descripción                                                  | D     | I     | C     | A     | T     |
|--------|-------------------------------|--------------------------------------------------------------|-------|-------|-------|-------|-------|
| AS001  | Servidores Centrales           | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. | Alta  | Alta  | Alta  | Alta  | Media |
| AS002  | Red de Área Local (LAN)       | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos. | Alta  | Alta  | Media | Alta  | Alta  |
| AS003  | Sistema de seguridad de red   | Implementación de firewalls, antivirus y otras medidas para salvaguardar la integridad de la red. | Alta  | Alta  | Alta  | Alta  | Alta  |
| AS004  | Políticas de acceso y control | Definición de políticas que regulan el acceso a la información y la administración de privilegios. | Alta  | Alta  | Alta  | Alta  | Alta  |
| AS005  | Infraestructura de respaldo   | Sistemas y procedimientos para realizar copias de seguridad periódicas y garantizar la disponibilidad de datos. | Alta  | Alta  | Alta  | Alta  | Media |


Estos elementos contribuyen a la seguridad, confiabilidad y eficiencia de la infraestructura tecnológica del bufete, asegurando la integridad de la información y la continuidad de las operaciones.




### 2.2.3 [D] Datos / Información

Los datos e información manejados por el bufete son vitales para su funcionamiento. Aquí pongo los más importantes:

| Código | Nombre                          | Descripción                                            | D     | I     | C     | A     | T     |
|--------|---------------------------------|--------------------------------------------------------|-------|-------|-------|-------|-------|
| D001   | Casos legales en curso          | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. | Alta  | Alta  | Alta  | Alta  | Alta  |
| D002   | Contratos y acuerdos            | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. | Alta  | Alta  | Alta  | Alta  | Media |
| D003   | Información confidencial del cliente | Datos sensibles de los clientes, como información financiera y personal. | Alta  | Alta  | Alta  | Alta  | Alta  |
| D004   | Precedentes legales             | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. | Alta  | Alta  | Alta  | Alta  | Media |
| D005   | Servicios Digitales             | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). | Alta  | Alta  | Alta  | Alta  | Alta  |

Estos datos son esenciales para la práctica legal diaria y su confidencialidad e integridad deben ser protegidas, por lo que hay que considerar la gestión de versiones y la trazabilidad de los cambios en los documentos legales para garantizar la integridad y autenticidad de la información.

Para un manejo eficiente de la información, deberiamos implementar sistemas de gestión documental que faciliten la organización, búsqueda y acceso controlado a los documentos clave del bufete cuando un empleado lo necesite.

### 2.2.4 [K] Claves criptográficas

Las claves criptográficas desempeñan un papel crucial en la seguridad de la información confidencial del bufete. A continuación, se presentan algunas de las claves criptográficas utilizadas, cada una cumpliendo una función específica en la protección de datos sensibles (más detalles en la parte específica de seguridad):

| Código | Nombre | Descripción | D     | I     | C     | A     | T     |
|--------|--------|-------------|-------|-------|-------|-------|-------|
| KC001  | Claves de acceso a bases de datos | Garantizan la seguridad de las bases de datos legales del bufete, evitando accesos no autorizados. | Alta  | Alta  | Alta  | Alta  | Alta  |
| KC002  | Claves de correo electrónico | Aseguran la confidencialidad de las comunicaciones por correo electrónico dentro del bufete, protegiendo la privacidad de la correspondencia legal. | Alta  | Alta  | Alta  | Alta  | Alta  |
| KC003  | Claves de acceso a sistemas internos | Utilizadas para acceder a sistemas internos que gestionan información crítica y legal, asegurando la autenticación de usuarios autorizados. | Alta  | Alta  | Alta  | Alta  | Alta  |
| KC004  | Claves de cifrado de documentos | Protegen la integridad y confidencialidad de documentos legales almacenados en sistemas digitales, evitando accesos no autorizados y manipulación no autorizada. | Alta  | Alta  | Alta  | Alta  | Alta  |
| KC005  | Claves de firma digital | Garantizan la autenticidad de documentos legales firmados digitalmente por el bufete, proporcionando una capa adicional de seguridad en transacciones electrónicas. | Alta  | Alta  | Alta  | Alta  | Alta  |


Estas claves son gestionadas con frecuencia para prevenir accesos no autorizados, protegiendo así la confidencialidad e integridad de la información legal del bufete.


### 2.2.5 [S] Servicios

La función de los servicios es la clave para satisfacer las necesidades de los usuarios y contribuir al cumplimiento de la misión del bufete. Se clasifican como activos imprescindibles, como utilidades para usuarios finales, servicios utilizados internamente o servicios contratados a otras organizaciones con sus propios recursos ajenos a la propia empresa.

En este rango se abarca servicios para atender las necesidades colectivas, servicios empresariales brindados por el bufete para satisfacer a sus clientes, así como servicios internos gestionados por departamentos especializados, dependiendo que tipo de casos los gestionan unos departamentos u otros.

Por lo que, aquí se abordan servicios relacionados con la información, comunicaciones, seguridad, entre otros. La diversidad de estos servicios es esencial para el desempeño eficaz de la misión del bufete.

| Código | Nombre                                    | Descripción                                                  | D     | I     | C     | A     | T     |
|--------|-------------------------------------------|--------------------------------------------------------------|-------|-------|-------|-------|-------|
| S001   | Intranet                                   | Servicio de red interna para los empleados del bufete.        | Media | Media | Alta  | Media | Media |
| S002   | Exchange Server  | Plataforma de correo electrónico propia que facilita la comunicación electrónica segura.                              | Alta  | Alta  | Alta  | Alta  | Alta  |
| S003   | SFTP                                   | Intercambio seguro de archivos.                               | Media | Media | Media  | Media | Media |
| S004   | Active Directory (AD)             | Servicio centralizado propio para gestionar identidades y accesos en entornos Windows.                           | Alta  | Alta  | Alta  | Alta  | Alta  |
| S005   | Software ARP                              | Servicio que realiza el descubrimiento y mapeo de dispositivos en la red para gestionar altas, bajas y cambios en usuarios.| Media | Media | Baja  | Media | Media |
| S006   | PKI - Infraestructura de clave pública  | Gestión segura de certificados y criptografía de clave pública.| Alta  | Alta  | Alta  | Alta  | Alta  |


Hay muchas más posibilidades pero he elegido estas porque sino seria interminable si no recortamos partes todos los miembros. 

Estos servicios son la base para la operación del bufete, requiriendo atención especial en términos de seguridad y eficiencia para su correcto desempeño y contribución a la misión del bufete.


## 2.2.6 [SW] Software / Aplicaciones

El conjunto de software y aplicaciones utilizadas en el bufete abarca una gama amplia de funciones, todas imprescindibles para el funcionamiento eficiente y seguro. Aquí dejo una lista detallada de algunas de las aplicaciones que se usarán en nuestro bufete:

| Código | Nombre del software                      | Descripción                                                | Valoración D | Valoración I | Valoración C | Valoración A | Valoración T |
|--------|----------------------------------|------------------------------------------------------------|--------------|--------------|--------------|--------------|--------------|
| SW000  | Debian 12                         | Sistema operativo confiable y de código abierto. Proporciona una base segura y estable para todas las operaciones. | Alta         | Media        | Baja         | Media        | Alta         |
| SW001  | Windows 11                        | Sistema operativo de Microsoft con una interfaz moderna y mejoras en seguridad y rendimiento. | Alta         | Media        | Alta         | Media        | Alta         |
| SW002  | Clio Manage                       | Sistema de Gestión de Casos Legales. Facilita el seguimiento y gestión de casos legales. | Alta         | Alta         | Media        | Media        | Alta         |
| SW003  | Westlaw                           | Herramientas de Investigación Legal. Proporciona acceso a bases de datos legales y recursos de investigación. | Alta         | Alta         | Alta         | Media        | Alta         |
| SW004  | Microsoft Teams                   | Plataforma de Colaboración. Mejora la colaboración interna y externa facilitando la comunicación y el intercambio de documentos. | Alta         | Alta         | Media        | Media        | Alta         |
| SW005  | Clio Billing                      | Software de Facturación Legal. Gestiona la facturación de servicios legales. | Alta         | Media        | Alta         | Media        | Alta         |
| SW006  | NetDocuments                      | Plataforma de Gestión Documental. Organiza y almacena documentos legales de manera segura. | Alta         | Alta         | Alta         | Media        | Alta         |
| SW007  | Lex Machina                       | Herramientas de Analítica Legal. Ofrece capacidades analíticas para evaluar tendencias legales. | Alta         | Alta         | Media        | Media        | Alta         |
| SW008  | LexisNexis                        | Plataforma de Investigación Legal. Facilita la búsqueda y análisis de jurisprudencia y legislación. | Alta         | Alta         | Alta         | Media        | Alta         |
| SW009  | Ravel Law                         | Herramientas de Analítica Legal. Proporciona capacidades analíticas para evaluar tendencias legales. | Alta         | Alta         | Media        | Media        | Alta         |
| SW010  | QuickBooks Legal                  | Software de Administración Financiera. Gestiona aspectos financieros y contabilidad del bufete. | Alta         | Media        | Alta         | Media        | Alta         |
| SW011  | Zoom Meetings                     | Herramientas de Videoconferencia. Amplía las capacidades de comunicación remota. | Alta         | Media        | Media        | Baja         | Alta         |
| SW012  | Varonis Data Security Platform    | Plataforma de Gestión de Privilegios. Controla y audita los accesos a información confidencial. | Alta         | Alta         | Media        | Media        | Alta         |
| SW013  | Symantec Encryption               | Sistemas de Cifrado de Comunicaciones. Asegura la privacidad de las comunicaciones. | Alta         | Alta         | Media        | Media        | Alta         |


Estas aplicaciones adicionales refuerzan la capacidad del bufete para abordar diversos aspectos legales, financieros y de gestión, mientras garantizan la seguridad y eficiencia en todas las operaciones. Podría haber elegido diferentes opciones, pero en un entorno profesional, estas suelen ser las más comunes, aunque normalmente suele usarse solamente Windows, he añadido tambien Debian para los usuarios que prefieran este sistema operativo.


## 2.2.7 [HW] Equipamiento Informático (Hardware)

El bufete legal se basa en una infraestructura sólida y diversa, proporcionando a sus trabajadores las herramientas necesarias para el desempeño eficiente de sus tareas. Desde servidores potentes hasta estaciones de trabajo especializadas y dispositivos de almacenamiento de última generación, el equipamiento informático y hardware desempeña un papel crucial en la operación diaria del bufete. Como en las partes anteriores, he hecho una tabla que abarca desde servidores hasta sistemas de videovigilancia, destacando la variedad de recursos que respaldan la seguridad y productividad del bufete.

| Código | Nombre                                    | Descripción                                                                                     | D     | I     | C     | A     | T     |
|--------|-------------------------------------------|-------------------------------------------------------------------------------------------------|-------|-------|-------|-------|-------|
| HW000  | Servidores Dell PowerEdge                 | Componentes clave utilizados para ejecutar aplicaciones críticas del bufete.                     | Alta  | Alta  | Alta  | Alta  | Alta  |
| HW001  | Estación de Trabajo HP ZBook              | Equipos portátiles diseñados para tareas intensivas en diseño y análisis legal.                  | Alta  | Alta  | Media | Alta  | Alta  |
| HW002  | PC de Escritorio Lenovo ThinkCentre       | Equipos de escritorio confiables ideales para el uso cotidiano de los empleados.             | Media | - | -  | Alta | - |
| HW003  | Dispositivos de Almacenamiento Synology   | Unidades de almacenamiento en red para la gestión segura de datos con capacidades escalables.     | Alta  | Alta  | Alta  | Alta  | Alta  |
| HW004  | Impresoras HP LaserJet                    | Impresoras esenciales para la impresión eficiente de documentos legales.                           | Baja  | -  | Media | -  | Media  |
| HW005  | Enrutador Cisco Catalyst                  | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad.      | Alta  | Alta  | Alta  | Alta  | Alta  |
| HW006  | Sistema de Videovigilancia Axis           | Sistema completo de videovigilancia con cámaras para la seguridad física del bufete.             | Alta  | Alta  | Alta  | -  | Alta  |
| HW007  | Escáner Epson WorkForce                   | Escáner de alta velocidad para digitalizar documentos legales y mantener registros digitales.    | Baja  | -  | - | -  | -  |
| HW008  | Teléfonos VoIP Grandstream                | Dispositivos de comunicación empresarial que ofrecen funciones avanzadas de telefonía IP.       | Alta  | Alta  | Alta  | Alta  | Alta  |
| HW009  | UPS APC Smart-UPS                        | Sistema de alimentación ininterrumpida para proteger contra cortes de energía y asegurar la continuidad de operaciones. | Alta  | -  | - | -  | Baja  |
| HW010  | Estación Docking para Portátiles          | Permite a las estaciones de trabajo portátiles conectarse fácilmente a periféricos de escritorio. | Media  | -  | - | -  | -  |
| HW011  | Sistemas de Control de Acceso             | Dispositivos biométricos y de tarjetas para garantizar la seguridad en el acceso a áreas restringidas. | Alta  | Alta  | Alta  | Alta  | Alta  |
| HW012  | Pizarras Interactivas SMART                | Herramientas colaborativas para presentaciones y discusiones legales interactivas.               | Media | Media | Baja  | - | - |


Esta tabla incluye equipos adicionales como estaciones de acoplamiento, sistemas de control de acceso y pizarras interactivas, por mencionar algunos ejemplos más aparte de limitarme solamente a equipos.


### 2.2.8 [COM] Redes de comunicaciones

La infraestructura de comunicaciones del bufete proporciona la columna vertebral que conecta todos los componentes tecnológicos, garantizando una comunicación fluida y segura. Desde redes locales que facilitan la colaboración interna hasta conexiones a Internet y servicios de telefonía, cada elemento contribuye a la eficiencia operativa y la conectividad integral del bufete. 


| Código | Nombre                        | Descripción                                                               | D     | I     | C     | A     | T     |
|--------|------------------------------|---------------------------------------------------------------------------|-------|-------|-------|-------|-------|
| COM001 | Red de Invitados              | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad.| Baja     | Media     | Alta     | Alta     | Media     |
| COM002 | Red 5G para Dispositivos Móviles | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes.| - | - | -  | - | - |
| COM003 | Fibra Óptica                   | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. | Alta  | -  | -  | -  | -  |
| COM004 | Red de Alta Seguridad Interna   | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete.| Alta  | Alta  | Alta  | Alta  | Alta  |
| COM005 | Red Inalámbrica Segura (WPA3)  | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos.| Alta  | Alta  | Alta  | Alta  | Alta  |
| COM006 | Red de Área Local (LAN)         | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. | Media | Media | Baja  | Media | Media |
| COM007 | Red de Voz sobre IP (VoIP)      | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente.| Alta  | Alta  | Alta  | Alta  | Alta  |
| COM008 | Red Privada Virtual (VPN)       | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información.| Alta  | Alta  | Alta  | Alta  | Alta  |




### 2.2.9 [Media] Soportes de información

La gestión de soportes de información es esencial para garantizar la integridad y disponibilidad del bufete. Algunos de los soportes de información y su función:

| Código | Nombre               	| Descripción                                                              	| D     | I     | C     | A     | T     |
|--------|--------------------------|------------------------------------------------------------------------------|-------|-------|-------|-------|-------|
| SI001  | Almacenamiento en Red (SAN) | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento.| Alta  | Alta  | Alta  | Alta  | Alta  |
| SI002  | Disco Duro Externo    	| Ofrece una solución portátil y conveniente para el respaldo de datos importantes, facilitando la transferencia y protección de información clave fuera de la red principal.| Media | Media | Media  | Media | Media |
| SI003  | Tarjeta de Memoria    	| Utilizada en dispositivos móviles y cámaras para almacenar y transferir datos. Aporta flexibilidad y movilidad a la captura y transporte de información relevante.| Media | Baja  | Baja  | Media | Media |
| SI004  | Almacenamiento en la Nube | Permite el acceso remoto y la colaboración en documentos desde cualquier ubicación, facilitando el intercambio de información entre miembros del bufete y garantizando su respaldo seguro.| Alta  | Alta  | Alta  | Alta  | Alta  |
| SI005  | Disco Óptico (DVD)    	| Ideal para almacenar datos, proporciona una forma duradera y fácil de distribuir y respaldar información crítica, especialmente para archivar documentos legales.| Baja | Baja  | Baja  | Media | Media |
| SI006  | Unidad USB           	| Ofrece portabilidad y accesibilidad rápida a datos esenciales. Su capacidad de almacenamiento y facilidad de uso la convierten en una herramienta fundamental para el transporte seguro de información.| Media | Media | Baja  | Media | Media |
| SI007  | Tarjeta Inteligente (Smart Card) | Proporciona autenticación segura y control de acceso a sistemas críticos. Su uso protege la confidencialidad y garantiza que solo personal autorizado tenga acceso a información sensible.| Alta  | Alta  | Alta  | Alta  | Alta  |


En esta parte es donde se almacenan todos los documentos importantes. Desde contratos legales hasta datos cruciales, este sistema asegura que la información esté organizada y lista para ser accedida cuando se necesite. Además, implementa medidas de respaldo y recuperación para garantizar que nada se pierda.


### 2.2.10 [AUX] Equipamiento auxiliar

El equipamiento auxiliar en el bufete es como el equipo de apoyo que mantiene todo en marcha sin estar directamente relacionado con los datos. Desde fuentes de alimentación hasta sistemas de climatización, estos elementos aseguran que los sistemas de información funcionen sin problemas. Los elementos de equipamiento auxiliar y sus funciones dentro del entorno legal:

| Código | Nombre                            	| Descripción                                                                                                                                                             	| D     | I     | C     | A     | T     |
|--------|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|-------|-------|-------|-------|
| AUX001 | Fuentes de Alimentación           	| Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía.          	| Alta  | Alta  | Media | Media  | Alta  |
| AUX002 | Sistemas de Alimentación Ininterrumpida  | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. | Alta  | -  | -  | -  | -  |
| AUX003 | Equipos de Climatización          	| Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos.	| Alta  | - | - | -  | -  |
| AUX004 | Cableado                          	| Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red.        	| Alta | Media | -  | Media | Media |
| AUX005 | Mobiliario: Armarios, etc.        	| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. | Media | -  | -  | - | - |



### 2.2.11 [L] Instalaciones

Pearson Specter, como bufete de abogados líder en Madrid, se beneficia de instalaciones estratégicamente ubicadas y diseñadas para satisfacer las necesidades específicas de sus equipos legal y tecnológico.

| Código | Nombre           	| Descripción                                                                                                       	|
|--------|----------------------|-----------------------------------------------------------------------------------------------------------------------|
| L001   | Edificio Principal	| Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal	| Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales.  |
| L003   | Centro Tecnológico 	| Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores 	| Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.              	|

Estas instalaciones forman la base desde la cual Pearson Specter ofrece servicios legales y tecnológicos de vanguardia, combinando eficacia y seguridad.


### 2.2.12 [P] Personal

La estructura organizativa de Pearson Specter refleja la importancia de cada departamento y su papel en la excelencia legal y tecnológica.
| Departamento                 	| Posición            	| Responsabilidades                                                                                                                                                                                                                                  	|
|----------------------------------|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Dirección y Socios           	| Socio Fundador      	| Toma de decisiones estratégicas, supervisión de la visión y estrategia de crecimiento, relaciones clave con clientes, gestión de casos complejos.                                                                                                   	|
| Dirección y Socios           	| Socio Gerente       	| Supervisión de operaciones diarias, gestión de recursos humanos y financieros, toma de decisiones operativas, liderazgo del equipo directivo.                                                                                                        	|
| Jefes de Departamento        	| Jefe Legal Civil     	| Supervisión de litigios civiles, coordinación de abogados especializados, garantía del cumplimiento de plazos y brindar asesoramiento legal sólido.                                                                                                   	|
| Jefes de Departamento        	| Jefe Legal Penal     	| Dirección de actividades en derecho penal, supervisión de defensa legal en casos penales, estrategias de litigio penal.                                                                                                                              	|
| Jefes de Departamento        	| Jefe Derecho Corporativo | Coordinación de servicios legales en empresas y negocios, formación de sociedades, gestión de fusiones y adquisiciones, contratos comerciales.                                                                                                      	|
| Jefes de Departamento        	| Jefe Propiedad Intelectual| Liderazgo en derechos de autor, patentes, marcas registradas, protección y defensa de la propiedad intelectual.                                                                                                                                      	|
| Jefes de Departamento        	| Jefe Tecnología e IT  	| Supervisión de la infraestructura tecnológica, garantizar el cumplimiento de estándares de seguridad, colaboración con abogados en casos tecnológicos.                                                                                                  	|
| Jefes de Departamento        	| Jefe Recursos Humanos 	| Dirección de recursos humanos, gestión de contrataciones, desarrollo y retención del personal, responsabilidad de la cultura organizacional y capacitación.                                                                                         	|
| Jefes de Departamento        	| Jefe Finanzas y Adm.  	| Supervisión de la gestión financiera, presupuesto, contabilidad, administración eficiente de recursos financieros.                                                                                                                                	|
| Jefes de Departamento        	| Jefe Marketing y Com. 	| Promoción de la firma, gestión de comunicación con clientes, desarrollo de estrategias de marketing y relaciones públicas.                                                                                                                        	|
| Personal IT                  	| Profesionales de TI  	| Mantenimiento de infraestructura tecnológica, implementación de soluciones tecnológicas, asesoramiento en casos legales digitales.                               

