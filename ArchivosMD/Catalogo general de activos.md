## 2 Catalogo general de activos

Identificar y clasificar los activos es imprescindible para documentar el estado de la empresa, y también para entender las posibles amenazas y las medidas de seguridad adecuadas. A continuación explico como funciona e incluyo algunos de los posibles activos y puede cambiar con el tiempo dependendiendo del desarrollo de la empresa con el tiempo. 

La implementación de la metodología MAGERIT consiste en la creación de un catálogo de activos. Este proceso, esencial antes de tomar decisiones sobre seguridad, implica la identificación precisa de los activos de la empresa. Según la norma UNE 71504:2008 [6] (pdf de referencia), un activo se define como cualquier componente o funcionalidad en un sistema de información vulnerable a ataques deliberados o accidentales con consecuencias para la organización. Estos abarcan información, datos, servicios, aplicaciones (software), equipos (hardware), comunicaciones, recursos administrativos, recursos físicos y recursos humanos.

Dentro de un sistema de información, identificamos dos categorías principales de activos: la información y los servicios que proporciona. Subordinados a estos, encontramos otros elementos clave, desde datos y servicios auxiliares hasta aplicaciones informáticas, equipos informáticos, soportes de información, equipamiento auxiliar, redes de comunicaciones, instalaciones y el personal operativo.

Cada activo tiene un valor, que no se refiere simplemente al costo, sino a la importancia que tiene para la empresa. Esta valoración se realiza considerando dimensiones críticas de seguridad, tales como la confidencialidad, integridad y disponibilidad del activo.

En el ámbito de los servicios digitales, se añaden dos dimensiones adicionales relacionadas con el conocimiento de los actores involucrados: la autenticidad de los usuarios y la trazabilidad del uso del servicio (más en su respectiva parte mas adelante).

Para evaluar los activos, se usan escalas de valores que permitan una comparación efectiva de riesgos. Es crucial emplear una escala común para todas las dimensiones, preferiblemente logarítmica y centrada en diferencias relativas de valor. MAGERIT ofrece dos escalas, una más sencilla y otra más detallada. La elección de una escala sencilla de diez valores, adaptada a la envergadura del despacho y sus activos, facilita la identificación de elementos despreciables y aquellos irremplazables.

Este proceso de catalogar activos y asignarles valor no solo establece una base sólida para la seguridad, sino que también proporciona un marco homogéneo para analizar riesgos de manera efectiva y tomar decisiones informadas.

Los puntos de la siguiente tabla, organizan los activos en una jerarquía, asignándoles un código que muestra su posición en la jerarquía, un nombre y una breve descripción de lo que representa cada tipo de activo. Los activos No tienen que ser estrictamente como tal, y perfectamente pueden pertenecer a diferentes categorias.


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



La valoración es una forma de asignar un puntaje o evaluación a cada activo en diferentes dimensiones de seguridad. Generalmente se utiliza para indicar cuánto valor tiene cada activo para la organización en términos de:

- D (Disponibilidad): ¿Qué tan importante es que este activo esté siempre disponible?
- I (Integridad): ¿Qué tan crítico es mantener la integridad o exactitud de este activo?
- C (Confidencialidad): ¿Qué tan sensible o confidencial es la información contenida en este activo?
- A (Autenticidad): ¿Cuán importante es asegurar que este activo sea auténtico y provenga de una fuente confiable?
- T (Trazabilidad): ¿Cuánta importancia se le da al seguimiento y registro de las acciones relacionadas con este activo?

La valoración se realiza utilizando una escala, que puede ser numérica (por ejemplo, del 1 al 10) o cualitativa (baja, media, alta). En el ejemplo que proporcioné anteriormente, utilicé una escala numérica entre corchetes [D/I/C/A/T] para representar la valoración en cada dimensióna modo de lo visto en la documentación.


### 2.2 Fichas detalle archivo

Las fichas son documentos o formularios que contienen información detallada sobre un elemento específico. En la metodología MAGERIT para la gestión de riesgos en sistemas de información, las fichas de detalle de activos son registros detallados para cada tipo de activo identificado en el catálogo. Cada ficha proporciona información específica sobre el activo, como su código de identificación, nombre, descripción, y cualquier otra información relevante que facilite su gestión y evaluación de riesgos.

Estas fichas (mas bien herramientas prácticas) ayudan a documentar y organizar la información sobre los activos del bufete en este caso. Además, son fundamentales para llevar a cabo evaluaciones de riesgos, ya que proporcionan datos detallados de cada activo, así como sus posibles amenazas y las salvaguardas aplicadas.



### 2.2.1 [I] Activos esenciales

Los activos esenciales forman el núcleo de la infraestructura, comprendiendo elementos vitales para el funcionamiento del bufete. Estos pueden incluir información crítica, servicios fundamentales, y cualquier otro componente que sea indispensable para la operatividad diaria.

| Código | Nombre | Descripción |
|--------|--------|-------------|
| AE001  | Archivo Digital de Casos | Almacena información crítica de casos, indispensable para la práctica legal diaria. |
| AE002  | Sistema de Comunicaciones | Facilita la comunicación interna y externa, siendo vital para la colaboración y la prestación de servicios. |
| AE003  | Base de datos de clientes      | Almacena información detallada sobre los clientes, incluyendo historial legal, preferencias y contactos. |
| AE004  | Sistema de gestión financiera  | Herramienta que facilita la gestión financiera del bufete, incluyendo facturación, ingresos y gastos. |
| AE005  | Plataforma de colaboración interna | Espacio digital que permite la colaboración eficiente entre los miembros del bufete en documentos y proyectos. |

Estos activos no solo son esenciales para la operación interna, sino que también contribuyen a mejorar la eficiencia, la toma de decisiones y la prestación de servicios de calidad a los clientes.



### 2.2.2 [A] Arquitectura del sistema

La arquitectura del sistema engloba los elementos que sustentan la infraestructura tecnológica del bufete. Estos pueden abarcar desde servidores y redes hasta la disposición física de los equipos.

| Código | Nombre | Descripción |
|--------|--------|-------------|
| AS001  | Servidores Centrales | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |
| AS002  | Red de Área Local (LAN) | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos. |
| AS003  | Sistema de seguridad de red           | Implementación de firewalls, antivirus y otras medidas para salvaguardar la integridad de la red. |
| AS004  | Políticas de acceso y control         | Definición de políticas que regulan el acceso a la información y la administración de privilegios. |
| AS005  | Infraestructura de respaldo           | Sistemas y procedimientos para realizar copias de seguridad periódicas y garantizar la disponibilidad de datos. |

Estos elementos contribuyen a la seguridad, confiabilidad y eficiencia de la infraestructura tecnológica del bufete, asegurando la integridad de la información y la continuidad de las operaciones.




### 2.2.3 [D] Datos / Información

Los datos e información manejados por el bufete son vitales para su funcionamiento. Aquí pongo los más importantes:

| Código | Nombre                          | Descripción                                            |
|--------|---------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso          | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos            | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales             | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales             | Se incluyen servicios tales como correo electrónico ([email]), almacenamiento de ficheros ([file]), y gestión de identidades ([idm]). Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete. |

Estos datos son esenciales para la práctica legal diaria y su confidencialidad e integridad deben ser protegidas, por lo que hay que considerar la gestión de versiones y la trazabilidad de los cambios en los documentos legales para garantizar la integridad y autenticidad de la información.

Para un manejo eficiente de la información, deberiamos implementar sistemas de gestión documental que faciliten la organización, búsqueda y acceso controlado a los documentos clave del bufete cuando un empleado lo necesite.

### 2.2.4 [K] Claves criptográficas

Las claves criptográficas desempeñan un papel crucial en la seguridad de la información confidencial del bufete. A continuación, se presentan algunas de las claves criptográficas utilizadas, cada una cumpliendo una función específica en la protección de datos sensibles (más detalles en la parte específica de seguridad):

| Código | Nombre | Descripción |
|--------|--------|-------------|
| KC001  | Claves de acceso a bases de datos | Garantizan la seguridad de las bases de datos legales del bufete, evitando accesos no autorizados. |
| KC002  | Claves de correo electrónico | Aseguran la confidencialidad de las comunicaciones por correo electrónico dentro del bufete, protegiendo la privacidad de la correspondencia legal. |
| KC003  | Claves de acceso a sistemas internos | Utilizadas para acceder a sistemas internos que gestionan información crítica y legal, asegurando la autenticación de usuarios autorizados. |
| KC004  | Claves de cifrado de documentos | Protegen la integridad y confidencialidad de documentos legales almacenados en sistemas digitales, evitando accesos no autorizados y manipulación no autorizada. |
| KC005  | Claves de firma digital | Garantizan la autenticidad de documentos legales firmados digitalmente por el bufete, proporcionando una capa adicional de seguridad en transacciones electrónicas.

Estas claves son gestionadas con frecuencia para prevenir accesos no autorizados, protegiendo así la confidencialidad e integridad de la información legal del bufete.


### 2.2.5 [S] Servicios

La función de los servicios es la clave para satisfacer las necesidades de los usuarios y contribuir al cumplimiento de la misión del bufete. Se clasifican como activos imprescindibles, como utilidades para usuarios finales, servicios utilizados internamente o servicios contratados a otras organizaciones con sus propios recursos ajenos a la propia empresa.

En este rango se abarca servicios para atender las necesidades colectivas, servicios empresariales brindados por el bufete para satisfacer a sus clientes, así como servicios internos gestionados por departamentos especializados, dependiendo que tipo de casos los gestionan unos departamentos u otros.

Por lo que, aquí se abordan servicios relacionados con la información, comunicaciones, seguridad, entre otros. La diversidad de estos servicios es esencial para el desempeño eficaz de la misión del bufete.



| Código | Nombre                          | Descripción                                                  |
|--------|---------------------------------|--------------------------------------------------------------|
| S001   | Anónimo                         | Servicios sin requerir identificación del usuario.            |
| S002   | Al público en general           | Ofrecidos sin relación contractual específica.                |
| S003   | A usuarios externos             | Dirigidos a usuarios externos bajo contrato.                  |
| S004   | Interno                         | Servicios para usuarios y medios internos del bufete.         |
| S005   | Contratado a terceros           | Servicios prestados con medios externos.                      |
| S006   | World Wide Web (www)            | Acceso a servicios web.                                       |
| S007   | Acceso remoto a cuenta local    | Conexiones remotas a cuentas locales de forma segura.         |
| S008   | Correo electrónico              | Comunicación electrónica segura.                              |
| S009   | Almacenamiento de ficheros      | Gestión segura de documentos y archivos.                      |
| S010   | Transferencia de ficheros       | Intercambio seguro de archivos.                               |
| S011   | Intercambio electrónico de datos| Facilita la transferencia segura de información.              |
| S012   | Servicio de directorio          | Localización de personas y empresas.                          |
| S013   | Gestión de identidades          | Servicios para altas y bajas de usuarios y aprovisionamiento.|
| S014   | Gestión de privilegios          | Control seguro y gestión de privilegios.                       |
| S015   | PKI - Infraestructura de clave pública | Gestión segura de certificados y criptografía de clave pública.|

Hay muchas más posibilidades pero he elegido estas porque sino seria interminable si no recortamos partes todos los miembros. 

Estos servicios son la base para la operación del bufete, requiriendo atención especial en términos de seguridad y eficiencia para su correcto desempeño y contribución a la misión del bufete.


## 2.2.6 [SW] Software / Aplicaciones

El conjunto de software y aplicaciones utilizadas en el bufete abarca una gama amplia de funciones, todas imprescindibles para el funcionamiento eficiente y seguro. Aquí dejo una lista detallada de algunas de las aplicaciones que se usarán en nuestro bufete:

| Código | Nombre del software                      | Descripción                                                |
|--------|----------------------------------|------------------------------------------------------------|
| SW000  | Debian 12                         | Sistema operativo confiable y de código abierto. Proporciona una base segura y estable para todas las operaciones. |
| SW001  | Windows 11                        | Sistema operativo de Microsoft con una interfaz moderna y mejoras en seguridad y rendimiento. |
| SW002  | Clio Manage                       | Sistema de Gestión de Casos Legales. Facilita el seguimiento y gestión de casos legales. |
| SW003  | Westlaw                           | Herramientas de Investigación Legal. Proporciona acceso a bases de datos legales y recursos de investigación. |
| SW004  | Microsoft Teams                   | Plataforma de Colaboración. Mejora la colaboración interna y externa facilitando la comunicación y el intercambio de documentos. |
| SW005  | Clio Billing                      | Software de Facturación Legal. Gestiona la facturación de servicios legales. |
| SW006  | NetDocuments                      | Plataforma de Gestión Documental. Organiza y almacena documentos legales de manera segura. |
| SW007  | Lex Machina                       | Herramientas de Analítica Legal. Ofrece capacidades analíticas para evaluar tendencias legales. |
| SW008  | LexisNexis                        | Plataforma de Investigación Legal. Facilita la búsqueda y análisis de jurisprudencia y legislación. |
| SW009  | Ravel Law                         | Herramientas de Analítica Legal. Proporciona capacidades analíticas para evaluar tendencias legales. |
| SW010  | QuickBooks Legal                  | Software de Administración Financiera. Gestiona aspectos financieros y contabilidad del bufete. |
| SW011  | Zoom Meetings                     | Herramientas de Videoconferencia. Amplía las capacidades de comunicación remota. |
| SW012  | Varonis Data Security Platform    | Plataforma de Gestión de Privilegios. Controla y audita los accesos a información confidencial. |
| SW013  | Symantec Encryption               | Sistemas de Cifrado de Comunicaciones. Asegura la privacidad de las comunicaciones. |

Estas aplicaciones adicionales refuerzan la capacidad del bufete para abordar diversos aspectos legales, financieros y de gestión, mientras garantizan la seguridad y eficiencia en todas las operaciones. Podría haber elegido diferentes opciones, pero en un entorno profesional, estas suelen ser las más comunes, aunque normalmente suele usarse solamente Windows, he añadido tambien Debian para los usuarios que prefieran este sistema operativo.



### 2.2.7 [HW] Equipamiento informático (hardware)

### 2.2.8 [COM] Redes de comunicaciones

### 2.2.9 [Media] Soportes de información

### 2.2.10 [AUX] Equipamiento auxiliar

### 2.2.11 [L] Instalaciones

### 2.2.12 [P] Personal

