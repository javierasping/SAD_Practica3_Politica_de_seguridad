# SAD Práctica 1 - Definición de una Política de Seguridad de un bufete de abogados

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
    - Canalo González, José Antonio : Redacción del apartado
4. Estudio de medidas de protección (5)
    - Rodríguez García, David: Redacción del apartado


5. Redacción de una política de seguridad(1,6,7)
    - Responsabilidad grupal: Realización de la última fase

# ÍNDICE

## INTRODUCCIÓN


**Indice es temporal o de ejemplo para tener una guia de los diferentes apartados que hay que desarollar , escribe todo lo referenta a cada apartado dentro del archivo de md con el mismo nombre** 

- [1 Contexto de la organización](ArchivosMD/Contexto%20de%20la%20organización.md)
    -  1.1 Introducción
    -  1.2 Estructura de la empresa
    -  1.3 Aspectos técnicos
    -  1.4 Políticas de seguridad de la información

- [2 Catalogo general de activos](ArchivosMD/Catalogo%20general%20de%20activos.md)
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

- [3 Identificación de amenazas](ArchivosMD/Identificación%20de%20amenazas.md)
    - 3.1 [DN] Desastres naturales
    - 3.2 [OI] De origen industrial
    - 3.3 [NI] Errores y fallos no intencionados
    - 3.4 [AI] Ataques intencionados

- [4 Cálculo del riesgo](ArchivosMD/Cálculo%20del%20riesgo.md)
    - 4.1 [DN] Desastres naturales
    - 4.2 [OI] De origen industrial
    - 4.3 [NI] Errores y fallos no intencionados
    - 4.4 [AI] Ataques intencionados

- [5 Estudio de medidas de protección](ArchivosMD/Evaluación%20de%20salvaguardas.md) 
    - 5.1.1 Medidas Preventivas [N.1] Fuego
    - 5.1.2 Medidas Preventivas [N.2] Daños por Agua
    - 5.1.3 Medidas Preventivas [I.1] Contaminación Mecánica
    - 5.1.4 Medidas Preventivas [I.2] Avería de Origen Físico o Lógico
    - 5.1.5 Medidas Preventivas [I.3] Corte del Suministro Eléctrico
    - 5.1.6 Medidas Preventivas [I.4] Averías en la Electrónica de Red (Switches y Routers)
    - 5.1.7 Medidas Preventivas [NI.1] Errores de los Usuarios
    - 5.1.8 Medidas Preventivas [NI.2] Errores de los Usuarios
    - 5.1.9 Medidas Preventivas [NI.3] Errores de Configuración
    - 5.1.10 Medidas Preventivas [NI.4] Difusión de Software Dañino
    - 5.1.11 Medidas Preventivas [NI.5] Escapes de Información
    - 5.1.12 Medidas Preventivas [NI.6] Alteración de la Información
    - 5.1.13 Medidas Preventivas [NI.7] Destrucción de la Información
    - 5.1.14 Medidas Preventivas [AI.1] Acceso no Autorizado al CPD
    - 5.1.15 Medidas Preventivas [AI.2] Ransomware
    - 5.1.16 Medidas Preventivas [AI.3] Conflicto Armado
    - 5.1.17 Medidas Preventivas [AI.4] Phishing
    - 5.1.18 Medidas Preventivas [AI.5] Robo
    - 5.1.19 Medidas Preventivas [AI.6] Compromiso de Credenciales
    - 5.1.20 Medidas Preventivas [AI.7] Ataques de Denegación de Servicio SYN Flood
    - 5.1.21 Medidas Preventivas [AI.8] Vulnerabilidades de las Aplicaciones
    - 5.1.22 Medidas Preventivas [AI.9] Fugas de Información en la Nube

- [6 Tratamiento del riesgo](ArchivosMD/Tratamiento%20del%20riesgo.md)
    - 6.1.1 Medidas  reactivas  [N.1] Fuego
    - 6.1.2 Medidas  reactivas  [N.2] Daños por Agua
    - 6.1.3 Medidas  reactivas  [I.1] Contaminación Mecánica
    - 6.1.4 Medidas  reactivas  [I.2] Avería de Origen Físico o Lógico
    - 6.1.5 Medidas  reactivas  [I.3] Corte del Suministro Eléctrico
    - 6.1.6 Medidas  reactivas  [I.4] Averías en la Electrónica de Red (Switches y Routers)
    - 6.1.7 Medidas  reactivas  [NI.1] Errores de los Usuarios
    - 6.1.8 Medidas  reactivas  [NI.2] Errores de los Usuarios
    - 6.1.9 Medidas  reactivas  [NI.3] Errores de Configuración
    - 6.1.10 Medidas reactivas  [NI.4] Difusión de Software Dañino
    - 6.1.11 Medidas reactivas  [NI.5] Escapes de Información
    - 6.1.12 Medidas reactivas  [NI.6] Alteración de la Información
    - 6.1.13 Medidas reactivas  [NI.7] Destrucción de la Información
    - 6.1.14 Medidas reactivas  [AI.1] Acceso no Autorizado al CPD
    - 6.1.15 Medidas reactivas  [AI.2] Ransomware
    - 6.1.16 Medidas reactivas  [AI.3] Conflicto Armado
    - 6.1.17 Medidas reactivas  [AI.4] Phishing
    - 6.1.18 Medidas reactivas  [AI.5] Robo
    - 6.1.19 Medidas reactivas  [AI.6] Compromiso de Credenciales
    - 6.1.20 Medidas reactivas  [AI.7] Ataques de Denegación de Servicio SYN Flood
    - 6.1.21 Medidas reactivas  [AI.8] Vulnerabilidades de las Aplicaciones
    - 6.1.22 Medidas reactivas  [AI.9] Fugas de Información en la Nube




- Bibliografía 
    - [SGCI bufete abogados](https://rua.ua.es/dspace/bitstream/10045/96787/1/Desarrollo_del_Plan_Director_de_Seguridad_para_un_bufete_Peco_Moreno_Agustin.pdf)
    - [SGCI pyme](https://rua.ua.es/dspace/bitstream/10045/102087/1/Esquema_Director_de_Seguridad_para_Empresas_pymes_d_Diaz_Perez_Juan_Salvador.pdf)
    - [SGSI comercio electrónico](https://rua.ua.es/dspace/bitstream/10045/135228/1/Diseno_y_desarrollo_del_SGSI_para_una_empresa_de_ecommerce_Amaro_Perez_Paola.pdf)
    - [SGCI Pequeña empresa](https://educacionadistancia.juntadeandalucia.es/centros/sevilla/pluginfile.php/515326/mod_resource/content/1/48ca15671b800.pdf)
