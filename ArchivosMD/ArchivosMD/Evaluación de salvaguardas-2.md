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

### [AUX] Equipamiento auxiliar (

salvaguardas)

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
