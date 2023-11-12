## 3 Identificación de amenazas
<!-- https://www.pilar-tools.com/doc/magerit/v2/cat-es-v11.pdf -->

En esta sección, nos enfocamos en la identificación exhaustiva de todas las amenazas potenciales que podrían representar un riesgo para nuestros recursos. Además, evaluamos las diversas dimensiones en las que estas amenazas pueden impactar. Para lograr este objetivo, creamos una ficha detallada para cada amenaza, en la cual documentamos los tipos de activos que podrían verse afectados y las dimensiones en las que dicha amenaza podría tener consecuencias.

A través de este proceso, también revisamos nuestro inventario de activos en busca de aquellos que cumplen con las condiciones relacionadas con cada amenaza específica. Esta revisión minuciosa nos permite comprender mejor cómo nuestras valiosas propiedades y recursos podrían estar expuestos a diversos riesgos y peligros potenciales. Al identificar y documentar estas amenazas de manera precisa, estamos en una posición más sólida para tomar medidas preventivas y desarrollar estrategias de mitigación efectivas para proteger nuestros activos y garantizar la continuidad de nuestras operaciones.

### 3.1 [DN] Desastres naturales
Los desastres naturales representan una categoría crítica de amenazas que enfrentan las infraestructuras y entornos de procesamiento de datos. Estos eventos, originados por la naturaleza, abarcan una amplia gama de fenómenos, desde terremotos y inundaciones hasta incendios forestales y tormentas, con el potencial de causar impactos devastadores en la infraestructura tecnológica.

La vulnerabilidad de los Centros de Procesamiento de Datos (CPDs) frente a estos desastres radica en la posibilidad de interrupción o pérdida total de los servicios que proveen, lo que incluye la infraestructura física y lógica esencial para el funcionamiento de sistemas, almacenamiento de datos y comunicación.

#### 3.1 Fuego

El fuego como riesgo en un Centro de Procesamiento de Datos (CPD) es una amenaza crítica debido a la alta concentración de equipos electrónicos y la sensibilidad a las temperaturas extremas. Un incendio podría causar daños catastróficos a los servidores, almacenamiento de datos y sistemas de red, llevando a la pérdida de información crucial. La presencia de cables, hardware y sistemas eléctricos aumenta la probabilidad de un incendio, haciendo que las medidas de prevención, detección temprana y extinción sean fundamentales para mitigar este riesgo.

| N.1 Fuego |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [COM] Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| - [L]: Instalaciones |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo afecta a los siguientes activos :

| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| AS001  | Servidores Centrales                   | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
| HW000  | Servidores Dell PowerEdge             | Componentes clave utilizados para ejecutar aplicaciones críticas del bufete. |
| HW001  | Estación de Trabajo HP ZBook          | Equipos portátiles diseñados para tareas intensivas en diseño y análisis legal. |
| HW002  | PC de Escritorio Lenovo ThinkCentre   | Equipos de escritorio confiables ideales para el uso cotidiano de los empleados. |
| HW003  | Dispositivos de Almacenamiento Synology | Unidades de almacenamiento en red para la gestión segura de datos con capacidades escalables. |
| HW004  | Impresoras HP LaserJet                | Impresoras esenciales para la impresión eficiente de documentos legales. |
| HW005  | Enrutador Cisco Catalyst              | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad. |
| HW006  | Sistema de Videovigilancia Axis       | Sistema completo de videovigilancia con cámaras para la seguridad física del bufete. |
| HW007  | Escáner Epson WorkForce               | Escáner de alta velocidad para digitalizar documentos legales y mantener registros digitales. |
| HW008  | Teléfonos VoIP Grandstream            | Dispositivos de comunicación empresarial que ofrecen funciones avanzadas de telefonía IP. |
| HW009  | UPS APC Smart-UPS                    | Sistema de alimentación ininterrumpida para proteger contra cortes de energía y asegurar la continuidad de operaciones. |
| HW010  | Estación Docking para Portátiles      | Permite a las estaciones de trabajo portátiles conectarse fácilmente a periféricos de escritorio. |
| HW011  | Sistemas de Control de Acceso         | Dispositivos biométricos y de tarjetas para garantizar la seguridad en el acceso a áreas restringidas. |
| HW012  | Pizarras Interactivas SMART           | Herramientas colaborativas para presentaciones y discusiones legales interactivas. |
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |
| SI002  | Disco Duro Externo                   | Ofrece una solución portátil y conveniente para el respaldo de datos importantes, facilitando la transferencia y protección de información clave fuera de la red principal. |
| SI003  | Tarjeta de Memoria                   | Utilizada en dispositivos móviles y cámaras para almacenar y transferir datos. Aporta flexibilidad y movilidad a la captura y transporte de información relevante. |
| SI004  | Almacenamiento en la Nube            | Permite el acceso remoto y la colaboración en documentos desde cualquier ubicación, facilitando el intercambio de información entre miembros del bufete y garantizando su respaldo seguro. |
| SI005  | Disco Óptico (DVD)                   | Ideal para almacenar datos, proporciona una forma duradera y fácil de distribuir y respaldar información crítica, especialmente para archivar documentos legales. |
| SI006  | Unidad USB                           | Ofrece portabilidad y accesibilidad rápida a datos esenciales. Su capacidad de almacenamiento y facilidad de uso la convierten en una herramienta fundamental para el transporte seguro de información. |
| SI007  | Tarjeta Inteligente (Smart Card)     | Proporciona autenticación segura y control de acceso a sistemas críticos. Su uso protege la confidencialidad y garantiza que solo personal autorizado tenga acceso a información sensible. |
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. | Alta  | Media |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. | Media | -     |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

#### 3.2 Inundaciones
| N.2 Inundaciones |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [COM] Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| - [L]: Instalaciones |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Las inundaciones representan una seria amenaza para un Centro de Procesamiento de Datos (CPD) debido a la potencial destrucción de equipos críticos. La presencia de agua puede dañar irreversiblemente servidores, sistemas de almacenamiento y otros componentes, causando pérdida de datos y tiempo de inactividad prolongado. Las inundaciones pueden ser resultado de fugas, inundaciones naturales o problemas de las tuberías.

Este riesgo  afecta a los siguientes activos :

| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| AS001  | Servidores Centrales                   | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
| HW000  | Servidores Dell PowerEdge             | Componentes clave utilizados para ejecutar aplicaciones críticas del bufete. |
| HW001  | Estación de Trabajo HP ZBook          | Equipos portátiles diseñados para tareas intensivas en diseño y análisis legal. |
| HW002  | PC de Escritorio Lenovo ThinkCentre   | Equipos de escritorio confiables ideales para el uso cotidiano de los empleados. |
| HW003  | Dispositivos de Almacenamiento Synology | Unidades de almacenamiento en red para la gestión segura de datos con capacidades escalables. |
| HW004  | Impresoras HP LaserJet                | Impresoras esenciales para la impresión eficiente de documentos legales. |
| HW005  | Enrutador Cisco Catalyst              | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad. |
| HW006  | Sistema de Videovigilancia Axis       | Sistema completo de videovigilancia con cámaras para la seguridad física del bufete. |
| HW007  | Escáner Epson WorkForce               | Escáner de alta velocidad para digitalizar documentos legales y mantener registros digitales. |
| HW008  | Teléfonos VoIP Grandstream            | Dispositivos de comunicación empresarial que ofrecen funciones avanzadas de telefonía IP. |
| HW009  | UPS APC Smart-UPS                    | Sistema de alimentación ininterrumpida para proteger contra cortes de energía y asegurar la continuidad de operaciones. |
| HW010  | Estación Docking para Portátiles      | Permite a las estaciones de trabajo portátiles conectarse fácilmente a periféricos de escritorio. |
| HW011  | Sistemas de Control de Acceso         | Dispositivos biométricos y de tarjetas para garantizar la seguridad en el acceso a áreas restringidas. |
| HW012  | Pizarras Interactivas SMART           | Herramientas colaborativas para presentaciones y discusiones legales interactivas. |
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |
| SI002  | Disco Duro Externo                   | Ofrece una solución portátil y conveniente para el respaldo de datos importantes, facilitando la transferencia y protección de información clave fuera de la red principal. |
| SI003  | Tarjeta de Memoria                   | Utilizada en dispositivos móviles y cámaras para almacenar y transferir datos. Aporta flexibilidad y movilidad a la captura y transporte de información relevante. |
| SI004  | Almacenamiento en la Nube            | Permite el acceso remoto y la colaboración en documentos desde cualquier ubicación, facilitando el intercambio de información entre miembros del bufete y garantizando su respaldo seguro. |
| SI005  | Disco Óptico (DVD)                   | Ideal para almacenar datos, proporciona una forma duradera y fácil de distribuir y respaldar información crítica, especialmente para archivar documentos legales. |
| SI006  | Unidad USB                           | Ofrece portabilidad y accesibilidad rápida a datos esenciales. Su capacidad de almacenamiento y facilidad de uso la convierten en una herramienta fundamental para el transporte seguro de información. |
| SI007  | Tarjeta Inteligente (Smart Card)     | Proporciona autenticación segura y control de acceso a sistemas críticos. Su uso protege la confidencialidad y garantiza que solo personal autorizado tenga acceso a información sensible. |
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. | Alta  | Media |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. | Media | -     |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

### 3.2 [OI] De origen industrial
### 3.3 [NI] Errores y fallos no intencionados
### 3.4 [AI] Ataques intencionados
### 3.5 [AE] Amenazas del Entorno


Tabla completa ignorar

| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| AE001  | Archivo Digital de Casos                | Almacena información crítica de casos, indispensable para la práctica legal diaria. |
| AE002  | Sistema de Comunicaciones               | Facilita la comunicación interna y externa, siendo vital para la colaboración y la prestación de servicios. |
| AE003  | Base de datos de clientes               | Almacena información detallada sobre los clientes, incluyendo historial legal, preferencias y contactos. |
| AE004  | Sistema de gestión financiera           | Herramienta que facilita la gestión financiera del bufete, incluyendo facturación, ingresos y gastos. |
| AE005  | Plataforma de colaboración interna      | Espacio digital que permite la colaboración eficiente entre los miembros del bufete en documentos y proyectos. |
| AS001  | Servidores Centrales                   | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |
| AS002  | Red de Área Local (LAN)                | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos. |
| AS003  | Sistema de seguridad de red            | Implementación de firewalls, antivirus y otras medidas para salvaguardar la integridad de la red. |
| AS004  | Políticas de acceso y control          | Definición de políticas que regulan el acceso a la información y la administración de privilegios. |
| AS005  | Infraestructura de respaldo            | Sistemas y procedimientos para realizar copias de seguridad periódicas y garantizar la disponibilidad de datos. |
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
| KC001  | Claves de acceso a bases de datos      | Garantizan la seguridad de las bases de datos legales del bufete, evitando accesos no autorizados. |
| KC002  | Claves de correo electrónico           | Aseguran la confidencialidad de las comunicaciones por correo electrónico dentro del bufete, protegiendo la privacidad de la correspondencia legal. |
| KC003  | Claves de acceso a sistemas internos   | Utilizadas para acceder a sistemas internos que gestionan información crítica y legal, asegurando la autenticación de usuarios autorizados. |
| KC004  | Claves de cifrado de documentos        | Protegen la integridad y confidencialidad de documentos legales almacenados en sistemas digitales, evitando accesos no autorizados y manipulación no autorizada. |
| KC005  | Claves de firma digital                | Garantizan la autenticidad de documentos legales firmados digitalmente por el bufete, proporcionando una capa adicional de seguridad en transacciones electrónicas. |
| S001   | Intranet                              | Servicio de red interna para los empleados del bufete. |
| S002   | Exchange Server                       | Plataforma de correo electrónico propia que facilita la comunicación electrónica segura. |
| S003   | SFTP                                  | Intercambio seguro de archivos. |
| S004   | Active Directory (AD)                 | Servicio centralizado propio para gestionar identidades y accesos en entornos Windows. |
| S005   | Software ARP                          | Servicio que realiza el descubrimiento y mapeo de dispositivos en la red para gestionar altas, bajas y cambios en usuarios. |
| S006   | PKI - Infraestructura de clave pública | Gestión segura de certificados y criptografía de clave pública. |
| SW000  | Debian 12                             | Sistema operativo confiable y de código abierto. Proporciona una base segura y estable para todas las operaciones. |
| SW001  | Windows 11                            | Sistema operativo de Microsoft con una interfaz moderna y mejoras en seguridad y rendimiento. |
| SW002  | Clio Manage                           | Sistema de Gestión de Casos Legales. Facilita el seguimiento y gestión de casos legales. |
| SW003  | Westlaw                               | Herramientas de Investigación Legal. Proporciona acceso a bases de datos legales y recursos de investigación. |
| SW004  | Microsoft Teams                       | Plataforma de Colaboración. Mejora la colaboración interna y externa facilitando la comunicación y el intercambio de documentos. |
| SW005  | Clio Billing                          | Software de Facturación Legal. Gestiona la facturación de servicios legales. |
| SW006  | NetDocuments                          | Plataforma de Gestión Documental. Organiza y almacena documentos legales de manera segura. |
| SW007  | Lex Machina                           | Herramientas de Analítica Legal. Ofrece capacidades analíticas para evaluar tendencias legales. |
| SW008  | LexisNexis                            | Plataforma de Investigación Legal. Facilita la búsqueda y análisis de jurisprudencia y legislación. |
| SW009  | Ravel Law                             | Herramientas de Analítica Legal. Proporciona capacidades analíticas para evaluar tendencias legales. |
| SW010  | QuickBooks Legal                      | Software de Administración Financiera. Gestiona aspectos financieros y contabilidad del bufete. |
| SW011  | Zoom Meetings                         | Herramientas de Videoconferencia. Amplía las capacidades de comunicación remota. |
| SW012  | Varonis Data Security Platform        | Plataforma de Gestión de Privilegios. Controla y audita los accesos a información confidencial. |
| SW013  | Symantec Encryption                   | Sistemas de Cifrado de Comunicaciones. Asegura la privacidad de las comunicaciones. |
| HW000  | Servidores Dell PowerEdge             | Componentes clave utilizados para ejecutar aplicaciones críticas del bufete. |
| HW001  | Estación de Trabajo HP ZBook          | Equipos portátiles diseñados para tareas intensivas en diseño y análisis legal. |
| HW002  | PC de Escritorio Lenovo ThinkCentre   | Equipos de escritorio confiables ideales para el uso cotidiano de los empleados. |
| HW003  | Dispositivos de Almacenamiento Synology | Unidades de almacenamiento en red para la gestión segura de datos con capacidades escalables. |
| HW004  | Impresoras HP LaserJet                | Impresoras esenciales para la impresión eficiente de documentos legales. |
| HW005  | Enrutador Cisco Catalyst              | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad. |
| HW006  | Sistema de Videovigilancia Axis       | Sistema completo de videovigilancia con cámaras para la seguridad física del bufete. |
| HW007  | Escáner Epson WorkForce               | Escáner de alta velocidad para digitalizar documentos legales y mantener registros digitales. |
| HW008  | Teléfonos VoIP Grandstream            | Dispositivos de comunicación empresarial que ofrecen funciones avanzadas de telefonía IP. |
| HW009  | UPS APC Smart-UPS                    | Sistema de alimentación ininterrumpida para proteger contra cortes de energía y asegurar la continuidad de operaciones. |
| HW010  | Estación Docking para Portátiles      | Permite a las estaciones de trabajo portátiles conectarse fácilmente a periféricos de escritorio. |
| HW011  | Sistemas de Control de Acceso         | Dispositivos biométricos y de tarjetas para garantizar la seguridad en el acceso a áreas restringidas. |
| HW012  | Pizarras Interactivas SMART           | Herramientas colaborativas para presentaciones y discusiones legales interactivas. |
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |
| SI002  | Disco Duro Externo                   | Ofrece una solución portátil y conveniente para el respaldo de datos importantes, facilitando la transferencia y protección de información clave fuera de la red principal. |
| SI003  | Tarjeta de Memoria                   | Utilizada en dispositivos móviles y cámaras para almacenar y transferir datos. Aporta flexibilidad y movilidad a la captura y transporte de información relevante. |
| SI004  | Almacenamiento en la Nube            | Permite el acceso remoto y la colaboración en documentos desde cualquier ubicación, facilitando el intercambio de información entre miembros del bufete y garantizando su respaldo seguro. |
| SI005  | Disco Óptico (DVD)                   | Ideal para almacenar datos, proporciona una forma duradera y fácil de distribuir y respaldar información crítica, especialmente para archivar documentos legales. |
| SI006  | Unidad USB                           | Ofrece portabilidad y accesibilidad rápida a datos esenciales. Su capacidad de almacenamiento y facilidad de uso la convierten en una herramienta fundamental para el transporte seguro de información. |
| SI007  | Tarjeta Inteligente (Smart Card)     | Proporciona autenticación segura y control de acceso a sistemas críticos. Su uso protege la confidencialidad y garantiza que solo personal autorizado tenga acceso a información sensible. |
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. | Alta  | Media |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. | Media | -     |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

