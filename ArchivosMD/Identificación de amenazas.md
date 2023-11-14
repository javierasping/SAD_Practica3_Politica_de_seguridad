## 3 Identificación de amenazas
<!--   PG 27 https://www.pilar-tools.com/doc/magerit/v2/cat-es-v11.pdf -->

En esta sección, nos enfocamos en la identificación exhaustiva de todas las amenazas potenciales que podrían representar un riesgo para nuestros recursos. Además, evaluamos las diversas dimensiones en las que estas amenazas pueden impactar. Para lograr este objetivo, creamos una ficha detallada para cada amenaza, en la cual documentamos los tipos de activos que podrían verse afectados y las dimensiones en las que dicha amenaza podría tener consecuencias.

A través de este proceso, también revisamos nuestro inventario de activos en busca de aquellos que cumplen con las condiciones relacionadas con cada amenaza específica. Esta revisión minuciosa nos permite comprender mejor cómo nuestras valiosas propiedades y recursos podrían estar expuestos a diversos riesgos y peligros potenciales. Al identificar y documentar estas amenazas de manera precisa, estamos en una posición más sólida para tomar medidas preventivas y desarrollar estrategias de mitigación efectivas para proteger nuestros activos y garantizar la continuidad de nuestras operaciones.

### 3.1 [DN] Desastres naturales
Los desastres naturales representan una categoría crítica de amenazas que enfrentan las infraestructuras y entornos de procesamiento de datos. Estos eventos, originados por la naturaleza, abarcan una amplia gama de fenómenos, desde terremotos y inundaciones hasta incendios forestales y tormentas, con el potencial de causar impactos devastadores en la infraestructura tecnológica.

La vulnerabilidad de los Centros de Procesamiento de Datos (CPDs) frente a estos desastres radica en la posibilidad de interrupción o pérdida total de los servicios que proveen, lo que incluye la infraestructura física y lógica esencial para el funcionamiento de sistemas, almacenamiento de datos y comunicación.

#### 3.1.1 Fuego

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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

#### 3.1.2 Inundaciones
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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

### 3.2 [OI] De origen industrial

#### 3.2.1 Contaminación mecánica 
| I.1 Contaminación mecánica  |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [COM] Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |


#### 3.2.2 Avería de origen físico o lógico
Los fallos en los equipos o programas pueden tener su origen en defectos intrínsecos o surgir durante la operación del sistema. En entornos con sistemas especializados, la distinción entre fallos físicos o lógicos a menudo se torna borrosa, dificultando la identificación del origen del fallo. Sin embargo, en términos de las consecuencias resultantes, esta distinción suele carecer de relevancia práctica. Estos fallos representan una amenaza a la integridad y la continuidad de las operaciones.

| I.2 Avería de origen físico o lógico  |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [SW] aplicaciones (software) |
| - [COM] Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |

#### 3.2.3 Corte del suministro eléctrico
El corte del suministro eléctrico representa una interrupción en la alimentación energética necesaria para el funcionamiento de los sistemas informáticos. Esta situación puede originarse por diversas razones, desde problemas en la red eléctrica hasta fallos internos en las instalaciones. Los cortes de energía plantean un riesgo crítico, ya que pueden provocar la pérdida de datos, interrumpir operaciones en curso y, en situaciones extremas, dañar el hardware o software sensible al apagarse repentinamente. 

| I.3 Corte del suministro eléctrico  |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [SW] aplicaciones (software) |
| - [COM] Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
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
| AUX001 | Fuentes de Alimentación              | Proporcionan energía eléctrica estable y confiable para garantizar el funcionamiento continuo de los equipos informáticos y de comunicación, mitigando riesgos asociados a cortes de energía. |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Ofrecen respaldo eléctrico temporal para permitir un cierre seguro de sistemas en caso de interrupciones repentinas, protegiendo contra pérdida de datos y daños en equipos sensibles. |
| AUX003 | Equipos de Climatización              | Mantienen las condiciones ambientales óptimas en salas de servidores y centros de datos para prevenir sobrecalentamientos, garantizando el rendimiento y la vida útil de los equipos. |
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |

#### 3.2.4 Degradación de los soportes de almacenamiento de la información
El corte del suministro eléctrico representa una interrupción en la alimentación energética necesaria para el funcionamiento de los sistemas informáticos. Esta situación puede originarse por diversas razones, desde problemas en la red eléctrica hasta fallos internos en las instalaciones. Los cortes de energía plantean un riesgo crítico, ya que pueden provocar la pérdida de datos, interrumpir operaciones en curso y, en situaciones extremas, dañar el hardware o software sensible al apagarse repentinamente. 

| I.3 Degradación de los soportes de almacenamiento de la información  |
| --- |
| **Tipos de Activos:** |
| - [Media]: Soportes de información |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |
| SI002  | Disco Duro Externo                   | Ofrece una solución portátil y conveniente para el respaldo de datos importantes, facilitando la transferencia y protección de información clave fuera de la red principal. |
| SI003  | Tarjeta de Memoria                   | Utilizada en dispositivos móviles y cámaras para almacenar y transferir datos. Aporta flexibilidad y movilidad a la captura y transporte de información relevante. |
| SI005  | Disco Óptico (DVD)                   | Ideal para almacenar datos, proporciona una forma duradera y fácil de distribuir y respaldar información crítica, especialmente para archivar documentos legales. |
| SI006  | Unidad USB                           | Ofrece portabilidad y accesibilidad rápida a datos esenciales. Su capacidad de almacenamiento y facilidad de uso la convierten en una herramienta fundamental para el transporte seguro de información. |
| SI007  | Tarjeta Inteligente (Smart Card)     | Proporciona autenticación segura y control de acceso a sistemas críticos. Su uso protege la confidencialidad y garantiza que solo personal autorizado tenga acceso a información sensible. |

#### 3.2.4  Averías en la Electrónica de Red (Switches y Routers)
La amenaza de fallo en los servicios de comunicación representa un riesgo significativo en entornos tecnológicos, poniendo en peligro la conectividad, colaboración y flujo de información crítica. Estos fallos pueden surgir por diversos motivos, desde interrupciones en la red hasta problemas en los servidores, generando la pérdida momentánea o prolongada de la capacidad de comunicarse y compartir datos.

| I.4  Averías en la Electrónica de Red (Switches y Routers)  |
| --- |
| **Tipos de Activos:** |
| - [COM] Redes de comunicaciones |
| **Dimensiones:** |
| 1. [D] disponibilidad |

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| HW005  | Enrutador Cisco Catalyst              | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad. |
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |







### 3.3 [NI] Errores y fallos no intencionados

Los errores y fallos no intencionados representan una categoría de riesgos inherentes en entornos tecnológicos. Estos pueden manifestarse como fallas inesperadas en hardware, software o en el personal, resultando en problemas que pueden afectar la integridad, disponibilidad o confidencialidad de la información. Estos incidentes, a menudo involuntarios, pueden surgir por múltiples causas, desde simples equivocaciones humanas hasta defectos en el diseño o implementación de sistemas.

#### 3.3.1 Errores de los usuarios 

Los errores de los usuarios, comunes en entornos tecnológicos, representan un riesgo sustancial en la seguridad y eficiencia de las operaciones. Estos errores pueden variar desde acciones no intencionadas hasta malas prácticas al utilizar sistemas, programas o servicios, pudiendo desencadenar brechas de seguridad, pérdida de datos y fallas en el funcionamiento general de los sistemas.

| NI.1  Errores de los usuarios   |
| --- |
| **Tipos de Activos:** |
| - [COM] Redes de comunicaciones |
| - [SW] aplicaciones (software) |
| - [D] Datos|
| **Dimensiones:** |
| 1. [D] disponibilidad |
| 2. [I] integridad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| HW005  | Enrutador Cisco Catalyst              | Enrutador utilizado para la conectividad de red y la implementación de medidas de seguridad. |
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
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


#### 3.3.2 Errores del administrador
Los errores del administrador, aunque menos comunes, pueden ser devastadores para la estabilidad y seguridad de un sistema. Incluyen acciones inadecuadas en la configuración, actualización o mantenimiento de sistemas, redes o bases de datos. Desde omisiones hasta configuraciones erróneas, estos errores pueden resultar en interrupciones de servicio, exposición de datos confidenciales o incluso la inutilización de sistemas críticos. 

| NI.2  Errores de los usuarios   |
| --- |
| **Tipos de Activos:** |
| - [S] Servicios|
| - [D] Datos / información|
| - [SW] Aplicaciones (software)|
| - [HW] Equipos informáticos (hardware)|
| - [COM] Redes de comunicaciones |
| **Dimensiones:** |
| 1. [D] Disponibilidad |
| 2. [I] Integridad|
| 3. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |



#### 3.3.3 Errores de configuración 
Los errores del administrador, aunque menos comunes, pueden ser devastadores para la estabilidad y seguridad de un sistema. Incluyen acciones inadecuadas en la configuración, actualización o mantenimiento de sistemas, redes o bases de datos. Desde omisiones hasta configuraciones erróneas, estos errores pueden resultar en interrupciones de servicio, exposición de datos confidenciales o incluso la inutilización de sistemas críticos. 

| NI.3  Errores de configuración    |
| --- |
| **Tipos de Activos:** |
| - [S] Servicios|
| - [D] Datos / información|
| - [SW] Aplicaciones (software)|
| - [HW] Equipos informáticos (hardware)|
| - [COM] Redes de comunicaciones |
| **Dimensiones:** |
| 1. [D] Disponibilidad |
| 2. [I] Integridad|
| 3. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |

#### 3.3.4 Difusión de software dañino
La difusión de software dañino se refiere a la propagación intencionada o accidental de programas malignos, como virus, gusanos o troyanos. Estos programas son diseñados para infiltrarse en sistemas, comprometer datos o interrumpir operaciones normales. La difusión de este tipo de software puede ocurrir a través de correos electrónicos, descargas no autorizadas, sitios web comprometidos o dispositivos de almacenamiento infectados.

| NI.4  Difusión de software dañino |
| --- |
| **Tipos de Activos:** |
| - [SW] Aplicaciones (software)|

| **Dimensiones:** |
| 1. [D] Disponibilidad |
| 2. [I] Integridad|
| 3. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
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


#### 3.3.5 Fugas de información
Las Fugas de información de información constituyen la divulgación no autorizada de datos confidenciales o sensibles de una organización. Pueden ocurrir debido a vulnerabilidades en la seguridad, errores humanos, actividades maliciosas o fallas técnicas. Estos escapes representan una amenaza significativa para la privacidad y la integridad de la información.

| NI.5 Escapes de información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| - [SW] Aplicaciones (software)|
| - [COM] Redes de comunicaciones |
| **Dimensiones:** |
| 1. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
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
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |

#### 3.3.6 Alteración de la información
La alteración de la información implica la modificación indebida o no autorizada de los datos, lo que puede comprometer la integridad y veracidad de la información. 

| NI.6 Alteración de la información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| **Dimensiones:** |
| 1. [I] Integridad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |

#### 3.3.7 Destrucción de la información
La destrucción de información representa la pérdida irreversible de datos valiosos. Puede ocurrir por fallas técnicas, ataques maliciosos o errores humanos. Esta amenaza puede comprometer la disponibilidad y confidencialidad de datos esenciales para las operaciones, la toma de decisiones y la continuidad del negocio. 

| NI.7 Destrucción de la información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| **Dimensiones:** |
| 1. [D] Disponibilidad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |

### 3.4 [AI] Ataques intencionados
Estos ataques, perpetrados de forma deliberada por individuos o grupos, buscan vulnerar la integridad, confidencialidad o disponibilidad de los activos de un CPD. Pueden provenir de fuentes externas o internas, involucrando la manipulación, destrucción o robo de información, así como la interrupción de los servicios esenciales.

#### 3.4.1 Acceso no autorizados al CPD
El acceso no autorizado a un Centro de Procesamiento de Datos (CPD) es una amenaza que pone en riesgo la integridad, confidencialidad y disponibilidad de los activos críticos. Este riesgo puede manifestarse a través de intrusiones no permitidas, donde personas no autorizadas intentan o logran ingresar a la infraestructura del CPD. Esto puede resultar en la manipulación, robo o alteración de datos, así como en la interrupción de los servicios clave. 


| AI.1 Acceso no autorizados al CPD |
| --- |
| **Tipos de Activos:** |
| - [HW]: Equipos informáticos (hardware) |
| - [SW]: Aplicaciones (software) |
| - [COM]: Redes de comunicaciones |
| - [Media]: Soportes de información |
| - [Aux]: Equipamiento auxiliar |
| **Dimensiones:** |
| 1. [D] Disponibilidad |
| 2. [I] Integridad|
| 3. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :

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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |



#### 3.4.2 Ransomware
El ransomware es una forma insidiosa de software malicioso que se infiltra en sistemas informáticos para cifrar archivos o restringir el acceso a los datos, exigiendo un rescate a cambio de su liberación. Esto genera un impacto grave en la integridad y disponibilidad de los datos, pudiendo paralizar sistemas completos y, en muchos casos, comprometer la confidencialidad de la información. El impacto es doble, ya que no solo afecta a los datos y sistemas, sino que también puede influir en la reputación y la confianza de una organización.

| AI.2 Ransomware |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| - [SW] Aplicaciones (software)|
| **Dimensiones:** |
| 1. [D] Disponibilidad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
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
| AE001  | Archivo Digital de Casos                | Almacena información crítica de casos, indispensable para la práctica legal diaria. |
| AE002  | Sistema de Comunicaciones               | Facilita la comunicación interna y externa, siendo vital para la colaboración y la prestación de servicios. |
| AE003  | Base de datos de clientes               | Almacena información detallada sobre los clientes, incluyendo historial legal, preferencias y contactos. |
| AE004  | Sistema de gestión financiera           | Herramienta que facilita la gestión financiera del bufete, incluyendo facturación, ingresos y gastos. |
| AE005  | Plataforma de colaboración interna      | Espacio digital que permite la colaboración eficiente entre los miembros del bufete en documentos y proyectos. |


#### 3.4.3 Conflicto Armado
Los conflictos armados plantean riesgos significativos para la infraestructura crítica y los centros de datos, ya que pueden provocar daños físicos, interrupciones masivas y pérdidas de información vital. Estos eventos pueden afectar la disponibilidad, integridad y confidencialidad de los datos, interrumpiendo la operatividad y provocando un impacto profundo en la continuidad del negocio.

| AI.3 Conflicto Armado |
| --- |
| **Tipos de Activos:** |
| - [I] Activos Esenciales - Activos críticos para la operación del bufete|
| - [D] Datos / Información - Casos legales en curso|
| - [K] Claves Criptográficas - Claves de acceso a información sensible|
| - [S] Servicios - Servicios de investigación legal|
| - [SW] Software - Aplicaciones informáticas - Sistema de gestión de casos|
| - [HW] Equipamiento informático (hardware) - Computadoras y servidores|
| - [COM] Redes de comunicaciones - Red interna del bufete|
| - [Media] Soportes de información - Copias de seguridad en la nube|
| - [AUX] Equipamiento auxiliar - Sistemas de seguridad física|
| - [L] Instalaciones|
| **Dimensiones:** |
| 1. [D] Disponibilidad|
| 2. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               |

#### 3.4.4 Phishing
El phishing es una forma de ciberataque que implica engañar a las personas para obtener información confidencial, como contraseñas, detalles de tarjetas de crédito u otra información sensible. Los atacantes suelen suplantar identidades o entidades confiables, enviando correos electrónicos o mensajes diseñados para parecer legítimos.

| AI.4 Phishing |
| --- |
| **Tipos de Activos:** |
| - [P] Personal |


| **Dimensiones:** |
| 1. [C] Confidencialidad|

Este riesgo podría llegar a afectar a los siguientes activos :

| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
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


#### 3.4.5 Robo de dispositivos móviles 

El robo de dispositivos móviles es el acto de sustracción ilegal de teléfonos inteligentes, tabletas u otros dispositivos portátiles. Este incidente puede provocar la pérdida de información confidencial o sensible, exponiendo datos personales, financieros o laborales a personas no autorizadas.
Esta amenaza incluye cualquier robo de material es propiedad de la empresa .
| AI.5 Robo de dispositivos |
| --- |
| **Tipos de Activos:** |
| - [P] Personal |
| - [HW] Hardware|
| **Dimensiones:** |
| 1. [C] Confidencialidad|
| 2. [D] Disponibilidad  |

Este riesgo  afecta a los siguientes activos :

| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 



#### 3.4.6 Compromiso de credenciales

La amenaza de comprometer las credenciales de acceso representa un riesgo significativo para la seguridad de una organización. La pérdida o compromiso de credenciales puede abrir la puerta a accesos no autorizados, exponiendo información confidencial y poniendo en peligro la integridad de los sistemas. Este riesgo no solo implica la posibilidad de intrusiones externas, sino también amenazas internas potenciales si las credenciales caen en manos equivocadas. La introducción no autorizada a sistemas y datos sensibles puede tener consecuencias graves, desde la pérdida de la confianza del cliente hasta impactos financieros significativos.

| AI.6 Compromiso de credenciales |
| --- |
| **Tipos de Activos:** |
| - [I] Activos Esenciales - Activos críticos para la operación del bufete|
| - [D] Datos / Información - Casos legales en curso|
| - [K] Claves Criptográficas - Claves de acceso a información sensible|
| - [S] Servicios - Servicios de investigación legal|
| - [SW] Software - Aplicaciones informáticas - Sistema de gestión de casos|
| - [COM] Redes de comunicaciones - Red interna del bufete|
| - [Media] Soportes de información - Copias de seguridad en la nube|
| **Dimensiones:** |
| 1. [C] Confidencialidad|

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
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |

#### 3.4.7 Ataques de denegación de servicio SYN Flood

Los ataques de denegación de servicio, y en particular el tipo conocido como SYN Flood, representan una seria amenaza para la disponibilidad y estabilidad de los sistemas informáticos. Este tipo de ataque busca abrumar un servidor con un volumen masivo de solicitudes de conexión TCP SYN, agotando los recursos y haciendo que la entidad objetivo sea incapaz de atender las solicitudes legítimas. El SYN Flood puede paralizar servicios críticos, afectar la experiencia del usuario y, en casos extremos, causar interrupciones prolongadas en la operatividad de la red.

| AI.7 Phishing |
| --- |
| **Tipos de Activos:** |
| - [I] Activos Esenciales - Activos críticos para la operación del bufete|
| - [D] Datos / Información - Casos legales en curso|
| - [S] Servicios - Servicios de investigación legal|
| - [SW] Software - Aplicaciones informáticas - Sistema de gestión de casos|
| - [COM] Redes de comunicaciones - Red interna del bufete|
| **Dimensiones:** |
| 1. [C] Confidencialidad|


Este riesgo  afecta a los siguientes activos :

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
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |




#### 3.4.8 Vulnerabilidades de las aplicaciones

Las vulnerabilidades en las aplicaciones representan una puerta de entrada crítica para posibles amenazas cibernéticas, exponiendo sistemas a riesgos significativos de explotación. Estas debilidades pueden manifestarse en diversas formas, como fallos en la gestión de sesiones, validación insuficiente de datos de entrada, o incluso defectos en el diseño arquitectónico. La explotación exitosa de estas vulnerabilidades podría permitir a los atacantes el acceso no autorizado, la manipulación de datos o la interrupción de servicios esenciales.

| AI.7 Vulnerabilidades de las aplicaciones |
| --- |
| **Tipos de Activos:** |
| - [I] Activos Esenciales - Activos críticos para la operación del bufete|
| - [D] Datos / Información - Casos legales en curso|
| - [S] Servicios - Servicios de investigación legal|
| - [SW] Software - Aplicaciones informáticas - Sistema de gestión de casos|
| - [COM] Redes de comunicaciones - Red interna del bufete|
| **Dimensiones:** |
| 1. [D] Disponibilidad|
| 2. [I] Integridad|
| 3. [C] Confidencialidad|


Este riesgo  afecta a los siguientes activos :

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
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM002 | Red 5G para Dispositivos Móviles      | Brinda conectividad ultrarrápida y estable para dispositivos móviles utilizados por empleados y clientes. |
| COM003 | Fibra Óptica                         | Conexión de banda ancha a Internet mediante la última tecnología de fibra óptica para transmisión de datos a altas velocidades. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |
| SI001  | Almacenamiento en Red (SAN)           | Proporciona un entorno de almacenamiento compartido que mejora la eficiencia y velocidad en el acceso a datos, crucial para operaciones que requieren alto rendimiento. |

#### 3.3.9 Fugas de información en la nube
Las Fugas de información en la nube de información constituyen la divulgación no autorizada de datos confidenciales o sensibles de una organización. Pueden ocurrir debido a vulnerabilidades en la seguridad, errores humanos, actividades maliciosas o fallas técnicas. Estos escapes representan una amenaza significativa para la privacidad y la integridad de la información.

| AI.9 Escapes de información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| - [SW] Aplicaciones (software)|
| - [COM] Redes de comunicaciones |
| **Dimensiones:** |
| 1. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :


| Código | Nombre                                  | Descripción                                            |
|--------|-----------------------------------------|--------------------------------------------------------|
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. |
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). |
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
| COM001 | Red de Invitados                      | Permite a visitantes acceder a Internet mientras mantiene separada la red interna, evitando riesgos de seguridad. |
| COM004 | Red de Alta Seguridad Interna         | Configuración especializada para la transmisión segura de información crítica y confidencial dentro del bufete. |
| COM005 | Red Inalámbrica Segura (WPA3)        | Proporciona conectividad sin cables con los más altos estándares de seguridad para dispositivos internos. |
| COM006 | Red de Área Local (LAN)               | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos dentro del bufete. |
| COM007 | Red de Voz sobre IP (VoIP)           | Integra servicios de voz en la red, facilitando la comunicación telefónica interna y externa de manera eficiente. |
| COM008 | Red Privada Virtual (VPN)             | Permite a empleados acceder de manera segura a la red interna desde ubicaciones externas, garantizando la confidencialidad de la información. |





<!-- Plantilla -->
<!-- 
| AI.3 Phishing |
| --- |
| **Tipos de Activos:** |
| - [I] Activos Esenciales - Activos críticos para la operación del bufete|
| - [D] Datos / Información - Casos legales en curso|
| - [K] Claves Criptográficas - Claves de acceso a información sensible|
| - [S] Servicios - Servicios de investigación legal|
| - [SW] Software - Aplicaciones informáticas - Sistema de gestión de casos|
| - [HW] Equipamiento informático (hardware) - Computadoras y servidores|
| - [COM] Redes de comunicaciones - Red interna del bufete|
| - [Media] Soportes de información - Copias de seguridad en la nube|
| - [AUX] Equipamiento auxiliar - Sistemas de seguridad física|
| - [L] Instalaciones|
| **Dimensiones:** |
| 1. [D] Disponibilidad|
| 2. [C] Confidencialidad|

Este riesgo  afecta a los siguientes activos :

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
| HW013  | Switches Cisco Catalyst 2960              | Equipos de red para la gestión eficiente del tráfico y la conectividad en la infraestructura del bufete. |
| HW014  | iPhone 13 Pro Max                        | Teléfono móvil para la comunicación y acceso a aplicaciones empresariales.                        | 
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
| AUX004 | Cableado                 | Infraestructura esencial que conecta y permite la comunicación entre dispositivos. Un diseño eficiente y seguro de cableado contribuye a la integridad y estabilidad de la red. |
| AUX005 | Mobiliario: Armarios, etc.| Proporciona almacenamiento seguro y organizado para equipos, documentos y otros elementos esenciales, contribuyendo a la eficiencia y seguridad en la gestión del espacio de trabajo. |
| L001   | Edificio Principal | Moderno edificio de dos plantas ubicado en el corazón de Madrid, alberga las oficinas y salas de reuniones de los abogados, así como los servidores y equipos de TI. |
| L002   | Departamento Legal | Espacio en la primera planta dedicado a los abogados y profesionales legales, proporcionando un entorno adecuado para la prestación de servicios legales excepcionales. |
| L003   | Centro Tecnológico | Segunda planta destinada a servidores y al equipo de más de 20 profesionales de TI, garantizando la infraestructura tecnológica necesaria para casos legales digitales.   |
| L004   | Sala de Servidores | Espacio dedicado en la segunda planta para alojar servidores críticos que respaldan la infraestructura informática y la gestión de casos legales digitales.               | -->