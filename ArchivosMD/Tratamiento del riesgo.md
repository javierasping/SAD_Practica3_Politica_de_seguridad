[N.1] Fuego					--> Obligatoria
[N.2] Daños por agua		--> Obligatoria			

[I.1] Contaminación mecánica
[I.2] Avería de origen físico o lógico
[I.3] Corte del suministro eléctrico        --> Obligatoria
[I.4]  Averías en la Electrónica de Red (Switches y Routers)    --> Obligatoria

[NI.1]  Errores de los usuarios 
[NI.2]  Errores de los usuarios
[NI.3]  Errores de configuración
[NI.4]  Difusión de software dañino
[NI.5] Escapes de información   --> Obligatoria
[NI.6] Alteración de la información
[NI.7] Destrucción de la información

[AI.1] Acceso no autorizados al CPD --> Obligatoria
[AI.2] Ransomware --> Obligatoria
[AI.3] Conflicto Armado --> Obligatoria
[AI.4] Phishing --> Obligatoria
[AI.5] Robo --> Obligatoria
[AI.6] Compromiso de credenciales --> Obligatoria
[AI.7] Ataques de denegación de servicio SYN Flood --> Obligatoria

[AI.8] Vulnerabilidades de las aplicaciones
[AI.9] Fugas de información en la nube

Hay que desarrollar 1 apartado para cada amenaza indicando que hay que hacer cuando el riego se materialize y quien tiene que hacerlo .


Lo que hay aqui abajo no cumple eso ..... 


Nota Javi .


## 6 Tratamiento del riesgo

El tratamiento del riesgo consiste en aplicar medidas adecuadas para reducir, transferir, evitar o aceptar los riesgos identificados en la evaluación. En el contexto de nuestra firma legal, el tratamiento de riesgos se enfoca en la protección de activos críticos, asegurando la confidencialidad, integridad y disponibilidad de la información.

### 6.1 [D][info] Datos / Información (tratamiento del riesgo)

#### 6.1.1 Activos I001-Fichero Clientes, D001-Expediente Cliente
- Implementar cifrado AES de 256 bits para el almacenamiento de datos sensibles.
- Restringir el acceso a los datos mediante controles de autenticación multifactor.
- Realizar auditorías regulares y monitorización de los accesos a ficheros de clientes.

#### 6.1.2 Activos D002-Datos acceso Servidor, D003-Datos acceso Usuarios
- Establecer políticas de contraseñas fuertes y rotación de credenciales periódica.
- Utilizar gestores de contraseñas seguros para almacenar y gestionar las credenciales de acceso.
- Aplicar el principio de privilegio mínimo, otorgando acceso únicamente a la información necesaria para cada rol.

#### 6.1.3 Activo D004-Backup Servidor
- Configurar copias de seguridad automáticas con frecuencia diaria y almacenamiento en ubicación segura y separada.
- Probar restauraciones periódicas para asegurar la viabilidad de las copias de seguridad.
- Utilizar sistemas de backup que incluyan verificación de integridad de los datos.

#### 6.1.4 Activos D005-Logs, D006-Ficheros configuraciones
- Almacenar logs en un sistema de gestión centralizado con acceso controlado.
- Proteger los ficheros de configuración mediante sistemas de detección de intrusos y auditorías periódicas.

### 6.2 [K] Claves criptográficas (tratamiento del riesgo)

#### 6.2.1 Activo K001-Certificados FMNT
- Renovar los certificados digitales antes de su expiración y revocar aquellos que ya no se utilicen.
- Almacenar los certificados digitales en módulos de seguridad hardware (HSM) para evitar su extracción y copia no autorizada.

### 6.3 [SW] Software – Aplicaciones informáticas (tratamiento del riesgo)

#### 6.3.1 Activo SW001-ERP
- Mantener el software ERP actualizado a su última versión para corregir vulnerabilidades conocidas.
- Realizar pruebas de penetración anuales por parte de terceros para identificar y corregir posibles debilidades.

#### 6.3.2 Activos SW002-Paquete ofimático, SW003-Cliente de correo, SW006- Navegador web
- Implementar políticas de actualización automática para mantener el software actualizado.
- Capacitar al personal sobre los riesgos de seguridad asociados al uso de aplicaciones ofimáticas y navegación web.

#### 6.3.3 Activo SW004-Antivirus
- Configurar el software antivirus para actualizaciones automáticas y escaneos periódicos.
- Asegurar que el antivirus esté configurado para proteger contra amenazas conocidas y desconocidas utilizando heurística avanzada.

#### 6.3.4 Activo SW005-Sistema de backup
- Establecer políticas de retención de datos y asegurar la encriptación de las copias de seguridad.
- Implementar controles de acceso robustos para el sistema de gestión de copias de seguridad.

#### 6.3.5 Activo SW007-Portal Web
- Utilizar un firewall de aplicaciones web (WAF) para proteger el portal web de ataques comunes.
- Realizar auditorías de seguridad del código y pruebas de carga antes de implementar actualizaciones importantes.

#### 6.3.6 Activo SW008-Sistema operativo Servidor
- Aplicar parches de seguridad de forma regular y automatizar este proceso cuando sea posible.
- Utilizar herramientas de configuración de sistemas para garantizar que los servidores se desplieguen con una configuración segura y homogénea.

#### 6.3.7 Activo SW009-Sistema operativo Cliente
- Asegurar que todas las estaciones de trabajo ejecuten la misma versión del sistema operativo con las últimas actualizaciones de seguridad.
- Restringir a los usuarios la capacidad de instalar software no autorizado en sus estaciones de trabajo.

### 6.4 [HW] Equipamiento informático (hardware) (tratamiento del riesgo)

#### 6.4.1 Activo HW001-Servidor
- Colocar los servidores en una sala segura con acceso controlado y sistemas de monitoreo ambiental.
- Mantener un inventario actualizado de hardware y realizar un mantenimiento preventivo regular.

#### 6.4.2 Activos HW002-Desktop, HW003-Workstation, HW004-Laptop
- Implementar soluciones de cifrado de disco completo para proteger la información en caso de robo o pérdida.
- Establecer una política de reemplazo para actualizar el hardware obsoleto y mantener la eficiencia.

#### 6.4.3 Activo HW005-Unidad de Backup
- Almacenar las unidades de backup en un lugar seguro y realizar pruebas periódicas de restauración de datos.
- Usar unidades de backup con cifrado integrado para proteger los datos en reposo.

#### 6.4.4 Activos HW006-Impresora, HW007-Plotter
- Configurar las impresoras para que sólo acepten trabajos de impresión de usuarios autenticados y registren los trabajos de impresión.
- Asegurar físicamente los dispositivos para prevenir el acceso no autorizado o el robo.

#### 6.4.5 Activos HW008-Router, HW009-Switch
- Mantener el firmware de los dispositivos de red actualizado y cambiar las contraseñas predeterminadas por contraseñas seguras y únicas.
- Configurar listas de control de acceso (ACL) para limitar el tráfico de red a lo estrictamente necesario.

### 6.5 [COM] Redes de comunicaciones (tratamiento del riesgo)

#### 6.5.1 Activos COM002-Red local y COM004-Red Wifi
- Implementar segregación de red para separar el tráfico crítico del tráfico general.
- Asegurar la red Wi-Fi con WPA3 y establecer un sistema de detección de intrusiones de red (NIDS).

#### 6.5.2 Activos COM001-Servicio de Telefonía y COM003-ADSL
- Utilizar VPNs para comunicaciones a través de servicios de telefonía y ADSL para garantizar la seguridad de los datos en tránsito.
- Monitorear y gestionar el tráfico para detectar y responder a actividades sospechosas.

### 6.6 [Media] Soportes de información (tratamiento del riesgo)

#### 6.6.1 Activos [MEDIA001]-Memorias USB y [MEDIA002]-Discos USB
- Restringir el uso de dispositivos USB no autorizados mediante políticas de grupo.
- Cifrar todos los dispositivos USB utilizados para transferir datos sensibles.

### 6.7 [AUX] Equipamiento auxiliar (tratamiento del riesgo)

#### 6.7.1 Activo AUX001-SAI
- Realizar pruebas regulares del SAI para garantizar su funcionamiento en caso de interrupción del suministro eléctrico.
- Configurar alertas para notificar al personal de TI sobre fallas o mantenimiento requerido.

### 6.8 [L] Instalaciones (tratamiento del riesgo)

#### 6.8.1 Activo L001-Edificio empresa
- Contratar seguros adecuados para proteger contra daños a la propiedad y responsabilidad civil.
- Implementar medidas de seguridad física como cámaras de vigilancia y controles de acceso.

#### 6.8.2 Activo L002-Cuarto de comunicaciones
- Utilizar sistemas de extinción de incendios que no dañen el equipo electrónico.
- Mantener el cuarto de comunicaciones a una temperatura y humedad controladas para evitar daños en los equipos.

### 6.9 [P] Personal (tratamiento del riesgo)
- Desarrollar programas de formación y concienciación en seguridad de la información.
- Establecer procedimientos de respuesta ante incidentes y asignar roles y responsabilidades claras.
