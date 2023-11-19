
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

Los errores de los usuarios, comunes en entornos tecnológicos, representan un riesgo sustancial en la seguridad y eficiencia de las operaciones. Estos errores pueden variar desde acciones no intencionadas hasta malas prácticas al utilizar sistemas, programas o servicios, pudiendo desencadenar brechas de seguridad, pérdida de datos y fallas en el funcionamiento general de los sistemas.





| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| COM001 | Red de Invitados                        |   |   |   |         |
| COM002 | Red 5G para Dispositivos Móviles        |   |   |   |         |
| COM003 | Fibra Óptica                           |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna           |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)          |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)             |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst                |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| D001   | Casos legales en curso                   |   |   |   |         |
| D002   | Contratos y acuerdos                     |   |   |   |         |
| D003   | Información confidencial del cliente     |   |   |   |         |
| D004   | Precedentes legales                      |   |   |   |         |
| D005   | Servicios Digitales                      |   |   |   |         |
| SW000  | Debian 12                               |   |   |   |         |
| SW001  | Windows 11                              |   |   |   |         |
| SW002  | Clio Manage                             |   |   |   |         |
| SW003  | Westlaw                                 |   |   |   |         |
| SW004  | Microsoft Teams                         |   |   |   |         |
| SW005  | Clio Billing                            |   |   |   |         |
| SW006  | NetDocuments                            |   |   |   |         |
| SW007  | Lex Machina                             |   |   |   |         |
| SW008  | LexisNexis                              |   |   |   |         |
| SW009  | Ravel Law                               |   |   |   |         |
| SW010  | QuickBooks Legal                        |   |   |   |         |
| SW011  | Zoom Meetings                           |   |   |   |         |
| SW012  | Varonis Data Security Platform          |   |   |   |         |
| SW013  | Symantec Encryption                     |   |   |   |         |


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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| KC001  | Claves de acceso a bases de datos      |   |   |   |         |
| KC002  | Claves de correo electrónico           |   |   |   |         |
| KC003  | Claves de acceso a sistemas internos   |   |   |   |         |
| KC004  | Claves de cifrado de documentos        |   |   |   |         |
| KC005  | Claves de firma digital                |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| HW000  | Servidores Dell PowerEdge             |   |   |   |         |
| HW001  | Estación de Trabajo HP ZBook          |   |   |   |         |
| HW002  | PC de Escritorio Lenovo ThinkCentre   |   |   |   |         |
| HW003  | Dispositivos de Almacenamiento Synology |   |   |   |         |
| HW004  | Impresoras HP LaserJet                |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst              |   |   |   |         |
| HW006  | Sistema de Videovigilancia Axis       |   |   |   |         |
| HW007  | Escáner Epson WorkForce               |   |   |   |         |
| HW008  | Teléfonos VoIP Grandstream            |   |   |   |         |
| HW009  | UPS APC Smart-UPS                    |   |   |   |         |
| HW010  | Estación Docking para Portátiles      |   |   |   |         |
| HW011  | Sistemas de Control de Acceso         |   |   |   |         |
| HW012  | Pizarras Interactivas SMART           |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |



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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| KC001  | Claves de acceso a bases de datos      |   |   |   |         |
| KC002  | Claves de correo electrónico           |   |   |   |         |
| KC003  | Claves de acceso a sistemas internos   |   |   |   |         |
| KC004  | Claves de cifrado de documentos        |   |   |   |         |
| KC005  | Claves de firma digital                |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| HW000  | Servidores Dell PowerEdge             |   |   |   |         |
| HW001  | Estación de Trabajo HP ZBook          |   |   |   |         |
| HW002  | PC de Escritorio Lenovo ThinkCentre   |   |   |   |         |
| HW003  | Dispositivos de Almacenamiento Synology |   |   |   |         |
| HW004  | Impresoras HP LaserJet                |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst              |   |   |   |         |
| HW006  | Sistema de Videovigilancia Axis       |   |   |   |         |
| HW007  | Escáner Epson WorkForce               |   |   |   |         |
| HW008  | Teléfonos VoIP Grandstream            |   |   |   |         |
| HW009  | UPS APC Smart-UPS                    |   |   |   |         |
| HW010  | Estación Docking para Portátiles      |   |   |   |         |
| HW011  | Sistemas de Control de Acceso         |   |   |   |         |
| HW012  | Pizarras Interactivas SMART           |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |



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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |




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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |


.3.6 Alteración de la información

La alteración de la información implica la modificación indebida o no autorizada de los datos, lo que puede comprometer la integridad y veracidad de la información.

markdown

| NI.6 Alteración de la información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| **Dimensiones:** |
| 1. [I] Integridad|

Este riesgo  afecta a los siguientes activos :

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |

3.3.7 Destrucción de la información

La destrucción de información representa la pérdida irreversible de datos valiosos. Puede ocurrir por fallas técnicas, ataques maliciosos o errores humanos. Esta amenaza puede comprometer la disponibilidad y confidencialidad de datos esenciales para las operaciones, la toma de decisiones y la continuidad del negocio.

markdown

| NI.7 Destrucción de la información |
| --- |
| **Tipos de Activos:** |
| - [D] Datos / información|
| **Dimensiones:** |
| 1. [D] Disponibilidad|

Este riesgo  afecta a los siguientes activos :

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |




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





| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| KC001  | Claves de acceso a bases de datos      |   |   |   |         |
| KC002  | Claves de correo electrónico           |   |   |   |         |
| KC003  | Claves de acceso a sistemas internos   |   |   |   |         |
| KC004  | Claves de cifrado de documentos        |   |   |   |         |
| KC005  | Claves de firma digital                |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| HW000  | Servidores Dell PowerEdge             |   |   |   |         |
| HW001  | Estación de Trabajo HP ZBook          |   |   |   |         |
| HW002  | PC de Escritorio Lenovo ThinkCentre   |   |   |   |         |
| HW003  | Dispositivos de Almacenamiento Synology |   |   |   |         |
| HW004  | Impresoras HP LaserJet                |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst              |   |   |   |         |
| HW006  | Sistema de Videovigilancia Axis       |   |   |   |         |
| HW007  | Escáner Epson WorkForce               |   |   |   |         |
| HW008  | Teléfonos VoIP Grandstream            |   |   |   |         |
| HW009  | UPS APC Smart-UPS                    |   |   |   |         |
| HW010  | Estación Docking para Portátiles      |   |   |   |         |
| HW011  | Sistemas de Control de Acceso         |   |   |   |         |
| HW012  | Pizarras Interactivas SMART           |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |



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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| KC001  | Claves de acceso a bases de datos      |   |   |   |         |
| KC002  | Claves de correo electrónico           |   |   |   |         |
| KC003  | Claves de acceso a sistemas internos   |   |   |   |         |
| KC004  | Claves de cifrado de documentos        |   |   |   |         |
| KC005  | Claves de firma digital                |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| HW000  | Servidores Dell PowerEdge             |   |   |   |         |
| HW001  | Estación de Trabajo HP ZBook          |   |   |   |         |
| HW002  | PC de Escritorio Lenovo ThinkCentre   |   |   |   |         |
| HW003  | Dispositivos de Almacenamiento Synology |   |   |   |         |
| HW004  | Impresoras HP LaserJet                |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst              |   |   |   |         |
| HW006  | Sistema de Videovigilancia Axis       |   |   |   |         |
| HW007  | Escáner Epson WorkForce               |   |   |   |         |
| HW008  | Teléfonos VoIP Grandstream            |   |   |   |         |
| HW009  | UPS APC Smart-UPS                    |   |   |   |         |
| HW010  | Estación Docking para Portátiles      |   |   |   |         |
| HW011  | Sistemas de Control de Acceso         |   |   |   |         |
| HW012  | Pizarras Interactivas SMART           |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960              |   |   |   |         |
| HW014  | iPhone 13 Pro Max                        |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM002 | Red 5G para Dispositivos Móviles      |   |   |   |         |
| COM003 | Fibra Óptica                         |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |
| SI001  | Almacenamiento en Red (SAN)           |   |   |   |         |
| SI002  | Disco Duro Externo                   |   |   |   |         |
| SI003  | Tarjeta de Memoria                   |   |   |   |         |
| SI004  | Almacenamiento en la Nube            |   |   |   |         |
| SI005  | Disco Óptico (DVD)                   |   |   |   |         |
| SI006  | Unidad USB                           |   |   |   |         |
| SI007  | Tarjeta Inteligente (Smart Card)     |   |   |   |         |
| AUX001 | Fuentes de Alimentación              |   |   |   |         |
| AUX002 | Sistemas de Alimentación Ininterrumpida |   |   |   |         |
| AUX003 | Equipos de Climatización              |   |   |   |         |
| AUX004 | Cableado                 |   |   |   |         |
| AUX005 | Mobiliario: Armarios, etc.|   |   |   |         |
| L001   | Edificio Principal |   |   |   |         |
| L002   | Departamento Legal |   |   |   |         |
| L003   | Centro Tecnológico |   |   |   |         |
| L004   | Sala de Servidores |   |   |   |         |



#### 3.4.4 Phishing
El phishing es una forma de ciberataque que implica engañar a las personas para obtener información confidencial, como contraseñas, detalles de tarjetas de crédito u otra información sensible. Los atacantes suelen suplantar identidades o entidades confiables, enviando correos electrónicos o mensajes diseñados para parecer legítimos.

| AI.4 Phishing |
| --- |
| **Tipos de Activos:** |
| - [P] Personal |


| **Dimensiones:** |
| 1. [C] Confidencialidad|

Este riesgo podría llegar a afectar a los siguientes activos :


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |


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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| HW000  | Servidores Dell PowerEdge               |   |   |   |         |
| HW001  | Estación de Trabajo HP ZBook            |   |   |   |         |
| HW002  | PC de Escritorio Lenovo ThinkCentre     |   |   |   |         |
| HW003  | Dispositivos de Almacenamiento Synology |   |   |   |         |
| HW004  | Impresoras HP LaserJet                  |   |   |   |         |
| HW005  | Enrutador Cisco Catalyst                |   |   |   |         |
| HW006  | Sistema de Videovigilancia Axis         |   |   |   |         |
| HW007  | Escáner Epson WorkForce                 |   |   |   |         |
| HW008  | Teléfonos VoIP Grandstream              |   |   |   |         |
| HW009  | UPS APC Smart-UPS                      |   |   |   |         |
| HW010  | Estación Docking para Portátiles        |   |   |   |         |
| HW011  | Sistemas de Control de Acceso           |   |   |   |         |
| HW012  | Pizarras Interactivas SMART             |   |   |   |         |
| HW013  | Switches Cisco Catalyst 2960            |   |   |   |         |
| HW014  | iPhone 13 Pro Max                      |   |   |   |         |


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

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| KC001  | Claves de acceso a bases de datos      |   |   |   |         |
| KC002  | Claves de correo electrónico           |   |   |   |         |
| KC003  | Claves de acceso a sistemas internos   |   |   |   |         |
| KC004  | Claves de cifrado de documentos        |   |   |   |         |
| KC005  | Claves de firma digital                |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |
| SI001  | Almacenamiento en Red (SAN)           |   |   |   |         |



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

| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM002 | Red 5G para Dispositivos Móviles      |   |   |   |         |
| COM003 | Fibra Óptica                         |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |
| SI001  | Almacenamiento en Red (SAN)           |   |   |   |         |





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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| AE001  | Archivo Digital de Casos                |   |   |   |         |
| AE002  | Sistema de Comunicaciones               |   |   |   |         |
| AE003  | Base de datos de clientes               |   |   |   |         |
| AE004  | Sistema de gestión financiera           |   |   |   |         |
| AE005  | Plataforma de colaboración interna      |   |   |   |         |
| AS001  | Servidores Centrales                   |   |   |   |         |
| AS002  | Red de Área Local (LAN)                |   |   |   |         |
| AS003  | Sistema de seguridad de red            |   |   |   |         |
| AS004  | Políticas de acceso y control          |   |   |   |         |
| AS005  | Infraestructura de respaldo            |   |   |   |         |
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| S001   | Intranet                              |   |   |   |         |
| S002   | Exchange Server                       |   |   |   |         |
| S003   | SFTP                                  |   |   |   |         |
| S004   | Active Directory (AD)                 |   |   |   |         |
| S005   | Software ARP                          |   |   |   |         |
| S006   | PKI - Infraestructura de clave pública |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM002 | Red 5G para Dispositivos Móviles      |   |   |   |         |
| COM003 | Fibra Óptica                         |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |
| SI001  | Almacenamiento en Red (SAN)           |   |   |   |         |

### 3.3.9 Fugas de información en la nube
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


| Código | Nombre                                  | D | I | C | Impacto |
|--------|-----------------------------------------|---|---|---|---------|
| D001   | Casos legales en curso                 |   |   |   |         |
| D002   | Contratos y acuerdos                   |   |   |   |         |
| D003   | Información confidencial del cliente   |   |   |   |         |
| D004   | Precedentes legales                    |   |   |   |         |
| D005   | Servicios Digitales                    |   |   |   |         |
| SW000  | Debian 12                             |   |   |   |         |
| SW001  | Windows 11                            |   |   |   |         |
| SW002  | Clio Manage                           |   |   |   |         |
| SW003  | Westlaw                               |   |   |   |         |
| SW004  | Microsoft Teams                       |   |   |   |         |
| SW005  | Clio Billing                          |   |   |   |         |
| SW006  | NetDocuments                          |   |   |   |         |
| SW007  | Lex Machina                           |   |   |   |         |
| SW008  | LexisNexis                            |   |   |   |         |
| SW009  | Ravel Law                             |   |   |   |         |
| SW010  | QuickBooks Legal                      |   |   |   |         |
| SW011  | Zoom Meetings                         |   |   |   |         |
| SW012  | Varonis Data Security Platform        |   |   |   |         |
| SW013  | Symantec Encryption                   |   |   |   |         |
| COM001 | Red de Invitados                      |   |   |   |         |
| COM004 | Red de Alta Seguridad Interna         |   |   |   |         |
| COM005 | Red Inalámbrica Segura (WPA3)        |   |   |   |         |
| COM006 | Red de Área Local (LAN)               |   |   |   |         |
| COM007 | Red de Voz sobre IP (VoIP)           |   |   |   |         |
| COM008 | Red Privada Virtual (VPN)             |   |   |   |         |




