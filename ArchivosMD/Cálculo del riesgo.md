
 Cada columna representa un aspecto importante en la evaluación de riesgos:

    Código: Es un identificador único para cada riesgo. Sirve para referenciar y rastrear el riesgo fácilmente en la documentación y discusiones.

    Nombre: Describe el riesgo de forma breve pero clara. Por ejemplo, "Ataque de phishing a empleados" o "Fallo de software en el servidor principal".

    D (Disponibilidad): Evalúa cómo el riesgo afecta la disponibilidad de los sistemas o servicios. Un valor alto indica que el riesgo puede causar una interrupción significativa.

    I (Integridad): Mide el potencial del riesgo para comprometer la integridad de los datos o sistemas, es decir, la posibilidad de que la información sea alterada o dañada.

    C (Confidencialidad): Considera cómo el riesgo podría afectar la confidencialidad de la información, es decir, si podría exponer datos sensibles a personas no autorizadas.

    Impacto: Es una evaluación general del daño potencial que el riesgo podría causar, teniendo en cuenta los factores de Disponibilidad, Integridad y Confidencialidad.

Esta tabla ayuda a tener una visión clara y estructurada de los diferentes riesgos en un plan de ciberseguridad, facilitando su análisis y la toma de decisiones sobre cómo manejarlos.

 considerando el impacto de un incendio (fuego) en los diferentes activos de un bufete de abogados, centrado principalmente en la Disponibilidad (D), ya que es la dimensión que más afecta el fuego. La Integridad (I) y la Confidencialidad (C) se verán afectadas en menor medida en la mayoría de los casos, a excepción de aquellos activos donde la destrucción física conlleve a la pérdida de información crítica.


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X |   |   | Alto    |
| AE002  | Sistema de Comunicaciones               | X |   |   | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X |   |   | Alto    |
| AE005  | Plataforma de colaboración interna      | X |   |   | Alto    |
| AS001  | Servidores Centrales                    | X | X |   | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X |   |   | Medio   |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Muy Alto|
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Alto    |
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X | X | X | Muy Alto|
| KC001  | Claves de acceso a bases de datos       | X | X | X | Muy Alto|
| KC002  | Claves de correo electrónico            | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X | X | X | Muy Alto|
| KC004  | Claves de cifrado de documentos         | X | X | X | Alto    |
| KC005  | Claves de firma digital                 | X | X | X | Muy Alto|
| S001   | Intranet                                | X |   |   | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Muy Alto|
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Muy Alto|
| SW000  | Debian 12                               |   |   |   |         |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Muy Alto|
| SW004  | Microsoft Teams                         | X | X | X | Alto    |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Muy Alto|
| SW007  | Lex Machina                             | X | X | X | Alto    |
| SW008  | LexisNexis                              | X | X | X | Muy Alto|
| SW009  | Ravel Law                               | X | X | X | Alto    |
| SW010  | QuickBooks Legal                        | X | X | X | Muy Alto|
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Muy Alto|
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X | X | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X | X | X | Muy Alto|
| HW007  | Escáner Epson WorkForce                 | X | X | X | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X | X | X | Alto    |
| HW009  | UPS APC Smart-UPS                       | X | X | X | Muy Alto|
| HW010  | Estación Docking para Portátiles        |   |   |   |         |
| HW011  | Sistemas de Control de Acceso           |   |   |   |         |
| HW012  | Pizarras Interactivas SMART             |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960            |   |   |   |         |
| HW014  | iPhone 13 Pro Max                       |   |   |   |         |
| COM001 | Red de Invitados                        | X |   | X | Alto    |
| COM002 | Red 5G para Dispositivos Móviles        |   |   | X | Medio   |
| COM003 | Fibra Óptica                           | X | X | X | Muy Alto|
| COM004 | Red de Alta Seguridad Interna           | X |   | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          |   | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                 |   | X | X | Medio   |
| COM007 | Red de Voz sobre IP (VoIP)             |   | X | X | Alto    |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Muy Alto|
| SI001  | Almacenamiento en Red (SAN)             | X |   | X | Alto    |
| SI002  | Disco Duro Externo                      | X |   | X | Medio   |
| SI003  | Tarjeta de Memoria                      | X |   | X | Bajo    |
| SI004  | Almacenamiento en la Nube               | X | X | X | Muy Alto|
| SI005  | Disco Óptico (DVD)                      | X |   | X | Bajo    |
| SI006  | Unidad USB                              | X |   | X | Medio   |
| SI007  | Tarjeta Inteligente (Smart Card)        | X | X | X | Alto    |
| AUX001 | Fuentes de Alimentación                 |   |   |   |         |
| AUX002 | Sistemas de Alimentación Ininterrumpida |   |   |   |         |
| AUX003 | Equipos de Climatización                |   |   |   |         |
| AUX004 | Cableado                                |   |   |   |         |
| AUX005 | Mobiliario: Armarios, etc.              |   |   |   |         |
| L001   | Edificio Principal                      |   |   |   |         |
| L002   | Departamento Legal                      |   |   |   |         |
| L003   | Centro Tecnológico                      |   |   |   |         |
| L004   | Sala de Servidores                      |   |   |   |         |





| N.2 Inundaciones |

esta tabla considerando el impacto de las inundaciones en los distintos activos de un bufete de abogados, nos centraremos principalmente en la Disponibilidad (D), ya que las inundaciones pueden hacer que los equipos y las instalaciones no estén operativos. La Integridad (I) y la Confidencialidad (C) se verán afectadas en algunos casos donde la destrucción física o el daño conlleven a la pérdida o exposición de información sensible.


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AS001  | Servidores Centrales                    | X | X |   | Muy Alto|
| D001   | Casos legales en curso                  | X | X |   | Alto    |
| D002   | Contratos y acuerdos                    | X | X |   | Alto    |
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X |   | Medio   |
| D005   | Servicios Digitales                     | X |   |   | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X |   | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X |   |   | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   |   | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X |   | Alto    |
| HW004  | Impresoras HP LaserJet                  | X |   |   | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X |   |   | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X |   |   | Medio   |
| HW007  | Escáner Epson WorkForce                 | X |   |   | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X |   |   | Medio   |
| HW009  | UPS APC Smart-UPS                       | X |   |   | Alto    |
| HW010  | Estación Docking para Portátiles        | X |   |   | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X |   |   | Medio   |
| HW012  | Pizarras Interactivas SMART             | X |   |   | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X |   |   | Medio   |
| HW014  | iPhone 13 Pro Max                       | X |   |   | Bajo    |
| COM001 | Red de Invitados                        | X |   |   | Alto    |
| COM002 | Red 5G para Dispositivos Móviles        | X |   |   | Medio   |
| COM003 | Fibra Óptica                            | X |   |   | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X |   |   | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           | X |   |   | Medio   |
| COM006 | Red de Área Local (LAN)                 | X |   |   | Medio   |
| COM007 | Red de Voz sobre IP (VoIP)              | X |   |   | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X |   |   | Alto    |
| SI001  | Almacenamiento en Red (SAN)             | X | X |   | Alto    |
| SI002  | Disco Duro Externo                      | X |   |   | Medio   |
| SI003  | Tarjeta de Memoria                      | X |   |   | Bajo    |
| SI004  | Almacenamiento en la Nube               |   |   |   | Bajo    |
| SI005  | Disco Óptico (DVD)                      | X |   |   | Bajo    |
| SI006  | Unidad USB                              | X |   |   | Medio   |
| SI007  | Tarjeta Inteligente (Smart Card)        | X | X |   | Medio   |
| AUX001 | Fuentes de Alimentación                 | X |   |   | Medio   |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X |   |   | Alto    |
| AUX003 | Equipos de Climatización                | X |   |   | Medio   |
| AUX004 | Cableado                                | X |   |   | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              | X |   |   | Bajo    |
| L001   | Edificio Principal                      | X |   |   | Muy Alto|
| L002   | Departamento Legal                      | X |   |   | Alto    |
| L003   | Centro Tecnológico                      | X |   |   | Alto    |
| L004   | Sala de Servidores                      | X | X |   | Muy Alto|



#### 3.2.1 Contaminación mecánica 
| I.1 Contaminación mecánica  |
a contaminación mecánica puede afectar a los activos de un bufete de abogados principalmente en términos de Disponibilidad (D), ya que este tipo de contaminación podría dañar físicamente los equipos o impedir su funcionamiento normal. En esta situación, la Integridad (I) y la Confidencialidad (C) generalmente no se ven afectadas a menos que el daño físico conduzca a la pérdida de datos.




| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| HW000  | Servidores Dell PowerEdge               | X |   |   | Alto    |
| HW001  | Estación de Trabajo HP ZBook            | X |   |   | Medio   |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   |   | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X |   |   | Alto    |
| HW004  | Impresoras HP LaserJet                  | X |   |   | Bajo    |
| HW005  | Enrutador Cisco Catalyst                | X |   |   | Medio   |
| HW006  | Sistema de Videovigilancia Axis         | X |   |   | Medio   |
| HW007  | Escáner Epson WorkForce                 | X |   |   | Bajo    |
| HW008  | Teléfonos VoIP Grandstream              | X |   |   | Bajo    |
| HW009  | UPS APC Smart-UPS                       | X |   |   | Medio   |
| HW010  | Estación Docking para Portátiles        | X |   |   | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X |   |   | Medio   |
| HW012  | Pizarras Interactivas SMART             | X |   |   | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X |   |   | Medio   |
| HW014  | iPhone 13 Pro Max                       | X |   |   | Bajo    |
| COM001 | Red de Invitados                        | X |   |   | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X |   |   | Bajo    |
| COM003 | Fibra Óptica                            | X |   |   | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X |   |   | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           | X |   |   | Medio   |
| COM006 | Red de Área Local (LAN)                 | X |   |   | Medio   |
| COM007 | Red de Voz sobre IP (VoIP)              | X |   |   | Bajo    |
| COM008 | Red Privada Virtual (VPN)               | X |   |   | Medio   |
| SI001  | Almacenamiento en Red (SAN)             | X |   |   | Alto    |
| SI002  | Disco Duro Externo                      | X |   |   | Bajo    |
| SI003  | Tarjeta de Memoria                      | X |   |   | Bajo    |
| SI004  | Almacenamiento en la Nube               |   |   |   | Bajo    |
| SI005  | Disco Óptico (DVD)                      | X |   |   | Bajo    |
| SI006  | Unidad USB                              | X |   |   | Bajo    |
| AUX001 | Fuentes de Alimentación                 | X |   |   | Medio   |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X |   |   | Medio   |
| AUX003 | Equipos de Climatización                | X |   |   | Medio   |
| AUX004 | Cableado                                | X |   |   | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              | X |   |   | Bajo    |



#### 3.2.2 Avería de origen físico o lógico

a avería de origen físico o lógico puede impactar significativamente la Disponibilidad (D) de los activos tecnológicos de un bufete de abogados. En este contexto, la Integridad (I) y la Confidencialidad (C) pueden verse comprometidas si la avería afecta la seguridad o la integridad de los datos. 

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| SW000  | Debian 12                               | X | X | X | Alto    |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X |   | Medio   |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X |   |   | Bajo    |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X |   | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X |   |   | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   |   | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X |   | Alto    |
| HW004  | Impresoras HP LaserJet                  | X |   |   | Bajo    |
| HW005  | Enrutador Cisco Catalyst                | X |   |   | Medio   |
| HW006  | Sistema de Videovigilancia Axis         | X |   |   | Medio   |
| HW007  | Escáner Epson WorkForce                 | X |   |   | Bajo    |
| HW008  | Teléfonos VoIP Grandstream              | X |   |   | Bajo    |
| HW009  | UPS APC Smart-UPS                       | X |   |   | Medio   |
| HW010  | Estación Docking para Portátiles        | X |   |   | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X |   |   | Medio   |
| HW012  | Pizarras Interactivas SMART             | X |   |   | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X |   |   | Medio   |
| HW014  | iPhone 13 Pro Max                       | X |   |   | Bajo    |
| COM001 | Red de Invitados                        | X |   |   | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X |   |   | Bajo    |
| COM003 | Fibra Óptica                            | X | X |   | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X | X |   | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           | X |   |   | Medio   |
| COM006 | Red de Área Local (LAN)                 | X |   |   | Medio   |
| COM007 | Red de Voz sobre IP (VoIP)              | X |   |   | Bajo    |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Alto    |
| SI001  | Almacenamiento en Red (SAN)             | X | X |   | Alto    |
| SI002  | Disco Duro Externo                      | X |   |   | Medio   |
| SI003  | Tarjeta de Memoria                      | X |   |   | Bajo    |
| SI004  | Almacenamiento en la Nube               | X | X | X | Alto    |
| SI005  | Disco Óptico (DVD)                      | X |   |   | Bajo    |
| SI006  | Unidad USB                              | X |   |   | Bajo    |
| AUX001 | Fuentes de Alimentación                 | X |   |   | Medio   |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X |   |   | Medio   |
| AUX003 | Equipos de Climatización                | X |   |   | Medio   |
| AUX004 | Cableado                                | X |   |   | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              | X |   |   | Bajo    |


El corte del suministro eléctrico afecta principalmente la Disponibilidad (D) de varios activos críticos en una organización, especialmente aquellos que dependen directamente de la energía eléctrica para su funcionamiento. A continuación, se muestra cómo se podría rellenar la tabla considerando el impacto en la Disponibilidad de los activos mencionados:

markdown

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| HW000  | Servidores Dell PowerEdge               | X |   |   | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X |   |   | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   |   | Alto    |
| HW003  | Dispositivos de Almacenamiento Synology | X |   |   | Alto    |
| HW004  | Impresoras HP LaserJet                  | X |   |   | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X |   |   | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X |   |   | Medio   |
| HW007  | Escáner Epson WorkForce                 | X |   |   | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X |   |   | Medio   |
| HW009  | UPS APC Smart-UPS                       | X |   |   | Alto    |
| HW010  | Estación Docking para Portátiles        | X |   |   | Medio   |
| HW011  | Sistemas de Control de Acceso           | X |   |   | Medio   |
| HW012  | Pizarras Interactivas SMART             | X |   |   | Medio   |
| HW013  | Switches Cisco Catalyst 2960            | X |   |   | Alto    |
| COM001 | Red de Invitados                        | X |   |   | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X |   |   | Medio   |
| COM003 | Fibra Óptica                            | X |   |   | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X |   |   | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X |   |   | Alto    |
| COM006 | Red de Área Local (LAN)                 | X |   |   | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X |   |   | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X |   |   | Alto    |
| SI001  | Almacenamiento en Red (SAN)             | X |   |   | Alto    |
| SI002  | Disco Duro Externo                      | X |   |   | Medio   |
| SI003  | Tarjeta de Memoria                      | X |   |   | Bajo    |
| SI004  | Almacenamiento en la Nube               | X |   |   | Alto    |
| SI005  | Disco Óptico (DVD)                      | X |   |   | Bajo    |
| SI006  | Unidad USB                              | X |   |   | Medio   |
| AUX001 | Fuentes de Alimentación                 | X |   |   | Alto    |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X |   |   | Muy Alto|
| AUX003 | Equipos de Climatización                | X |   |   | Alto    |
| AUX004 | Cableado                                | X |   |   | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              |   |   |   | Bajo    |



#### 3.2.4 Degradación de los soportes de almacenamiento de la información

La degradación de los soportes de almacenamiento de la información puede afectar principalmente la Disponibilidad (D) de estos activos. Además, en algunos casos, la Integridad (I) de los datos también podría verse comprometida. La Confidencialidad (C), en cambio, generalmente no se ve afectada directamente por la degradación física, a menos que el deterioro de los medios facilite la exposición de datos confidenciales.

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| SI001  | Almacenamiento en Red (SAN)             | X | X |   | Alto    |
| SI002  | Disco Duro Externo                       | X | X |   | Medio   |
| SI003  | Tarjeta de Memoria                       | X | X |   | Bajo    |
| SI005  | Disco Óptico (DVD)                       | X | X |   | Medio   |
| SI006  | Unidad USB                               | X | X |   | Bajo    |
| SI007  | Tarjeta Inteligente (Smart Card)         | X |   |   | Bajo    |




#### 3.2.4  Averías en la Electrónica de Red (Switches y Routers)

las averías en la electrónica de red, como en switches y routers, afectan principalmente la Disponibilidad (D) de los servicios de red. Estos dispositivos son cruciales para mantener la conectividad y el flujo de información. La Integridad (I) y la Confidencialidad (C) podrían no verse afectadas directamente por la avería de estos dispositivos, a menos que el fallo conlleve a la exposición o alteración de datos.

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| COM001 | Red de Invitados                        | X |   |   | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X |   |   | Medio   |
| COM003 | Fibra Óptica                            | X |   |   | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X |   |   | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           | X |   |   | Alto    |
| COM006 | Red de Área Local (LAN)                 | X |   |   | Muy Alto|
| COM007 | Red de Voz sobre IP (VoIP)              | X |   |   | Alto    |
| COM008 | Red Privada Virtual (VPN)               | X |   |   | Alto    |
| HW005  | Enrutador Cisco Catalyst                | X |   |   | Muy Alto|
| HW013  | Switches Cisco Catalyst 2960            | X |   |   | Muy Alto|


### 3.3 [NI] Errores y fallos no intencionados



#### 3.3.1 Errores de los usuarios 

Los errores de los usuarios pueden afectar todas las dimensiones de la seguridad: Disponibilidad (D), Integridad (I) y Confidencialidad (C), dependiendo de la naturaleza del error. Estos errores pueden causar desde interrupciones en el servicio hasta brechas de seguridad y pérdida de datos. El impacto también varía según el tipo de activo y la importancia de este para las operaciones del bufete.

Aquí está cómo se podría rellenar la tabla:

markdown

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X | X | X | Bajo    |
| COM003 | Fibra Óptica                            | X | X | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Muy Alto|
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                | X | X | X | Muy Alto|
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Medio   |
| COM008 | Red Privada Virtual (VPN)              | X | X | X | Alto    |
| HW005  | Enrutador Cisco Catalyst               | X | X | X | Alto    |
| HW013  | Switches Cisco Catalyst 2960           | X | X | X | Alto    |
| HW014  | iPhone 13 Pro Max                      | X | X | X | Medio   |
| D001   | Casos legales en curso                 | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                   | X | X | X | Alto    |
| D003   | Información confidencial del cliente   | X | X | X | Muy Alto|
| D004   | Precedentes legales                    | X | X | X | Medio   |
| D005   | Servicios Digitales                    | X | X | X | Alto    |
| SW000  | Debian 12                              | X | X | X | Alto    |
| SW001  | Windows 11                             | X | X | X | Alto    |
| SW002  | Clio Manage                            | X | X | X | Alto    |
| SW003  | Westlaw                                | X | X | X | Alto    |
| SW004  | Microsoft Teams                        | X | X | X | Medio   |
| SW005  | Clio Billing                           | X | X | X | Medio   |
| SW006  | NetDocuments                           | X | X | X | Alto    |
| SW007  | Lex Machina                            | X | X | X | Medio   |
| SW008  | LexisNexis                             | X | X | X | Alto    |
| SW009  | Ravel Law                              | X | X | X | Medio   |
| SW010  | QuickBooks Legal                       | X | X | X | Alto    |
| SW011  | Zoom Meetings                          | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform         | X | X | X | Alto    |
| SW013  | Symantec Encryption                    | X | X | X | Alto    |

En esta tabla, la mayoría de los activos se marcan con una "X" en todas las dimensiones debido a la amplia gama de errores que los usuarios pueden cometer, y que podrían afectar la disponibilidad, integridad y confidencialidad de estos activos. Los impactos se clasifican como "Alto", "Medio" o "Bajo" según la criticidad del activo y la probabilidad de que los errores de los usuarios afecten dicho activo.




#### 3.3.2 Errores del administrador
Los errores del administrador, aunque menos comunes, pueden ser devastadores para la estabilidad y seguridad de un sistema. Incluyen acciones inadecuadas en la configuración, actualización o mantenimiento de sistemas, redes o bases de datos. Desde omisiones hasta configuraciones erróneas, estos errores pueden resultar en interrupciones de servicio, exposición de datos confidenciales o incluso la inutilización de sistemas críticos. 

| NI.2  Errores de los usuarios   |

Los errores de los usuarios pueden impactar significativamente en todas las dimensiones de la seguridad de los activos tecnológicos: Disponibilidad (D), Integridad (I) y Confidencialidad (C). Estos errores pueden variar desde acciones no intencionadas hasta malas prácticas, afectando desde la operatividad de los sistemas hasta la seguridad de los datos.





| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X | X | X | Alto    |
| AE002  | Sistema de Comunicaciones               | X | X | X | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X | X | X | Alto    |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Alto    |
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Alto    |
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Medio   |
| D005   | Servicios Digitales                     | X | X | X | Alto    |
| KC001  | Claves de acceso a bases de datos       | X | X | X | Muy Alto|
| KC002  | Claves de correo electrónico            | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X | X | X | Muy Alto|
| KC004  | Claves de cifrado de documentos         | X | X | X | Alto    |
| KC005  | Claves de firma digital                 | X | X | X | Alto    |
| S001   | Intranet                                | X | X | X | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Alto    |
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Alto    |
| SW000  | Debian 12                               | X | X | X | Alto    |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Medio   |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X | X | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X | X | X | Medio   |
| HW007  | Escáner Epson WorkForce                 | X | X | X | Bajo    |
| HW008  | Teléfonos VoIP Grandstream              | X | X | X | Medio   |
| HW009  | UPS APC Smart-UPS                       | X | X | X | Medio   |
| HW010  | Estación Docking para Portátiles        | X | X | X | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X | X | X | Medio   |
| HW012  | Pizarras Interactivas SMART             | X | X | X | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X | X | X | Alto    |
| HW014  | iPhone 13 Pro Max                       | X | X | X | Medio   |
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                 | X | X | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Alto    |

Esta tabla refleja cómo los errores de los usuarios pueden impactar todos los aspectos de la seguridad de los activos, incluyendo la disponibilidad, integridad y confidencialidad. El grado de impacto varía según la criticidad del activo y la naturaleza del error que pueda ocurrir.



#### 3.3.3 Errores de configuración 
Los errores del administrador, aunque menos comunes, pueden ser devastadores para la estabilidad y seguridad de un sistema. Incluyen acciones inadecuadas en la configuración, actualización o mantenimiento de sistemas, redes o bases de datos. Desde omisiones hasta configuraciones erróneas, estos errores pueden resultar en interrupciones de servicio, exposición de datos confidenciales o incluso la inutilización de sistemas críticos. 

| NI.3  Errores de configuración    |

Los errores de configuración pueden afectar la Disponibilidad (D), Integridad (I) y Confidencialidad (C) de varios activos en una organización. A continuación, se muestra cómo se podría rellenar la tabla considerando el impacto de estos errores en los activos mencionados:



| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X | X | X | Alto    |
| AE002  | Sistema de Comunicaciones               | X | X | X | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X | X | X | Alto    |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Muy Alto|
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Alto    |
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X | X | X | Alto    |
| KC001  | Claves de acceso a bases de datos       | X | X | X | Muy Alto|
| KC002  | Claves de correo electrónico            | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X | X | X | Muy Alto|
| KC004  | Claves de cifrado de documentos         | X | X | X | Alto    |
| KC005  | Claves de firma digital                 | X | X | X | Muy Alto|
| S001   | Intranet                                | X | X | X | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Alto    |
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Alto    |
| SW000  | Debian 12                               | X | X | X | Medio   |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Alto    |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X | X | X | Alto    |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X | X | X | Alto    |
| HW007  | Escáner Epson WorkForce                 | X | X | X | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X | X | X | Medio   |
| HW009  | UPS APC Smart-UPS                       | X | X | X | Alto    |
| HW010  | Estación Docking para Portátiles        | X | X | X | Medio   |
| HW011  | Sistemas de Control de Acceso           | X | X | X | Alto    |
| HW012  | Pizarras Interactivas SMART             | X | X | X | Medio   |
| HW013  | Switches Cisco Catalyst 2960            | X | X | X | Alto    |
| HW014  | iPhone 13 Pro Max                       | X | X | X | Medio   |
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                | X | X | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Alto    |
| COM008 | Red Privada Virtual (VPN)              | X | X | X | Alto    |


#### 3.3.4 Difusión de software dañino
La difusión de software dañino se refiere a la propagación intencionada o accidental de programas malignos, como virus, gusanos o troyanos. Estos programas son diseñados para infiltrarse en sistemas, comprometer datos o interrumpir operaciones normales. La difusión de este tipo de software puede ocurrir a través de correos electrónicos, descargas no autorizadas, sitios web comprometidos o dispositivos de almacenamiento infectados.

| NI.4  Difusión de software dañino |
La difusión de software dañino, como virus, malware y ransomware, puede tener un impacto severo en las aplicaciones de software. Afecta la Disponibilidad (D) al interrumpir el funcionamiento normal del software, la Integridad (I) al alterar o dañar los datos, y la Confidencialidad (C) al permitir el acceso no autorizado a información sensible.

A continuación, se muestra cómo se podría rellenar la tabla considerando estos impactos:



| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| SW000  | Debian 12                               | X | X | X | Muy Alto|
| SW001  | Windows 11                              | X | X | X | Muy Alto|
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Alto    |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |

Esta tabla refleja cómo la difusión de software dañino puede comprometer todos los aspectos de la seguridad de las aplicaciones de software. El impacto se clasifica como "Alto" o "Muy Alto" para la mayoría de los softwares, dada la naturaleza crítica de estos activos y los posibles daños que el software dañino puede causar.


#### 3.3.5 Fugas de información
as fugas de información en la nube representan un riesgo serio para la confidencialidad de los datos y la información almacenados o procesados en la nube. Este riesgo puede afectar tanto a los datos almacenados como a las aplicaciones que gestionan o transmiten estos datos, así como a las redes a través de las cuales se accede a ellos.

Aquí te muestro cómo se podría rellenar la tabla considerando el impacto en la Confidencialidad (C) de estos activos:

markdown

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                  |   |   | X | Muy Alto|
| D002   | Contratos y acuerdos                    |   |   | X | Muy Alto|
| D003   | Información confidencial del cliente    |   |   | X | Muy Alto|
| D004   | Precedentes legales                     |   |   | X | Alto    |
| D005   | Servicios Digitales                     |   |   | X | Alto    |
| SW000  | Debian 12                               |   |   | X | Medio   |
| SW001  | Windows 11                              |   |   | X | Medio   |
| SW002  | Clio Manage                             |   |   | X | Alto    |
| SW003  | Westlaw                                 |   |   | X | Alto    |
| SW004  | Microsoft Teams                         |   |   | X | Alto    |
| SW005  | Clio Billing                            |   |   | X | Medio   |
| SW006  | NetDocuments                            |   |   | X | Alto    |
| SW007  | Lex Machina                             |   |   | X | Medio   |
| SW008  | LexisNexis                              |   |   | X | Alto    |
| SW009  | Ravel Law                               |   |   | X | Medio   |
| SW010  | QuickBooks Legal                        |   |   | X | Alto    |
| SW011  | Zoom Meetings                           |   |   | X | Medio   |
| SW012  | Varonis Data Security Platform          |   |   | X | Alto    |
| SW013  | Symantec Encryption                     |   |   | X | Alto    |
| COM001 | Red de Invitados                        |   |   | X | Medio   |
| COM004 | Red de Alta Seguridad Interna           |   |   | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           |   |   | X | Alto    |
| COM006 | Red de Área Local (LAN)                 |   |   | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)              |   |   | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               |   |   | X | Alto    |

.3.6 Alteración de la información

La alteración de la información, que compromete la integridad (I) de los datos, es un riesgo grave en cualquier organización, especialmente en un bufete de abogados donde la precisión de la información es crítica. A continuación se muestra cómo se podría rellenar la tabla considerando este riesgo:



| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                  |   | X |   | Muy Alto|
| D002   | Contratos y acuerdos                    |   | X |   | Muy Alto|
| D003   | Información confidencial del cliente    |   | X |   | Muy Alto|
| D004   | Precedentes legales                     |   | X |   | Alto    |
| D005   | Servicios Digitales                     |   | X |   | Alto    |




3.3.7 Destrucción de la información

La alteración de la información se refiere a la modificación indebida o no autorizada de datos, lo que compromete la integridad de la información. Este riesgo es particularmente relevante para los datos y la información que son críticos para las operaciones de una organización, como un bufete de abogados. En este caso, la Integridad (I) es la dimensión principal afectada.

Aquí te muestro cómo se podría rellenar la tabla considerando el impacto en la Integridad (I) de estos activos:

markdown

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                  |   | X |   | Muy Alto|
| D002   | Contratos y acuerdos                    |   | X |   | Muy Alto|
| D003   | Información confidencial del cliente    |   | X |   | Muy Alto|
| D004   | Precedentes legales                     |   | X |   | Alto    |
| D005   | Servicios Digitales                     |   | X |   | Alto    |

En esta tabla, la marca "X" en la columna de Integridad (I) indica que estos activos son susceptibles a riesgos de alteración de la información. El impacto se clasifica como "Alto" o "Muy Alto" dependiendo de la criticidad del activo y la importancia de la integridad de los datos para las operaciones y la toma de decisiones del bufete. Los activos que contienen información altamente sensible y crítica, como los casos legales en curso y los contratos, tienen un impacto clasificado como "Muy Alto".

### 3.4 [AI] Ataques intencionados
Estos ataques, perpetrados de forma deliberada por individuos o grupos, buscan vulnerar la integridad, confidencialidad o disponibilidad de los activos de un CPD. Pueden provenir de fuentes externas o internas, involucrando la manipulación, destrucción o robo de información, así como la interrupción de los servicios esenciales.

#### 3.4.1 Acceso no autorizados al CPD

El acceso no autorizado a un Centro de Procesamiento de Datos (CPD) es una grave amenaza que puede afectar la Disponibilidad (D), Integridad (I) y Confidencialidad (C) de los activos críticos de una organización. Dado que este tipo de incidente puede resultar en la manipulación, robo o alteración de datos, así como en la interrupción de los servicios clave, es importante evaluar su impacto en una variedad de activos.

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X | X | X | Muy Alto|
| AE002  | Sistema de Comunicaciones               | X | X | X | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X | X | X | Alto    |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Alto    |
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Muy Alto|
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X | X | X | Alto    |
| KC001  | Claves de acceso a bases de datos       | X | X | X | Alto    |
| KC002  | Claves de correo electrónico            | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X | X | X | Alto    |
| KC004  | Claves de cifrado de documentos         | X | X | X | Alto    |
| KC005  | Claves de firma digital                 | X | X | X | Alto    |
| S001   | Intranet                                | X | X | X | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Alto    |
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Alto    |
| SW000  | Debian 12                               | X | X | X | Alto    |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Medio   |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X | X | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X | X | X | Medio   |
| HW007  | Escáner Epson WorkForce                 | X | X | X | Bajo    |
| HW008  | Teléfonos VoIP Grandstream              | X | X | X | Medio   |
| HW009  | UPS APC Smart-UPS                       | X | X | X | Medio   |
| HW010  | Estación Docking para Portátiles        | X | X | X | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X | X | X | Alto    |
| HW012  | Pizarras Interactivas SMART             | X | X | X | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X | X | X | Alto    |
| HW014  | iPhone 13 Pro Max                       | X | X | X | Medio   |
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                 | X | X | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Alto    |


#### 3.4.2 Ransomware

El ransomware es una seria amenaza que puede afectar no solo la Disponibilidad (D) de los datos y sistemas, sino también su Integridad (I) y en algunos casos la Confidencialidad (C). Al cifrar archivos y restringir el acceso a los datos, el ransomware puede paralizar sistemas completos y exponer a la organización a riesgos de seguridad de la información.


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X | X | X | Muy Alto|
| AE002  | Sistema de Comunicaciones               | X | X | X | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X | X | X | Alto    |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Alto    |
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Muy Alto|
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X | X | X | Alto    |
| KC001  | Claves de acceso a bases de datos       | X | X | X | Alto    |
| KC002  | Claves de correo electrónico            | X | X | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X | X | X | Alto    |
| KC004  | Claves de cifrado de documentos         | X | X | X | Alto    |
| KC005  | Claves de firma digital                 | X | X | X | Alto    |
| S001   | Intranet                                | X | X | X | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Alto    |
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Alto    |
| SW000  | Debian 12                               | X | X | X | Alto    |
| SW001  | Windows 11                              | X | X | X | Alto    |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Medio   |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X | X | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X | X | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X | X | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X | X | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X | X | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X | X | X | Medio   |
| HW007  | Escáner Epson WorkForce                 | X | X | X | Bajo    |
| HW008  | Teléfonos VoIP Grandstream              | X | X | X | Medio   |
| HW009  | UPS APC Smart-UPS                       | X | X | X | Medio   |
| HW010  | Estación Docking para Portátiles        | X | X | X | Bajo    |
| HW011  | Sistemas de Control de Acceso           | X | X | X | Alto    |
| HW012  | Pizarras Interactivas SMART             | X | X | X | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            | X | X | X | Alto    |
| HW014  | iPhone 13 Pro Max                       | X | X | X | Medio   |
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X | X | X | Bajo    |
| COM003 | Fibra Óptica                            | X | X | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                 | X | X | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Alto    |
| SI001  | Almacenamiento en Red (SAN)             | X | X | X | Alto    |
| SI002  | Disco Duro Externo                      | X | X | X | Medio   |
| SI003  | Tarjeta de Memoria                      | X | X | X | Bajo    |
| SI004  | Almacenamiento en la Nube               | X | X | X | Alto    |
| SI005  | Disco Óptico (DVD)                      | X | X | X | Bajo    |
| SI006  | Unidad USB                              | X | X | X | Bajo    |
| SI007  | Tarjeta Inteligente (Smart Card)        | X | X | X | Medio   |
| AUX001 | Fuentes de Alimentación                 | X | X | X | Medio   |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X | X | X | Medio   |
| AUX003 | Equipos de Climatización                | X | X | X | Bajo    |
| AUX004 | Cableado                                | X | X | X | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              | X | X | X | Bajo    |
| L001   | Edificio Principal                      | X | X | X | Alto    |
| L002   | Departamento Legal                      | X | X | X | Alto    |
| L003   | Centro Tecnológico                      | X | X | X | Alto    |
| L004   | Sala de Servidores                      | X | X | X | Muy Alto|

3.4.3 Conflicto Armado


El riesgo de un conflicto armado impacta significativamente en varios activos de un bufete de abogados, afectando la disponibilidad (D), la confidencialidad (C) y, en ciertos casos, la integridad (I) de los datos e infraestructura. Aquí se muestra cómo se podría rellenar la tabla considerando este riesgo:

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X |   | X | Muy Alto|
| AE002  | Sistema de Comunicaciones               | X |   | X | Muy Alto|
| AE003  | Base de datos de clientes               | X |   | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X |   | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X |   | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X |   | X | Alto    |
| AS003  | Sistema de seguridad de red             | X |   | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X |   | X | Alto    |
| AS005  | Infraestructura de respaldo             | X |   | X | Muy Alto|
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Muy Alto|
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X |   | X | Alto    |
| KC001  | Claves de acceso a bases de datos       | X |   | X | Alto    |
| KC002  | Claves de correo electrónico            | X |   | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    | X |   | X | Alto    |
| KC004  | Claves de cifrado de documentos         | X |   | X | Alto    |
| KC005  | Claves de firma digital                 | X |   | X | Alto    |
| S001   | Intranet                                | X |   | X | Medio   |
| S002   | Exchange Server                         | X |   | X | Alto    |
| S003   | SFTP                                    | X |   | X | Alto    |
| S004   | Active Directory (AD)                   | X |   | X | Alto    |
| S005   | Software ARP                            | X |   | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X |   | X | Alto    |
| SW000  | Debian 12                               | X |   | X | Alto    |
| SW001  | Windows 11                              | X |   | X | Alto    |
| SW002  | Clio Manage                             | X |   | X | Alto    |
| SW003  | Westlaw                                 | X |   | X | Alto    |
| SW004  | Microsoft Teams                         | X |   | X | Alto    |
| SW005  | Clio Billing                            | X |   | X | Medio   |
| SW006  | NetDocuments                            | X |   | X | Alto    |
| SW007  | Lex Machina                             | X |   | X | Alto    |
| SW008  | LexisNexis                              | X |   | X | Alto    |
| SW009  | Ravel Law                               | X |   | X | Alto    |
| SW010  | QuickBooks Legal                        | X |   | X | Alto    |
| SW011  | Zoom Meetings                           | X |   | X | Medio   |
| SW012  | Varonis Data Security Platform          | X |   | X | Alto    |
| SW013  | Symantec Encryption                     | X |   | X | Alto    |
| HW000  | Servidores Dell PowerEdge               | X | X | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X |   | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   | X | Medio   |
| HW003  | Dispositivos de Almacenamiento Synology | X |   | X | Alto    |
| HW004  | Impresoras HP LaserJet                  | X |   | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                | X |   | X | Alto    |
| HW006  | Sistema de Videovigilancia Axis         | X |   | X | Alto    |
| HW007  | Escáner Epson WorkForce                 | X |   | X | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X |   | X | Medio   |
| HW009  | UPS APC Smart-UPS                       | X |   | X | Alto    |
| HW010  | Estación Docking para Portátiles        | X |   | X | Medio   |
| HW011  | Sistemas de Control de Acceso           | X |   | X | Alto    |
| HW012  | Pizarras Interactivas SMART             | X |   | X | Medio   |
| HW013  | Switches Cisco Catalyst 2960            | X |   | X | Medio   |
| HW014  | iPhone 13 Pro Max                       | X |   | X | Medio   |
| COM001 | Red de Invitados                        | X |   | X | Alto    |
| COM002 | Red 5G para Dispositivos Móviles        | X |   | X | Medio   |
| COM003 | Fibra Óptica                            | X |   | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X |   | X | Muy Alto|
| COM005 | Red Inalámbrica Segura (WPA3)          | X |   | X | Alto    |
| COM006 | Red de Área Local (LAN)                 | X |   | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)              | X |   | X | Alto    |
| COM008 | Red Privada Virtual (VPN)               | X |   | X | Muy Alto|
| SI001  | Almacenamiento en Red (SAN)             | X |   | X | Alto    |
| SI002  | Disco Duro Externo                      | X |   | X | Medio   |
| SI003  | Tarjeta de Memoria                      | X |   | X | Bajo    |
| SI004  | Almacenamiento en la Nube               | X |   | X | Muy Alto|
| SI005  | Disco Óptico (DVD)                      | X |   | X | Bajo    |
| SI006  | Unidad USB                              | X |   | X | Medio   |
| SI007  | Tarjeta Inteligente (Smart Card)        | X |   | X | Alto    |
| AUX001 | Fuentes de Alimentación                 | X |   | X | Medio   |
| AUX002 | Sistemas de Alimentación Ininterrumpida | X |   | X | Alto    |
| AUX003 | Equipos de Climatización                | X |   | X | Medio   |
| AUX004 | Cableado                                | X |   | X | Medio   |
| AUX005 | Mobiliario: Armarios, etc.              | X |   | X | Bajo    |
| L001   | Edificio Principal                      | X | X | X | Muy Alto|
| L002   | Departamento Legal                      | X | X | X | Muy Alto|
| L003   | Centro Tecnológico                      | X | X | X | Muy Alto|
| L004   | Sala de Servidores                      | X | X | X | Muy Alto|



#### 3.4.4 Phishing
El phishing es una técnica de engaño que busca obtener acceso no autorizado a información confidencial, afectando principalmente la Confidencialidad (C) de los datos e información. Los ataques de phishing pueden dirigirse a empleados u otras personas dentro de una organización para acceder a datos sensibles, contraseñas, y más.

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                  |   |   | X | Alto    |
| D002   | Contratos y acuerdos                    |   |   | X | Alto    |
| D003   | Información confidencial del cliente    |   |   | X | Muy Alto|
| D004   | Precedentes legales                     |   |   | X | Medio   |
| D005   | Servicios Digitales                     |   |   | X | Alto    |
| SW000  | Debian 12                               |   |   | X | Medio   |
| SW001  | Windows 11                              |   |   | X | Medio   |
| SW002  | Clio Manage                             |   |   | X | Alto    |
| SW003  | Westlaw                                 |   |   | X | Alto    |
| SW004  | Microsoft Teams                         |   |   | X | Medio   |
| SW005  | Clio Billing                            |   |   | X | Medio   |
| SW006  | NetDocuments                            |   |   | X | Alto    |
| SW007  | Lex Machina                             |   |   | X | Medio   |
| SW008  | LexisNexis                              |   |   | X | Alto    |
| SW009  | Ravel Law                               |   |   | X | Medio   |
| SW010  | QuickBooks Legal                        |   |   | X | Alto    |
| SW011  | Zoom Meetings                           |   |   | X | Medio   |
| SW012  | Varonis Data Security Platform          |   |   | X | Alto    |
| SW013  | Symantec Encryption                     |   |   | X | Alto    |



#### 3.4.5 Robo de dispositivos móviles 

El robo de dispositivos móviles y de hardware puede provocar la pérdida de información confidencial y afectar la disponibilidad de los datos y sistemas. Este riesgo es particularmente significativo para dispositivos que contienen o tienen acceso a información sensible de la empresa.

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| HW000  | Servidores Dell PowerEdge               | X |   | X | Muy Alto|
| HW001  | Estación de Trabajo HP ZBook            | X |   | X | Alto    |
| HW002  | PC de Escritorio Lenovo ThinkCentre     | X |   | X | Alto    |
| HW003  | Dispositivos de Almacenamiento Synology | X |   | X | Alto    |
| HW004  | Impresoras HP LaserJet                  |   |   | X | Medio   |
| HW005  | Enrutador Cisco Catalyst                |   |   | X | Medio   |
| HW006  | Sistema de Videovigilancia Axis         |   |   | X | Medio   |
| HW007  | Escáner Epson WorkForce                 | X |   | X | Medio   |
| HW008  | Teléfonos VoIP Grandstream              | X |   | X | Alto    |
| HW009  | UPS APC Smart-UPS                       | X |   | X | Medio   |
| HW010  | Estación Docking para Portátiles        | X |   | X | Alto    |
| HW011  | Sistemas de Control de Acceso           |   |   | X | Bajo    |
| HW012  | Pizarras Interactivas SMART             |   |   | X | Bajo    |
| HW013  | Switches Cisco Catalyst 2960            |   |   | X | Medio   |
| HW014  | iPhone 13 Pro Max                       | X |   | X | Alto    |


#### 3.4.6 Compromiso de credenciales

El compromiso de credenciales representa un riesgo grave, especialmente en lo que respecta a la Confidencialidad (C) de los activos de una organización. Este riesgo puede dar lugar a accesos no autorizados, exponiendo información confidencial y comprometiendo la integridad de los sistemas. La pérdida de credenciales puede afectar a una amplia gama de activos, desde datos e información hasta redes de comunicaciones y software.

El riesgo de compromiso de credenciales afecta a numerosos activos en un bufete de abogados, principalmente en la dimensión de la confidencialidad (C). Este riesgo puede tener un impacto significativo en la seguridad y la operatividad del bufete. A continuación, se muestra cómo se podría rellenar la tabla para reflejar este riesgo:


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   | X | Muy Alto|
| AE002  | Sistema de Comunicaciones               |   |   | X | Muy Alto|
| AE003  | Base de datos de clientes               |   |   | X | Muy Alto|
| AE004  | Sistema de gestión financiera           |   |   | X | Alto    |
| AE005  | Plataforma de colaboración interna      |   |   | X | Alto    |
| AS001  | Servidores Centrales                    |   |   | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 |   |   | X | Alto    |
| AS003  | Sistema de seguridad de red             |   |   | X | Muy Alto|
| AS004  | Políticas de acceso y control           |   |   | X | Muy Alto|
| AS005  | Infraestructura de respaldo             |   |   | X | Alto    |
| D001   | Casos legales en curso                  |   |   | X | Muy Alto|
| D002   | Contratos y acuerdos                    |   |   | X | Muy Alto|
| D003   | Información confidencial del cliente    |   |   | X | Muy Alto|
| D004   | Precedentes legales                     |   |   | X | Alto    |
| D005   | Servicios Digitales                     |   |   | X | Alto    |
| KC001  | Claves de acceso a bases de datos       |   |   | X | Muy Alto|
| KC002  | Claves de correo electrónico            |   |   | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    |   |   | X | Muy Alto|
| KC004  | Claves de cifrado de documentos         |   |   | X | Alto    |
| KC005  | Claves de firma digital                 |   |   | X | Muy Alto|
| S001   | Intranet                                |   |   | X | Medio   |
| S002   | Exchange Server                         |   |   | X | Alto    |
| S003   | SFTP                                    |   |   | X | Alto    |
| S004   | Active Directory (AD)                   |   |   | X | Alto    |
| S005   | Software ARP                            |   |   | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  |   |   | X | Alto    |
| SW000  | Debian 12                               |   |   | X | Alto    |
| SW001  | Windows 11                              |   |   | X | Alto    |
| SW002  | Clio Manage                             |   |   | X | Alto    |
| SW003  | Westlaw                                 |   |   | X | Alto    |
| SW004  | Microsoft Teams                         |   |   | X | Alto    |
| SW005  | Clio Billing                            |   |   | X | Medio   |
| SW006  | NetDocuments                            |   |   | X | Alto    |
| SW007  | Lex Machina                             |   |   | X | Alto    |
| SW008  | LexisNexis                              |   |   | X | Alto    |
| SW009  | Ravel Law                               |   |   | X | Alto    |
| SW010  | QuickBooks Legal                        |   |   | X | Alto    |
| SW011  | Zoom Meetings                           |   |   | X | Medio   |
| SW012  | Varonis Data Security Platform          |   |   | X | Alto    |
| SW013  | Symantec Encryption                     |   |   | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           |   |   | X | Muy Alto|
| COM005 | Red Inalámbrica Segura (WPA3)          |   |   | X | Alto    |
| COM006 | Red de Área Local (LAN)                 |   |   | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)              |   |   | X | Alto    |
| COM008 | Red Privada Virtual (VPN)               |   |   | X | Muy Alto|
| SI001  | Almacenamiento en Red (SAN)             |   |   | X | Alto    |




#### 3.4.7 Ataques de denegación de servicio SYN Flood

Los ataques de denegación de servicio, y en particular el tipo conocido como SYN Flood, representan una seria amenaza para la disponibilidad y estabilidad de los sistemas informáticos. Este tipo de ataque busca abrumar un servidor con un volumen masivo de solicitudes de conexión TCP SYN, agotando los recursos y haciendo que la entidad objetivo sea incapaz de atender las solicitudes legítimas. El SYN Flood puede paralizar servicios críticos, afectar la experiencia del usuario y, en casos extremos, causar interrupciones prolongadas en la operatividad de la red.

| AI.7 Phishing |


El compromiso de credenciales representa un riesgo grave, especialmente en lo que respecta a la Confidencialidad (C) de los activos de una organización. Este riesgo puede dar lugar a accesos no autorizados, exponiendo información confidencial y comprometiendo la integridad de los sistemas. La pérdida de credenciales puede afectar a una amplia gama de activos, desde datos e información hasta redes de comunicaciones y software.




| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   | X | Muy Alto|
| AE002  | Sistema de Comunicaciones               |   |   | X | Alto    |
| AE003  | Base de datos de clientes               |   |   | X | Muy Alto|
| AE004  | Sistema de gestión financiera           |   |   | X | Alto    |
| AE005  | Plataforma de colaboración interna      |   |   | X | Alto    |
| AS001  | Servidores Centrales                    |   |   | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 |   |   | X | Alto    |
| AS003  | Sistema de seguridad de red             |   |   | X | Muy Alto|
| AS004  | Políticas de acceso y control           |   |   | X | Alto    |
| AS005  | Infraestructura de respaldo             |   |   | X | Alto    |
| D001   | Casos legales en curso                  |   |   | X | Muy Alto|
| D002   | Contratos y acuerdos                    |   |   | X | Muy Alto|
| D003   | Información confidencial del cliente    |   |   | X | Muy Alto|
| D004   | Precedentes legales                     |   |   | X | Alto    |
| D005   | Servicios Digitales                     |   |   | X | Alto    |
| KC001  | Claves de acceso a bases de datos       |   |   | X | Muy Alto|
| KC002  | Claves de correo electrónico            |   |   | X | Alto    |
| KC003  | Claves de acceso a sistemas internos    |   |   | X | Muy Alto|
| KC004  | Claves de cifrado de documentos         |   |   | X | Alto    |
| KC005  | Claves de firma digital                 |   |   | X | Muy Alto|
| S001   | Intranet                                |   |   | X | Medio   |
| S002   | Exchange Server                         |   |   | X | Alto    |
| S003   | SFTP                                    |   |   | X | Alto    |
| S004   | Active Directory (AD)                   |   |   | X | Alto    |
| S005   | Software ARP                            |   |   | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  |   |   | X | Alto    |
| SW000  | Debian 12                               |   |   | X | Medio   |
| SW001  | Windows 11                              |   |   | X | Medio   |
| SW002  | Clio Manage                             |   |   | X | Alto    |
| SW003  | Westlaw                                 |   |   | X | Alto    |
| SW004  | Microsoft Teams                         |   |   | X | Medio   |
| SW005  | Clio Billing                            |   |   | X | Medio   |
| SW006  | NetDocuments                            |   |   | X | Alto    |
| SW007  | Lex Machina                             |   |   | X | Medio   |
| SW008  | LexisNexis                              |   |   | X | Alto    |
| SW009  | Ravel Law                               |   |   | X | Medio   |
| SW010  | QuickBooks Legal                        |   |   | X | Alto    |
| SW011  | Zoom Meetings                           |   |   | X | Medio   |
| SW012  | Varonis Data Security Platform          |   |   | X | Alto    |
| SW013  | Symantec Encryption                     |   |   | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           |   |   | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          |   |   | X | Alto    |
| COM006 | Red de Área Local (LAN)                 |   |   | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             |   |   | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               |   |   | X | Alto    |
| SI001  | Almacenamiento en Red (SAN)             |   |   | X | Alto    |

#### 3.4.8 Vulnerabilidades de las aplicaciones

Las vulnerabilidades en las aplicaciones representan una puerta de entrada crítica para posibles amenazas cibernéticas, exponiendo sistemas a riesgos significativos de explotación. Estas debilidades pueden manifestarse en diversas formas, como fallos en la gestión de sesiones, validación insuficiente de datos de entrada, o incluso defectos en el diseño arquitectónico. La explotación exitosa de estas vulnerabilidades podría permitir a los atacantes el acceso no autorizado, la manipulación de datos o la interrupción de servicios esenciales.

| AI.7 Vulnerabilidades de las aplicaciones |

Las vulnerabilidades en las aplicaciones pueden comprometer la Disponibilidad (D), la Integridad (I) y la Confidencialidad (C) de diversos activos dentro de una organización. Estas vulnerabilidades pueden ser explotadas para acceder, modificar o interrumpir datos y servicios críticos. Es importante evaluar el impacto potencial de estas vulnerabilidades en cada activo.


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                | X | X | X | Alto    |
| AE002  | Sistema de Comunicaciones               | X | X | X | Alto    |
| AE003  | Base de datos de clientes               | X | X | X | Muy Alto|
| AE004  | Sistema de gestión financiera           | X | X | X | Alto    |
| AE005  | Plataforma de colaboración interna      | X | X | X | Alto    |
| AS001  | Servidores Centrales                    | X | X | X | Muy Alto|
| AS002  | Red de Área Local (LAN)                 | X | X | X | Alto    |
| AS003  | Sistema de seguridad de red             | X | X | X | Muy Alto|
| AS004  | Políticas de acceso y control           | X | X | X | Alto    |
| AS005  | Infraestructura de respaldo             | X | X | X | Alto    |
| D001   | Casos legales en curso                  | X | X | X | Muy Alto|
| D002   | Contratos y acuerdos                    | X | X | X | Alto    |
| D003   | Información confidencial del cliente    | X | X | X | Muy Alto|
| D004   | Precedentes legales                     | X | X | X | Alto    |
| D005   | Servicios Digitales                     | X | X | X | Alto    |
| S001   | Intranet                                | X | X | X | Medio   |
| S002   | Exchange Server                         | X | X | X | Alto    |
| S003   | SFTP                                    | X | X | X | Alto    |
| S004   | Active Directory (AD)                   | X | X | X | Alto    |
| S005   | Software ARP                            | X | X | X | Medio   |
| S006   | PKI - Infraestructura de clave pública  | X | X | X | Alto    |
| SW000  | Debian 12                               | X | X | X | Medio   |
| SW001  | Windows 11                              | X | X | X | Medio   |
| SW002  | Clio Manage                             | X | X | X | Alto    |
| SW003  | Westlaw                                 | X | X | X | Alto    |
| SW004  | Microsoft Teams                         | X | X | X | Medio   |
| SW005  | Clio Billing                            | X | X | X | Medio   |
| SW006  | NetDocuments                            | X | X | X | Alto    |
| SW007  | Lex Machina                             | X | X | X | Medio   |
| SW008  | LexisNexis                              | X | X | X | Alto    |
| SW009  | Ravel Law                               | X | X | X | Medio   |
| SW010  | QuickBooks Legal                        | X | X | X | Alto    |
| SW011  | Zoom Meetings                           | X | X | X | Medio   |
| SW012  | Varonis Data Security Platform          | X | X | X | Alto    |
| SW013  | Symantec Encryption                     | X | X | X | Alto    |
| COM001 | Red de Invitados                        | X | X | X | Medio   |
| COM002 | Red 5G para Dispositivos Móviles        | X | X | X | Bajo    |
| COM003 | Fibra Óptica                            | X | X | X | Alto    |
| COM004 | Red de Alta Seguridad Interna           | X | X | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)          | X | X | X | Alto    |
| COM006 | Red de Área Local (LAN)                 | X | X | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)             | X | X | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               | X | X | X | Alto    |
| SI001  | Almacenamiento en Red (SAN)             | X | X | X | Alto   


### 3.3.9 Fugas de información en la nube

Los escapes de información representan un riesgo significativo para la Confidencialidad (C) de los datos, las aplicaciones de software y las redes de comunicaciones. Este riesgo se asocia con la exposición no intencionada de información confidencial debido a brechas de seguridad, errores humanos o fallos técnicos.



Las fugas de información en la nube representan un riesgo serio para la confidencialidad de los datos y la información almacenados o procesados en la nube. Este riesgo puede afectar tanto a los datos almacenados como a las aplicaciones que gestionan o transmiten estos datos, así como a las redes a través de las cuales se accede a ellos.

Aquí te muestro cómo se podría rellenar la tabla considerando el impacto en la Confidencialidad (C) de estos activos:


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                  |   |   | X | Muy Alto|
| D002   | Contratos y acuerdos                    |   |   | X | Muy Alto|
| D003   | Información confidencial del cliente    |   |   | X | Muy Alto|
| D004   | Precedentes legales                     |   |   | X | Alto    |
| D005   | Servicios Digitales                     |   |   | X | Alto    |
| SW000  | Debian 12                               |   |   | X | Medio   |
| SW001  | Windows 11                              |   |   | X | Medio   |
| SW002  | Clio Manage                             |   |   | X | Alto    |
| SW003  | Westlaw                                 |   |   | X | Alto    |
| SW004  | Microsoft Teams                         |   |   | X | Alto    |
| SW005  | Clio Billing                            |   |   | X | Medio   |
| SW006  | NetDocuments                            |   |   | X | Alto    |
| SW007  | Lex Machina                             |   |   | X | Medio   |
| SW008  | LexisNexis                              |   |   | X | Alto    |
| SW009  | Ravel Law                               |   |   | X | Medio   |
| SW010  | QuickBooks Legal                        |   |   | X | Alto    |
| SW011  | Zoom Meetings                           |   |   | X | Medio   |
| SW012  | Varonis Data Security Platform          |   |   | X | Alto    |
| SW013  | Symantec Encryption                     |   |   | X | Alto    |
| COM001 | Red de Invitados                        |   |   | X | Medio   |
| COM004 | Red de Alta Seguridad Interna           |   |   | X | Alto    |
| COM005 | Red Inalámbrica Segura (WPA3)           |   |   | X | Alto    |
| COM006 | Red de Área Local (LAN)                 |   |   | X | Alto    |
| COM007 | Red de Voz sobre IP (VoIP)              |   |   | X | Medio   |
| COM008 | Red Privada Virtual (VPN)               |   |   | X | Alto    |

En esta tabla, la marca "X" en la columna de Confidencialidad (C) indica que estos activos son susceptibles a riesgos de fuga de información. El impacto varía según la criticidad del activo y el nivel de sensibilidad de la información que manejan. Los activos que contienen o gestionan información altamente confidencial, como datos de clientes y casos legales, tienen un impacto clasificado como "Muy Alto".





