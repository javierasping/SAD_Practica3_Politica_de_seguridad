# SAD Práctica 1 - Definición de una Política de Seguridad

## Roles
- Coordinador : Fernández de Santaella Rodríguez, Andrés
- Portavoz : Rodríguez García, David
- Investigador : Canalo González, José Antonio 
- Secretario : Cruces Doval, Francisco Javier

## Desarrollo de la Práctica
1. Identificación y valoración de los activos del sistema (2)
    - Fernández de Santaella Rodríguez, Andrés: Redacción del apartado
2. Identificación de amenazas(3)
    - Cruces Doval, Francisco Javier: Redacción del apartado
3. Valoración de riesgos (4)
    - Rodríguez García, David: Redacción del apartado 
4. Estudio de medidas de protección (6)
    - Canalo González, José Antonio : Redacción del apartado
5. Redacción de una política de seguridad(1)
    - Responsabilidad grupal: Realización de la última fase

# ÍNDICE

## INTRODUCCIÓN

- 1 Contexto de la organización
    -  1.1 Introducción
    -  1.2 Estructura de la empresa
    -  1.3 Aspectos técnicos
    -  1.4 Políticas de seguridad de la información

- 2 Catalogo general de activos
    - 2.1 Inventario de activos
    - 2.2 Fichas detalle archivo
    - 2.2.1 [I] Activos esenciales
    - 2.2.2 [A] Arquitectura del sistema
    - 2.2.3 [D] Datos / Información
    - 2.2.4 [K] Claves criptográficas
    - 2.2.5 [S] Servicios
    - 2.2.6 [SW] Software - Aplicaciones informáticas
    - 2.2.7 [HW] Equipamiento informático (hardware)
    - 2.2.8 [COM] Redes de comunicaciones
    - 2.2.9 [Media] Soportes de información
    - 2.2.10 [AUX] Equipamiento auxiliar
    - 2.2.11 [L] Instalaciones
    - 2.2.12 [P] Personal

- 3 Identificación de amenazas
    - 3.1 [N] Desastres naturales
    - 3.2 [I] De origen industrial
    - 3.3 [E] Errores y fallos no intencionados
    - 3.4 [A] Ataques intencionados

- 4 Cálculo del riesgo
    - 4.1 [info] Activos esenciales (impacto y riesgo)
    - 4.2 [D] Datos / Información (impacto y riesgo)
    - 4.3 [K] Claves criptográficas (impacto y riesgo)
    - 4.4 [SW] Software - Aplicaciones informáticas (impacto y riesgo)
    - 4.5 [HW] Equipamiento informático (hardware) (impacto y riesgo)
    - 4.6 [COM] Redes de comunicaciones (impacto y riesgo)
    - 4.7 [Media] Soportes de información (impacto y riesgo)
    - 4.8 [AUX] Equipamiento auxiliar (impacto y riesgo)
    - 4.9 [L] Instalaciones (impacto y riesgo)
    - 4.10 [P] Personal (impacto y riesgo)

- 5 Evaluación de salvaguardas
    - 5.1 [D][info] Datos / Información (salvaguardas)
    - 5.2 [K] Claves criptográficas (salvaguardas)
    - 5.3 [SW] Software – Aplicaciones informáticas (salvaguardas)
    - 5.4 [HW] Equipamiento informático (hardware) (salvaguardas)
    - 5.5 [COM] Redes de comunicaciones (salvaguardas)
    - 5.6 [Media] Soportes de información (salvaguardas)
    - 5.7 [AUX] Equipamiento auxiliar (salvaguardas)
    - 5.8 [L] Instalaciones (salvaguardas)
    - 5.9 [P] Personal (salvaguardas)

- 6 Tratamiento del riesgo
    - 6.1 [D][info] Datos / Información (tratamiento del riesgo)
    - 6.1.1 Activos I001-Fichero Clientes, D001-Expediente Cliente
    - 6.1.2 Activos D002-Datos acceso Servidor, D003-Datos acceso Usuarios
    - 6.1.3 Activo D004-Backup Servidor
    - 6.1.4 Activos D005-Logs, D006-Ficheros configuraciones
    - 6.2 [K] Claves criptográficas (tratamiento del riesgo)
    - 6.2.1 Activo K001-Certificados FMNT
    - 6.3 [SW] Software – Aplicaciones informáticas (tratamiento del riesgo)
    - 6.3.1 Activo SW001-ERP
    - 6.3.2 Activos SW002-Paquete ofimático, SW003-Cliente de correo, SW006- Navegador web
    - 6.3.3 Activo SW004-Antivirus
    - 6.3.4 Activo SW005-Sistema de backup
    - 6.3.5 Activo SW007-Portal Web
    - 6.3.6 Activo SW008-Sistema operativo Servidor
    - 6.3.7 Activo SW009-Sistema operativo Cliente
    - 6.4 [HW] Equipamiento informático (hardware) (tratamiento del riesgo)
    - 6.4.1 Activo HW001-Servidor
    - 6.4.2 Activos HW002-Desktop, HW003-Workstation, HW004-Laptop
    - 6.4.3 Activo HW005-Unidad de Backup
    - 6.4.4 Activos HW006-Impresora, HW007-Plotter
    - 6.4.5 Activos HW008-Router, HW009-Switch
    - 6.5 [COM] Redes de comunicaciones (tratamiento del riesgo)
    - 6.5.1 Activos COM002-Red local y COM004-Red Wifi
    - 6.5.2 Activos COM001-Servicio de Telefonía y COM003-ADSL
    - 6.6 [Media] Soportes de información (tratamiento del riesgo)
    - 6.6.1 Activos [MEDIA001]-Memorias USB y [MEDIA002]-Discos USB
    - 6.7 [AUX] Equipamiento auxiliar (tratamiento del riesgo)
    - 6.7.1 Activo AUX001-SAI
    - 6.8 [L] Instalaciones (tratamiento del riesgo)
    - 6.8.1 Activo L001-Edificio empresa
    - 6.8.2 Activo L002-Cuarto de comunicaciones
    - 6.9 [P] Personal (tratamiento del riesgo)

- 7 Planes de seguridad
    - 7.1 Protección de cifrado
    - 7.2 Política de Seguridad Corporativa
    - 7.3 Formación y concienciación
    - 7.4 Copias de Seguridad
    - 7.5 Zona CPD
    - 7.6 Fortalecimiento Red
    - 7.7 Gestión de la Información
    - 7.8 ERP on Cloud
    - 7.9 Alta disponibilidad del Servidor
    - 7.10 Prevención-Control Seguridad(SIEM/IDS)
    - 7.11 Planificación Plan Director de Seguridad



- Bibliografía 
    - [SGCI buffete abogados](https://rua.ua.es/dspace/bitstream/10045/96787/1/Desarrollo_del_Plan_Director_de_Seguridad_para_un_bufete_Peco_Moreno_Agustin.pdf)
    - [SGCI pyme](https://rua.ua.es/dspace/bitstream/10045/102087/1/Esquema_Director_de_Seguridad_para_Empresas_pymes_d_Diaz_Perez_Juan_Salvador.pdf)
    - [SGSI ecomerce](https://rua.ua.es/dspace/bitstream/10045/135228/1/Diseno_y_desarrollo_del_SGSI_para_una_empresa_de_ecommerce_Amaro_Perez_Paola.pdf)
    - [SGCI Pequeña empresa](https://educacionadistancia.juntadeandalucia.es/centros/sevilla/pluginfile.php/515326/mod_resource/content/1/48ca15671b800.pdf)
