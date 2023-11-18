#### 3.1.1 Fuego


| Código | Nombre                                  | Descripción                                            | D | I | C | Impacto |
|--------|-----------------------------------------|--------------------------------------------------------|---|---|---|---------|
| AS001  | Servidores Centrales                   | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |   |   |   |         |
| D001   | Casos legales en curso                 | Información detallada sobre los casos legales actuales, incluyendo clientes, detalles del caso y estado actual. | X |   | X | Alto    |
| D002   | Contratos y acuerdos                   | Documentación de contratos y acuerdos legales firmados con clientes y otras partes involucradas. | X |   | X | Medio   |
| D003   | Información confidencial del cliente   | Datos sensibles de los clientes, como información financiera y personal. | X | X | X | Muy Alto|
| D004   | Precedentes legales                    | Base de datos que contiene precedentes legales relevantes para casos en curso y futuros. | X |   | X | Alto    |
| D005   | Servicios Digitales                    | Se incluyen servicios tales como correo electrónico, almacenamiento de ficheros, y gestión de identidades. Estos servicios son fundamentales para la comunicación, colaboración y seguridad digital del bufete (Aquí abarca en tránsito y almacenados). | X | X | X | Muy Alto|





-- Deberías de hacer por cada RIESGO una tabla , te voy a dejar la tabla completa sin rellenar y vas copiando y pegando los activos que necesites y ty los valoras :) .  Si usas el VisualStudio puedes ver el resultado de la pagina usando CTRL + SHIFT + V si en la pagina de vista previa haces doble click en algún punto o texto te abre el archivo en ese punto exacto por si te das cuenta de algún error . 

Añade si quieres también al principio del apartado un poco explicando las tablas , en resumen las 3 columnas son el calculo del riesgo en concreto para cada activo  , mientas que la ultima Es el impacto que tendría a la empresa 

Creo que te va a resultar mas rápido y Comodo Ver en la tabla de identificación de amenazas a que "apartado" le afectan y copiarlos de esta tabla para crear una nueva , me refiero al tipo de activos de las tablas de mi apartado  :


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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   | X | X | Medio   |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   | X | X | Medio   |
| AS003  | Sistema de seguridad de red            | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control          | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo            | X | X | X | Muy Alto|
| D001   | Casos legales en curso                 | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                   | X | X | X | Alto    |
| D003   | Información confidencial del cliente   | X | X | X | Muy Alto|
| D004   | Precedentes legales                    | X | X | X | Alto    |
| D005   | Servicios Digitales                    | X | X | X | Muy Alto|
| KC001  | Claves de acceso a bases de datos      | X | X | X | Muy Alto|
| KC002  | Claves de correo electrónico           | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos   | X | X | X | Muy Alto|
| KC004  | Claves de cifrado de documentos        | X | X | X | Alto    |
| KC005  | Claves de firma digital                | X | X | X | Muy Alto|
| S001   | Intranet                              |   | X | X | Medio   |
| S002   | Exchange Server                       | X | X | X | Alto    |
| S003   | SFTP                                  | X | X | X | Muy Alto|
| S004   | Active Directory (AD)                 | X | X | X | Alto    |
| S005   | Software ARP                          | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública | X | X | X | Muy Alto|
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            | X | X | X | Alto    |
| SW002  | Clio Manage                           | X | X | X | Alto    |
| SW003  | Westlaw                               | X | X | X | Muy Alto|
| SW004  | Microsoft Teams                       | X | X | X | Alto    |
| SW005  | Clio Billing                          | X | X | X | Medio   |
| SW006  | NetDocuments                          | X | X | X | Muy Alto|
| SW007  | Lex Machina                           | X | X | X | Alto    |
| SW008  | LexisNexis                            | X | X | X | Muy Alto|
| SW009  | Ravel Law                             | X | X | X | Alto    |
| SW010  | QuickBooks Legal                      | X | X | X | Muy Alto|
| SW011  | Zoom Meetings                         | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform        | X | X | X | Alto    |
| SW013  | Symantec Encryption                   | X | X | X | Muy Alto|
| HW000  | Servidores Dell PowerEdge             | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook          | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre   | X | X | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst              | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis       | X | X | X | Muy Alto|
| HW007  | Escáner Epson WorkForce               | X | X | X | Medio   |
| HW008  | Teléfonos VoIP Grandstream            | X | X | X | Alto    |
| HW009  | UPS APC Smart-UPS                    | X | X | X | Muy Alto|
| HW010  | Estación Docking para Portátiles      |   |   |   |         |
| HW011  | Sistemas de Control de Acceso         |   |   |   |         |
| HW012  | Pizarras Interactivas SMART           |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| COM001 | Red de Invitados                      | X |   | X | Alto    |
| COM002 | Red 5G para Dispositivos Móviles      |   |   | X | Medio   |
| COM003 | Fibra Óptica                         | X | X | X | Muy Alto|
| COM004 | Red de Alta Seguridad Interna         | X |   | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)        |   | X | X | Alto    |
| COM006 | Red de Área Local (LAN)               |   | X | X | Medio   |
| COM007 | Red de Voz sobre IP (VoIP)           |   | X | X | Alto    |
| COM008 | Red Privada Virtual (VPN)             | X | X | X | Muy Alto|
| SI001  | Almacenamiento en Red (SAN)           | X |   | X | Alto    |
| SI002  | Disco Duro Externo                   | X |   | X | Medio   |
| SI003  | Tarjeta de Memoria                   | X |   | X | Bajo    |
| SI004  | Almacenamiento en la Nube            | X | X | X | Muy Alto|
| SI005  | Disco Óptico (DVD)                   | X |   | X | Bajo    |
| SI006  | Unidad USB                           | X |   | X | Medio   |
| SI007  | Tarjeta Inteligente (Smart Card)     | X | X | X | Alto    |
| AUX001 | Fuentes de Alimentación              |   |   |   |         |
| AUX002 | Sistemas de Alimentación Ininterrumpida |   |   |   |         |
| AUX003 | Equipos de Climatización              |   |   |   |         |
| AUX004 | Cableado                 |   |   |   |         |
| AUX005 | Mobiliario: Armarios, etc.|   |   |   |         |
| L001   | Edificio Principal |   |   |   |         |
| L002   | Departamento Legal |   |   |   |         |
| L003   | Centro Tecnológico |   |   |   |         |
| L004   | Sala de Servidores |   |   |   |         |