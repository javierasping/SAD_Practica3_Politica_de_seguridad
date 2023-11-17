## 4 Cálculo del riesgo

Nuestra estrategia para calcular el riesgo sigue un proceso ordenado y detallado, enfocado en una evaluación minuciosa de los riesgos que afectan a todos los bienes de la empresa. Empleamos la metodología MAGERIT para empezar identificando los activos más importantes, y los clasificamos en grupos relevantes como información/datos, llaves de cifrado, software, hardware, sistemas de comunicación y medios de almacenamiento de información.

En cada grupo, identificamos posibles peligros y analizamos cómo estos pueden impactar en aspectos clave como la disponibilidad, integridad y privacidad de la información. Para evaluar el impacto y la probabilidad de que ocurran estas amenazas, utilizamos una escala de riesgo que va de bajo a alto. Este análisis se hace revisando historiales de incidentes previos, comparando con situaciones similares en otros entornos y con la ayuda del conocimiento de nuestro equipo especializado en seguridad informática.

Durante este proceso, tomamos en cuenta tanto elementos externos como internos, conscientes de que los empleados, las metodologías de trabajo y el ambiente operativo son factores clave en el nivel de riesgo de la empresa. El resultado de esta evaluación nos da una visión clara de los riesgos que enfrentamos, lo cual nos permite enfocar mejor los esfuerzos para reducir estos riesgos y asignar de manera eficiente los recursos para su manejo.

### 4.1 [info] Activos esenciales (impacto y riesgo)

Los activos esenciales incluyen todos aquellos recursos críticos para la operación de la firma legal. Desde archivos de casos digitales hasta sistemas de gestión financiera, estos activos son vitales para mantener la continuidad del negocio y su seguridad jurídica. La interrupción o compromiso de estos activos podría tener consecuencias devastadoras tanto para la operatividad de la empresa como para su reputación en el mercado.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| AE001  | Archivo Digital de Casos | Fuego, Inundación | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| AE002  | Sistema de Comunicaciones | Fuego, Inundación, Corte eléctrico | Disponibilidad | Alta | Media | Alto |
| AE003  | Base de datos de clientes | Fuego, Inundación, Errores de Usuario | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| AE004  | Sistema de gestión financiera | Fuego, Avería lógica | Disponibilidad, Integridad | Alta | Baja | Medio |
| AE005  | Plataforma de colaboración interna | Inundación, Errores de Usuario | Disponibilidad, Integridad | Alta | Baja | Medio |

### 4.2 [D] Datos / Información (impacto y riesgo)

Esta categoría se refiere a la información almacenada, procesada y transmitida, incluyendo casos legales activos, contratos y acuerdos, así como datos personales de clientes. Consideramos la importancia crítica de la confidencialidad y la integridad de los datos en el contexto legal, donde la fuga o corrupción de información podría resultar en daños legales y financieros significativos.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| D001   | Casos legales en curso | Errores de Usuario | Disponibilidad, Integridad, Confidencialidad | Alta | Alta | Alto |
| D002   | Contratos y acuerdos | Avería lógica, Errores de Usuario | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| D003   | Información confidencial del cliente | Acceso no autorizado, Fuga de información | Confidencialidad, Integridad | Alta | Baja | Medio |
| D004   | Precedentes legales | Avería lógica | Integridad, Confidencialidad | Alta | Media | Alto |
| D005   | Servicios Digitales | Corte del suministro eléctrico | Disponibilidad | Alta | Baja | Medio |

### 4.3 [K] Claves criptográficas (impacto y riesgo)

Las claves criptográficas protegen la confidencialidad e integridad de la información sensible. Su compromiso podría permitir el acceso no autorizado a información privilegiada, poniendo en peligro la seguridad de los datos del cliente y la infraestructura de TI de la firma.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| KC001  | Claves de acceso a bases de datos | Acceso no autorizado, Suplantación de identidad | Confidencialidad, Integridad | Alta | Baja | Medio |
| KC002  | Claves de correo electrónico | Phishing, Malware | Confidencialidad | Alta | Media | Alto |
| KC003  | Claves de acceso a sistemas internos | Acceso no autorizado | Confidencialidad, Integridad | Alta | Media | Alto |
| KC004  | Claves de cifrado de documentos | Avería lógica | Integridad, Confidencialidad | Alta | Baja | Medio |
| KC005  | Claves de firma digital | Suplantación de identidad | Autenticidad | Alta | Baja | Medio |

### 4.4 [SW] Software - Aplicaciones informáticas (impacto y riesgo)

El software y las aplicaciones informáticas son herramientas fundamentales para la prestación de servicios legales y administrativos. Un fallo o vulnerabilidad en estos sistemas puede llevar a una parálisis en las operaciones, así como a posibles brechas de seguridad.

| Código | Nombre del Activo        | Tipo de Amenaza           | Dimensiones Afectadas              | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|--------------------------|---------------------------|------------------------------------|-----------------------|--------------|-----------------|
| SW000  | Debian 12                | Malware, Avería lógica    | Disponibilidad, Integridad         | Alta                  | Media        | Alto            |
| SW001  | Windows 11               | Malware, Vulnerabilidades | Disponibilidad, Integridad, Confidencialidad | Alta | Alta | Alto |
| SW002  | Clio Manage              | Avería lógica, Ataque cibernético | Disponibilidad, Integridad | Alta | Media | Alto |
| SW003  | Westlaw                  | Fuga de información       | Confidencialidad                    | Alta                  | Baja         | Medio           |
| SW004  | Microsoft Teams          | Interrupción de servicio  | Disponibilidad                     | Alta                  | Media        | Alto            |
| SW005  | Software de Gestión de Casos | Ataque cibernético, Errores de Usuario | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| SW006  | Herramientas de Investigación Legal | Pérdida de datos, Acceso no autorizado | Confidencialidad, Integridad | Alta | Baja | Medio |
| SW007  | Sistema de Facturación Legal | Errores de Usuario, Avería lógica | Disponibilidad, Integridad | Alta | Media | Alto |
| SW008  | Plataforma de Gestión Documental | Ataque cibernético, Fuga de información | Confidencialidad, Integridad | Alta | Media | Alto |
| SW009  | Software de Administración Financiera | Fraude, Avería lógica | Disponibilidad, Integridad, Confidencialidad | Alta | Baja | Medio |
| SW010  | Cliente de correo electrónico | Phishing, Malware | Disponibilidad, Confidencialidad | Alta | Media | Alto |
| SW011  | Suite Ofimática           | Vulnerabilidades, Malware | Disponibilidad, Integridad | Alta | Media | Alto |

### 4.5 [HW] Equipamiento informático (hardware) (impacto y riesgo)

El hardware es la base sobre la que se ejecutan todos los sistemas críticos. Los daños o fallos pueden causar interrupciones significativas y pérdida de datos, afectando la capacidad de la empresa para funcionar de manera eficiente.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| HW000  | Servidores Dell PowerEdge | Fuego, Inundación, Corte eléctrico | Disponibilidad | Alta | Media | Alto |
| HW001  | Estación de Trabajo HP ZBook | Contaminación mecánica, Robo | Disponibilidad, Integridad | Alta | Baja | Medio |
| HW002  | PC de Escritorio Lenovo ThinkCentre | Corte eléctrico, Avería lógica | Disponibilidad | Alta | Baja | Medio |
| HW003  | Dispositivos de Almacenamiento Synology | Fuego, Inundación | Disponibilidad, Integridad | Alta | Media | Alto |
| HW004  | Impresoras HP LaserJet | Corte eléctrico, Avería física | Disponibilidad | Media | Baja | Bajo |

### 4.6 [COM] Redes de comunicaciones (impacto y riesgo)

Las redes de comunicación son esenciales para la conectividad interna y externa. Un ataque o fallo en la red puede aislar a la firma, interrumpir la comunicación con los clientes y comprometer datos sensibles.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| COM001 | Red de Invitados | Acceso no autorizado, Malware | Disponibilidad, Integridad, Confidencialidad | Media | Alta | Alto |
| COM002 | Red 5G para Dispositivos Móviles | Interrupción de servicio, Ataque cibernético | Disponibilidad | Alta | Media | Alto |
| COM003 | Fibra Óptica | Daño físico, Avería técnica | Disponibilidad | Alta | Baja | Medio |
| COM004 | Red de Alta Seguridad Interna | Ataque cibernético, Corte eléctrico | Disponibilidad, Confidencialidad | Alta | Media | Alto |
| COM005 | Red Inalámbrica Segura (WPA3) | Ataque cibernético, Interrupción de servicio | Disponibilidad, Confidencialidad | Alta | Media | Alto |

### 4.7 [Media] Soportes de información (impacto y riesgo)

Los soportes físicos y digitales de almacenamiento de información son fundamentales para la recuperación de datos y la continuidad del negocio. Su degradación o pérdida pueden resultar en la incapacidad para acceder a información legal importante.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| SI001  | Almacenamiento en Red (SAN) | Degradación, Avería técnica | Disponibilidad, Integridad | Alta | Baja | Medio |
| SI002  | Disco Duro Externo | Daño físico, Pérdida | Disponibilidad, Integridad | Alta | Media | Alto |
| SI003  | Tarjeta de Memoria | Pérdida, Daño físico | Disponibilidad, Integridad | Media | Alta | Alto |
| SI004  | Almacenamiento en la Nube | Ataque cibernético, Interrupción de servicio | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| SI005  | Disco Óptico (DVD) | Degradación, Daño físico | Disponibilidad, Integridad | Media | Baja | Bajo |

### 4.8 [AUX] Equipamiento auxiliar (impacto y riesgo)

Incluye todos los sistemas de soporte como alimentación eléctrica, climatización y seguridad física. Son activos que, aunque no están directamente relacionados con la prestación de servicios legales, su fallo puede tener un impacto crítico en las operaciones.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| AUX001 | Sistemas de Alimentación Ininterrumpida | Corte eléctrico, Fallo técnico | Disponibilidad | Alta | Media | Alto |
| AUX002 | Equipos de Climatización | Avería técnica, Corte eléctrico | Disponibilidad | Alta | Baja | Medio |
| AUX003 | Cableado Estructurado | Daño físico, Sabotaje | Disponibilidad, Integridad | Alta | Baja | Medio |
| AUX004 | Sistemas de Detección y Extinción de Incendios | Fallo técnico, Corte eléctrico | Disponibilidad | Alta | Baja | Medio |
| AUX005 | Generadores Eléctricos | Corte eléctrico, Fallo técnico | Disponibilidad | Alta | Baja | Medio |

### 4.9 [L] Instalaciones (impacto y riesgo)

Las instalaciones físicas de la firma, como el edificio principal y las salas de servidores, son esenciales para el funcionamiento diario. Desastres naturales o fallos estructurales podrían poner en riesgo la seguridad del personal y la infraestructura tecnológica.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| L001   | Edificio Principal | Fuego, Inundación, Terremoto | Disponibilidad, Integridad | Muy Alta | Baja | Alto |
| L002   | Departamento Legal | Fuego, Inundación | Disponibilidad, Integridad | Alta | Baja | Medio |
| L003   | Centro Tecnológico | Fuego, Inundación, Ataque cibernético | Disponibilidad, Integridad, Confidencialidad | Muy Alta | Media | Alto |
| L004   | Sala de Servidores | Fuego, Inundación, Contaminación | Disponibilidad, Integridad | Muy Alta | Media | Alto |

### 4.10 [P] Personal (impacto y riesgo)

El personal es el activo más valioso de la empresa. Errores humanos, fraude o pérdida de empleados clave pueden tener un impacto profundo en la firma, desde la pérdida de conocimientos especializados hasta la vulnerabilidad ante amenazas internas.

| Código | Nombre del Activo | Tipo de Amenaza | Dimensiones Afectadas | Valoración de Impacto | Probabilidad | Nivel de Riesgo |
|--------|-------------------|-----------------|-----------------------|-----------------------|---------------|-----------------|
| P001   | Abogados | Errores de Usuario, Fraude | Integridad, Confidencialidad | Alta | Media | Alto |
| P002   | Personal de TI | Errores de Usuario, Fraude | Disponibilidad, Integridad, Confidencialidad | Alta | Media | Alto |
| P003   | Personal Administrativo | Errores de Usuario, Fraude | Integridad, Confidencialidad | Alta | Media | Alto |
| P004   | Personal de Seguridad | Sabotaje, Errores de Usuario | Disponibilidad, Integridad | Alta | Baja | Medio |
| P005   | Personal de Mantenimiento | Errores de Usuario, Sabotaje | Disponibilidad, Integridad | Media | Baja | Medio |
