## 5 Evaluación de salvaguardas

La evaluación de salvaguardas es un componente crítico en la gestión de la seguridad informática. Se realiza tras un análisis exhaustivo de los riesgos asociados a cada activo dentro de la organización. Esta evaluación toma en cuenta las amenazas potenciales y las contramedidas establecidas para mitigarlas. La metodología aplicada se basa en los principios de MAGERIT (Metodología de Análisis y Gestión de Riesgos de los Sistemas de Información), que es un estándar reconocido para la administración de riesgos informáticos.

El proceso comienza con la identificación de activos críticos, seguido de un análisis de las amenazas y vulnerabilidades que los afectan. Posteriormente, se revisan las salvaguardas existentes, que son los controles y medidas de seguridad implementados para proteger estos activos. La efectividad de estas salvaguardas se evalúa en términos de su capacidad para reducir la probabilidad de ocurrencia de una amenaza o minimizar su impacto. Esta evaluación considera varios factores, como la adecuación de la salvaguarda al riesgo específico, la fiabilidad de la implementación y la respuesta ante incidentes previos.

La efectividad de las salvaguardas se clasifica en tres niveles:

- **Alta**: Indica que la salvaguarda reduce significativamente la probabilidad de la amenaza o su impacto potencial, y que hay evidencia sólida de su desempeño efectivo.
- **Media**: Sugiere que la salvaguarda tiene una capacidad moderada de mitigación y puede requerir ajustes o refuerzos adicionales para ser completamente efectiva.
- **Baja**: Refleja que la salvaguarda ofrece una protección mínima y es necesaria una revisión urgente para mejorar la seguridad del activo.

La tabla siguiente muestra la evaluación de las salvaguardas para varios activos, resaltando las amenazas potenciales identificadas y la efectividad de las medidas de protección aplicadas. Esta información es vital para la toma de decisiones informadas sobre dónde enfocar los esfuerzos de mejora en la infraestructura de seguridad.

Es importante resaltar que la seguridad es un proceso dinámico. La organización debe revisar continuamente la efectividad de sus salvaguardas frente a un panorama de amenazas en constante evolución y adaptar sus estrategias de protección en consecuencia. Estas tablas se actualizan regularmente para reflejar los cambios en la infraestructura, las prácticas de trabajo y el entorno tecnológico.

La presente evaluación es el resultado de una colaboración estrecha entre los equipos de seguridad, TI y las unidades de negocio, asegurando que la protección de los activos está alineada con las necesidades y los objetivos estratégicos de la organización.

### [D][info] Datos / Información (salvaguardas)

| Código | Nombre del Activo | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|-------------------|-------------------|------------------------|-------------|
| D001   | Casos legales en curso | Acceso no autorizado, Fuga de datos | Encriptación de datos, Control de acceso | Alta |
| D002   | Contratos y acuerdos | Alteración no intencionada, Pérdida de datos | Gestión de versiones, Backups regulares | Alta |
| D003   | Información confidencial del cliente | Divulgación de información, Phishing | Autenticación multifactor, Políticas de seguridad | Alta |
| D004   | Precedentes legales | Corrupción de datos, Ataques cibernéticos | Sistemas de detección de intrusos, Actualizaciones de seguridad | Media |
| D005   | Servicios Digitales | Interrupciones de servicio, Malware | Firewalls avanzados, Sistemas antivirus | Alta |

### [K] Claves criptográficas (salvaguardas)

| Código | Nombre del Activo | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|-------------------|-------------------|------------------------|-------------|
| KC001  | Claves de acceso a bases de datos | Acceso no autorizado, Fuga de información | Gestión centralizada de claves, Rotación de claves | Alta |
| KC002  | Claves de correo electrónico | Phishing, Interceptación de datos | Cifrado de correo electrónico, Educación de usuarios | Media |
| KC003  | Claves de acceso a sistemas internos | Ataques cibernéticos, Suplantación de identidad | Autenticación robusta, Políticas de acceso | Alta |
| KC004  | Claves de cifrado de documentos | Manipulación no autorizada, Acceso no autorizado | Cifrado de archivos, Control de acceso a documentos | Alta |
| KC005  | Claves de firma digital | Suplantación de identidad, Ataques de intermediarios | Infraestructura de clave pública (PKI), Sellos de tiempo | Alta |

### [SW] Software – Aplicaciones informáticas (salvaguardas)

| Código | Nombre del Software | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|---------------------|-------------------|------------------------|-------------|
| SW000  | Debian 12 | Vulnerabilidades del sistema | Parches de seguridad regulares, Auditorías de seguridad | Alta |
| SW001  | Windows 11 | Malware, Ataques cibernéticos | Actualizaciones automáticas, Protección antivirus | Alta |
| SW002  | Clio Manage | Pérdida de datos, Interrupciones de servicio | Backups en la nube, Alta disponibilidad | Media |
| SW003  | Westlaw | Acceso no autorizado, Fuga de información | Autenticación robusta, Encriptación de datos | Alta |
| SW004  | Microsoft Teams | Interceptación de datos, Malware | Comunicaciones cifradas, Gestión de identidades y accesos | Alta |

### [HW] Equipamiento informático (hardware) (salvaguardas)

| Código | Nombre del Hardware | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|---------------------|-------------------|------------------------|-------------|
| HW000  | Servidores Dell PowerEdge | Fallos de hardware, Cortes de energía | Sistemas UPS, Mantenimiento preventivo | Alta |
| HW001  | Estación de Trabajo HP ZBook | Robo, Daño físico | Seguridad física, Cifrado de disco completo | Media |
| HW002  | PC de Escritorio Lenovo ThinkCentre | Malware, Ataques cibernéticos | Software de seguridad, Actualizaciones regulares | Alta |
| HW003  | Dispositivos de Almacenamiento Synology | Fallos de hardware, Pérdida de datos | RAID, Backups regulares | Alta |
| HW004  | Impresoras HP LaserJet | Acceso no autorizado, Fallos de hardware | Gestión de acceso a la impresora, Mantenimiento regular | Media |

### [COM] Redes de comunicaciones (salvaguardas)

| Código | Nombre de la Red | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|------------------|-------------------|------------------------|-------------|
| COM001 | Red de Invitados | Acceso no autorizado, Malware | Aislamiento de red, Monitorización de tráfico | Alta |
| COM002 | Red 5G para Dispositivos Móviles | Interrupciones de servicio, Ataques cibernéticos | Tecnología de seguridad 5G, Gestión de dispositivos móviles | Alta |
| COM003 | Fibra Óptica | Daño físico, Interrupción de servicio | Protección física, Redundancia de ruta | Media |
| COM004 | Red de Alta Seguridad Interna | Ataques cibernéticos, Fuga de datos | Firewalls de última generación, Segmentación de red | Alta |
| COM005 | Red Inalámbrica Segura (WPA3) | Ataques cibernéticos, Intercepción de datos | WPA3, Monitorización y gestión de acceso | Alta |

### [Media] Soportes de información (salvaguardas)

| Código | Nombre del Soporte | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|--------------------|-------------------|------------------------|-------------|
| SI001  | Almacenamiento en Red (SAN) | Pérdida de datos, Fallos técnicos | Sistemas de redundancia, Protocolos de recuperación | Alta |
| SI002  | Disco Duro Externo | Pérdida, Daño físico | Cifrado de datos, Carcasas protectoras | Media |
| SI003  | Tarjeta de Memoria | Pérdida, Daño físico | Cifrado de datos, Uso restringido | Media |
| SI004  | Almacenamiento en la Nube | Ataques cibernéticos, Interrupciones de servicio | Autenticación multifactor, Acuerdos de nivel de servicio (SLA) | Alta |
| SI005  | Disco Óptico (DVD) | Degradación, Daño físico | Almacenamiento en condiciones controladas, Digitalización | Baja |

### [AUX] Equipamiento auxiliar (salvaguardas)

| Código | Nombre del Auxiliar | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|---------------------|-------------------|------------------------|-------------|
| AUX001 | Fuentes de Alimentación | Cortes de energía, Fallos técnicos | Sistemas UPS, Mantenimiento regular | Alta |
| AUX002 | Sistemas de Alimentación Ininterrumpida | Cortes de energía, Fallos técnicos | Mantenimiento de baterías, Pruebas regulares | Alta |
| AUX003 | Equipos de Climatización | Sobrecalentamiento, Fallos técnicos | Mantenimiento preventivo, Monitorización de temperatura | Alta |
| AUX004 | Cableado Estructurado | Daño físico, Sabotaje | Canalizaciones protegidas, Gestión de cableado | Alta |
| AUX005 | Generadores Eléctricos | Cortes de energía prolongados, Desastres naturales | Generadores de respaldo, Combustible almacenado | Media |

### [L] Instalaciones (salvaguardas)

| Código | Nombre de la Instalación | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|---------------------------|-------------------|------------------------|-------------|
| L001   | Edificio Principal | Fuego, Inundación, Terremoto | Sistemas contra incendios, Seguro de propiedad | Alta |
| L002   | Departamento Legal | Acceso no autorizado, Fuego | Control de acceso, Detectores de humo | Alta |
| L003   | Centro Tecnológico | Ataques cibernéticos, Fuego | Sala segura, Sistemas de supresión de fuego | Alta |
| L004   | Sala de Servidores | Sobrecalentamiento, Fallos de hardware | Climatización controlada, Mantenimiento de hardware | Alta |

### [P] Personal (salvaguardas)

| Código | Rol del Personal | Amenaza Potencial | Salvaguardas Aplicadas | Efectividad |
|--------|------------------|-------------------|------------------------|-------------|
| P001   | Abogados | Errores de Usuario, Fraude | Capacitación en seguridad, Políticas de manejo de información | Alta |
| P002   | Personal de TI | Errores de Usuario, Ataques cibernéticos | Certificaciones profesionales, Protocolos de seguridad | Alta |
| P003   | Personal Administrativo | Errores de Usuario, Divulgación de información | Controles de acceso a datos, Acuerdos de confidencialidad | Alta |
| P004   | Personal de Seguridad | Sabotaje, Acceso no autorizado | Verificación de antecedentes, Entrenamiento en seguridad física | Alta |
| P005   | Personal de Mantenimiento | Errores de Usuario, Daño accidental | Protocolos de trabajo, Seguros de responsabilidad | Media |

### Medidas

#### Protección Avanzada de Datos e Información

**Activos que se protegen:**
- D001, Casos legales en curso
- D002, Contratos y acuerdos
- D003, Información confidencial del cliente

**Objetivo:**
El principal objetivo de este proyecto es fortalecer la protección de los datos críticos del bufete, incluyendo los casos legales en curso, los contratos y la información confidencial de los clientes. Se implementarán medidas avanzadas de cifrado y controles de acceso para mitigar riesgos como el acceso no autorizado y la fuga de datos.

**Prioridad:**
Alta. Este proyecto es crítico y debe iniciarse a la mayor brevedad posible, dada su importancia para la seguridad de la información del bufete.

**Ubicación temporal:**
Se estima que el proyecto requerirá una dedicación de 3 horas diarias durante un periodo de 4 semanas.

**Salvaguardas:**
- Encriptación de datos: Se aplicará cifrado de extremo a extremo para los datos en tránsito y en reposo.
- Control de acceso: Se reforzarán las políticas de autenticación y autorización, incluyendo el uso de autenticación multifactor.
- Backups regulares: Se establecerá un calendario de copias de seguridad periódicas y automáticas.

**Unidad responsable de ejecución:**
Responsable de seguridad de la información o CISO (Chief Information Security Officer).

**Costes:**
- Recursos humanos: 60 horas del CISO.
- Inversiones en software de cifrado y sistemas de backup, estimado en 10.000€.

**Descripción de tareas:**
- Evaluación de las soluciones de cifrado actuales y selección de nuevas tecnologías si es necesario.
- Implementación de controles de acceso basados en roles para datos sensibles.
- Configuración y automatización de backups regulares.
- Desarrollo y documentación de políticas y procedimientos de seguridad actualizados.
- Formación y concienciación para el personal sobre las nuevas políticas y procedimientos de seguridad.

Este proyecto busca no solo cumplir con las normativas de protección de datos más estrictas sino también reforzar la confianza de los clientes en la capacidad del bufete para proteger su información. La finalización exitosa de este proyecto es esencial para la integridad y reputación de la firma.


#### Protección Avanzada de Claves Criptográficas

**Activos que se protegen:**
- KC001, Claves de acceso a bases de datos
- KC002, Claves de correo electrónico
- KC003, Claves de acceso a sistemas internos

**Objetivo:**
Refinar la gestión de claves criptográficas para asegurar la confidencialidad e integridad de la información del bufete. Se fortalecerán las políticas de control y rotación de claves para contrarrestar amenazas como el acceso no autorizado y la suplantación de identidad.

**Prioridad:**
Alta. La seguridad de las claves criptográficas es fundamental para mantener la protección de datos y la infraestructura TI.

**Ubicación temporal:**
Con una dedicación estimada de 2 horas al día, se espera completar el proyecto en 3 semanas.

**Salvaguardas:**
- Gestión centralizada de claves: Implementar un sistema de gestión de claves centralizado para monitorear y controlar la distribución de claves.
- Rotación de claves: Establecer un proceso automático para la rotación periódica de claves.
- Educación de usuarios: Capacitar a los empleados en prácticas de seguridad para el manejo de claves criptográficas.

**Unidad responsable de ejecución:**
Responsable de seguridad de la información o CISO.

**Costes:**
- Recursos humanos: 42 horas del CISO y equipo de TI.
- Software de gestión de claves criptográficas, estimado en 7.000€.

**Descripción de tareas:**
- Selección e implementación de una solución de gestión de claves centralizada.
- Configuración de la rotación automática de claves.
- Desarrollo de materiales de formación y realización de sesiones de capacitación.


#### Fortalecimiento de Software y Aplicaciones

**Activos que se protegen:**
- SW000, Debian 12
- SW001, Windows 11
- SW002, Clio Manage

**Objetivo:**
Actualizar y reforzar el software y aplicaciones informáticas para proteger contra vulnerabilidades y ataques cibernéticos. Las salvaguardas se centrarán en mantener los sistemas operativos y las aplicaciones críticas seguras y funcionales.

**Prioridad:**
Alta. La seguridad del software es crucial para la operatividad y protección contra amenazas informáticas.

**Ubicación temporal:**
Se anticipa que el proyecto requiera 3 horas diarias por parte del equipo de TI, con una duración estimada de 1 mes.

**Salvaguardas:**
- Parches de seguridad regulares: Programar actualizaciones automáticas y revisión de parches.
- Auditorías de seguridad: Realizar auditorías regulares para detectar y remediar vulnerabilidades.
- Protección antivirus: Asegurar que todas las estaciones de trabajo y servidores tengan protección antivirus actualizada.

**Unidad responsable de ejecución:**
Equipo de TI, bajo la supervisión del CISO.

**Costes:**
- Recursos humanos: 60 horas del equipo de TI.
- Herramientas de seguridad y licencias de software, estimado en 15.000€.

**Descripción de tareas:**
- Programar y verificar la implementación de actualizaciones de seguridad.
- Realizar auditorías periódicas de seguridad del sistema.
- Renovar y actualizar suscripciones de software antivirus y herramientas de seguridad.


#### Seguridad de Hardware Informático

**Activos que se protegen:**
- HW000, Servidores Dell PowerEdge
- HW001, Estación de Trabajo HP ZBook
- HW002, PC de Escritorio Lenovo ThinkCentre

**Objetivo:**
Incrementar la resiliencia y seguridad del hardware informático frente a fallos físicos y ataques externos, asegurando la continuidad de las operaciones del bufete.

**Prioridad:**
Alta. El correcto funcionamiento del hardware es vital para el negocio.

**Ubicación temporal:**
Se estima una duración de 4 semanas con una dedicación de 2 horas diarias.

**Salvaguardas:**
- Sistemas UPS: Proteger contra cortes de energía y fluctuaciones.
- Mantenimiento preventivo: Realizar revisiones periódicas para anticipar y prevenir fallos.

**Unidad responsable de ejecución:**
Departamento de Infraestructura TI.

**Costes:**
- Recursos humanos: 40 horas del personal técnico.
- Inversión en UPS y componentes de repuesto, estimado en 8.000€.

**Descripción de tareas:**
- Instalación y configuración de UPS para servidores y estaciones de trabajo.
- Desarrollo de un programa de mantenimiento preventivo.
- Formación del personal en el manejo y cuidado del hardware.


#### Optimización de la Red de Comunicaciones

**Activos que se protegen:**
- COM001, Red de Invitados
- COM004, Red de Alta Seguridad Interna

**Objetivo:**
Fortalecer la infraestructura de la red para prevenir accesos no autorizados y asegurar la integridad de las comunicaciones del bufete.

**Prioridad:**
Alta. La protección de la red es crucial para mantener la confidencialidad y disponibilidad de los servicios del bufete.

**Ubicación temporal:**
Este proyecto tendrá una duración estimada de 3 semanas con una dedicación diaria de 2 horas.

**Salvaguardas:**
- Aislamiento de red: Crear VLANs para aislar la red de invitados.
- Firewalls de última generación: Implementar firewalls avanzados para proteger la red interna.

**Unidad responsable de ejecución:**
Responsable de redes y seguridad.

**Costes:**
- Recursos humanos: 30 horas del especialista en redes.
- Hardware y software para seguridad de red, estimado en 12.000€.

**Descripción de tareas:**
- Diseño e implementación de la arquitectura de red segregada.
- Configuración y puesta en marcha de firewalls avanzados.
- Monitoreo y ajuste continuo de las políticas de seguridad de la red.


#### Protección de Medios de Almacenamiento de Información

**Activos que se protegen:**
- SI001, Almacenamiento en Red (SAN)
- SI002, Disco Duro Externo
- SI003, Tarjeta de Memoria
- SI004, Almacenamiento en la Nube
- SI005, Disco Óptico (DVD)

**Objetivo:**
Asegurar la integridad y disponibilidad de la información almacenada en diferentes medios, implementando soluciones de cifrado y redundancia.

**Prioridad:**
Alta, dada la necesidad crítica de proteger la información almacenada de pérdidas y accesos no autorizados.

**Ubicación temporal:**
Se espera completar en 4 semanas con un compromiso de 2 horas diarias de trabajo.

**Salvaguardas:**
- Sistemas de redundancia para SAN y dispositivos de almacenamiento.
- Cifrado de datos para dispositivos externos y almacenamiento en la nube.
- Políticas de acceso y uso restringido para medios físicos.

**Unidad responsable de ejecución:**
Equipo de gestión de datos y almacenamiento.

**Costes:**
- Mano de obra: Aproximadamente 48 horas de trabajo del equipo técnico.
- Inversión en software/hardware de cifrado y sistemas de redundancia, estimado en 10.000€.

**Descripción de tareas:**
- Instalación y configuración de sistemas RAID para SAN.
- Implementación de soluciones de cifrado para discos duros externos y almacenamiento en la nube.
- Establecimiento de políticas para el manejo seguro de tarjetas de memoria y DVDs.


#### Fortificación de Equipamiento Auxiliar

**Activos que se protegen:**
- AUX001, Fuentes de Alimentación
- AUX002, Sistemas de Alimentación Ininterrumpida (SAI)
- AUX003, Equipos de Climatización
- AUX004, Cableado Estructurado
- AUX005, Generadores Eléctricos

**Objetivo:**
Mejorar la resiliencia de los sistemas de soporte críticos para garantizar la operatividad continua del bufete.

**Prioridad:**
Media. Si bien no están directamente implicados en las operaciones diarias, su fallo puede tener consecuencias graves.

**Ubicación temporal:**
Con un compromiso de 1 hora diaria, el proyecto tendrá una duración estimada de 6 semanas.

**Salvaguardas:**
- Mantenimiento preventivo para todos los equipos auxiliares.
- Pruebas de carga y funcionamiento para los SAI y generadores eléctricos.
- Inspecciones y actualizaciones del cableado estructurado.

**Unidad responsable de ejecución:**
Equipo de mantenimiento de instalaciones y operaciones.

**Costes:**
- Mano de obra: 30 horas del personal de mantenimiento.
- Inversión en equipos de mantenimiento y piezas de repuesto, estimado en 5.000€.

**Descripción de tareas:**
- Programación y realización de mantenimiento preventivo para todos los equipos auxiliares.
- Pruebas periódicas de los SAI y generadores para asegurar su funcionamiento óptimo.
- Revisión y mejora del cableado estructurado para prevenir fallos y optimizar el rendimiento.

#### Aseguramiento de las Instalaciones

**Activos que se protegen:**
- L001, Edificio Principal
- L002, Departamento Legal
- L003, Centro Tecnológico
- L004, Sala de Servidores

**Objetivo:**
Garantizar la seguridad física y la integridad de las instalaciones clave del bufete.

**Prioridad:**
Alta, debido a la importancia de proteger las áreas donde se maneja información sensible y se alojan recursos críticos.

**Ubicación temporal:**
Este proyecto se llevará a cabo durante 8 semanas con una asignación de 2 horas diarias.

**Salvaguardas:**
- Sistemas contra incendios y medidas de prevención de desastres.
- Control de acceso y sistemas de vigilancia mejorados.
- Protocolos de emergencia y planes de contingencia actualizados.

**Unidad responsable de ejecución:**
Administrador de las instalaciones y seguridad física.

**Costes:**
- Mano de obra: 64 horas de trabajo del personal de seguridad y mantenimiento.
- Inversión en sistemas de seguridad física y medidas de prevención, estimado en 20.000€.

**Descripción de tareas:**
- Instalación y actualización de sistemas contra incendios y de seguridad.
- Implementación de controles de acceso biométricos y circuito cerrado de televisión (CCTV).
- Elaboración de planes de contingencia y realización de simulacros de emergencia.

#### Capacitación y Concienciación del Personal

**Activos que se protegen:**
- P001, Abogados
- P002, Personal de TI
- P003, Personal Administrativo
- P004, Personal de Seguridad
- P005, Personal de Mantenimiento

**Objetivo:**
Desarrollar un programa integral de capacitación en seguridad de la información para todo el personal, reduciendo el riesgo de errores humanos y aumentando la respuesta a incidentes.

**Prioridad:**
Alta, considerando que el factor humano es crítico en la gestión de la seguridad de la información.

**Ubicación temporal:**
Se desarrollará a lo largo de 3 meses con sesiones semanales de capacitación.

**Salvaguardas:**
- Programas de capacitación en seguridad informática y buenas prácticas.
- Políticas de manejo de información y protocolos de respuesta ante incidentes.
- Simulacros de phishing y otros ejercicios prácticos.

**Unidad responsable de ejecución:**
Departamento de Recursos Humanos en colaboración con el CISO.

**Costes:**
- Mano de obra: 120 horas de los departamentos de RH y TI.
- Materiales y servicios de capacitación, estimado en 3.000€.

**Descripción de tareas:**
- Diseño e implementación de un programa de capacitación y concienciación.
- Coordinación de sesiones de capacitación y talleres prácticos.
- Evaluación del impacto de la capacitación y ajustes del programa según sea necesario.
