## 2 Catalogo general de activos

## Bufete de Abogados

Identificar y clasificar los activos es impresncindible para documentar el estado de la empresa, y también para entender las posibles amenazas y las medidas de seguridad adecuadas. A continuación explico como funciona e incluyo algunos de los posibles activos y puede cambiar con el tiempo dependendiendo del desarrollo de la empresa con el tiempo. 

La implementación de la metodología MAGERIT consiste en la creación de un catálogo de activos. Este proceso, esencial antes de tomar decisiones sobre seguridad, implica la identificación precisa de los activos de la empresa. Según la norma UNE 71504:2008 [6] (pdf de referencia), un activo se define como cualquier componente o funcionalidad en un sistema de información vulnerable a ataques deliberados o accidentales con consecuencias para la organización. Estos abarcan información, datos, servicios, aplicaciones (software), equipos (hardware), comunicaciones, recursos administrativos, recursos físicos y recursos humanos.

Dentro de un sistema de información, identificamos dos categorías principales de activos: la información y los servicios que proporciona. Subordinados a estos, encontramos otros elementos clave, desde datos y servicios auxiliares hasta aplicaciones informáticas, equipos informáticos, soportes de información, equipamiento auxiliar, redes de comunicaciones, instalaciones y el personal operativo.

Cada activo tiene un valor, que no se refiere simplemente al costo, sino a la importancia que tiene para la empresa. Esta valoración se realiza considerando dimensiones críticas de seguridad, tales como la confidencialidad, integridad y disponibilidad del activo.

En el ámbito de los servicios digitales, se añaden dos dimensiones adicionales relacionadas con el conocimiento de los actores involucrados: la autenticidad de los usuarios y la trazabilidad del uso del servicio (más en su respectiva parte mas adelante).

Para evaluar los activos, se usan escalas de valores que permitan una comparación efectiva de riesgos. Es crucial emplear una escala común para todas las dimensiones, preferiblemente logarítmica y centrada en diferencias relativas de valor. MAGERIT ofrece dos escalas, una más sencilla y otra más detallada. La elección de una escala sencilla de diez valores, adaptada a la envergadura del despacho y sus activos, facilita la identificación de elementos despreciables y aquellos irremplazables.

Este proceso de catalogar activos y asignarles valor no solo establece una base sólida para la seguridad, sino que también proporciona un marco homogéneo para analizar riesgos de manera efectiva y tomar decisiones informadas.

Los puntos de la siguiente tabla, organizan los activos en una jerarquía, asignándoles un código que muestra su posición en la jerarquía, un nombre y una breve descripción de lo que representa cada tipo de activo. Los activos No tienen que ser estrictamente como tal, y perfectamente pueden pertenecer a diferentes categorias.

### 2.1 Inventario de activos (sin terminar)

| Número | Tipo de Activo                            | Descripción                                      |
|--------|------------------------------------------|--------------------------------------------------|
| 1      | [I] Activos Esenciales                   | Activos críticos para la operación del bufete    |
| 2      | [D] Datos / Información                   | Casos legales en curso                           |
| 3      | [K] Claves Criptográficas                 | Claves de acceso a información sensible          |
| 4      | [S] Servicios                             | Servicios de investigación legal                 |
| 5      | [SW] Software - Aplicaciones informáticas | Sistema de gestión de casos                       |
| 6      | [HW] Equipamiento informático (hardware)  | Computadoras y servidores                        |
| 7      | [COM] Redes de comunicaciones             | Red interna del bufete                           |
| 8      | [Media] Soportes de información           | Copias de seguridad en la nube                   |
| 9      | [AUX] Equipamiento auxiliar               | Sistemas de seguridad física                     |
| 10     | [L] Instalaciones                         | Oficinas y salas de reuniones                    |
| 11     | [P] Personal                              | Abogados y personal legal                        |



La valoración es una forma de asignar un puntaje o evaluación a cada activo en diferentes dimensiones de seguridad. Generalmente se utiliza para indicar cuánto valor tiene cada activo para la organización en términos de:

- D (Disponibilidad): ¿Qué tan importante es que este activo esté siempre disponible?
- I (Integridad): ¿Qué tan crítico es mantener la integridad o exactitud de este activo?
- C (Confidencialidad): ¿Qué tan sensible o confidencial es la información contenida en este activo?
- A (Autenticidad): ¿Cuán importante es asegurar que este activo sea auténtico y provenga de una fuente confiable?
- T (Trazabilidad): ¿Cuánta importancia se le da al seguimiento y registro de las acciones relacionadas con este activo?

La valoración se realiza utilizando una escala, que puede ser numérica (por ejemplo, del 1 al 10) o cualitativa (baja, media, alta). En el ejemplo que proporcioné anteriormente, utilicé una escala numérica entre corchetes [D/I/C/A/T] para representar la valoración en cada dimensióna modo de lo visto en la documentación.

### 2.2 Fichas detalle archivo

Las fichas son documentos o formularios que contienen información detallada sobre un elemento específico. En la metodología MAGERIT para la gestión de riesgos en sistemas de información, las fichas de detalle de activos son registros detallados para cada tipo de activo identificado en el catálogo. Cada ficha proporciona información específica sobre el activo, como su código de identificación, nombre, descripción, y cualquier otra información relevante que facilite su gestión y evaluación de riesgos.

Estas fichas (mas bien herramientas prácticas) ayudan a documentar y organizar la información sobre los activos del bufete en este caso. Además, son fundamentales para llevar a cabo evaluaciones de riesgos, ya que proporcionan datos detallados de cada activo, así como sus posibles amenazas y las salvaguardas aplicadas.


### 2.2.1 [I] Activos esenciales

Los activos esenciales forman el núcleo de la infraestructura, comprendiendo elementos vitales para el funcionamiento del bufete. Estos pueden incluir información crítica, servicios fundamentales, y cualquier otro componente que sea indispensable para la operatividad diaria.

| Código | Nombre | Descripción |
|--------|--------|-------------|
| AE001  | Archivo Digital de Casos | Almacena información crítica de casos, indispensable para la práctica legal diaria. |
| AE002  | Sistema de Comunicaciones | Facilita la comunicación interna y externa, siendo vital para la colaboración y la prestación de servicios. |

### 2.2.2 [A] Arquitectura del sistema

La arquitectura del sistema engloba los elementos que sustentan la infraestructura tecnológica del bufete. Estos pueden abarcar desde servidores y redes hasta la disposición física de los equipos.

| Código | Nombre | Descripción |
|--------|--------|-------------|
| AS001  | Servidores Centrales | Componentes esenciales que respaldan la infraestructura informática, garantizando la disponibilidad y el rendimiento. |
| AS002  | Red de Área Local (LAN) | Facilita la comunicación interna, conectando equipos y permitiendo el intercambio eficiente de datos. |

### 2.2.3 [D] Datos / Información

### 2.2.4 [K] Claves criptográficas

### 2.2.5 [S] Servicios

### 2.2.6 [SW] Software - Aplicaciones informáticas

### 2.2.7 [HW] Equipamiento informático (hardware)

### 2.2.8 [COM] Redes de comunicaciones

### 2.2.9 [Media] Soportes de información

### 2.2.10 [AUX] Equipamiento auxiliar

### 2.2.11 [L] Instalaciones

### 2.2.12 [P] Personal

