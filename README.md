<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br><img src="https://www.upc.edu.pe/static/img/logo_upc_red.png"></img><br>
    <br>
    <strong>Ingeniería de Software - 2025-01</strong><br>
    <br>
    <strong>1ASI0572 - DESARROLLO DE SOLUCIONES IOT - 2941</strong><br>  
    <br>
    <strong>Profesor: Marco Antonio Leon Baca</strong><br>
    <br> <strong>INFORME DE TRABAJO 1 - TB1</strong> 
</p>
<p align="center">
    <strong>Startup: Find&Park</strong><br>
    <strong>Producto: ParkUp</strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Miembro</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Vargas Revollé, Ariana</td>
            <td>u20221a928</td>
        </tr>
        <tr>
            <td>Obispo Rios, Lucero Abigail</td>
            <td>u202111465</td>
        </tr>
        <tr>
            <td>Cuevas Rios, Eric Fernando</td>
            <td>u202112766</td>
        </tr>
        <tr>
            <td>Elsner De La Torre Ugarte, Julio Esteban</td>
            <td>u202211654</td>
        </tr>
        <tr>
            <td>Herrera González, Luis Eduardo</td>
            <td>u202218227</td>
        </tr>
    </table>
</div>
<br>

---

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<div align="center">

| Versión | Fecha | Autor | Descripción de modificación | 
|:-------:|:-----:|:-----:|:----------------------------| 
|TB1| 25/05/25  |  <br>Vargas Revollé, Ariana<br> <br>Obispo Rios, Lucero Abigail<br> <br>Cuevas Rios, Eric Fernando<br> <br>Elsner De La Torre Ugarte, Julio Esteban<br> <br>Herrera González, Luis Eduardo<br>   | Investigación de mercado y del problema, obtención y análisis de requisitos, especificación de requisitos, y diseño de la solución de software.                           |
</div>

---

<div style="page-break-after: always;"></div>

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome)
### [Capítulo I: Presentación](#capítulo-i-presentación)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Needfinding](#capítulo-ii-needfinding)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)  
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
        - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
        - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
        - [4.1.1.3 Bounded Context Canvases](#4112-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Software Architecture Deployment Diagrams](#4124-software-architecture-deployment-diagrams)
- [4.2.X. Bounded Context: <Bounded Context Name>](#42X-bounded-context-bounded-context-name)
    - [4.2.X.1. Domain Layer](#42X1-domain-layer)
    - [4.2.X.2. Interface Layer](#42X2-interface-layer)
    - [4.2.X.3. Application Layer](#42X3-application-layer)
    - [4.2.X.4. Infrastructure Layer](#42X4-application-layer)
    - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42X5-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42X6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1, Bounded Context Domain Layer Class Diagrams](#42X61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2, Bounded Context Database Design Diagram](#42X62-bounded-context-database-design-diagram)

### [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ui-ux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
  - [5.2.4. Searching Systems](#524-searching-systems)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-ux-ui-design)
  - [5.4.1. Applications Wireframes](#541-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
  - [5.4.3. Applications User Flow Diagrams](#543-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

### [Capítulo VI: Product Implementation & Validation](#capítulo-vi-product-implementation-validation)
- [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide-conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services-applications-implementation)
    - [6.2.1. Sprint 1](#621-sprint-1)
        - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
        - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
        - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
        - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
        - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
        - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
        - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
        - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
        - [6.2.1.9. Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño de Entrevistas](#631-diseno-de-entrevistas)
    - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones según Heurísticas](#633-evaluaciones-segun-heuristicas)
- [6.4. Video About the Product](#64-video-about-the-product)


### [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
### [Bibliografía](#bibliografía)
### [Anexos](#anexos)

---
<div style="page-break-after: always;"></div>

# Student Outcome

<div align="justify">

| **Criterio Específico** | **Acciones Realizadas** | **Conclusiones** |
|-------------------------|-------------------------|------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | <br>- *Obispo Rios, Lucero Abigail*<br> <br>**TB1**<br>  <br>Participar en reuniones de equipo para definir el alcance del proyecto y la arquitectura. <br> <br>- *Cuevas Rios, Eric Fernando*<br> <br>**TB1** <br> <br>-<br> <br>- *Vargas Revollé, Ariana*<br> <br>**TB1**<br>  <br>-<br> <br>- *Elsner De La Torre Ugarte, Julio Esteban*<br> <br>**TB1**<br>  <br>Brindar ideas en reuniones cada semana del equipo con la finalidad de realizar retroalimentación y mejora de aspectos del infomre.<br> <br>- *Herrera González, Luis Eduardo*<br> <br>**TB1**<br>  <br>-<br> |  |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | <br>- *Obispo Ríos, Lucero Abigail*<br> <br>**TB1**<br>  <br>Participar en el proceso de asignación de tareas y cumplir con las actividades asignadas en relación a las entrevistas, To-Be y As-Is Scneario Mapping, Journey Mapping, Historias de Usuario, Eventstorming, entre otros. <br> <br>- *Cuevas Rios, Eric Fernando*<br> <br>**TB1** <br> <br>-<br> <br>- *Vargas Revollé, Ariana*<br> <br>**TB1**<br>  <br>-<br> <br>- *Elsner De La Torre Ugarte, Julio Esteban*<br> <br>**TB1**<br> <br>Elaborar con mis compañeros el proceso de event storming, AS-IS, C4, entre otros procesos clave para la culmniación de la TB1. <br> <br><br> <br>-  *Herrera González, Luis Eduardo*<br> <br>**TB1**<br>  <br>-<br>  | *(Sin conclusiones registradas)* |

</div>

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

En el contexto actual de crecimiento urbano y aumento del parque automotor, encontrar estacionamiento se ha convertido en una experiencia tediosa, lenta e ineficiente para miles de conductores en ciudades como Lima. La mayoría de soluciones tradicionales aún dependen de tickets físicos, interacciones manuales y procesos poco claros que afectan directamente la comodidad del usuario.

**ParkUp** nace como una respuesta a este problema. Es una aplicación móvil peruana que transforma por completo la experiencia de estacionamiento, integrando tecnología de lectura de placas, vinculación inteligente entre QR, vehículo y usuario, y un sistema de pago completamente automatizado. Todo esto se realiza sin necesidad de sacar el celular, después del escaneo inicial. ParkUp reduce los tiempos de entrada, elimina errores y simplifica el proceso de estacionarse con una interfaz moderna y centrada en el usuario.

La propuesta de valor de ParkUp se diferencia claramente de otras aplicaciones disponibles en el mercado peruano, ofreciendo una experiencia sin contacto, eficiente y totalmente digital, adaptada a la vida urbana moderna.  
  
Misión:  
Facilitar y modernizar la experiencia de estacionamiento en entornos urbanos mediante soluciones tecnológicas automatizadas, seguras y sin contacto, que integren al usuario con el sistema de manera intuitiva, eficiente y confiable.  

Visión:  
Convertirnos en la plataforma líder de estacionamiento inteligente en Perú, siendo referentes en innovación, automatización y experiencia de usuario, para transformar la manera en que las personas se movilizan y estacionan.  

### 1.1.2. Perfiles de integrantes del equipo 

| Foto | Perfil de Integrante |
|------|-------------|
| <p align="center"><img src="assets/capitulo-1/1.1.2-Perfiles-Integrantes-1.PNG" alt="Foto de integrante 1" width="100" height="100"/></p> | **Obispo Rios, Lucero Abigail**  <br> *U202111465 - Ingeniería de Software*  <br> <br> Para este proyecto, puedo aportar mis habilidades de redacción, diseño y programación. Además, estoy dispuesta a capacitarme con las herramientas que se consideren necesarias.  Por otro lado, me considero una persona responsable y comprometida con el proyecto. |
| <p align="center"><img src="assets/capitulo-1/imagen-vacia.PNG" alt="Foto de integrante 2" width="100" height="100"/></p> | **Vargas Revollé, Ariana**  <br> *Código - Carrera*  <br> <br> - <br> |
|<p align="center"><img src="assets/capitulo-1/1.1.2-Perfiles-Integrantes-3.jpg" alt="Foto de integrante 1" width="100" height="130"/></p>| **Cuevas Rios, Eric Fernando**  <br> *Código - Carrera*  <br> <br> - <br>  |
| <p align="center"><img src="assets/capitulo-1/1.1.2-Perfiles-Integrantes-4.jpg" alt="Foto de integrante 4" width="100" height="110"/></p> | **Elsner De La Torre Ugarte, Julio Esteban**  <br> *U202111654 - Ingeniería de Software*  <br> Para este proyecto, puedo aportar con habilidades de indagación y pensamiento crítico, diseño de prototipo en Figma y programación back-End. Añadido a esto, estoy me es grato poder aprender de mis demás compañeros y de sus habilidades individuales. Me considero una persona responsable y que cumple con los plazos establecidos en una entrega. <br>   |
| <p align="center"><img src="assets/capitulo-1/imagen-vacia.PNG" alt="Foto de integrante 5" width="100" height="100"/></p> | **Herrera González, Luis Eduardo**  <br> *Código - Carrera*  <br> <br> - <br> |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática  

##### 1. Who (¿Quién?)
Conductores urbanos en Perú, especialmente en Lima Metropolitana, que necesitan estacionar de manera rápida, eficiente y sin complicaciones. También incluye operadores de playas de estacionamiento interesados en digitalizar y automatizar sus procesos.

##### 2. What (¿Qué?)
Una aplicación móvil que automatiza la experiencia de estacionamiento mediante lectura de placas, vinculación digital entre vehículo y usuario, y pago sin contacto. Desde el ingreso hasta la salida, el proceso es rápido, seguro y sin necesidad de intervención manual.

##### 3. When (¿Cuándo?)
En el momento en que el conductor necesita ingresar, estacionar o salir de un establecimiento. ParkUp opera en tiempo real, desde que el usuario escanea un QR para iniciar la experiencia, hasta que se le autoriza la salida sin tener que usar su celular nuevamente.

##### 4. Where (¿Dónde?)
En playas de estacionamiento privadas o públicas ubicadas en zonas urbanas de Lima y, próximamente, en otras ciudades del Perú. También se accede desde cualquier dispositivo móvil (iOS o Android).

##### 5. Why (¿Por qué?)
Porque el proceso actual de estacionamiento es lento, anticuado y genera fricciones innecesarias. ParkUp ofrece una alternativa moderna y automatizada que mejora la experiencia del usuario y optimiza la operación para los dueños de los estacionamientos.

##### 6. How (¿Cómo?)
- El usuario escanea un QR al llegar.
- El sistema vincula automáticamente su placa, usuario y sesión.
- Al estacionarse, se valida su presencia con lectura de placa.
- El usuario puede pagar automáticamente o convalidar/pagar manualmente.
- Sale del estacionamiento sin necesidad de tickets ni intervención adicional.

##### 7. How much (¿Cuánto?)
El uso de ParkUp puede ser gratuito para el usuario final (dependiendo del modelo de negocio), mientras que el operador del estacionamiento paga una comisión por transacción o un plan mensual por digitalizar su sistema. El costo para el usuario es el mismo que pagaría tradicionalmente, pero con mejor experiencia.  

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El problema se presenta cuando los conductores en zonas urbanas del Perú deben enfrentarse a procesos de estacionamiento poco eficientes, con sistemas manuales, colas, tickets físicos, métodos de pago limitados y una experiencia general poco amigable.

Actualmente, el mercado peruano carece de soluciones de estacionamiento verdaderamente automatizadas que permitan una experiencia fluida, sin contacto, rápida y vinculada a la tecnología móvil y sistemas IoT.

ParkUp busca aprovechar esta oportunidad, ofreciendo una solución moderna que transforma radicalmente la experiencia de estacionarse, al digitalizar por completo el proceso: desde la lectura de placas y vinculación del usuario, hasta el pago y salida.

Hemos observado que los usuarios valoran cada vez más la comodidad y rapidez en sus desplazamientos. La experiencia actual de estacionamiento representa una fricción innecesaria en su día a día, mientras que los operadores de playas buscan alternativas para optimizar sus operaciones y digitalizar su infraestructura.

**Pregunta clave:**
¿Cómo podemos automatizar, simplificar y mejorar la experiencia de estacionamiento urbano para los conductores peruanos a través de tecnología sin contacto, moderna e intuitiva?

#### 1.2.2.2. Lean UX Assumptions  

## Business Assumptions

1. **Creemos que nuestros clientes necesitan:**  
Una manera eficiente, rápida y sin contacto para estacionar su vehículo sin depender de tickets ni procesos manuales.

2. **Estas necesidades se pueden resolver con:**  
Una app que automatiza el ingreso, pago y salida del estacionamiento mediante lectura de placas, escaneo de QR y confirmación automática de estacionamiento.

3. **Nuestros clientes iniciales son:**  
Conductores entre 20 y 45 años en zonas urbanas (principalmente Lima), con uso activo de smartphones y afinidad por soluciones digitales. También operadores de playas de estacionamiento que buscan digitalizar sus operaciones.

4. **El valor #1 que un cliente quiere obtener de nuestro servicio es:**  
Rapidez, comodidad y una experiencia completamente sin contacto al estacionar.

5. **El cliente también puede tener estos beneficios adicionales:**  
- Acceso a promociones o beneficios por uso frecuente.  
- Seguimiento de historial de estacionamientos y gastos.  
- Posibilidad de recibir recomendaciones de zonas con alta disponibilidad.

6. **Vamos a adquirir la mayoría de nuestros clientes a través de:**  
Marketing digital (Instagram, TikTok, YouTube), alianzas con playas de estacionamiento y activaciones presenciales.

7. **Haremos dinero a través de:**  
Comisiones por transacción de pago, planes de suscripción mensual para operadores, y potencial venta de soluciones integradas (software + hardware IoT).

8. **Nuestra principal competencia en el mercado será:**  
Otras apps de estacionamiento como Apparka y Parkealo. Los superaremos gracias a nuestra propuesta de automatización total y experiencia sin contacto desde el ingreso hasta la salida.

9. **El mayor riesgo del producto es:**  
Resistencia al cambio por parte de operadores tradicionales y poca educación digital en algunos usuarios.

10. **Resolveremos esto a través de:**  
Una interfaz extremadamente intuitiva, onboarding simple, pilotos en zonas de alta rotación vehicular y soporte técnico continuo a operadores.

## User Assumptions

- **¿Quién es el usuario?**  
Conductores entre 20 y 45 años con acceso a smartphones, que se mueven frecuentemente en zonas urbanas de alta congestión vehicular.

- **¿Dónde encaja nuestro producto en su vida?**  
Se integra en su rutina diaria de transporte y estacionamiento, eliminando una de las partes más tediosas del día: buscar dónde y cómo estacionar.

- **¿Qué problemas resuelve nuestro producto?**  
Falta de automatización, pérdida de tiempo al ingresar/salir, pagos manuales, tickets físicos, falta de información en tiempo real y métodos de pago limitados.

- **¿Cuándo y cómo se utiliza nuestro producto?**  
Desde el momento en que se acerca al estacionamiento: escanea el QR, se le lee la placa, se confirma el ingreso, se valida el estacionamiento y se paga al salir (o automáticamente si está configurado).

- **¿Qué características son importantes?**  
Automatización, seguridad, precisión en lectura de placas, rapidez, facilidad de uso y compatibilidad con múltiples formas de pago.

- **¿Cómo debe verse y comportarse nuestro producto?**  
Moderno, confiable, limpio visualmente y tan intuitivo que requiera mínima intervención. Compatible con múltiples dispositivos y adaptable a diversos perfiles de usuario.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 01:**  
Creemos que los usuarios iniciales serán conductores entre 20 y 45 años con alto uso de tecnología, que estacionan regularmente en zonas de alta congestión urbana.  
Sabremos que hemos tenido éxito cuando este grupo represente al menos el 60% de los usuarios activos en nuestra app durante los primeros 6 meses.

**Hypothesis Statement 02:**  
Creemos que nuestros ingresos vendrán por una combinación de comisiones por transacción, suscripciones mensuales a operadores y venta de hardware IoT.  
Sabremos que hemos tenido éxito cuando el 30% de los estacionamientos afiliados estén usando un plan de suscripción y tengamos una conversión de al menos 50% de usuarios que pagan mediante la app.

**Hypothesis Statement 03:**  
Creemos que los usuarios valorarán altamente la experiencia de estacionamiento sin contacto, especialmente si no necesitan sacar su celular después del ingreso.  
Sabremos que hemos tenido éxito cuando al menos el 70% de usuarios completen el flujo completo sin necesidad de asistencia manual, y reporten una experiencia positiva en encuestas de satisfacción.

#### 1.2.2.4. Lean UX Canvas

| **Sección**    | **Contenido**  |
|-----------------------------|----------------------------|
| **1. Problema del negocio** | El proceso de estacionamiento en ciudades como Lima es manual, lento y poco eficiente. Los usuarios pierden tiempo en colas, tickets físicos y pagos manuales. Los operadores tienen operaciones costosas y desactualizadas. |
| **2. Resultados del negocio** | - Reducir tiempo de ingreso y salida.<br>- Aumentar adopción del sistema.<br>- Generar ingresos por comisiones y planes B2B.<br>- Optimizar operaciones de operadores.<br>- Ser líderes en estacionamiento inteligente en Perú. |
| **3. Usuarios**             | Segmento 1: Conductores urbanos (20-45 años) que usan apps, buscan rapidez y prefieren experiencias sin contacto.<br>Segmento 2: Operadores de estacionamiento que buscan digitalizar sus servicios y reducir costos. |
| **4. Beneficios para el usuario** | - No necesita sacar su celular después del escaneo inicial.<br>- Flujo de estacionamiento sin contacto.<br>- Elimina tickets y pagos físicos.<br>- Ahorro de tiempo.<br>- Mayor seguridad y control. |
| **5. Ideas de solución**    | - App con escaneo QR y vinculación a placa.<br>- Lectura automática de placas.<br>- Confirmación de estacionamiento automatizada.<br>- Pagos digitales o automáticos.<br>- Dashboard para operadores. |
| **6. Hipótesis**            | - Los usuarios valorarán la experiencia sin contacto.<br>- Los operadores buscarán modernizar su operación.<br>- Éxito si +60% de usuarios son conductores frecuentes y +30% de operadores se suscriben. |
| **7. Supuestos**            | - Usuarios están dispuestos a cambiar hábitos por comodidad.<br>- Operadores quieren digitalizar sus servicios.<br>- La tecnología de lectura de placas funcionará en distintos entornos.<br>- La app debe ser extremadamente intuitiva. |
| **8. Métricas**             | - Tasa de adopción mensual.<br>- % de flujos completados sin asistencia.<br>- Número de estacionamientos afiliados.<br>- Tiempo promedio de ingreso/salida.<br>- Satisfacción del usuario (NPS).<br>- Retención mensual.<br>- Ingresos por comisiones y planes. |

## 1.3. Segmentos objetivo

Se plantearon 2 segmentos claramente diferenciados.
 
#### 1. Conductores Urbanos

##### Descripción del segmento:
- Personas entre 20 y 45 años.
- Se movilizan frecuentemente en ciudades como Lima Metropolitana.
- Poseen vehículo propio.
- Estacionan regularmente en centros comerciales, oficinas, clínicas, universidades u otras zonas de alta demanda.
- Son usuarios activos de smartphones y pagos digitales (Yape, Plin, tarjeta).

#### 2. Operadores de Estacionamientos

##### Descripción del segmento:
- Administradores o propietarios de playas de estacionamiento, edificios corporativos, centros comerciales o negocios con espacios de estacionamiento.
- Actualmente utilizan sistemas manuales o semiautomáticos.
- Buscan digitalizar y optimizar su operación.

# Capítulo II: Needfinding

## 2.1. Competidores

### 2.1.1. Análisis competitivo
  
| Perfil  | Parkner PE  | Apparka | Parkealo  | ParkUp  |
|:----------------------:|:-------------------------:|:----------------------:|:---------------------:|:------------------------------------------:|
| **Overview**          | Plataforma web que permite a los usuarios registrar y alquilar espacios de estacionamiento privados en Lima, operando principalmente en los distritos de San Isidro y Miraflores.| Aplicación móvil que facilita la búsqueda, reserva y pago de estacionamientos en Lima, ofreciendo opciones de pago como tarjeta de crédito, débito y su monedero digital "Apparka Wallet".| Plataforma que permite a los usuarios encontrar y reservar estacionamientos urbanos, ofreciendo una variedad de opciones para conductores y propietarios de estacionamientos. | Aplicación móvil que automatiza la experiencia de estacionamiento, incluyendo lectura de placas, vinculación con usuarios y pagos automáticos, mejorando la eficiencia y comodidad del proceso. |
| **Mercado Objetivo**  | Conductores en Lima que buscan alquilar espacios de estacionamiento privados, especialmente en áreas con alta demanda como San Isidro y Miraflores. | Usuarios en Lima que requieren estacionamiento en zonas urbanas, incluyendo tanto conductores frecuentes como ocasionales. | Propietarios de estacionamientos y conductores en Lima que buscan soluciones eficientes para encontrar y reservar espacios de estacionamiento. | Conductores en Lima que buscan una experiencia de estacionamiento sin contacto, con procesos automatizados y pagos simplificados. |
| **Estrategias**      | - Permitir a los propietarios de espacios libres registrarlos y establecer precios y tiempos de alquiler. <br> - Ofrecer una plataforma que facilite la búsqueda y reserva de estacionamientos. <br> - Expandirse a otros distritos y países.| - Integración con estacionamientos existentes en Lima. <br> - Ofrecer múltiples métodos de pago, incluyendo su propio monedero digital. <br> - Proporcionar información en tiempo real sobre disponibilidad y tarifas. | - Crear un marketplace que conecte a propietarios de estacionamientos con conductores. <br> - Ofrecer una plataforma fácil de usar para la reserva y gestión de espacios. | - Automatizar el proceso de estacionamiento desde la llegada hasta la salida. <br> - Integrar tecnología de lectura de placas y pagos automáticos. <br> - Mejorar la experiencia del usuario con interfaces intuitivas. |
| **Ventaja Competitiva** | - Permite a los usuarios generar ingresos alquilando sus espacios privados. <br> - Ofrece una amplia variedad de opciones en zonas clave de Lima. | - Proporciona una solución integral para encontrar, reservar y pagar estacionamientos. <br> - Facilita el proceso con múltiples opciones de pago y gestión de tiempo. | - Amplia base de datos de estacionamientos disponibles en Lima. <br> - Plataforma intuitiva que simplifica la reserva y gestión de espacios. | - Proceso completamente automatizado que reduce tiempos y errores. <br> - Integración de tecnología avanzada para una experiencia sin fricciones. |
| **Canal de distribución** | - Plataforma web accesible desde cualquier navegador. <br> - Aplicación móvil disponible para Android e iOS. | - Aplicación móvil disponible para Android e iOS. <br> - Integración con sistemas de estacionamientos locales. | - Aplicación móvil disponible para Android e iOS. <br> - Plataforma web para gestión de estacionamientos. | - Aplicación móvil disponible para Android e iOS. <br> - Integración con sistemas de gestión de estacionamientos y dispositivos IoT. |  
  
### 2.1.2. Estrategias y tácticas frente a competidores  

## Afrontando las fortalezas de nuestros competidores

### Fortalezas identificadas en los competidores:
- Amplia base de usuarios y presencia consolidada (ej. Apparka con Los Portales).
- Interfaces simples con información clara de tarifas y horarios.
- Variedad de métodos de pago y facilidad de uso.
- Disponibilidad en zonas céntricas y de alta demanda.

### Fortalezas propias de ParkUp:
- Flujo 100% automatizado: desde lectura de placa hasta pago sin intervención del usuario.
- Experiencia sin contacto y sin tickets.
- Vinculación inteligente entre QR, usuario y vehículo.
- Interfaz moderna orientada a usuarios tech-savvy.
- Posibilidad de integración con sistemas de parking y dispositivos IoT.

### Estrategia:
Desarrollar una ventaja basada en tecnología de automatización y UX fluida, que reduzca la fricción del usuario al mínimo, superando a las apps tradicionales que aún requieren intervención manual.

### Tácticas:
- Potenciar campañas que comuniquen la experiencia “sin sacar el celular” como propuesta de valor diferenciadora.
- Implementar mejoras constantes en lectura de placas y eficiencia del flujo de entrada/salida.
- Incluir comparativas visuales en redes sociales entre la experiencia ParkUp vs. tickets o apps tradicionales.

## Afrontando las oportunidades de nuestros competidores

### Oportunidades detectadas en el mercado:
- Expansión geográfica a más distritos y ciudades con alto tráfico.
- Alianzas con centros comerciales, supermercados, clínicas y universidades.
- Posibilidad de convertirse en plataforma de referencia para movilidad urbana.

### Oportunidades propias de ParkUp:
- Crecimiento de la demanda de soluciones sin contacto post-pandemia.
- Interés creciente en eficiencia tecnológica en ciudades como Lima.
- Nicho aún poco explotado de “parking inteligente” con automatización completa.

### Estrategia:
Expandir ParkUp como solución plug & play para estacionamientos medianos y pequeños que aún no están digitalizados, empezando por zonas donde otras apps no tienen cobertura.

### Tácticas:
- Identificar distritos con alta densidad vehicular pero baja presencia de apps de parking (ej. Lince, Surquillo, Breña).
- Ofrecer planes B2B a propietarios con sistemas antiguos para integrar ParkUp con hardware mínimo.
- Asistir a ferias de tecnología urbana y movilidad para visibilizar el modelo.
  
## Afrontando las amenazas de nuestros competidores

### Amenazas comunes del mercado:
- Dominio de marcas ya establecidas con alianzas estratégicas.
- Preferencia de usuarios por apps conocidas o vinculadas a marcas inmobiliarias.
- Sensibilidad al precio o al modelo tradicional de ticket físico.

### Amenazas particulares de ParkUp:
- Ser percibidos como “demasiado nuevo” o complejo en comparación a soluciones tradicionales.
- Requiere más educación del usuario sobre su modelo automatizado.

### Estrategia:
Adoptar una estrategia de comunicación educativa y experiencial, donde el usuario descubra el valor de ParkUp al vivirlo (más que solo leerlo).

### Tácticas:
- Crear contenido en redes mostrando el paso a paso de un usuario real usando ParkUp (incluyendo el "no sacar el celular").
- Incentivar recomendaciones con recompensas por referidos.
- Generar alianzas con pequeños operadores para mostrar casos de éxito reales.  
  
## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

##### Preguntas de introducción (Para todos los segmentos):
1. ¿Cuál es su nombre?
2. ¿Cuántos años tiene?
3. ¿En qué cuidad del Perú reside?
4. ¿Cuál considera que es su estatus social limitando la descripción a Clase Baja, Clase Media, Clase Media-Alta y Clase Alta? 
   
##### Segmento 1: Conductores
1. ¿Con qué frecuencia utilizas estacionamientos privados durante tu semana?
2. ¿Cómo describirías tu experiencia ideal al momento de ingresar, estacionar y salir de un parqueo?
3. ¿Puedes contarme sobre una experiencia positiva o negativa que hayas tenido al pagar por un servicio de estacionamiento?
4. ¿Alguna vez se te ha perdido el ticket de estacionamiento?
5. ¿Alguna vez ha ido a algún parking sin portar el celular?
6. ¿Qué método de pago prefieres cuando pagas estacionamiento? (Ej. tarjeta, Yape, Plin, efectivo)
7. ¿Qué preocupaciones tendrías al usar un sistema que lee tu placa y automatiza el pago del estacionamiento?
8. ¿Te seria útil visualizar en la aplicación sobre que espacios hay libres antes de entrar al parking? 
9. ¿Qué esperas ver o saber en la app al momento de estacionarte? ¿Qué información sería útil para ti?

##### Segmento 2: Administradores de parking
1. ¿Con qué frecuencia revisan cámaras de seguridad para el monitoreo de vehículos?
2. ¿Cuál es el protocolo actual ante una emergencia o incidente de seguridad?
3. ¿Qué tipo de información te resulta más útil visualizar a diario para monitorear el funcionamiento del estacionamiento?
4. ¿Cómo se gestiona actualmente los errores o problemas en el sistema de validación o cobro del estacionamiento?
5. ¿Qué funcionalidades consideras esenciales en una plataforma web para administrar y monitorear espacios de parqueo?
6. ¿Qué herramientas usas hoy para controlar los vehículos que entran y salen?
7. ¿Qué información consideras más importante tener a la mano mientras gestionas el estacionamiento?
8. ¿Qué tan importante sería para ti poder ver en tiempo real quién está estacionado y quién ha pagado?
9. ¿Te sentirías cómodo con un sistema que detecta automáticamente las placas y realiza los cobros sin que tú intervengas?



### 2.2.2. Registro de entrevistas
##### Segmento 1: Conductores
![](https://i.postimg.cc/rFVrFVWQ/interview-driver.png)

Eva utiliza estacionamientos privados cinco veces por semana y valora una experiencia fluida, con espacios amplios y fáciles de encontrar. Considera la seguridad un aspecto esencial, destacando la importancia de contar con vigilancia. Siempre porta su celular, por lo que acepta el uso de aplicaciones móviles, y prefiere pagar con tarjeta. Aunque ve con buenos ojos la automatización mediante lectura de placas, le preocupa no poder validar cobros automáticos, por lo que el sistema debería ofrecer confirmación previa antes de realizar cargos. Además, considera fundamental que la aplicación muestre en tiempo real los espacios libres, priorizando los más cercanos a entradas y salidas para optimizar su tiempo.

  - Entrevistado: Eva Revollé
  
  - Residencia: Lima
  
  - Ocupación: Empresaria
  
  - Entrevistadora: Ariana Vargas

 - Enlace: [Entrevista driver Eva](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a928_upc_edu_pe/EfYrrssrhMtJgwaB70Bbw08BUB1vmFhogew_rTpUJlsqYg?e=uiQebR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
 
  Segunda Entrevista:
  - Entrevistado: Ian Sanchez
  - Residencia: Lima
  - Ocupación: Estudiante Universitario
  - Entrevistador: Julio Elsner
  - Enlace: [https://drive.google.com/file/d/1GZ1zA9s69y3c5qnWJaKKor_zflNRgF96/view?usp=sharing]
  <p align="left"><img src="assets/capitulo-2/Ian.png" alt="Entrevista 1" width="500" height="250"/></p>
**Resumen de la entrevista:**

    0:47 - ¿Cual seria tu experiencia ideal a la hora de encontrar un sitio?
    Mi experiencia ideal al entrar a un parkeo seria muy fluida que me muestre los lugares vacios y una ruta.

    0:57 - ¿Cuál fue una de tus experiencias negativas al usar un ticket?
    Saliendo del mall mientras compraba se me cayó el ticket y fue un lió porque no tenia como salir del estacionamiento.

    2:11 - ¿Qué metodo de pago prefieres cuando pagas el estacionamiento?
    Yape o Plin son rapidos y no necesito estar llevando efectivo, casi nunca uso efectivo.

    2:28 - ¿Qué preocupaciones tendrías al usar un sistema que lee tu placa y automatiza el pago del estacionamiento?
    Me preocuparia que el sistema no identifique la placa de mi vehiculo y me cobre de más o se quede abierto el cobro, también pensaria en la seguridad de mis datos pero si esta bien implementado seria bastante comodo.

    2:54 - ¿Te seria útil visualizar en la aplicación sobre que espacios hay libres antes de entrar al parking?
    Si, eso sería ideal para no tener que estar buscando sitio y perder mi tiempo. Si la app te muestra que niveles son los que tiene mas espacio seria un Golazo.

    3:28 - ¿Qué esperas ver o saber en la app al momento de estacionarte? ¿Qué información sería útil para ti?
    Me gustaria ver si hay espacios libre, el costo por hora, tener que pagar sin tener que hacer cola. También tener que ver si hay zonas techadas o comodas.

  Tercera Entrevista:
  - Entrevistado: Oscar Garayar
  - Residencia: Lima
  - Ocupación: Contador Privado
  - Entrevistadora: Julio Elsner
  - Enlace: [https://drive.google.com/file/d/1BD9ja1CMf6CAnO4BzFJKKQvH9ArLhj36/view?usp=sharing]
  <p align="left"><img src="assets/capitulo-2/Oscar.png" alt="Entrevista 1" width="500" height="250"/></p>

**Resumen de la entrevista:**

    0:47 - ¿Cual seria tu experiencia ideal a la hora de encontrar un sitio?
    Que sea lo mas cerca posible de las tiendas mas conocidas para no tener que estar caminando hasta un lugar alejado.

    0:57 - ¿Puedes contarme sobre una experiencia positiva o negativa que hayas tenido al pagar por un servicio de estacionamiento?
    Una vez el sistema de un centro comercial se cayó y tuve que hacer una fila gigante para poder pagar el estacionamiento de manera fisica y sin metodos de pago online.

    2:11 - ¿Qué metodo de pago prefieres cuando pagas el estacionamiento?
    Metodos de pago como tarjeta que suelo usar mucho para evitar tener que ir cargando efectivo.

    2:28 - ¿Qué preocupaciones tendrías al usar un sistema que lee tu placa y automatiza el pago del estacionamiento?
    La verdad es que ya un montón de estacionamientos lo usan asi que no tendría problema de su uso.

    2:54 - ¿Te seria útil visualizar en la aplicación sobre que espacios hay libres antes de entrar al parking?
    Si definitivamente porque me ahorra bastante tiempo a la hora de buscar un sitio libre y estar haciendo colas o rondando por el lugar.

    3:28 - ¿Qué esperas ver o saber en la app al momento de estacionarte? ¿Qué información sería útil para ti?
    Lo mas util para mi sería visualizar los espacios libre, zonas de estacionamientos cercanos, tarifas aplicables al pago del ticket, etc.



##### Segmento 2: Administradores de parking
- Primera Entrevista:
  <p align="left"><img src="assets/capitulo-2/2.2.2-Entrevista-Administrador-1.PNG" alt="Entrevista 1" width="150" height="250"/></p>
  
  - Entrevistado: Jose Alberto
  
  - Residencia: Lima
  
  - Ocupación: Seguridad de Parking
  
  - Entrevistadora: Lucero Obispo
  
  - Enlace: [https://youtu.be/ebwojw4HlCo]
  
  - Resumen de la entrevista:
    0:30 - ¿Con qué frecuencia revisan cámaras de seguridad para el monitoreo de vehículos?
    Las cámaras estan vigilando en cada momento, yo también bajo para ver y verificar que los autos no se esten llevando algo de lo ajeno.

    0:57 - ¿Cuál es el protocolo actual ante una emergencia o incidente de seguridad?
    Ante un incidente de seguridad, nos comunicamos con el gerente de tienda mediante una radio

    1:13 - ¿Qué tipo de información te resulta más útil visualizar a diario para monitorear el funcionamiento del estacionamiento?
    Las cámaras y hacer las rondas para que no pase nada

    2:00 - ¿Qué funcionalidades consideras esenciales en una plataforma web para administrar y monitorear espacios de parqueo?
    Este parqueo es gratuito así que no necesitamos una plataforma web, no se visualizaría bien la información. Sin embargo, si fuera cobro, el parqueo tuviera un costo sería diferente, ahí si se podría visualizar información útil.

    2:45 - ¿Qué herramientas usas hoy para controlar los vehículos que entran y salen?
    Los tickets y un lapicero para anotar la hora que entra el cliente, la placa y apuntar también la hora que sale el vehículo.

    3:28 - ¿Qué información consideras más importante tener a la mano mientras gestionas el estacionamiento?
    Sería el ticket, la placa y el rostro del chofer.

- Segunda Entrevista: 
  - Entrevistado: Jorge Rosales
  - Residencia: Lima
  - Ocupación: Operador de Parking
  - Entrevistador: Eric Cuevas
  - Enlace: [https://youtu.be/BB-ZCcDnO-Q]
  - Resumen de la entrevista:
    1:05 - ¿Qué tipo de información te resulta más útil visualizar a diario para monitorear el funcionamiento del estacionamiento?
    Que personas y vehiculos ingresan, como se han estacionado y quienes estan circulando en las instalaciones.

    2:14 - ¿Qué funcionalidades consideras esenciales en una plataforma web para administrar y monitorear espacios de parqueo?
    Visión todo el día del estacionamiento, permita grabar el estado de los espacios y que se permita gestionar situaciones en los estacionamientos.

    3:00 - ¿Qué herramientas usas hoy para controlar los vehículos que entran y salen?
    Un programa contratado de facturación, el control de lo demás se hace manual

    4:48 - ¿Te sentirías cómodo con un sistema que detecta automáticamente las placas y realiza los cobros sin que tú intervengas?
    Cloaro, nos permitiria agilizar el trabajo.

### 2.2.3. Análisis de entrevistas
##### Segmento 1: Conductores

##### Segmento 2: Administradores de parking
- Primera Entrevista: El entrevistado señaló que el monitoreo se realiza principalmente mediante cámaras activas todo el tiempo y rondas presenciales para verificar el estado del parqueo. Ante emergencias, se comunica directamente con el gerente de tienda por radio, sin un protocolo formal establecido. La información más útil para su labor diaria incluye las grabaciones de las cámaras, el ticket del vehículo, la placa y el rostro del conductor. Actualmente no utilizan una plataforma web, ya que el parqueo es gratuito y no considera necesaria una visualización digital; sin embargo, si hubiera cobro, sí vería valor en implementarla. El control de ingreso y salida se realiza de forma manual con tickets y anotaciones en papel.
- Segunda Entrevista: El entrevistado Señalo que se tienen contratado un sistema que les permite realizar las facturaciones, pero que el resto de los controles del estacionamiento los realizan manualmente y recae en los empleados aplicar los protocolos en caso de incidentes. A partir de esto señalo en las siguientes respuestas que esta interesado en adquirir un sistema que le permita automatizar más partes de la gestión del estacionamiento.

## 2.3. Needfinding

### 2.3.1. User Personas

Como parte del análisis centrado en el usuario, se realizaron entrevistas semiestructuradas a personas representativas de nuestros segmentos objetivo. Estas entrevistas permitieron identificar patrones comunes en sus necesidades, comportamientos, frustraciones y expectativas en torno al proceso de entrada y salida en estacionamientos.

Se priorizó extraer información sobre los siguientes aspectos clave:

- **Frecuencia y contexto de uso del estacionamiento**, incluyendo zonas de alta congestión o acceso restringido.
- **Interacción actual con sistemas de pago**, validación o ingreso (boletos físicos, apps, sensores, etc.). 
- **Problemas recurrentes o puntos de fricción** (colas, fallos en reconocimiento de placas, confusión en las apps, tiempos muertos). 
- **Grado de familiaridad con la tecnología actual de vehículos y parking**, especialmente en relación con sensores vehiculares, apps móviles y plataformas de monitoreo. 
- **Expectativas respecto a una experiencia fluida**, sin necesidad de intervención humana o validaciones manuales.

A partir del análisis de esta información y de un benchmarking de soluciones similares en el mercado, se construyeron dos fichas de User Persona que representan a los principales usuarios de la solución propuesta:

- **Diego Luxemburgo**, conductor urbano que busca eficiencia y simplicidad al momento de estacionar. 
- **Dina Zimbabue**, administradora de estacionamientos que necesita control, automatización y reducción de la carga operativa.

Ambos perfiles fueron elaborados utilizando la herramienta UXPressia, siguiendo las mejores prácticas en diseño UX y representando arquetipos realistas y accionables para el diseño posterior del sistema.

**1. Diego Luxemburgo**

![2.3.1-User-Persona-Diego-Luxemburgo.png](assets/capitulo-2/2.3.1-User-Persona-Diego-Luxemburgo.png)

**Preferencia de ingreso:**

![chart1.png](assets/capitulo-2/chart1.png)

**Problemas frecuentes:**

![chart2.png](assets/capitulo-2/chart2.png)

**Nivel tecnológico:**

![chart3.png](assets/capitulo-2/chart3.png)

**2. Dina Zimbabue**

![2.3.1-User-Persona-Dina-Zimbabue.png](assets/capitulo-2/2.3.1-User-Persona-Dina-Zimbabue.png)

**Dispositivos de gestión:**

![chart4.png](assets/capitulo-2/chart4.png)

**Problemas de gestión:**

![chart5.png](assets/capitulo-2/chart5.png)

**Nivel tecnológico:**

![chart6.png](assets/capitulo-2/chart6.png)


### 2.3.2. User Task Matrix

User Task Matrix: Diego Luxemburgo y Dina Zimbabue

Con el fin de elaborar un Task Matrix adecuado para el proyecto, se han considerado los dos segmentos objetivo, producto del análisis de entrevistas, es decir, Conductores e Administradores de parking.

**User Task Matrix – Diego Luxemburgo - Conductores:**

| **User Task**                                                  | **Frecuencia** | **Importancia** |
| -------------------------------------------------------------- | -------------- | --------------- |
| Buscar estacionamiento cercano al destino                      | Alta           | Alta            |
| Hacer fila para pagar el estacionamiento (manual o con ticket) | Alta           | Alta            |
| Retirar ticket y conservarlo hasta el pago                     | Alta           | Alta            |
| Buscar la máquina de pago en el local                          | Media          | Alta            |
| Esperar a que el lector de ticket funcione correctamente       | Media          | Alta            |
| Coordinar pagos en efectivo o encontrar sencillo               | Media          | Alta            |
| Volver al vehículo antes que se venza el ticket o la tarifa    | Media          | Media           |
| Revisar si la cochera está operativa, abierta o disponible     | Baja           | Media           |
| Lidiar con problemas en la barrera de ingreso/salida           | Baja           | Alta            |
| Llamar o buscar personal de soporte del estacionamiento        | Baja           | Media           |

**User Task Matrix – Dina Zimbabue - Administradores de parking:**

| **User Task**                                                    | **Frecuencia** | **Importancia** |
| ---------------------------------------------------------------- | -------------- | --------------- |
| Supervisar el ingreso/salida del personal y visitantes           | Alta           | Alta            |
| Coordinar al personal para emitir tickets y controlar accesos    | Alta           | Alta            |
| Validar manualmente placas de vehículos conocidos                | Alta           | Alta            |
| Solucionar problemas de lectura de placas o pérdida de tickets   | Media          | Alta            |
| Redactar reportes de ingresos/salidas de forma manual o en Excel | Media          | Alta            |
| Contactar al personal de vigilancia ante incidentes              | Media          | Media           |
| Verificar la disponibilidad del local mediante rondas visuales   | Media          | Alta            |
| Atender quejas por demoras en el ingreso o salida                | Baja           | Alta            |
| Entrenar a nuevo personal en protocolos y sistemas antiguos      | Baja           | Media           |
| Buscar registros manuales para auditoría o consultas             | Baja           | Alta            |

### 2.3.3. User Journey Mapping

**User Journey Mapping: Situación As-Is**

En esta sección se presentan los User Journey Maps correspondientes a los perfiles de usuario elaborados para ParkUp. Los mapas muestran el recorrido actual de los usuarios antes de la existencia de la solución propuesta, ilustrando los puntos de contacto, frustraciones y oportunidades de mejora a lo largo del proceso.

Los User Personas fueron creados utilizando la herramienta UXPressia, y los Journey Maps a continuación se han vinculado con cada uno de ellos.

**User Journey Map - Diego Luxemburgo (Conductor):**

1. Descripción general del recorrido:

Diego es un profesional independiente con alta movilidad en Lima. Usa su auto diariamente para llegar a distintos puntos de interés. Su objetivo es estacionar rápido y continuar con su rutina sin perder tiempo en tareas manuales o esperas innecesarias. Actualmente, se enfrenta a un sistema tradicional de estacionamientos que requiere tickets físicos, pagos manuales y barreras que demoran.

2. Imagen:

![2.3.3-User-Journey-Mapping-Diego-Luxemburgo.png](assets/capitulo-2/2.3.3-User-Journey-Mapping-Diego-Luxemburgo.png)

**User Journey Map - Dina Zimbabue (Administradora de estacionamiento):**

1. Descripción general del recorrido:

Dina es administradora de varios estacionamientos privados y/o corporativos en Lima. Busca eficiencia operativa, minimizar la intervención humana y asegurar la seguridad vehicular sin afectar la experiencia del usuario. Actualmente, depende de procedimientos manuales, personal de vigilancia y herramientas poco automatizadas como Excel y WhatsApp para gestionar entradas y salidas.

2. Imagen:

![2.3.3-User-Journey-Mapping-Dina-Zimbabue.png](assets/capitulo-2/2.3.3-User-Journey-Mapping-Dina-Zimbabue.png)

### 2.3.4. Empathy Mapping

El empathy mapping es una herramienta de diseño centrado en el usuario que permite visualizar y comprender de manera integral lo que piensan, sienten, ven, dicen, escuchan, así como los dolores y ganancias de los usuarios respecto a un producto o servicio. Esta técnica se utiliza para empatizar con los diferentes segmentos de usuarios, identificar sus necesidades reales y diseñar soluciones efectivas que respondan a sus experiencias y expectativas.

**Empathy Mapping - Conductores:**

En el caso de los conductores, el empathy mapping revela que se sienten ansiosos y frustrados ante los procesos tradicionales basados en tickets en papel, lo que genera demoras y complicaciones como la pérdida de comprobantes. Observan entornos con largas filas, máquinas antiguas y falta de información sobre la disponibilidad de espacios y cobro de los estacionamientos. Además, sus comentarios y acciones reflejan la necesidad de contar con un método más ágil y confiable para poder estacionar y realizar el pago sin contratiempos, evidenciando el deseo de simplificar y optimizar la experiencia de estacionamiento.

![2.3.4-Empathy-Mapping-Diego-Luxemburgo.jpg](assets/capitulo-2/2.3.4-Empathy-Mapping-Diego-Luxemburgo.jpg)

**Empathy Mapping - Administradores de parking:**

Para los administradores de parking, el empathy mapping destaca la presión y el estrés derivados de gestionar un sistema manual que depende de registros en papel y anotaciones manuales. Se percibe su frustración por la ineficiencia y la vulnerabilidad de los datos, lo que a menudo dificulta la supervisión precisa del ingreso y egreso de vehículos. Asimismo, estos responsables manifiestan la necesidad de disponer de una herramienta que centralice y digitalice la información, de forma que puedan mejorar la trazabilidad, responder rápidamente a incidencias y optimizar el control general del estacionamiento.

![2.3.4-Empathy-Mapping-Dina-Zimbabue.jpg](assets/capitulo-2/2.3.4-Empathy-Mapping-Dina-Zimbabue.jpg)

### 2.3.5. As-is Scenario Mapping

El As-Is Scenario Mapping es una herramienta que permite visualizar el estado actual de un proceso, identificando qué hacen, piensan y sienten los usuarios en cada fase. Sirve para comprender de manera detallada los pasos, los puntos de dolor y las emociones involucradas en un flujo de trabajo tradicional, facilitando la identificación de oportunidades de mejora.

**As-is Scenario Mapping - Conductores:**

El As-is Scenario Mapping para los conductores revela un proceso tradicional basado en tickets en papel. Al ingresar, los conductores recogen un ticket físico y deben buscar manualmente un espacio de estacionamiento, enfrentándose a incertidumbre y demoras. Durante el pago y la salida, se experimentan largas filas, riesgos de extravío y frustración general por la lentitud del sistema. En cada fase, se aprecia una mezcla de rutina, preocupación y descontento ante la ineficiencia del proceso manual.

![2.3.5-As-Is-Scenario-Mapping-Conductor.jpg](assets/capitulo-2/2.3.5-As-Is-Scenario-Mapping-Conductor.jpg)

**As-is Scenario Mapping - Administradores de parking:**

Para los administradores de parking, el As-Is Scenario Mapping expone una gestión marcada por la dependencia de registros manuales y comprobantes en papel. Las tareas diarias incluyen la anotación de datos, la verificación física mediante rondas y la supervisión a través de cámaras de seguridad, lo que genera una alta carga de trabajo y vulnerabilidad en el control de la información.

![2.3.5-As-Is-Scenario-Mapping-Administrador-Parking.jpg](assets/capitulo-2/2.3.5-As-Is-Scenario-Mapping-Administrador-Parking.jpg)

## 2.4. Ubiquitous Language

Para mantener un lenguaje estándar en el equipo de trabajo y asegurar una comunicación clara entre desarrolladores, diseñadores, stakeholders y otros participantes del proyecto, se ha definido un Lenguaje Ubicuo basado en los principios de Domain-Driven Design (DDD).

Este glosario formaliza los términos clave utilizados en el dominio del sistema de estacionamiento inteligente para ParkUp, con el objetivo de evitar ambigüedades, mejorar la trazabilidad entre conceptos de negocio y su representación en el software.

1. **VehicleSession**: El ciclo completo de la presencia de un vehículo en el sistema de estacionamiento, desde que es detectado al ingresar hasta que se confirma su salida.

2. **AutoEntry**: Proceso mediante el cual un vehículo es reconocido (por placa, sensores o etiquetas) y se le permite el ingreso sin interacción manual.

3. **AutoExit**: Proceso de reconocimiento de la intención de salida del vehículo y ejecución automática de la salida, incluyendo el cálculo de tarifas y apertura de barrera si aplica.

4. **RecognitionUnit**: Subsistema (hardware y software) encargado de identificar vehículos mediante reconocimiento de placas, RFID o BLE.

5. **ParkingCredential**: Identificador virtual que permite al sistema reconocer un vehículo o usuario. Puede ser una placa, una ID móvil, una etiqueta, etc.

6. **FrictionlessFlow**: Estado del sistema en el cual los vehículos ingresan y salen sin detenerse ni interactuar físicamente o digitalmente.

7. **SmartBarrier**: Barrera conectada vía IoT que se abre automáticamente al verificar correctamente una ParkingCredential válida.

8. **AccessEvent**: Evento registrado por el sistema al detectar el ingreso o salida de un vehículo.

9. **SessionAlert**: Notificación en tiempo real al administrador ante eventos inusuales como placas no reconocidas, estancias prolongadas o intento de ingreso múltiple.

10. **Zone**: Área física definida dentro del estacionamiento (ej. Zona de Entrada, Zona de Salida, Zona de Administración), usada para lógica del sistema y mapeo de eventos.

11. **ParkingProfile**: Configuración específica por usuario que define su comportamiento en entradas, salidas, alertas, preferencias de pago y reconocimiento.

12. **FastTrackLane**: Carril dedicado para usuarios con ParkingCredential válida y alta fiabilidad de reconocimiento. Optimiza la fluidez.

13. **PlateMismatch**: Evento en el cual el sistema no puede asociar una placa detectada con ninguna ParkingCredential registrada, lo que genera un SessionAlert.

14. **AdminConsole**: Interfaz usada por administradores para monitorear AccessEvents, configurar el sistema, recibir alertas y generar reportes.

15. **ManualOverride**: Acción administrativa que omite el sistema automático debido a excepciones como fallos de reconocimiento o caídas del sistema.

16. **RecognitionConfidence**: Valor porcentual que indica el nivel de certeza con que el sistema reconoce una placa o vehículo. Se usa para decidir acciones automáticas o alertas.

17. **UserIntent**: Intención inferida del conductor al acercarse al sistema (por ejemplo: entrar, salir, detenerse brevemente), utilizada para anticipar respuestas del sistema.

18. **QueueEvacuation**: Respuesta automática para evitar congestión en entradas/salidas durante horas pico, activando todas las SmartBarriers para evacuar rápidamente.

19. **TicketlessSession**: Sesión de estacionamiento completada sin emisión de tickets físicos o virtuales.

20. **AccessAudit**: Registro detallado de todos los AccessEvents y decisiones del sistema relacionadas con una VehicleSession específica. Útil para auditoría y soporte.

21. **IdentityVerificationFallback**: Método alternativo de verificación usado cuando la ParkingCredential principal falla (ej. reconocimiento facial, confirmación vía app).

22. **FastExit**: Función para usuarios preautorizados que permite salir de inmediato gracias a credenciales y pagos almacenados, sin necesidad de detenerse.

23. **OperationalSilence**: Estado ideal del sistema donde no se requiere atención del usuario ni intervención del administrador.

24. **EntryAnomaly**: Comportamiento inusual durante el ingreso, como demoras en el reconocimiento, ingreso de múltiples vehículos, o placas conflictivas.

25. **StaffBypass**: Mecanismo que permite a personal autorizado saltarse los pasos de reconocimiento mediante credenciales especiales o interruptores manuales.




# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

El to-be scenario mapping es una herramienta que describe cómo será la experiencia ideal del usuario al interactuar con una solución propuesta, como una aplicación móvil o una plataforma web. A través de fases clave del proceso, se detallan las acciones (doing), pensamientos (thinking) y emociones (feeling) de los usuarios al usar el producto, permitiendo visualizar mejoras respecto al escenario actual (as-is). Esta herramienta ayuda a validar si la solución responde a las necesidades del usuario y facilita la identificación de oportunidades para optimizar su experiencia.

**To-Be Scenario Mapping - Conductores:**

El To-Be Scenario Mapping para conductores muestra una experiencia digital fluida y eficiente gracias al uso de la aplicación móvil. Desde el ingreso, los usuarios pueden escanear un código QR para obtener un ticket digital y acceder al sistema del estacionamiento, encontrar espacios disponibles mediante una guía interactiva, realizar pagos sin contacto desde la app y salir del estacionamiento sin fricciones. Este nuevo flujo mejora significativamente la comodidad, reduce tiempos de espera y elimina los puntos de frustración del proceso tradicional.

![3.1-To-Be-Scenario-Mapping-Conductor.jpg](assets/capitulo-3/3.1-To-Be-Scenario-Mapping-Conductor.jpg)

**To-Be Scenario Mapping - Administradores de Parking:**

El To-Be Scenario Mapping para administradores de parking muestra cómo, al usar el sistema web, pueden automatizar el registro de ingresos, monitorear en tiempo real la ocupación, verificar pagos de forma eficiente y gestionar incidencias operativas como pagos no registrados. La digitalización del proceso reduce errores y mejora el control en la gestión diaria del estacionamiento.

![3.1-To-Be-Scenario-Mapping-Administrador-Parking.jpg](assets/capitulo-3/3.1-To-Be-Scenario-Mapping-Administrador-Parking.jpg)

## 3.2. User Stories

***Epics***

| Epic                                                                       | Description                                                                                                                                                                                                |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01 (Landing Page atractiva de ParkUp)                                    | Como visitante, deseo una landing page intuitiva y atractiva que proporcione información clara sobre la aplicación de ParkUp, para facilitar mi toma de decisiones y acelerar mi uso de la plataforma.     |
| EP02 (Integración y desarrollo de Dispositivos IoT de Parking y Monitoreo) | Como developer, quiero que los sistemas de parqueo estén conectados mediante IoT, para obtener información en tiempo real sobre la disponibilidad de espacios y mejorar la experiencia de estacionamiento. |
| EP03 (Gestión de cuentas de usuarios en la Mobile App de ParkUp)           | Como conductor, quiero registrarme, iniciar sesión y gestionar mi cuenta desde la app móvil de ParkUp, para acceder de manera segura y controlar mis datos personales.                                     |
| EP04 (Entrada de parqueo)                                                  | Como conductor, quiero poder ingresar a un estacionamiento escaneando un código QR en la entrada con mi celular, para registrarse al sistema de estacionamiento virtual de mi destino.                     |
| EP05 (Notificaciones y Alertas)                                            | Como conductor, quiero recibir notificaciones y alertas confirmando mi entrada, pago y tiempo restante de tolerancias de pago, para estar informado y tomar decisiones oportunas.                          |
| EP06 (Gestión de pago en línea)                                            | Como conductor, quiero registrar mis tarjetas y preferencias de pago para pagar en línea o automáticamente por mi celular, para los momentos en qué desee retirarme del estacionamiento                    |
| EP07 (Pago y retiro del estacionamiento)                                   | Como conductor, quiero realizar el pago en línea o automático al momento de querer retirarme del estacionamiento, para poder salir de la ubicación sin hacer cola alguna.                                  |
| EP08 (Gestión de cuentas administrativas de ParkUp)                        | Como administrador, quiero obtener una cuenta, iniciar sesión y gestionar mi cuenta desde la aplicación web de ParkUp, para acceder de manera segura al sistema de monitoreo de ParkUp.                    |
| EP09 (Gestión de Información de Sistemas IoT)                              | Como administrador, quiero acceder y gestionar la información generada por los dispositivos IoT, para monitorear el sistema de parqueo y tomar decisiones basadas en datos.                                |
| EP10 (Optimización de la API)                                              | Como desarrollador, quiero implementar los protocolos de comunicación correctos de cada endpoint API para mejorar la eficiencia en la entrega de recursos y optimizar el rendimiento del sistema.          |
| EP11 (Sistema de Parking Spots)                                            | Como conductor, quiero ver los estacionamientos disponibles en mi ubicación por luz LED, para poder saber donde estacionarme.                                                                              |

| EP01 (Landing Page atractiva de ParkUp) | Como visitante, deseo una landing page intuitiva y atractiva que proporcione información clara sobre la aplicación de ParkUp, para facilitar mi toma de decisiones y acelerar mi uso de la plataforma. |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| US01                                    | Barra de navegación en Landing Page                                                                                                                                                                    |
| US02                                    | Encabezado de Bienvenida de Landing Page                                                                                                                                                               |
| US03                                    | Sección Sobre Nosotros de Landing page                                                                                                                                                                 |
| US04                                    | Demostración del funcionamiento de la aplicación en el Landing Page                                                                                                                                    |
| US05                                    | Descripción de las funcionalidades de la aplicación en el Landing Page                                                                                                                                 |
| US06                                    | Reseñas en el Landing page                                                                                                                                                                             |
| US07                                    | Preguntas y Respuestas en Landing Page                                                                                                                                                                 |
| US08                                    | Sección de Clientes Satisfechos                                                                                                                                                            |
| US09                                    | Sección de Contáctanos en Landing Page                                                                                                                                                                 |
| US10                                    | Footer en Landing Page                                                                                                                                                                                 |

| EP02 (Integración y desarrollo de Sistemas IoT de Parking y Monitoreo) | Como developer, quiero que los sistemas de parqueo estén conectados mediante IoT, para obtener información en tiempo real sobre la disponibilidad de espacios y mejorar la experiencia de estacionamiento. |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TS01                                                                   | Puerta de Entrada del Parking IoT con Cámara                                                                                                                                                               |
| TS02                                                                   | Puerta de Salida del Parking IoT con Cámara                                                                                                                                                                |
| TS03                                                                   | Sensores Magnéticos IoT en cada Estacionamiento                                                                                                                                                            |
| TS04                                                                   | IoT Gateway                                                                                                                                                                                                |
| TS05                                                                   | Edge Node IoT en cada Estacionamiento                                                                                                                                                                      |
| TS08                                                                   | Cámaras de Vigilancia IoT                                                                                                                                                                                  |

| EP03 (Gestión de cuentas de usuarios en la Mobile App de ParkUp) | Como conductor, quiero registrarme, iniciar sesión y gestionar mi cuenta desde la app móvil de ParkUp, para acceder de manera segura y controlar mis datos personales. |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US11                                                             | Registro de conductor como usuario                                                                                                                                     |
| US12                                                             | Inicio de sesión de conductor                                                                                                                                          |
| TS06                                                             | Autenticación basada en token JWT                                                                                                                                      |
| US13                                                             | Edición de perfil de conductor                                                                                                                                         |
| US14                                                             | Recuperación de contraseña                                                                                                                                             |
| US15                                                             | Eliminación de cuenta de conductor                                                                                                                                     |

| EP04 (Entrada de parqueo) | Como conductor, quiero poder ingresar a un estacionamiento escaneando un código QR en la entrada con mi celular, para registrarse al sistema de estacionamiento virtual de mi destino. |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US16                      | Escaneo QR mediante celular por el conductor                                                                                                                                           |
| US17                      | Visualización de estacionamientos disponibles, en tiempo-real, más cercanos al conductor                                                                                               |
| US18                      | Confirmación automática o manual de estacionamiento realizado por el conductor                                                                                                         |
| US19                      | Visualización de menú de estacionamiento para el conductor                                                                                                                             |

| EP05 (Notificaciones y Alertas) | Como conductor, quiero recibir notificaciones y alertas confirmando mi entrada, pago y tiempo restante de tolerancias de pago, para estar informado y tomar decisiones oportunas. |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US20                            | Notificación de entrada a estacionamiento para el conductor                                                                                                                       |
| US21                            | Notificación de pago de estacionamiento para el conductor                                                                                                                         |
| US22                            | Notificación de poco tiempo antes del fin de la tolerancia de pago de un estacionamiento para el conductor                                                                        |
| US23                            | Notificación de fin de tolerancia de pago de un estacionamiento para el conductor                                                                                                 |

| EP06 (Pago en línea al momento del retiro del estacionamiento) | Como conductor, quiero pagar en línea o automáticamente por mi celular al momento de querer retirarme del estacionamiento, para poder salir de la ubicación sin hacer cola alguna. |
| -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TS07                                                           | Permiso de bancas para utilizar sus datos en la pasarela de pago                                                                                                                   |
| US24                                                           | Registro de tarjeta de crédito/débito del conductor                                                                                                                                |
| US25                                                           | Eliminación de tarjeta de crédito/débito del conductor                                                                                                                             |
| US26                                                           | Visualización de listado de tarjetas de crédito/débito del conductor                                                                                                               |

| EP07 (Pago y retiro del estacionamiento) | Como conductor, quiero realizar el pago en línea o automático al momento de querer retirarme del estacionamiento, para poder salir de la ubicación sin hacer cola alguna. |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US27                                     | Activación y Desactivación de pago automático del conductor                                                                                                               |
| US28                                     | Realización de convalidación de pago del estacionamiento del conductor                                                                                                    |
| US29                                     | Realización del pago a cancelar del estacionamiento del conductor                                                                                                         |
| US30                                     | Retiro ininterrumpido del estacionamiento por pago automático                                                                                                             |
| US31                                     | Retiro posterior al pago manual del estacionamiento                                                                                                                       |
| US32                                     | Visualización de tiempo de tolerancia desde cancelación del pago del estacionamiento                                                                                      |
| US33                                     | Visualización de boleta virtual e interactiva del estacionamiento realizado                                                                                               |
| US34                                     | Visualización de listado de boletas virtuales e interactivas de estacionamientos realizados                                                                               |

| EP08 (Gestión de cuentas administrativas de ParkUp) | Como administrador, quiero obtener una cuenta, iniciar sesión y gestionar mi cuenta desde la aplicación web de ParkUp, para acceder de manera segura al sistema de monitoreo de ParkUp. |
| --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US35                                                | Obtención de cuenta administrativa de un estacionamiento                                                                                                                                |
| US36                                                | Inicio de sesión de administrador                                                                                                                                                       |
| US37                                                | Recuperación de una cuenta administrativa por correo vinculado                                                                                                                          |
| US38                                                | Servicio al cliente para edición o recuperación de una cuenta administrativa de un estacionamiento                                                                                      |
| US39                                                | Edición del perfil de una cuenta administrativa                                                                                                                                         |

| EP09 (Gestión de Información de Dispositivos IoT) | Como administrador, quiero acceder y gestionar la información generada por los dispositivos IoT, para monitorear el sistema de parqueo y tomar decisiones basadas en datos. |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TS09                                              | Dispositivos de Monitoreo de Funcionalidad de otros Dispositivos IoT                                                                                                        |
| US40                                              | Visualización de Resumen Estadístico del uso del Estacionamiento como menú principal                                                                                        |
| US41                                              | Visualización de las cámaras de seguridad del estacionamiento                                                                                                               |
| US42                                              | Visualización detallada de una cámara de seguridad del estacionamiento                                                                                                      |
| US43                                              | Visualización del listado de conductores estacionados actualmente y anteriormente                                                                                           |
| US44                                              | Visualización del listado de conductores estacionados durante un día en específico.                                                                                         |
| US45                                              | Visualización detallada de un conductor en específico.                                                                                                                      |
| US46                                              | Visualización de sistema de resolución de casos extremos en el estacionamiento                                                                                              |
| US47                                              | Cancelación manual del pago de algún conductor por caso extremo                                                                                                             |
| US48                                              | Visualización de monitoreo de la funcionalidad de los dispositivos IoT del estacionamiento                                                                                  |

| EP10 (Optimización de la API) | Como desarrollador, quiero implementar los protocolos de comunicación correctos de cada endpoint API para mejorar la eficiencia en la entrega de recursos y optimizar el rendimiento del sistema. |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TS10                          | Implementación de un servicio IAM con REST API                                                                                                                                                    |
| TS11                          | Implementación de un servicio Camera Feed con WebRTC                                                                                                                                              |
| TS13                          | Implementación de un servicio Payments con REST API                                                                                                                                               |
| TS14                          | Implementación de un servicio Parking Circulation con REST API                                                                                                                                    |
| TS15                          | Implementación de un servicio Monitoring con REST API                                                                                                                                             |
| TS16                          | Implementación de un servicio Ticket Validation con REST API                                                                                                                                      |
| TS17                          | Implementación de un servicio Notifications con REST API                                                                                                                                          |

| EP11 (Sistema de Parking Spots) | Como conductor, quiero ver los estacionamientos disponibles en mi ubicación por luz LED, para poder saber donde estacionarme. |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| TS12                            | Implementación de un servicio Parking Spots con REST API                                                                      |
| US49                            | Cambio de luz LED cuando un carro se estaciona                                                                                |

***User Stories***

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| --------------- | ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------- |
| US01 | Barra de navegación de Landing Page | Como visitante, quiero una barra de navegación accesible para moverme fácilmente entre las secciones principales de la landing page. | Feature: Barra de navegación de Landing Page<br><br>Scenario: Visualización y funcionamiento de la barra de navegación<br>Given que el visitante accede a la landing page<br>When visualiza la parte superior del sitio<br>Then debería ver una barra de navegación con enlaces a las secciones principales<br>And al hacer clic en un enlace, debería desplazarse a esa sección<br><br>Scenario: Error en la carga de la barra de navegación<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la barra de navegación<br>Then debería mostrarse un mensaje de error | EP01 |
| US02 | Encabezado de Bienvenida de Landing Page | Como visitante, quiero visualizar de forma inmediata un encabezado con el propósito de la aplicación ParkUp, junto con un llamado a la acción claro que me motive a explorar la plataforma. | Feature: Encabezado de Bienvenida de Landing Page<br><br>Scenario: Visualización del encabezado de bienvenida<br>Given que el visitante accede a la landing page<br>When observa la parte superior del sitio<br>Then debería ver un encabezado claro con el propósito de la aplicación ParkUp<br>And debería ver un llamado a la acción claro para explorar la plataforma<br><br>Scenario: Falta de visualización del encabezado<br>Given que el visitante accede a la landing page<br>When el encabezado no carga correctamente<br>Then debería mostrarse un mensaje de error indicando que el encabezado no está disponible | EP01 |
| US03 | Sección Sobre Nosotros de Landing Page | Como visitante, quiero conocer la misión, visión y el equipo de desarrollo de ParkUp, con el fin de generar confianza en el proyecto y comprender su impacto. | Feature: Sección Sobre Nosotros de Landing Page<br><br>Scenario: Visualización de la sección "Sobre Nosotros"<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Sobre Nosotros" en la barra de navegación<br>Then debería visualizar la misión, visión y el equipo de desarrollo de ParkUp<br>And la información debe estar organizada y ser clara<br><br>Scenario: Error en la carga de la sección "Sobre Nosotros"<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la sección "Sobre Nosotros"<br>Then debería mostrarse un mensaje de error | EP01 |
| US04 | Demostración del funcionamiento de la aplicación en la Landing Page | Como visitante, quiero observar una demostración visual del funcionamiento de la aplicación, para entender de manera práctica su utilidad y facilidad de uso. | Feature: Demostración del funcionamiento de la aplicación en el Landing Page<br><br>Scenario: Visualización de la demostración del funcionamiento de la aplicación<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de la demostración<br>Then debería ver un video o animación visual que explique cómo funciona la aplicación ParkUp<br>And el contenido debe ser claro y fácil de entender<br><br>Scenario: Error en la carga de la demostración<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la demostración<br>Then debería mostrarse un mensaje de error | EP01 |
| US05 | Descripción de las funcionalidades de la aplicación en el Landing Page | Como visitante, quiero explorar las funcionalidades principales de ParkUp, a fin de evaluar si satisfacen mis necesidades respecto a la gestión de estacionamientos. | Feature: Descripción de las funcionalidades de la aplicación en el Landing Page<br><br>Scenario: Visualización de las funcionalidades de la aplicación<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Funcionalidades" en la barra de navegación<br>Then debería visualizar una lista clara y detallada de las funcionalidades principales de ParkUp<br>And cada funcionalidad debe estar acompañada de una breve descripción<br><br>Scenario: Error en la carga de las funcionalidades<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la sección de funcionalidades<br>Then debería mostrarse un mensaje de error | EP01 |
| US06 | Reseñas en el Landing Page | Como visitante, quiero leer opiniones de otros usuarios sobre la aplicación, con el objetivo de obtener una referencia confiable sobre la efectividad del producto. | Feature: Reseñas en el Landing Page<br><br>Scenario: Visualización de las reseñas de otros usuarios<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Reseñas" en la barra de navegación<br>Then debería visualizar una lista de opiniones de otros usuarios sobre la aplicación<br>And las reseñas deben ser verídicas y fácilmente legibles<br><br>Scenario: Error en la carga de las reseñas<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de las reseñas<br>Then debería mostrarse un mensaje de error | EP01 |
| US07 | Preguntas y Respuestas en Landing Page | Como visitante, quiero acceder a una sección de preguntas frecuentes que resuelva dudas comunes de manera rápida y concisa. | Feature: Preguntas y Respuestas en Landing Page<br><br>Scenario: Visualización de la sección de Preguntas y Respuestas<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Preguntas y Respuestas" en la barra de navegación<br>Then debería visualizar una lista de preguntas frecuentes con respuestas claras y concisas<br><br>Scenario: Error en la carga de las preguntas y respuestas<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la sección de Preguntas y Respuestas<br>Then debería mostrarse un mensaje de error | EP01 |
| US08 | Clientes Satisfechos en Landing Page | Como visitante, quiero visualizar una sección de clientes satisfechos que muestre anteriores casos de exito para asegurarme la funcionalidad de la aplicación. | Feature: Clientes Satisfechos en Landing Page<br><br>Scenario: Visualización de la sección de Clientes Satisfechos<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Clientes Satisfechos" en la barra de navegación<br>Then debería visualizar una lista de establecimientos y clientes usuarios del sistema.<br><br>Scenario: Error en la carga de los Clientes Satisfechos<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la sección de Clientes Satisfechos<br>Then debería mostrarse un mensaje de error | EP01 |
| US09 | Sección de Contáctanos en Landing Page | Como visitante, quiero disponer de una sección de contacto para comunicarme con el equipo de ParkUp en caso de requerir más información o asistencia. | Feature: Sección de Contáctanos en Landing Page<br><br>Scenario: Visualización de la sección de contacto<br>Given que el visitante accede a la landing page<br>When hace clic en el enlace de "Contáctanos" en la barra de navegación<br>Then debería visualizar un formulario de contacto <br><br>Scenario: Error en la carga de la sección de contacto<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga de la sección de "Contáctanos"<br>Then debería mostrarse un mensaje de error | EP01 |
| US10 | Footer en Landing Page | Como visitante, quiero encontrar en el pie de página enlaces útiles y de acceso rápido que complementen mi navegación por el sitio. | Feature: Footer en Landing Page<br><br>Scenario: Visualización del pie de página<br>Given que el visitante accede a la landing page<br>When llega al final de la página<br>Then debería visualizar enlaces útiles en el pie de página <br>And los enlaces deben ser accesibles y funcionales<br><br>Scenario: Error en la carga del pie de página<br>Given que el visitante accede a la landing page<br>When ocurre un fallo en la carga del pie de página<br>Then debería mostrarse un mensaje de error | EP01 |
| US11 | Registro de conductor como usuario | Como developer, quiero que el conductor pueda registrarse como usuario en el sistema, para poder acceder a las funcionalidades del sistema de parqueo conectado por IoT. | Feature: Registro de conductor como usuario<br><br>Scenario: Registro exitoso de conductor<br>Given que el conductor accede al registro<br>When ingresa sus datos personales y presiona "Registrarse"<br>Then debería ver un mensaje de éxito indicando que el registro fue exitoso<br>And el conductor debería recibir un correo de confirmación<br><br>Scenario: Error en el registro por datos incompletos<br>Given que el conductor accede a la página de registro<br>When ingresa datos incompletos y presiona "Registrarse"<br>Then debería ver un mensaje de error indicando qué campos faltan<br>And no debería ser registrado en el sistema | EP01 |
| US12 | Inicio de sesión de conductor | Como developer, quiero que el conductor pueda iniciar sesión en el sistema utilizando sus credenciales, para que pueda acceder a la plataforma y gestionar su estacionamiento. | Feature: Inicio de sesión de conductor<br><br>Scenario: Inicio de sesión exitoso<br>Given que el conductor tiene una cuenta registrada<br>When ingresa sus credenciales correctas y presiona "Iniciar sesión"<br>Then debería ser redirigido a la página principal del sistema<br>And debería ver un mensaje de bienvenida<br><br>Scenario: Error en el inicio de sesión por credenciales incorrectas<br>Given que el conductor tiene una cuenta registrada<br>When ingresa credenciales incorrectas y presiona "Iniciar sesión"<br>Then debería ver un mensaje de error indicando que las credenciales son incorrectas<br>And no debería acceder a la plataforma | EP03 |
| US13 | Edición de perfil de conductor | Como developer, quiero que el conductor pueda editar su perfil, para que pueda actualizar sus datos personales y guardar su método de pago de preferencia en el sistema. | Feature: Edición de perfil de conductor<br><br>Scenario: Edición exitosa del perfil<br>Given que el conductor está autenticado en el sistema<br>When ingresa a la sección de "Editar perfil" y actualiza su información<br>Then debería ver un mensaje de éxito indicando que los cambios fueron guardados<br>And los cambios deberían reflejarse en su perfil<br><br>Scenario: Error al editar perfil por datos inválidos<br>Given que el conductor está autenticado en el sistema<br>When ingresa datos inválidos en el formulario de perfil y presiona "Guardar cambios"<br>Then debería ver un mensaje de error indicando qué datos son inválidos<br>And no deberían guardarse los cambios | EP03 |
| US14 | Recuperación de contraseña | Como developer, quiero permitir que el conductor recupere su contraseña de forma segura, para que pueda recuperar el acceso a su cuenta en caso de olvidar sus credenciales. | Feature: Recuperación de contraseña<br><br>Scenario: Recuperación exitosa de contraseña<br>Given que el conductor ha olvidado su contraseña<br>When ingresa su correo en la sección de "Recuperar contraseña" y presiona "Enviar enlace"<br>Then debería recibir un correo con el enlace para restablecer su contraseña<br>And debería poder ingresar una nueva contraseña<br><br>Scenario: Error en la recuperación de contraseña por correo no registrado<br>Given que el conductor ha olvidado su contraseña<br>When ingresa un correo no registrado en la sección de "Recuperar contraseña"<br>Then debería ver un mensaje de error indicando que el correo no está registrado<br>And no debería recibir un correo de recuperación | EP03 |
| US15 | Eliminación de cuenta de conductor | Como developer, quiero que el conductor pueda eliminar su cuenta de usuario, para permitirle desvincularse completamente del sistema cuando así lo desee. | Feature: Eliminación de cuenta de conductor<br><br>Scenario: Eliminación exitosa de cuenta<br>Given que el conductor está autenticado en el sistema<br>When solicita la eliminación de su cuenta y confirma la acción<br>Then su cuenta debería ser eliminada permanentemente del sistema<br>And debería ver un mensaje de confirmación indicando que la cuenta ha sido eliminada<br><br>Scenario: Error al intentar eliminar cuenta sin confirmación<br>Given que el conductor está autenticado en el sistema<br>When solicita la eliminación de su cuenta pero no confirma la acción<br>Then no debería eliminarse su cuenta<br>And debería ver un mensaje de advertencia indicando que la acción no se completó | EP03 |
| US16 | Escaneo QR mediante celular por el conductor | Como conductor, quiero poder escanear un código QR con mi celular al llegar al estacionamiento, para poder acceder al sistema de estacionamientos del lugar. | Feature: Escaneo QR mediante celular por el conductor<br><br>Scenario: Escaneo exitoso de código QR<br>Given que el conductor llega al estacionamiento y tiene la app instalada<br>When escanea el código QR del estacionamiento usando su celular<br>Then debería ser redirigido automáticamente al sistema de parqueo<br>And debería ver la disponibilidad de espacios<br><br>Scenario: Error al escanear código QR<br>Given que el conductor llega al estacionamiento y tiene la app instalada<br>When intenta escanear un código QR no válido o ilegible<br>Then debería ver un mensaje de error indicando que el código QR no es válido<br>And no debería ser redirigido al sistema de parqueo | EP04 |
| US17 | Visualización de estacionamientos disponibles en tiempo real más cercanos al conductor | Como conductor, quiero ver en tiempo real los estacionamientos disponibles más cercanos, para poder tomar decisiones rápidas sobre dónde estacionar. | Feature: Visualización de estacionamientos disponibles, en tiempo real, más cercanos al conductor<br><br>Scenario: Visualización exitosa de estacionamientos cercanos<br>Given que el conductor está autenticado en el sistema <br>When solicita ver los estacionamientos disponibles cercanos a su ubicación<br>Then debería ver una lista de los estacionamientos disponibles más cercanos<br><br>Scenario: Error al visualizar estacionamientos disponibles<br>Given que el conductor está autenticado en el sistema<br>When el sistema no puede obtener la información de estacionamientos disponibles por problemas de red <br>Then debería ver un mensaje de error indicando que no se pueden mostrar los estacionamientos<br>And no debería ver una lista de estacionamientos | EP04 |
| US18 | Confirmación automática o manual de estacionamiento realizado por el conductor | Como conductor, quiero que el sistema confirme automáticamente o me permita confirmar manualmente que he estacionado en el lugar exacto, para garantizar que mi acción sea registrada correctamente. | Feature: Confirmación automática o manual de estacionamiento realizado por el conductor<br><br>Scenario: Confirmación exitosa de estacionamiento<br>Given que el conductor ha estacionado su vehículo<br>When el sistema detecta automáticamente que el vehículo ha sido estacionado o el conductor lo confirma manualmente<br>Then debería ver un mensaje indicando que el estacionamiento ha sido registrado correctamente<br>And el sistema debería actualizar el estado del espacio de estacionamiento como ocupado<br><br>Scenario: Error en la confirmación de estacionamiento<br>Given que el conductor ha estacionado su vehículo<br>When el sistema no puede detectar el estacionamiento debido a un error de IoT o el conductor no confirma manualmente<br>Then debería ver un mensaje de error indicando que el estacionamiento no ha sido registrado correctamente<br>And no debería actualizarse el estado del espacio | EP04 |
| US19 | Visualización de menú de estacionamiento para el conductor | Como conductor, quiero tener acceso a un menú de opciones dentro del sistema de estacionamiento, para gestionar acciones como pago, convalidación y solicitudes adicionales. | Feature: Visualización de menú de estacionamiento para el conductor<br><br>Scenario: Visualización exitosa del menú de estacionamiento<br>Given que el conductor está autenticado en el sistema<br>When accede al sistema de estacionamiento<br>Then debería ver un menú de opciones con acciones como pago, convalidación y solicitudes adicionales<br><br>Scenario: Error al cargar el menú de estacionamiento<br>Given que el conductor está autenticado en el sistema<br>When ocurre un fallo al cargar el menú de estacionamiento<br>Then debería ver un mensaje de error indicando que no se pudo cargar el menú<br>And el conductor no debería tener acceso a las opciones | EP04 |
| US20 | Notificación de entrada a estacionamiento para el conductor | Como conductor, quiero recibir una notificación confirmando mi entrada al estacionamiento, para estar seguro de que mi registro ha sido exitoso y la placa de mi vehículo se haya obtenido correctamente. | Feature: Notificación de entrada a estacionamiento para el conductor<br><br>Scenario: Notificación exitosa de entrada al estacionamiento<br>Given que el conductor ha ingresado al estacionamiento y su placa ha sido registrada correctamente<br>When el sistema procesa la entrada del vehículo<br>Then el conductor debería recibir una notificación confirmando su entrada al estacionamiento<br><br>Scenario: Error en la notificación de entrada al estacionamiento<br>Given que el conductor ha ingresado al estacionamiento<br>When hay un problema al registrar la entrada del vehículo<br>Then el conductor debería ver un mensaje de error indicando que la entrada no ha sido procesada correctamente<br>And no debería recibir la notificación de entrada | EP04 |
| US21 | Notificación de pago de estacionamiento para el conductor | Como conductor, quiero recibir una notificación que confirme el pago de mi estacionamiento, para saber que mi transacción ha sido procesada correctamente. | Feature: Notificación de pago de estacionamiento para el conductor<br><br>Scenario: Notificación exitosa de pago realizado<br>Given que el conductor ha realizado el pago del estacionamiento<br>When el sistema procesa el pago correctamente<br>Then el conductor debería recibir una notificación confirmando que el pago ha sido procesado<br><br>Scenario: Error en la notificación de pago<br>Given que el conductor ha intentado realizar el pago del estacionamiento<br>When hay un problema con el pago<br>Then el conductor debería ver un mensaje de error indicando que el pago no ha sido procesado<br>And no debería recibir la notificación de pago exitoso | EP05 |
| US22 | Notificación de poco tiempo antes del fin de la tolerancia de pago | Como conductor, quiero recibir una notificación cuando el tiempo de tolerancia esté por terminar, y si supero ese tiempo, el sistema automáticamente me solicitará realizar un nuevo pago, para asegurar que el estacionamiento continúe registrado y evitar problemas al salir. | Feature: Notificación de poco tiempo antes del fin de la tolerancia de pago de un estacionamiento para el conductor<br><br>Scenario: Notificación exitosa antes de que termine el tiempo de tolerancia<br>Given que el conductor ha pagado el estacionamiento<br>When el tiempo de tolerancia está por finalizar<br>Then el conductor debería recibir una notificación indicando que el tiempo de tolerancia está por terminar<br><br>Scenario: Error en la notificación de tiempo de tolerancia<br>Given que el conductor ha pagado el estacionamiento<br>When el sistema no puede calcular correctamente el tiempo de tolerancia restante<br>Then el conductor debería recibir un mensaje de error o no recibir la notificación a tiempo | EP05 |
| US23 | Notificación de fin de tolerancia de pago de un estacionamiento | Como conductor, quiero recibir una notificación cuando el tiempo de tolerancia de pago haya terminado, para saber qué debo pagar de nuevo. | Feature: Notificación de fin de tolerancia de pago de un estacionamiento para el conductor<br><br>Scenario: Notificación exitosa de fin de tolerancia<br>Given que el conductor ha pagado el estacionamiento<br>When el tiempo de tolerancia ha terminado<br>Then el conductor debería recibir una notificación indicando que debe realizar un nuevo pago<br><br>Scenario: Error en la notificación de fin de tolerancia<br>Given que el conductor ha pagado el estacionamiento<br>When el sistema no puede procesar correctamente el tiempo de tolerancia<br>Then el conductor debería ver un mensaje de error indicando que no se pudo enviar la notificación | EP05 |
| US24 | Registro de tarjeta de crédito/débito del conductor | Como conductor, quiero registrar mi tarjeta de crédito/débito en el sistema, para poder realizar pagos automáticos cuando desee retirar el vehículo del estacionamiento. | Feature: Registro de tarjeta de crédito/débito del conductor<br><br>Scenario: Registro exitoso de tarjeta de crédito/débito<br>Given que el conductor está autenticado en el sistema<br>When ingresa los detalles de su tarjeta de crédito/débito y confirma<br>Then la tarjeta debería ser registrada en el sistema<br>And el conductor debería ver un mensaje de éxito<br><br>Scenario: Error al registrar tarjeta de crédito/débito<br>Given que el conductor está autenticado en el sistema<br>When ingresa datos incorrectos o incompletos para registrar su tarjeta<br>Then debería ver un mensaje de error indicando que los datos no son válidos<br>And no se debería registrar la tarjeta en el sistema | EP06 |
| US25 | Eliminación de tarjeta de crédito/débito del conductor | Como conductor, quiero poder eliminar mi tarjeta de crédito/débito del sistema, para asegurarme de que no se mantengan mis datos de pago almacenados si ya no los necesito. | Feature: Eliminación de tarjeta de crédito/débito del conductor<br><br>Scenario: Eliminación exitosa de tarjeta de crédito/débito<br>Given que el conductor tiene una tarjeta de crédito/débito registrada<br>When solicita eliminar la tarjeta y confirma la acción<br>Then la tarjeta debería ser eliminada del sistema<br>And el conductor debería recibir un mensaje de confirmación<br><br>Scenario: Error al intentar eliminar tarjeta de crédito/débito<br>Given que el conductor tiene una tarjeta de crédito/débito registrada<br>When solicita eliminar la tarjeta pero no confirma la acción<br>Then la tarjeta no debería ser eliminada<br>And el conductor debería ver un mensaje indicando que la eliminación no se realizó | EP06 |
| US26 | Visualización de listado de tarjetas de crédito/débito del conductor | Como conductor, quiero visualizar un listado de las tarjetas de crédito/débito registradas en mi perfil, para poder elegir cuál utilizar al momento de realizar el pago en línea. | Feature: Visualización de listado de tarjetas de crédito/débito del conductor<br><br>Scenario: Visualización exitosa del listado de tarjetas<br>Given que el conductor tiene varias tarjetas registradas<br>When accede a la sección de "Tarjetas de crédito/débito" en su perfil<br>Then debería ver un listado de las tarjetas registradas con su tipo y último dígito<br><br>Scenario: Error al intentar visualizar las tarjetas registradas<br>Given que el conductor tiene tarjetas registradas<br>When hay un fallo en la carga del listado de tarjetas<br>Then debería ver un mensaje de error indicando que no se pueden cargar las tarjetas<br>And no debería ver el listado | EP06 |
| US27 | Activación y Desactivación de pago automático del conductor | Como conductor, quiero poder activar o desactivar el pago automático para mis futuras transacciones de estacionamiento, para decidir cómo realizar el pago al momento de retirarme. | Feature: Activación y Desactivación de pago automático del conductor<br><br>Scenario: Activación exitosa de pago automático<br>Given que el conductor está autenticado en el sistema<br>When activa la opción de "Pago automático" en su perfil<br>Then el pago automático debería quedar habilitado para sus futuras transacciones<br>And el conductor debería recibir un mensaje de confirmación<br><br>Scenario: Error al intentar activar el pago automático<br>Given que el conductor está autenticado en el sistema<br>When hay un fallo en la activación del pago automático<br>Then debería ver un mensaje de error indicando que no se pudo activar la opción<br>And el pago automático no debería ser activado | EP06 |
| US28 | Realización de convalidación de pago del estacionamiento del conductor | Como conductor, quiero realizar la convalidación de mi pago de estacionamiento, para confirmar que mi transacción ha sido procesada correctamente antes de salir. | Feature: Realización de convalidación de pago del estacionamiento del conductor<br><br>Scenario: Convalidación exitosa del pago<br>Given que el conductor ha realizado el pago del estacionamiento<br>When solicita realizar la convalidación del pago<br>Then el sistema debería confirmar que la transacción ha sido procesada correctamente<br>And el conductor debería ver una notificación de confirmación<br><br>Scenario: Error al realizar la convalidación de pago<br>Given que el conductor ha intentado realizar la convalidación del pago<br>When hay un problema con el proceso de convalidación<br>Then el conductor debería ver un mensaje de error indicando que la convalidación no fue exitosa<br>And no debería quedar registrado el pago | EP07 |
| US29 | Realización del pago a cancelar del estacionamiento del conductor | Como conductor, quiero realizar el pago correspondiente al estacionamiento mediante una opción manual o automática, para completar mi transacción y poder retirarme sin problemas. | Feature: Realización del pago a cancelar del estacionamiento del conductor<br><br>Scenario: Pago exitoso realizado por el conductor<br>Given que el conductor desea pagar por su estacionamiento<br>When realiza el pago mediante el sistema<br>Then el sistema debería procesar el pago correctamente y actualizar el estado del estacionamiento<br><br>Scenario: Error al realizar el pago<br>Given que el conductor desea pagar por su estacionamiento<br>When hay un problema al procesar el pago<br>Then el conductor debería ver un mensaje de error indicando que el pago no fue exitoso<br>And el estado del estacionamiento no debe actualizarse | EP07 |
| US30 | Retiro ininterrumpido del estacionamiento por pago automático | Como conductor, quiero poder retirar mi vehículo sin interrupciones después de haber realizado el pago automático, para no tener que hacer ninguna acción adicional. | Feature: Retiro ininterrumpido del estacionamiento por pago automático<br><br>Scenario: Retiro exitoso después de pago automático<br>Given que el conductor ha activado el pago automático y el pago ha sido procesado correctamente<br>When el conductor llega a la salida del estacionamiento<br>Then debería poder retirar su vehículo sin interrupciones ni acciones adicionales<br><br>Scenario: Error al retirar el vehículo después de pago automático<br>Given que el conductor ha activado el pago automático y el pago ha sido procesado correctamente<br>When el sistema no permite el retiro del vehículo por un fallo en la validación de pago<br>Then el conductor debería ver un mensaje de error indicando que no puede retirar el vehículo<br>And el vehículo no debería salir del estacionamiento | EP07 |
| US31 | Retiro posterior al pago manual del estacionamiento | Como conductor, quiero poder retirar mi vehículo después de realizar el pago manual, asegurándome de que la transacción esté confirmada antes de salir del estacionamiento. | Feature: Retiro posterior al pago manual del estacionamiento<br><br>Scenario: Retiro exitoso después de pago manual<br>Given que el conductor ha realizado un pago manual y la transacción ha sido confirmada<br>When el conductor llega a la salida del estacionamiento<br>Then debería poder retirar su vehículo sin problemas, tras confirmar el pago<br><br>Scenario: Error al retirar el vehículo después de pago manual<br>Given que el conductor ha realizado un pago manual y la transacción ha sido confirmada<br>When el sistema no valida correctamente el pago del conductor<br>Then el conductor debería ver un mensaje de error indicando que la transacción no ha sido confirmada<br>And no debería poder retirar su vehículo hasta que el problema sea solucionado | EP07 |
| US32 | Visualización de tiempo de tolerancia desde cancelación del pago | Como conductor, quiero visualizar el tiempo de tolerancia después de cancelar el pago del estacionamiento, para saber cuánto tiempo tengo antes de que se genere una penalización o multa. | Feature: Visualización del tiempo de tolerancia después del pago<br><br>Scenario: Conductor visualiza el tiempo de tolerancia restante<br>Given que el conductor ha realizado un pago exitoso<br>When accede a la pantalla de tiempo de tolerancia<br>Then el sistema muestra una cuenta regresiva con el tiempo restante<br><br>Scenario: Conductor intenta ver tolerancia sin haber pagado<br>Given que el conductor no ha realizado un pago<br>When intenta acceder al tiempo de tolerancia<br>Then el sistema muestra un mensaje indicando que no hay tolerancia activa | EP07 |
| US33 | Visualización de boleta virtual e interactiva del estacionamiento realizado | Como conductor, quiero ver una boleta virtual e interactiva del estacionamiento realizado, para consultar los detalles de mi uso del estacionamiento de forma clara y digital. | Feature: Visualización de boleta virtual interactiva del estacionamiento<br><br>Scenario: Conductor accede a su boleta reciente<br>Given que el conductor tiene una boleta generada<br>When accede al módulo de boleta<br>Then el sistema muestra los detalles del estacionamiento (hora, pago, ubicación)<br><br>Scenario: No hay boleta disponible para mostrar<br>Given que el conductor aún no ha completado un estacionamiento<br>When intenta ver una boleta<br>Then el sistema muestra un mensaje de "sin boleta disponible" | EP07 |
| US34 | Visualización de listado de boletas virtuales e interactivas de estacionamientos realizados | Como conductor, quiero visualizar un listado de todas mis boletas virtuales e interactivas de estacionamientos realizados, para tener un historial de mis pagos y usos anteriores. | Feature: Historial de boletas virtuales de estacionamiento<br><br>Scenario: Conductor revisa su historial de boletas<br>Given que el conductor tiene estacionamientos previos<br>When accede al historial de boletas<br>Then el sistema muestra una lista con detalles resumidos de cada una<br><br>Scenario: Conductor sin historial previo<br>Given que el conductor nunca ha estacionado<br>When accede al historial de boletas<br>Then el sistema indica que no hay registros disponibles | EP07 |
| US35 | Obtención de cuenta administrativa de un estacionamiento | Como administrador, quiero obtener una cuenta administrativa para un estacionamiento, para poder gestionar y supervisar sus operaciones. | Feature: Registro de cuenta administrativa para un estacionamiento<br><br>Scenario: Administrador solicita y recibe acceso<br>Given que el administrador completa el formulario con los datos del estacionamiento<br>When envía la solicitud<br>Then el sistema genera la cuenta y envía las credenciales por correo<br><br>Scenario: Solicitud con datos incompletos o inválidos<br>Given que el formulario tiene errores de validación<br>When se intenta enviar<br>Then el sistema rechaza la solicitud y muestra los errores | EP08 |
| US36 | Inicio de sesión de administrador | Como administrador, quiero iniciar sesión en el sistema, para acceder a las funcionalidades de gestión del estacionamiento. | Feature: Inicio de sesión del administrador<br><br>Scenario: Acceso exitoso con credenciales válidas<br>Given que el administrador tiene un usuario y contraseña válidos<br>When ingresa sus credenciales en el login<br>Then accede correctamente al sistema<br><br>Scenario: Intento de login con credenciales incorrectas<br>Given que el administrador ingresa una contraseña errónea<br>When intenta iniciar sesión<br>Then el sistema muestra un mensaje de error<br>And no permite el acceso | EP08 |
| US37 | Recuperación de una cuenta administrativa por correo vinculado | Como administrador, quiero recuperar mi cuenta administrativa usando mi correo vinculado, para restablecer el acceso en caso de olvido de credenciales. | Feature: Recuperación de cuenta administrativa por correo<br><br>Scenario: Recuperación exitosa con correo válido<br>Given que el administrador ingresa un correo vinculado a su cuenta<br>When solicita recuperación<br>Then el sistema envía un enlace de restablecimiento al correo<br><br>Scenario: Correo no vinculado a ninguna cuenta<br>Given que el correo ingresado no está registrado<br>When se solicita recuperación<br>Then el sistema muestra un mensaje de "correo no registrado" | EP08 |
| US38 | Servicio al cliente para edición o recuperación de una cuenta administrativa | Como administrador, quiero contactar al servicio al cliente para editar o recuperar mi cuenta, para resolver problemas de acceso o errores en los datos de la cuenta. | Feature: Soporte para edición o recuperación de cuenta<br><br>Scenario: El administrador contacta al soporte y recibe respuesta<br>Given que el administrador completa el formulario de contacto<br>When envía la solicitud al servicio al cliente<br>Then recibe una confirmación y respuesta en menos de 24h<br><br>Scenario: El formulario de contacto es enviado incompleto<br>Given que el administrador no llena todos los campos requeridos<br>When intenta enviar el formulario<br>Then el sistema muestra los campos obligatorios con errores | EP08 |
| US39 | Edición del perfil de una cuenta administrativa | Como administrador, quiero editar el perfil de mi cuenta administrativa, para mantener mi información actualizada y correcta. | Feature: Edición del perfil del administrador<br><br>Scenario: El administrador actualiza su información correctamente<br>Given que el administrador está autenticado<br>When accede a su perfil y modifica su información<br>And guarda los cambios<br>Then el sistema actualiza el perfil correctamente<br>And muestra un mensaje de éxito<br><br>Scenario: El administrador deja campos requeridos vacíos<br>Given que el administrador accede a la edición del perfil<br>When deja el campo "correo electrónico" vacío<br>And guarda los cambios<br>Then el sistema muestra un mensaje de error de validación | EP08 |
| US40 | Visualización de Resumen Estadístico del uso del Estacionamiento como menú principal | Como administrador, quiero visualizar un resumen estadístico del uso del estacionamiento como menú principal, para obtener una visión general rápida del desempeño y uso del espacio. | Feature: Resumen estadístico como menú principal<br><br>Scenario: Acceso exitoso al panel estadístico<br>Given que el administrador inicia sesión en el sistema<br>When accede al menú principal<br>Then se muestran estadísticas de uso actual, histórico y ocupación promedio<br><br>Scenario: Fallo al cargar estadísticas por error de servicio<br>Given que hay un error en el servicio de estadísticas<br>When el administrador accede al menú principal<br>Then se muestra un mensaje de error<br>And se registra el incidente | EP08 |
| US41 | Visualización de las cámaras de seguridad del estacionamiento | Como administrador, quiero ver las cámaras de seguridad del estacionamiento, para monitorear en tiempo real lo que sucede en las instalaciones. | Feature: Visualización general de cámaras de seguridad<br><br>Scenario: El administrador visualiza correctamente todas las cámaras disponibles<br>Given que las cámaras están funcionando<br>When el administrador accede al módulo de cámaras<br>Then se muestran todas las transmisiones en tiempo real<br><br>Scenario: Una o más cámaras están desconectadas<br>Given que algunas cámaras están fuera de servicio<br>When el administrador accede al módulo de cámaras<br>Then el sistema muestra una indicación de cámara desconectada | EP09 |
| US42 | Visualización detallada de una cámara de seguridad del estacionamiento | Como administrador, quiero visualizar de forma detallada una cámara de seguridad específica, para enfocar mi atención en un área particular del estacionamiento. | Feature: Vista detallada de una cámara específica<br><br>Scenario: El administrador selecciona una cámara y visualiza su transmisión<br>Given que la cámara está conectada<br>When el administrador hace clic en una cámara del listado<br>Then se muestra su transmisión en vista ampliada<br><br>Scenario: La cámara seleccionada no tiene señal<br>Given que la cámara tiene problemas de conexión<br>When el administrador intenta abrir su vista detallada<br>Then el sistema informa que no hay señal disponible | EP09 |
| US43 | Visualización del listado de conductores estacionados actualmente y anteriormente | Como administrador, quiero ver el listado de conductores actualmente estacionados y de los que han estado anteriormente, para tener control y trazabilidad del uso del estacionamiento. | Feature: Visualización de conductores estacionados<br><br>Scenario: Visualización de conductores actualmente estacionados<br>Given que hay vehículos estacionados<br>When el administrador accede al módulo de conductores<br>Then se muestra el listado de usuarios presentes<br><br>Scenario: Error al recuperar historial de estacionados anteriores<br>Given que el sistema presenta un error de conexión con la base de datos<br>When el administrador solicita el historial<br>Then se muestra un mensaje de error temporal | EP09 |
| US44 | Visualización del listado de conductores estacionados durante un día en específico | Como administrador, quiero ver el listado de conductores que estuvieron estacionados durante un día específico, para realizar análisis o auditorías por fecha. | Feature: Visualización por fecha de conductores estacionados<br><br>Scenario: El administrador consulta el listado por una fecha válida<br>Given que hay registros del 15 de marzo<br>When selecciona esa fecha en el calendario<br>Then se muestra el listado de conductores de ese día<br><br>Scenario: El administrador selecciona una fecha sin registros<br>Given que no hay datos del 1 de enero<br>When selecciona esa fecha<br>Then el sistema muestra un mensaje indicando que no hay resultados | EP09 |
| US45 | Visualización detallada de un conductor en específico | Como administrador, quiero visualizar el detalle de un conductor en específico, para revisar su historial, pagos o incidentes relacionados. | Feature: Visualización del perfil de un conductor<br><br>Scenario: El administrador accede al perfil detallado de un conductor<br>Given que el conductor está registrado<br>When el administrador lo selecciona en la lista<br>Then se muestra su historial, pagos y eventos<br><br>Scenario: El conductor no existe en la base de datos<br>Given que el ID del conductor no es válido<br>When se intenta acceder a su detalle<br>Then el sistema muestra un mensaje de "conductor no encontrado" | EP09 |
| US46 | Visualización de sistema de resolución de casos extremos en el estacionamiento | Como administrador, quiero acceder al sistema de resolución de casos extremos en el estacionamiento, para poder actuar rápidamente ante situaciones fuera de lo común. | Feature: Gestión de casos extremos<br><br>Scenario: El administrador accede al sistema de casos extremos<br>Given que está autenticado como administrador<br>When accede a la sección de resolución de casos<br>Then puede visualizar y gestionar los casos activos<br><br>Scenario: El administrador sin permisos especiales intenta acceder<br>Given que el usuario tiene rol limitado<br>When accede al módulo de casos extremos<br>Then se deniega el acceso<br>And se muestra un mensaje de autorización insuficiente | EP09 |
| US47 | Cancelación manual del pago de algún conductor por caso extremo | Como administrador, quiero cancelar manualmente el pago de un conductor en un caso extremo, para ofrecer una solución rápida y excepcional ante imprevistos. | Feature: Cancelación excepcional de pago<br><br>Scenario: El administrador cancela el pago de un conductor<br>Given que hay un caso extremo aprobado<br>When el administrador selecciona el conductor y confirma la cancelación<br>Then el sistema anula el pago<br>And registra la excepción en el historial<br><br>Scenario: El administrador intenta cancelar un pago sin justificación<br>Given que no hay un caso extremo registrado<br>When intenta cancelar el pago<br>Then el sistema muestra una advertencia y bloquea la acción | EP09 |
| US48 | Visualización de monitoreo de la funcionalidad de los dispositivos IoT del estacionamiento | Como administrador, quiero visualizar el monitoreo de la funcionalidad de los dispositivos IoT del estacionamiento, para asegurarme de que todos los componentes estén operativos y detectar fallos a tiempo. | Feature: Visualización del estado de los dispositivos IoT<br><br>Scenario: Todos los dispositivos están operativos<br>Given que los sensores y cámaras están funcionando correctamente<br>When el administrador accede al panel de monitoreo<br>Then se muestran todos los dispositivos con estado "OK"<br><br>Scenario: Un sensor reporta fallo de funcionamiento<br>Given que un sensor no responde<br>When se consulta el estado en el panel<br>Then el dispositivo aparece en rojo o con estado "FALLANDO"<br>And se sugiere revisión técnica | EP09 |
| US49 | Cambio de luz LED cuando un carro se estaciona | Como conductor, quiero que la luz LED del espacio de estacionamiento cambie de color automáticamente cuando un vehículo se estacione, para saber visualmente si un espacio está ocupado o disponible. | Feature: Cambio de luz LED cuando un carro se estaciona<br><br>Scenario: Encendido de luz LED cuando un carro se estaciona correctamente<br>Given que el sensor IoT detecta la presencia de un vehículo en el espacio de estacionamiento<br>When el vehículo se posiciona correctamente dentro del espacio<br>Then la luz LED debería cambiar a color rojo para indicar que el espacio está ocupado<br><br>Scenario: Luz LED no cambia al detectar el vehículo<br>Given que el sensor IoT detecta un vehículo en el espacio de estacionamiento<br>When el sistema de control de luces presenta un fallo de comunicación<br>Then la luz LED debería mantenerse en su estado anterior<br>And se debería registrar un error en el sistema para su revisión técnica | EP09 |
| TS01 | Puerta de Entrada del Parking IoT con Cámara | Como desarrollador, quiero integrar una puerta de entrada IoT con cámara al sistema, para capturar imágenes o video de los vehículos al ingresar y permitir su control automatizado. | Feature: Registro de entrada de vehículos mediante cámara IoT<br><br>Scenario: Vehículo autorizado entra y es capturado correctamente<br>Given que el sistema está conectado a la cámara de la puerta de entrada<br>When un vehículo autorizado se aproxima<br>And la cámara captura la imagen del vehículo<br>Then la imagen se guarda en el sistema<br>And se abre la puerta automáticamente<br><br>Scenario: La cámara falla al capturar la imagen<br>Given que el sistema está operativo pero la cámara está desconectada<br>When un vehículo se aproxima<br>Then el sistema muestra una alerta de error de cámara<br>And no se permite el acceso al vehículo | EP11 |
| TS02 | Puerta de Salida del Parking IoT con Cámara | Como desarrollador, quiero implementar una puerta de salida IoT con cámara, para registrar la salida de vehículos y validar su autorización de forma visual o automática. | Feature: Registro de salida de vehículos mediante cámara IoT<br><br>Scenario: Vehículo con ticket válido sale y se registra su salida<br>Given que el sistema reconoce al vehículo mediante la cámara de salida<br>When el vehículo presenta un ticket válido<br>Then la cámara registra la salida<br>And la barrera se abre automáticamente<br><br>Scenario: Vehículo intenta salir sin autorización<br>Given que la cámara captura un vehículo en la salida<br>When el sistema no encuentra una entrada registrada o el ticket está vencido<br>Then el sistema muestra un mensaje de error<br>And no se abre la barrera | EP02 |
| TS03 | Sensores Magnéticos IoT en cada Estacionamiento | Como desarrollador, quiero instalar e integrar sensores magnéticos IoT en cada plaza de estacionamiento, para detectar la ocupación en tiempo real y alimentar el sistema de disponibilidad. | Feature: Detección de ocupación en tiempo real<br><br>Scenario: Un vehículo ocupa una plaza vacía<br>Given que el sensor magnético está activo en una plaza de estacionamiento<br>When un vehículo se estaciona<br>Then el sistema marca esa plaza como ocupada en el sistema<br><br>Scenario: El sensor reporta falsos positivos<br>Given que el sensor está mal calibrado<br>When no hay vehículo presente<br>Then el sistema marca incorrectamente la plaza como ocupada<br>And se notifica al administrador de la anomalía | EP02 |
| TS04 | IoT Gateway | Como desarrollador, quiero configurar un IoT Gateway que centralice la comunicación entre los dispositivos IoT y la nube, para asegurar la conectividad y sincronización de datos del sistema. | Feature: Comunicación centralizada entre dispositivos IoT y la nube<br><br>Scenario: Gateway conectado transmite datos correctamente<br>Given que todos los sensores y nodos Edge están conectados al Gateway<br>When se genera un evento de sensor<br>Then el Gateway transmite los datos a la nube exitosamente<br><br>Scenario: El Gateway pierde conexión con la nube<br>Given que el Gateway está en funcionamiento pero sin acceso a internet<br>When se genera un evento<br>Then el sistema guarda el evento en caché<br>And reintenta la sincronización cada 60 segundos | EP02 |
| TS05 | Edge Node IoT en cada Estacionamiento | Como desarrollador, quiero desplegar nodos Edge IoT en cada estación de parqueo, para procesar datos localmente y reducir la latencia en la toma de decisiones. | Feature: Procesamiento local de datos con nodos Edge<br><br>Scenario: El nodo Edge procesa la entrada de un vehículo<br>Given que el nodo Edge está operativo<br>When detecta un evento de entrada por el sensor<br>Then procesa el dato localmente<br>And envía resumen al Gateway<br><br>Scenario: Nodo Edge se desconecta del sistema<br>Given que el nodo Edge pierde energía o se desconecta<br>When ocurre un evento de sensor<br>Then no se realiza el procesamiento local<br>And se reporta la falla al sistema central | EP02 |
| TS06 | Autenticación basada en token JWT | Como desarrollador, quiero implementar un sistema de autenticación basado en tokens JWT, para permitir una autenticación segura y sin estado en todos los servicios del sistema. | Feature: Seguridad basada en autenticación JWT<br><br>Scenario: Usuario válido inicia sesión<br>Given que el usuario tiene credenciales válidas<br>When realiza login en la plataforma<br>Then se genera un token JWT firmado<br>And el usuario puede acceder a los servicios protegidos<br><br>Scenario: Usuario con credenciales inválidas<br>Given que el usuario proporciona una contraseña incorrecta<br>When intenta iniciar sesión<br>Then el sistema rechaza la solicitud<br>And no se genera ningún token JWT | EP03 |
| TS07 | Permiso de bancas para utilizar sus datos en la pasarela de pago | Como desarrollador, quiero gestionar los permisos y acuerdos necesarios con las instituciones bancarias o proveedores de pagos, para poder acceder y utilizar sus sistemas en la implementación de una pasarela de pago propia. | Feature: Integración con pasarelas de pago bancarias<br><br>Scenario: Acuerdo firmado con el banco<br>Given que se ha firmado un acuerdo de uso de API con el banco<br>When se realiza una transacción de pago<br>Then el sistema puede comunicarse con la API del banco<br>And la transacción se completa exitosamente<br><br>Scenario: No hay acuerdo firmado con el banco<br>Given que no se ha firmado ningún convenio con el banco<br>When se intenta acceder a sus sistemas de pago<br>Then el sistema bloquea el intento<br>And muestra un mensaje de error de integración no autorizada | EP03 |
| TS08 | Cámaras de Vigilancia IoT | Como desarrollador, quiero integrar cámaras de vigilancia IoT al sistema, para monitorear el entorno del estacionamiento en tiempo real y mejorar la seguridad. | Feature: Monitoreo de seguridad con cámaras de vigilancia IoT<br><br>Scenario: Cámaras operativas transmiten video correctamente<br>Given que las cámaras están encendidas y conectadas al sistema<br>When se inicia el monitoreo en tiempo real<br>Then se muestra la transmisión en vivo sin interrupciones<br><br>Scenario: Cámara fuera de línea<br>Given que una cámara ha perdido conexión con el sistema<br>When el sistema intenta acceder a su transmisión<br>Then se muestra una alerta de desconexión<br>And se notifica al personal técnico | EP06 |
| TS09 | Dispositivos de Monitoreo de Funcionalidad de otros Dispositivos IoT | Como desarrollador, quiero implementar dispositivos que supervisen el estado de funcionamiento de otros dispositivos IoT, para detectar fallos y garantizar la operatividad del sistema. | Feature: Supervisión del estado de dispositivos IoT<br><br>Scenario: Dispositivo IoT operativo es monitoreado correctamente<br>Given que un sensor está funcionando correctamente<br>When el sistema de monitoreo realiza una verificación<br>Then se registra el estado como "Operativo"<br><br>Scenario: Dispositivo presenta fallas<br>Given que un dispositivo no responde a la verificación<br>When el sistema intenta conectarse<br>Then se marca como "Inactivo"<br>And se genera una alerta automática | EP02 |
| TS10 | Implementación de un servicio IAM con REST API | Como desarrollador, quiero implementar un servicio de gestión de identidades y accesos (IAM) usando una REST API, para controlar la autenticación y autorización de usuarios dentro del sistema. | Feature: Gestión de identidades y accesos<br><br>Scenario: Usuario accede con token válido<br>Given que el usuario tiene un token válido<br>When accede a un recurso protegido vía API<br>Then el acceso es concedido<br><br>Scenario: Usuario intenta acceder sin token<br>Given que el usuario no proporciona un token<br>When intenta consumir un endpoint protegido<br>Then el sistema responde con código 401 | EP09 |
| TS11 | Implementación de un servicio Camera Feed con WebRTC | Como desarrollador, quiero implementar un servicio de transmisión de video en tiempo real desde cámaras usando WebRTC, para permitir la visualización en vivo del entorno del estacionamiento. | Feature: Transmisión en vivo por WebRTC<br><br>Scenario: WebRTC inicia transmisión exitosamente<br>Given que la cámara y el servidor están configurados correctamente<br>When un usuario accede al feed en tiempo real<br>Then se establece la conexión WebRTC<br>And se visualiza el video en vivo<br><br>Scenario: WebRTC falla por configuración incorrecta<br>Given que la señal WebRTC no puede establecerse<br>When el usuario intenta conectarse<br>Then se muestra un mensaje de error<br>And no se transmite el video | EP10 |
| TS12 | Implementación de un servicio Parking Spots con REST API | Como desarrollador, quiero crear un servicio REST API para gestionar la disponibilidad y estado de los espacios de estacionamiento, para facilitar la consulta y reserva en tiempo real. | Feature: Gestión de plazas de estacionamiento<br><br>Scenario: Consulta de disponibilidad exitosa<br>Given que hay plazas disponibles<br>When un cliente consulta el estado vía API<br>Then recibe una lista de espacios libres<br><br>Scenario: Reserva de una plaza ya ocupada<br>Given que una plaza ya está ocupada<br>When otro usuario intenta reservarla<br>Then el sistema responde con error de conflicto (409) | EP10 |
| TS13 | Implementación de un servicio Payments con REST API | Como desarrollador, quiero implementar un servicio REST API que gestione los pagos de estacionamiento, para permitir transacciones electrónicas de forma segura y eficiente. | Feature: Procesamiento de pagos de estacionamiento<br><br>Scenario: Realizar un pago exitoso<br>Given que un usuario tiene un ticket pendiente de pago<br>When accede al endpoint de pagos con los datos correctos<br>Then el sistema debe procesar el pago<br>And confirmar la transacción como exitosa<br><br>Scenario: Intentar pagar con datos incompletos<br>Given que un usuario intenta realizar un pago<br>When falta información requerida en la solicitud<br>Then el sistema debe rechazar el pago<br>And retornar un mensaje de error indicando qué falta<br><br>Scenario: Intentar pagar pero el banco rechaza la transacción<br>Given que un usuario envía los datos correctos<br>When el sistema contacta al banco y recibe un rechazo<br>Then el sistema debe marcar el pago como fallido<br>And notificar al usuario del rechazo | EP11 |
| TS14 | Implementación de un servicio Parking Circulation con REST API | Como desarrollador, quiero desarrollar un servicio REST API para registrar y monitorear la circulación de vehículos dentro del estacionamiento, para tener trazabilidad y control del flujo vehicular. | Feature: Registro de circulación vehicular<br><br>Scenario: Vehículo entra y se registra en el sistema<br>Given que el sistema está activo<br>When un vehículo entra al parqueadero<br>Then el evento de entrada es registrado vía API<br><br>Scenario: Vehículo no se registra por falla de red<br>Given que hay una interrupción en la conectividad<br>When el vehículo entra<br>Then no se registra el evento<br>And se almacena en buffer para reintento posterior | EP10 |
| TS15 | Implementación de un servicio Monitoring con REST API | Como desarrollador, quiero implementar un servicio REST API que centralice información de estado y métricas del sistema, para facilitar el monitoreo y la detección temprana de incidentes. | Feature: Monitoreo centralizado de estado del sistema<br><br>Scenario: Todos los servicios reportan estado "OK"<br>Given que todos los servicios están funcionando<br>When se consulta el endpoint de monitoreo<br>Then el sistema devuelve un estado 200 con detalles saludables<br><br>Scenario: Uno o más servicios están caídos<br>Given que el servicio de pagos está fuera de línea<br>When se consulta el estado del sistema<br>Then el sistema indica el estado "Degradado"<br>And muestra detalles del servicio caído | EP10 |
| TS16 | Implementación de un servicio Ticket Validation con REST API | Como desarrollador, quiero crear un servicio REST API para validar tickets de estacionamiento, para controlar el acceso y la salida de vehículos de manera automatizada y segura. | Feature: Validación de tickets de estacionamiento<br><br>Scenario: Ticket válido es aceptado<br>Given que el ticket tiene una entrada registrada y está vigente<br>When se valida vía API<br>Then el sistema responde con "válido"<br>And permite la salida del vehículo<br><br>Scenario: Ticket inválido o ya usado<br>Given que el ticket ha sido usado previamente<br>When se intenta validar nuevamente<br>Then el sistema responde con "inválido"<br>And deniega la salida | EP10 |
| TS17 | Implementación de un servicio Notifications con REST API | Como developer, quiero implementar un servicio de notificaciones mediante una REST API, para poder enviar mensajes automáticos a los conductores sobre eventos importantes del sistema, como pagos, entradas o salidas del estacionamiento. | Feature: Implementación de un servicio Notifications con REST API<br><br>Scenario: Envío exitoso de notificación al conductor mediante el servicio REST<br>Given que el sistema necesita enviar una notificación al conductor<br>And el servicio Notifications está disponible<br>When se realiza una solicitud POST válida a la API de notificaciones con el contenido correspondiente<br>Then la API debería responder con un código 200 OK<br>And el conductor debería recibir la notificación en su dispositivo<br><br>Scenario: Fallo al enviar la notificación por error en la solicitud<br>Given que se intenta enviar una notificación mediante el servicio Notifications<br>When la solicitud POST contiene datos incompletos o inválidos<br>Then la API debería responder con un código de error 400 Bad Request<br>And no se debería enviar ninguna notificación | EP10 |

## 3.3. Impact Mapping

El impact mapping es una técnica visual de planificación estratégica que ayuda a alinear los objetivos de un proyecto con los actores clave, sus comportamientos esperados (impactos) y las funcionalidades necesarias (entregables) para lograr dichos objetivos de forma efectiva.

![3.3-Impact-Mapping.jpg](assets/capitulo-3/3.3-Impact-Mapping.jpg)

## 3.4. Product Backlog

Utilizaremos la escala de Fibonacci (1/2/3/5/8/13/21) para realizar este valorización de User Stories por Story Points.

**User Story Base:**

Seleccionamos esta User Story como base de referencia para la valorización de las demás User Stories.

| \# Orden | User Story ID | Título                                       | Descripción                                                                                                                                                  | Story Points (1 / 2 / 3 / 5 / 8 / 13 /…) |
| -------- | ------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------- |
| 16       | US16          | Escaneo QR mediante celular por el conductor | Como conductor, quiero poder escanear un código QR con mi celular al llegar al estacionamiento, para poder acceder al sistema de estacionamientos del lugar. | 2                                        |

**Product Backlog:**

| \# Orden | User Story ID | Título                                                                                                     | Descripción                                                                                                                                                                                                                                                                      | Story Points (1 / 2 / 3 / 5 / 8 / 13 /…) |
| -------- | ------------- | ---------------------------------------------------------------------------------------------------------- |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| ---------------------------------------- |
| 1        | US01          | Barra de navegación de Landing Page                                                                        | Como visitante, quiero una barra de navegación accesible para moverme fácilmente entre las secciones principales de la landing page.                                                                                                                                             | 1                                        |
| 2        | US02          | Encabezado de Bienvenida de Landing Page                                                                   | Como visitante, quiero visualizar de forma inmediata un encabezado con el propósito de la aplicación ParkUp, junto con un llamado a la acción claro que me motive a explorar la plataforma                                                                                       | 1                                        |
| 3        | US03          | Sección Sobre Nosotros de Landing page                                                                     | Como visitante, quiero conocer la misión, visión y el equipo de desarrollo de ParkUp, con el fin de generar confianza en el proyecto y comprender su impacto.                                                                                                                    | 1                                        |
| 4        | US04          | Demostración del funcionamiento de la aplicación en el Landing Page                                        | Como visitante, quiero observar una demostración visual del funcionamiento de la aplicación, para entender de manera práctica su utilidad y facilidad de uso.                                                                                                                    | 1                                        |
| 5        | US05          | Descripción de las funcionalidades de la aplicación en el Landing Page                                     | Como visitante, quiero explorar las funcionalidades principales de ParkUp, a fin de evaluar si satisfacen mis necesidades respecto a la gestión de estacionamientos.                                                                                                             | 1                                        |
| 6        | US06          | Reseñas en el Landing page                                                                                 | Como visitante, quiero leer opiniones de otros usuarios sobre la aplicación, con el objetivo de obtener una referencia confiable sobre la efectividad del producto.                                                                                                              | 1                                        |
| 7        | US07          | Preguntas y Respuestas en Landing Page                                                                     | Como visitante, quiero acceder a una sección de preguntas frecuentes que resuelva dudas comunes de manera rápida y concisa.                                                                                                                                                      | 1                                        |
| 8        | US08          |                                                                                                            |                                                                                                                                                                                                                                                                                  | 1                                        |
| 9        | US09          | Sección de Contáctanos en Landing Page                                                                     | Como visitante, quiero disponer de una sección de contacto para comunicarme con el equipo de ParkUp en caso de requerir más información o asistencia.                                                                                                                            | 1                                        |
| 10       | US10          | Footer en Landing Page                                                                                     | Como visitante, quiero encontrar en el pie de página enlaces útiles y de acceso rápido que complementen mi navegación por el sitio.                                                                                                                                              | 1                                        |
| 11       | TS10          | Implementación de un servicio IAM con REST API                                                             | Como desarrollador, quiero implementar un servicio de gestión de identidades y accesos (IAM) usando una REST API, para controlar la autenticación y autorización de usuarios dentro del sistema.                                                                                 | 3                                        |
| 12       | TS06          | Autenticación basada en token JWT                                                                          | Como desarrollador, quiero implementar un sistema de autenticación basado en tokens JWT, para permitir una autenticación segura y sin estado en todos los servicios del sistema.                                                                                                 | 2                                        |
| 13       | US11          | Registro de conductor como usuario                                                                         | Como developer, quiero que el conductor pueda registrarse como usuario en el sistema, para poder acceder a las funcionalidades del sistema de parqueo conectado por IoT.                                                                                                         | 1                                        |
| 14       | US12          | Inicio de sesión de conductor                                                                              | Como developer, quiero que el conductor pueda iniciar sesión en el sistema utilizando sus credenciales, para que pueda acceder a la plataforma y gestionar su estacionamiento.                                                                                                   | 1                                        |
| 15       | US13          | Edición de perfil de conductor                                                                             | Como developer, quiero que el conductor pueda editar su perfil, para que pueda actualizar sus datos personales y guardar su método de pago de preferencia en el sistema.                                                                                                         | 2                                        |
| 16       | US14          | Recuperación de contraseña                                                                                 | Como developer, quiero permitir que el conductor recupere su contraseña de forma segura, para que pueda recuperar el acceso a su cuenta en caso de olvidar sus credenciales.                                                                                                     | 2                                        |
| 17       | US15          | Eliminación de cuenta de conductor                                                                         | Como developer, quiero que el conductor pueda eliminar su cuenta de usuario, para permitirle desvincularse completamente del sistema cuando así lo desee.                                                                                                                        | 2                                        |
| 18       | US35          | Obtención de cuenta administrativa de un estacionamiento                                                   | Como administrador, quiero obtener una cuenta administrativa para un estacionamiento, para poder gestionar y supervisar sus operaciones.                                                                                                                                         | 2                                        |
| 19       | US36          | Inicio de sesión de administrador                                                                          | Como administrador, quiero iniciar sesión en el sistema, para acceder a las funcionalidades de gestión del estacionamiento.                                                                                                                                                      | 1                                        |
| 20       | US37          | Recuperación de una cuenta administrativa por correo vinculado                                             | Como administrador, quiero recuperar mi cuenta administrativa usando mi correo vinculado, para restablecer el acceso en caso de olvido de credenciales.                                                                                                                          | 2                                        |
| 21       | US38          | Servicio al cliente para edición o recuperación de una cuenta administrativa de un estacionamiento         | Como administrador, quiero contactar al servicio al cliente para editar o recuperar mi cuenta, para resolver problemas de acceso o errores en los datos de la cuenta.<br>                                                                                                        | 2                                        |
| 22       | US39          | Edición del perfil de una cuenta administrativa                                                            | Como administrador, quiero editar el perfil de mi cuenta administrativa, para mantener mi información actualizada y correcta.                                                                                                                                                    | 2                                        |
| 23       | TS14          | Implementación de un servicio Parking Circulation con REST API                                             | Como desarrollador, quiero desarrollar un servicio REST API para registrar y monitorear la circulación de vehículos dentro del estacionamiento, para tener trazabilidad y control del flujo vehicular.                                                                           | 3                                        |
| 24       | TS01          | Puerta de Entrada del Parking IoT con Cámara                                                               | Como desarrollador, quiero integrar una puerta de entrada IoT con cámara al sistema, para capturar imágenes o video de los vehículos al ingresar y permitir su control automatizado.                                                                                             | 3                                        |
| 25       | TS04          | IoT Gateway                                                                                                | Como desarrollador, quiero configurar un IoT Gateway que centralice la comunicación entre los dispositivos IoT y la nube, para asegurar la conectividad y sincronización de datos del sistema.                                                                                   | 3                                        |
| 26       | TS05          | Edge Node IoT en cada Estacionamiento                                                                      | Como desarrollador, quiero desplegar nodos Edge IoT en cada estación de parqueo, para procesar datos localmente y reducir la latencia en la toma de decisiones.                                                                                                                  | 3                                        |
| 27       | US16          | Escaneo QR mediante celular por el conductor                                                               | Como conductor, quiero poder escanear un código QR con mi celular al llegar al estacionamiento, para poder acceder al sistema de estacionamientos del lugar.                                                                                                                     | 2                                        |
| 28       | US17          | Visualización de estacionamientos disponibles, en tiempo real, más cercanos al conductor                   | Como conductor, quiero ver en tiempo real los estacionamientos disponibles más cercanos, para poder tomar decisiones rápidas sobre dónde estacionar.                                                                                                                             | 2                                        |
| 29       | US18          | Confirmación automática o manual de estacionamiento realizado por el conductor                             | Como conductor, quiero que el sistema confirme automáticamente o me permita confirmar manualmente que he estacionado en el lugar exacto, para garantizar que mi acción sea registrada correctamente.                                                                             | 2                                        |
| 30       | US19          | Visualización de menú de estacionamiento para el conductor                                                 | Como conductor, quiero tener acceso a un menú de opciones dentro del sistema de estacionamiento, para gestionar acciones como pago, convalidación y solicitudes adicionales.                                                                                                     | 1                                        |
| 31       | TS07          | Permiso de bancas para utilizar sus datos en la pasarela de pago                                           | Como desarrollador, quiero gestionar los permisos y acuerdos necesarios con las instituciones bancarias o proveedores de pagos, para poder acceder y utilizar sus sistemas en la implementación de una pasarela de pago propia.                                                  | 1                                        |
| 32       | TS13          | Implementación de un servicio Payments con REST API                                                        | Como desarrollador, quiero implementar un servicio REST API que gestione los pagos de estacionamiento, para permitir transacciones electrónicas de forma segura y eficiente.                                                                                                     | 3                                        |
| 33       | US24          | Registro de tarjeta de crédito/débito del conductor                                                        | Como conductor, quiero registrar mi tarjeta de crédito/débito en el sistema, para poder realizar pagos automáticos cuando desee retirar el vehículo del estacionamiento.                                                                                                         | 2                                        |
| 34       | US25          | Eliminación de tarjeta de crédito/débito del conductor                                                     | Como conductor, quiero poder eliminar mi tarjeta de crédito/débito del sistema, para asegurarme de que no se mantengan mis datos de pago almacenados si ya no los necesito.                                                                                                      | 1                                        |
| 35       | US26          | Visualización de listado de tarjetas de crédito/débito del conductor                                       | Como conductor, quiero visualizar un listado de las tarjetas de crédito/débito registradas en mi perfil, para poder elegir cuál utilizar al momento de realizar el pago en línea.                                                                                                | 1                                        |
| 36       | TS02          | Puerta de Salida del Parking IoT con Cámara                                                                | Como desarrollador, quiero implementar una puerta de salida IoT con cámara, para registrar la salida de vehículos y validar su autorización de forma visual o automática.                                                                                                        | 3                                        |
| 37       | TS03          | Sensores Magnéticos IoT en cada Estacionamiento                                                            | Como desarrollador, quiero instalar e integrar sensores magnéticos IoT en cada plaza de estacionamiento, para detectar la ocupación en tiempo real y alimentar el sistema de disponibilidad.                                                                                     | 3                                        |
| 38       | TS08          | Cámaras de Vigilancia IoT                                                                                  | Como desarrollador, quiero integrar cámaras de vigilancia IoT al sistema, para monitorear el entorno del estacionamiento en tiempo real y mejorar la seguridad.                                                                                                                  | 3                                        |
| 39       | US27          | Activación y Desactivación de pago automático del conductor                                                | Como conductor, quiero poder activar o desactivar el pago automático para mis futuras transacciones de estacionamiento, para decidir cómo realizar el pago al momento de retirarme.                                                                                              | 1                                        |
| 40       | US29          | Realización del pago a cancelar del estacionamiento del conductor                                          | Como conductor, quiero realizar el pago correspondiente al estacionamiento mediante una opción manual o automática, para completar mi transacción y poder retirarme sin problemas.                                                                                               | 3                                        |
| 41       | US30          | Retiro ininterrumpido del estacionamiento por pago automático                                              | Como conductor, quiero poder retirar mi vehículo sin interrupciones después de haber realizado el pago automático, para no tener que hacer ninguna acción adicional.                                                                                                             | 2                                        |
| 42       | US31          | Retiro posterior al pago manual del estacionamiento                                                        | Como conductor, quiero poder retirar mi vehículo después de realizar el pago manual, asegurándome de que la transacción esté confirmada antes de salir del estacionamiento.                                                                                                      | 1                                        |
| 43       | US32          | Visualización de tiempo de tolerancia desde cancelación del pago del estacionamiento                       | Como conductor, quiero visualizar el tiempo de tolerancia después de cancelar el pago del estacionamiento, para saber cuánto tiempo tengo antes de que se genere una penalización o multa.                                                                                       | 1                                        |
| 44       | US33          | Visualización de boleta virtual e interactiva del estacionamiento realizado                                | Como conductor, quiero ver una boleta virtual e interactiva del estacionamiento realizado, para consultar los detalles de mi uso del estacionamiento de forma clara y digital.                                                                                                   | 1                                        |
| 45       | US34          | Visualización de listado de boletas virtuales e interactivas de estacionamientos realizados                | Como conductor, quiero visualizar un listado de todas mis boletas virtuales e interactivas de estacionamientos realizados, para tener un historial de mis pagos y usos anteriores.                                                                                               | 1                                        |
| 46       | TS11          | Implementación de un servicio Camera Feed con WebRTC                                                       | Como desarrollador, quiero implementar un servicio de transmisión de video en tiempo real desde cámaras usando WebRTC, para permitir la visualización en vivo del entorno del estacionamiento.                                                                                   | 3                                        |
| 47       | TS15          | Implementación de un servicio Monitoring con REST API                                                      | Como desarrollador, quiero implementar un servicio REST API que centralice información de estado y métricas del sistema, para facilitar el monitoreo y la detección temprana de incidentes.                                                                                      | 3                                        |
| 48       | TS09          | Dispositivos de Monitoreo de Funcionalidad de otros Dispositivos IoT                                       | Como desarrollador, quiero implementar dispositivos que supervisen el estado de funcionamiento de otros dispositivos IoT, para detectar fallos y garantizar la operatividad del sistema.                                                                                         | 3                                        |
| 49       | US40          | Visualización de Resumen Estadístico del uso del Estacionamiento como menú principal                       | Como administrador, quiero visualizar un resumen estadístico del uso del estacionamiento como menú principal, para obtener una visión general rápida del desempeño y uso del espacio.                                                                                            | 2                                        |
| 50       | US41          | Visualización de las cámaras de seguridad del estacionamiento                                              | Como administrador, quiero ver las cámaras de seguridad del estacionamiento, para monitorear en tiempo real lo que sucede en las instalaciones.                                                                                                                                  | 1                                        |
| 51       | US42          | Visualización detallada de una cámara de seguridad del estacionamiento                                     | Como administrador, quiero visualizar de forma detallada una cámara de seguridad específica, para enfocar mi atención en un área particular del estacionamiento.                                                                                                                 | 1                                        |
| 52       | US43          | Visualización del listado de conductores estacionados actualmente y anteriormente                          | Como administrador, quiero ver el listado de conductores actualmente estacionados y de los que han estado anteriormente, para tener control y trazabilidad del uso del estacionamiento.                                                                                          | 1                                        |
| 53       | US44          | Visualización del listado de conductores estacionados durante un día en específico.                        | Como administrador, quiero ver el listado de conductores que estuvieron estacionados durante un día específico, para realizar análisis o auditorías por fecha.                                                                                                                   | 1                                        |
| 54       | US45          | Visualización detallada de un conductor en específico.                                                     | Como administrador, quiero visualizar el detalle de un conductor en específico, para revisar su historial, pagos o incidentes relacionados.                                                                                                                                      | 1                                        |
| 55       | US46          | Visualización de sistema de resolución de casos extremos en el estacionamiento                             | Como administrador, quiero acceder al sistema de resolución de casos extremos en el estacionamiento, para poder actuar rápidamente ante situaciones fuera de lo común.                                                                                                           | 1                                        |
| 56       | US47          | Cancelación manual del pago de algún conductor por caso extremo                                            | Como administrador, quiero cancelar manualmente el pago de un conductor en un caso extremo, para ofrecer una solución rápida y excepcional ante imprevistos.                                                                                                                     | 2                                        |
| 57       | US48          | Visualización de monitoreo de la funcionalidad de los dispositivos IoT del estacionamiento                 | Como administrador, quiero visualizar el monitoreo de la funcionalidad de los dispositivos IoT del estacionamiento, para asegurarme de que todos los componentes estén operativos y detectar fallos a tiempo.                                                                    | 1                                        |
| 58       | TS12          | Implementación de un servicio Parking Spots con REST API                                                   | Como desarrollador, quiero crear un servicio REST API para gestionar la disponibilidad y estado de los espacios de estacionamiento, para facilitar la consulta y reserva en tiempo real.                                                                                         | 3                                        |
| 59       | US49          | Cambio de luz LED cuando un carro se estaciona                                                             | Como conductor, quiero que la luz LED del espacio de estacionamiento cambie de color automáticamente cuando un vehículo se estacione, para saber visualmente si un espacio está ocupado o disponible.                                                                            | 2                                        |
| 60       | TS16          | Implementación de un servicio Ticket Validation con REST API                                               | Como desarrollador, quiero crear un servicio REST API para validar tickets de estacionamiento, para controlar el acceso y la salida de vehículos de manera automatizada y segura.                                                                                                | 3                                        |
| 61       | US28          | Realización de convalidación de pago del estacionamiento del conductor                                     | Como conductor, quiero realizar la convalidación de mi pago de estacionamiento, para confirmar que mi transacción ha sido procesada correctamente antes de salir.                                                                                                                | 2                                        |
| 62       | TS17          | Implementación de un servicio Notifications con REST API                                                   | Como developer, quiero implementar un servicio de notificaciones mediante una REST API, para poder enviar mensajes automáticos a los conductores sobre eventos importantes del sistema, como pagos, entradas o salidas del estacionamiento.                                      | 3                                        |
| 63       | US20          | Notificación de entrada a estacionamiento para el conductor                                                | Como conductor, quiero recibir una notificación confirmando mi entrada al estacionamiento, para estar seguro de que mi registro ha sido exitoso y la placa de mi vehículo se haya obtenido correctamente.                                                                        | 1                                        |
| 64       | US21          | Notificación de pago de estacionamiento para el conductor                                                  | Como conductor, quiero recibir una notificación que confirme el pago de mi estacionamiento, para saber que mi transacción ha sido procesada correctamente.                                                                                                                       | 1                                        |
| 65       | US22          | Notificación de poco tiempo antes del fin de la tolerancia de pago de un estacionamiento para el conductor | Como conductor, quiero recibir una notificación cuando el tiempo de tolerancia esté por terminar, y si supero ese tiempo, el sistema automáticamente me solicitará realizar un nuevo pago, para asegurar que el estacionamiento continúe registrado y evitar problemas al salir. | 1                                        |
| 66       | US23          | Notificación de fin de tolerancia de pago de un estacionamiento para el conductor                          | Como conductor, quiero recibir una notificación cuando el tiempo de tolerancia de pago haya terminado, para saber qué debo pagar de nuevo.                                                                                                                                       | 1                                        |

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

**Step 1: Unstructured Exploration**

En esta etapa, se identificaron los eventos clave que representan las acciones significativas dentro del sistema. 

![4.1.1-EventStorming-Step-1.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-1.jpg)

**Step 2: Timelines**

Durante esta fase, los eventos identificados fueron agrupados en subgrupos liderados por un evento general que encapsula la función principal del grupo. Cada subgrupo incluyó tanto los happy paths, que representan los caminos ideales o exitosos de ejecución de los eventos, como los unhappy paths, que muestran los posibles problemas o situaciones no deseadas que pudieran surgir. Esto ayudó a estructurar los eventos de manera coherente y a comprender mejor las diferentes secuencias de acciones dentro del sistema. 

![4.1.1-EventStorming-Step-2.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-2.jpg)

**Step 3: Paint Points**

Durante el proceso, se identificaron los pain points o puntos problemáticos. Estos puntos son cruciales para mejorar la experiencia del usuario y optimizar el diseño del sistema. 

![4.1.1-EventStorming-Step-3.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-3.jpg)


**Step 4: Pivotal Points**

Se señalaron los pivotal points o puntos clave, que son eventos críticos que marcan hitos importantes en el flujo de trabajo del sistema. Estos eventos suelen tener un impacto significativo en el comportamiento del sistema o en la experiencia del usuario.

![4.1.1-EventStorming-Step-4.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-4.jpg)

**Step 5: Commands**

Cada evento se asoció con un comando específico que lo desencadena y un actor que lo realiza. Esto ayudó a clarificar quién es responsable de iniciar cada acción y cómo interactúan los diferentes usuarios con el sistema.

![4.1.1-EventStorming-Step-5.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-5.jpg)

**Step 6: Policies**

Durante esta etapa, se identifican los escenarios en el que un evento desencadena la ejecución de un comando 

![4.1.1-EventStorming-Step-6.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-6.jpg)

**Step 7: Read Models**

Durante esta fase, se diseñan y desarrollan los modelos de lectura para cada contexto del sistema, asegurando que proporcionen la información necesaria de manera eficiente y coherente 

![4.1.1-EventStorming-Step-7.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-7.jpg)

**Step 8: External Systems**

Durante esta etapa, se identifican los sistemas externos relevantes  

![4.1.1-EventStorming-Step-8.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-8.jpg)

**Step 9: Aggregates**

Durante esta etapa, se definen y diseñan los agregados para cada contexto del sistema, asegurando que representen correctamente las transacciones y operaciones coherentes dentro del sistema. 

![4.1.1-EventStorming-Step-9.jpg](assets/capitulo-4/4.1.1-EventStorming-Step-9.jpg)

#### 4.1.1.1. Candidate Context Discovery

En esta sección, a partir del dominio modelado como EventStorming, se explica y evidencia el proceso realizado para la sesión de Candidate Context Discovery, en la que se busca identificar los bounded contexts. En este proyecto se aplicó la técnica Start-with-Simple. Se descompuso el modelo en procesos secuenciales y se enfoca en la simplicidad a medida que se identifiquen más necesidades. 

Al final, obtuvimos ocho bounded context, que son: 

![4.1.1.1-IAM.jpg](assets/capitulo-4/4.1.1.1-IAM.jpg)

![4.1.1.1-Camera-Feed-On-WebRTC.jpg](assets/capitulo-4/4.1.1.1-Camera-Feed-On-WebRTC.jpg)

![4.1.1.1-Parking-Spots.jpg](assets/capitulo-4/4.1.1.1-Parking-Spots.jpg)

![4.1.1.1-Payments.jpg](assets/capitulo-4/4.1.1.1-Payments.jpg)

![4.1.1.1-Parking-Circulation.jpg](assets/capitulo-4/4.1.1.1-Parking-Circulation.jpg)

![4.1.1.1-Monitoring.jpg](assets/capitulo-4/4.1.1.1-Monitoring.jpg)

![4.1.1.1-Ticket-Validation.jpg](assets/capitulo-4/4.1.1.1-Ticket-Validation.jpg)

![4.1.1.1-Notifications.jpg](assets/capitulo-4/4.1.1.1-Notifications.jpg)

Lo que queda de la siguiente manera: 

![4.1.1.1-Candidate-Context-Discovery.jpg](assets/capitulo-4/4.1.1.1-Candidate-Context-Discovery.jpg)

#### 4.1.1.2. Domain Message Flows Modeling

El Domain Message Flow Modeling es una técnica utilizada en Domain-Driven Design (DDD) para visualizar y documentar cómo los mensajes, eventos y comandos fluyen entre los bounded contexts y los actores dentro de un sistema. Ayuda a identificar las interacciones clave entre los componentes del sistema y cómo los eventos desencadenan acciones en diferentes partes del dominio.

![4.1.1.2-Domain-Message-Floww.Modeling-Register.jpg](assets/capitulo-4/4.1.1.2-Domain-Message-Floww.Modeling-Register.jpg)

![4.1.1.2-Domain-Message-Floww.Modeling-Entry.jpg](assets/capitulo-4/4.1.1.2-Domain-Message-Floww.Modeling-Entry.jpg)

![4.1.1.2-Domain-Message-Floww.Modeling-Exit.jpg](assets/capitulo-4/4.1.1.2-Domain-Message-Floww.Modeling-Exit.jpg)

#### 4.1.1.3. Bounded Context Canvases


<p align="center">
  <img src="assets/capitulo-4/UserManagement.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/CamerFeed.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/Monitorin.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/ParkingSite.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/Notifications.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/TicketValidation.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/ParkingCirculation.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

<p align="center">
  <img src="assets/capitulo-4/Payments.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>


### 4.1.2. Context Mapping

Context Mapping es una técnica de Domain-Driven Design (DDD) que define las relaciones entre los bounded contexts en un sistema, estableciendo cómo interactúan e intercambian información. Permite gestionar dependencias y asegura que los modelos de dominio se mantengan consistentes y aislados.

![4.1.2-Context-Mapping.jpg](assets/capitulo-4/4.1.2-Context-Mapping.jpg)

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2.X. Bounded Context: <Payments & Notifications>

El dominio de Parking Management describe las funciones y procesos involucrados en la gestión del parqueo dentro de un centro comercial. Este sistema se encarga de administrar el ingreso y salida de vehículos, asignar espacios disponibles en las distintas zonas de parqueo, generar y validar tickets, y controlar la duración del uso de los espacios. Además, permite gestionar usuarios recurrentes y visitantes, facilitando una experiencia eficiente y organizada para todos los conductores. El sistema también contempla la tarificación automática según el tiempo de uso y el procesamiento de pagos correspondientes.

Este dominio opera dentro del bounded context de Notification & Payments, integrando funcionalidades clave como el envío de notificaciones al usuario (por ejemplo, alertas de vencimiento de ticket o confirmaciones de pago), así como la gestión completa del ciclo de pagos. Esto asegura que las transacciones se realicen de forma segura y que los usuarios estén informados en tiempo real, mejorando significativamente la eficiencia del sistema y la satisfacción del usuario.

### Payment

<p align="center">
  <img src="assets/capitulo-4/PaymentsBC.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

### Notification

<p align="center">
  <img src="assets/capitulo-4/NotificationsBC.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>

### 4.2.X.1. Domain Layer

### 4.2.X.2. Interface Layer

### 4.2.X.3. Application Layer

### 4.2.X.4. Infrastructure Layer

### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.X.6.2. Bounded Context Database Design Diagram

## 4.2.1. Bounded Context: IAM

En esta sección se documentan las principales clases que conforman el núcleo del contexto IAM, detallando sus atributos, métodos y relaciones.
El agregado raíz User representa a cada usuario registrado en la plataforma, con credenciales de acceso (username, password) y la asignación de un único Role, lo cual refleja las reglas de negocio que restringen a un solo rol por usuario.

La entidad Role modela los diferentes tipos de rol que puede asumir un usuario dentro del sistema, tales como administrador, usuario regular o instructor. Esta entidad incluye utilidades para la validación y conversión de roles a partir de representaciones textuales.
Por su parte, el objeto de valor Roles encapsula los valores constantes de los posibles roles, implementado como un enumerado (enum), asegurando la integridad de los roles permitidos y evitando inconsistencias.

Cada clase y objeto de valor está diseñado con principios de encapsulamiento, visibilidad controlada y responsabilidad única, en conformidad con los estándares de modelado de software orientado a objetos y Domain-Driven Design.


**Clase User**

| **Nombre**      | User                                                           |
|-----------------|----------------------------------------------------------------|
| **Relaciones**  | Muchos a uno con Role                                          |
| **Descripción** | Representa un usuario del sistema con credenciales y un rol.  |

Atributos

| Nombre   | Tipo de Dato | Visibilidad |
|----------|--------------|-------------|
| id       | Long         | private     |
| username | String       | private     |
| password | String       | private     |
| role     | Role         | private     |

Métodos

| Método                       |
|------------------------------|
| setRole(role: Role)          |
| getRole(): Role              |

**Clase Role**
| **Nombre**      | Role                                                              |
|-----------------|-------------------------------------------------------------------|
| **Relaciones**  | Uno a muchos con User                                             |
| **Descripción** | Representa un rol del sistema, como ADMIN o DRIVER.               |

Atributos

| Nombre | Tipo de Dato | Visibilidad |
|--------|--------------|-------------|
| id     | Long         | private     |
| name   | Roles (enum) | private     |

 Métodos

| Método                             |
|------------------------------------|
| getStringName(): String            |
| getDefaultRole(): Role             |
| toRoleFromName(name: String): Role |

### 4.2.1.1. Domain Layer

En la capa de dominio se modelan los conceptos centrales del contexto IAM siguiendo los principios de Domain-Driven Design.
 El agregado raíz User representa a un usuario dentro del sistema, asociado a un único Role. Esta relación permite garantizar que cada usuario tenga exactamente un rol, como ROLE_ADMIN, ROLE_USER o ROLE_INSTRUCTOR.
El objeto de valor Roles, modelado como un enum, establece un conjunto cerrado de posibles valores para la asignación de roles, garantizando la integridad del dominio.
Adicionalmente, los servicios de dominio UserCommandService y RoleCommandService encapsulan operaciones de negocio que no pertenecen naturalmente a ninguna entidad, cumpliendo con el principio de separación de responsabilidades.
Esta estructura permite mantener un dominio rico, expresivo y alineado con las reglas de negocio fundamentales del sistema.

**Agregates**
| Aggregate <<User>>                       |
|-------------------------------------------|
| - Long id (heredado de AuditableAbstractAggregateRoot) |
| - String username                         |
| - String password                         |
| - Role role                         |
|-------------------------------------------|
| + getUsername(): String                   |
| + getPassword(): String                   |
| + getRole(): Role                         |
| + setRole(role: Role): User               |

**Entities**
| Entity <<Role>>                         |
|------------------------------------------|
| - Long id                                |
| - Roles name                             |
|------------------------------------------|
| + getId(): Long                          |
| + getName(): Roles                       |
| + getStringName(): String                |
| + getDefaultRole(): Role                 |
| + toRoleFromName(name: String): Role     |
| + validateRoleSet(roles: List<Role>): List<Role> |

**Value Objects**
| Value Object <<Roles>>                 |
|-----------------------------------------|
| + ROLE_ADMIN                            |
| + ROLE_USER                             |
| + ROLE_INSTRUCTOR                      |
|-----------------------------------------|
| (Métodos estándar de enum Java)         |
| + name(): String                        |
| + values(): Roles[]                     |
| + valueOf(String): Roles                |

**Domain Services**
| RoleCommandService       |
|-----------------------------------------------|
| + handle(command: SeedRolesCommand): void     |

| UserCommandService                          |
|-----------------------------------------------------------------|
| + handle(command: SignUpCommand): Optional<User>                |
| + handle(command: SignInCommand): Optional<ImmutablePair<User, String>> |


### 4.2.1.2. Interface Layer

La capa de interfaz expone la funcionalidad del contexto IAM a través de controladores RESTful basados en el framework Spring Boot.
AuthenticationController gestiona los procesos de autenticación de usuarios, permitiendo tanto el inicio de sesión como el registro de nuevos usuarios.
RolesController proporciona endpoints para consultar los diferentes roles disponibles en el sistema, mientras que UsersController facilita la recuperación de información sobre los usuarios registrados.
Cada controlador delega la lógica de negocio en los servicios de dominio apropiados, actuando únicamente como capa de orquestación, en conformidad con el principio de Controller Thin.


| Controller <<AuthenticationController>>                         |
|-------------------------------------------------------------------|
| - UserCommandService userCommandService                          |
|-------------------------------------------------------------------|
| + signIn(signInResource: SignInResource): ResponseEntity<AuthenticatedUserResource> |
| + signUp(signUpResource: SignUpResource): ResponseEntity<UserResource>               |

| Controller <<RolesController>>                    |
|----------------------------------------------------|
| - RoleQueryService roleQueryService                |
|----------------------------------------------------|
| + getAllRoles(): ResponseEntity<List<RoleResource>> |

| Controller <<UsersController>>                                 |
|----------------------------------------------------------------|
| - UserQueryService userQueryService                            |
|----------------------------------------------------------------|
| + getAllUsers(): ResponseEntity<List<UserResource>>            |
| + getUserById(userId: Long): ResponseEntity<UserResource>      |


### 4.2.1.3. Application Layer

La capa de aplicación coordina la ejecución de las operaciones de negocio a través de componentes como event handlers y servicios de aplicación.
El ApplicationReadyEventHandler es responsable de inicializar los roles del sistema cuando la aplicación arranca. Este componente escucha el evento ApplicationReadyEvent de Spring y dispara la ejecución del comando SeedRolesCommand, garantizando que los roles fundamentales estén disponibles sin intervención manual.
Esta organización contribuye a desacoplar las operaciones de infraestructura del dominio y favorece la automatización de procesos iniciales del sistema.


| Event Handler <<ApplicationReadyEventHandler>>          |
|----------------------------------------------------------|
| - Logger LOGGER                                          |
| - RoleCommandService roleCommandService                  |
|----------------------------------------------------------|
| + on(event: ApplicationReadyEvent): void                 |
| - getCurrentTimestamp(): Timestamp                      |


### 4.2.1.4. Infrastructure Layer

La capa de infraestructura implementa los mecanismos de persistencia requeridos para soportar el dominio.
UserRepository y RoleRepository son interfaces que extienden JpaRepository, permitiendo operaciones de acceso a datos sobre las entidades User y Role, respectivamente.
Estos repositorios proporcionan métodos específicos como findByUsername, findByName y validaciones de existencia (existsByUsername, existsByName), que son esenciales para preservar la unicidad de los registros.
Al delegar la persistencia en esta capa, se preserva la pureza del modelo de dominio, favoreciendo una arquitectura limpia y sostenible.


| Infrastructure Repository <<RoleRepository>>              |
|-------------------------------------------------------------|
| Extiende: JpaRepository<Role, Long>                         |
|-------------------------------------------------------------|
| + findByName(name: Roles): Optional<Role>                   |
| + existsByName(name: Roles): boolean                        |

| Infrastructure Repository <<UserRepository>>               |
|-------------------------------------------------------------|
| Extiende: JpaRepository<User, Long>                         |
|-------------------------------------------------------------|
| + findByUsername(username: String): Optional<User>          |
| + existsByUsername(username: String): boolean               |


### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se presentan los diagramas de arquitectura a nivel de componentes para el contexto IAM.
Estos diagramas ilustran la interacción entre los principales artefactos del sistema, como controladores, servicios de dominio, agregados y repositorios.
La representación gráfica facilita la comprensión del flujo de información y responsabilidades entre capas, promoviendo la trazabilidad y la consistencia arquitectónica del contexto.

![](https://i.postimg.cc/DZ37w4bq/container-diagram.png)


### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

Los diagramas a nivel de código detallan los flujos de ejecución de los principales casos de uso del contexto IAM, incluyendo el proceso de registro (sign-up) y autenticación (sign-in).
Asimismo, se incluyen diagramas de clases que representan la estructura interna de las entidades y servicios, así como diagramas de base de datos que modelan la persistencia de los objetos del dominio.
Esta representación contribuye a visualizar la implementación técnica del contexto y a validar su alineación con el diseño conceptual.

![](https://i.postimg.cc/zXzXhh27/iam-sign-up-code-diagram.png)

![](https://i.postimg.cc/C5NhtM5b/iam-sign-in-code-diagram.png)


#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![](https://i.postimg.cc/9FLXYfvh/iam-class-diagram.png)

#### 4.2.1.6.2. Bounded Context Database Design Diagram

![](https://i.postimg.cc/jqQSCccC/iam-db-diagram.png)

## 4.2.6. Bounded Context: Monitoring

### 4.2.6.1. Domain Layer

### Entidad: CriticalEventLog

| **Nombre**           | **Categoría** | **Propósito**                                               |
|----------------------|---------------|-------------------------------------------------------------|
| CriticalEventLog     | Entity        | Registro de un caso que lleve a la cancelación del pago     |

#### Atributos

| **Nombre**        | **Tipo de dato** | **Visibilidad** | **Descripción**                                             |
|-------------------|------------------|-----------------|-------------------------------------------------------------|
| id                | Long             | Private         | Identificador único para el caso                            |
| typeOfViolation   | string           | Private         | Tipo de caso crítico registrado                             |
| vehiclePlate      | string           | Private         | Placa del vehículo involucrado en el caso                   |
| timestamp         | Time             | Private         | Hora de la ocurrencia                                       |
| handledBy         | Long             | Private         | ID del administrador que trató el caso                      |
| status            | string           | Private         | Estado actual del caso                                      |
| totalDuration     | string           | Private         | Duración total del caso                                     |
  
### 4.2.6.2. Interface Layer

### CriticalEventLogController  
| **Nombre**                 | **Categoría** | **Propósito**                                               |
|----------------------------|---------------|-------------------------------------------------------------|
| CriticalEventLogController | Controller    | Endpoints para la gestión de casos críticos                 |

| **Nombre**              | **Tipo de retorno**                                      | **Visibilidad** | **Descripción**                                             |
|-------------------------|----------------------------------------------------------|-----------------|-------------------------------------------------------------|
| Constructor             | void                                                     | Public          | Constructor del controlador                                  |
| createCriticalEventLog  | ResponseEntity&lt;CriticalEventLogResponseDto&gt;        | Public          | Crear un nuevo caso crítico                                  |
| getCriticalEventLog     | ResponseEntity&lt;CriticalEventLogResponseDto&gt;        | Public          | Obtener un caso crítico por su ID                            |
| getAllCriticalEventLogs | ResponseEntity&lt;List&lt;CriticalEventLogResponseDto&gt;&gt; | Public      | Obtener todos los casos críticos                             |


#### CriticalEventLogRequestDto  
| **Nombre**                   | **Categoría** | **Propósito**                                               |
|------------------------------|---------------|-------------------------------------------------------------|
| CriticalEventLogRequestDto   | DTO           | Datos necesarios para crear un nuevo caso crítico           |

| **Nombre**       | **Tipo de dato** | **Visibilidad** | **Descripción**                                             |
|------------------|------------------|-----------------|-------------------------------------------------------------|
| typeOfViolation  | string           | Private         | Tipo de violación que originó el caso crítico               |
| vehiclePlate     | string           | Private         | Placa del vehículo involucrado en el caso                   |
| timestamp        | Time             | Private         | Fecha y hora de la ocurrencia del caso                      |
| handledBy        | Long             | Private         | ID del administrador que atendió el caso                    |
  
#### CriticalEventLogResponseDto   
| **Nombre**                   | **Categoría** | **Propósito**                                               |
|------------------------------|---------------|-------------------------------------------------------------|
| CriticalEventLogResponseDto  | DTO           | Representación de un caso crítico con detalles completos    |

| **Nombre**       | **Tipo de dato** | **Visibilidad** | **Descripción**                                             |
|------------------|------------------|-----------------|-------------------------------------------------------------|
| id               | Long             | Private         | Identificador único del caso crítico                        |
| typeOfViolation  | string           | Private         | Tipo de violación que originó el caso crítico               |
| vehiclePlate     | string           | Private         | Placa del vehículo involucrado en el caso                   |
| timestamp        | Time             | Private         | Fecha y hora de la ocurrencia del caso                      |
| handledBy        | Long             | Private         | ID del administrador que atendió el caso                    |
| status           | string           | Private         | Estado actual del caso (ej. "En proceso", "Resuelto")       |
| totalDuration    | string           | Private         | Duración total del caso en formato HH:mm:ss                 |

### VehicleMonitoringController
| **Nombre**                  | **Categoría** | **Propósito**                                               |
|-----------------------------|---------------|-------------------------------------------------------------|
| VehicleMonitoringController | Controller    | Gestiona las operaciones relacionadas con los vehículos en el estacionamiento |

#### Atributos

| **Nombre**     | **Tipo de dato** | **Visibilidad** | **Descripción**                                 |
|----------------|------------------|-----------------|-------------------------------------------------|
| vehicleService | IVehicleService  | Private         | Servicio para operaciones con vehículos         |

#### Métodos

| **Nombre**           | **Tipo de retorno**                  | **Visibilidad** | **Descripción**                                      |
|----------------------|--------------------------------------|-----------------|------------------------------------------------------|
| getVehicleStatus     | ResponseEntity<VehicleDto>           | Public          | Obtiene el estado actual de un vehículo por su placa |
| getAllVehiclesStatus | ResponseEntity<List<VehicleDto>>     | Public          | Obtiene el estado de todos los vehículos             |

### DeviceMonitoringController  
| **Nombre**                  | **Categoría** | **Propósito**                                               |
|-----------------------------|---------------|-------------------------------------------------------------|
| DeviceMonitoringController  | Controller    | Gestiona las operaciones relacionadas con los dispositivos de monitoreo en el estacionamiento |

#### Atributos

| **Nombre**     | **Tipo de dato** | **Visibilidad** | **Descripción**                                 |
|----------------|------------------|-----------------|-------------------------------------------------|
| deviceService  | IDeviceService   | Private         | Servicio para operaciones con dispositivos de monitoreo |

#### Métodos

| **Nombre**           | **Tipo de retorno**                  | **Visibilidad** | **Descripción**                                      |
|----------------------|--------------------------------------|-----------------|------------------------------------------------------|
| getDeviceStatus      | ResponseEntity<DeviceDto>            | Public          | Obtiene el estado actual de un dispositivo por su ID |
| getAllDevicesStatus  | ResponseEntity<List<DeviceDto>>      | Public          | Obtiene el estado de todos los dispositivos          |


### 4.2.6.3. Application Layer
  
### ICriticalEventLogService  
| **Nombre**                 | **Categoría** | **Propósito**                                               |
|----------------------------|---------------|-------------------------------------------------------------|
| ICriticalEventLogService   | Service       | Define las operaciones para gestionar casos críticos        |

#### Métodos

| **Nombre**              | **Tipo de retorno**                               | **Descripción**                                             |
|-------------------------|---------------------------------------------------|-------------------------------------------------------------|
| createCriticalEventLog  | CriticalEventLogResponseDto                       | Crea un nuevo caso crítico                                  |
| getCriticalEventLog     | CriticalEventLogResponseDto                       | Obtiene un caso crítico por su ID                           |
| getAllCriticalEventLogs | List&lt;CriticalEventLogResponseDto&gt;           | Obtiene todos los casos críticos                            |

### CriticalEventLogServiceImpl  
| **Nombre**                    | **Categoría** | **Propósito**                                                         |
|-------------------------------|---------------|------------------------------------------------------------------------|
| CriticalEventLogServiceImpl   | Service       | Implementa las operaciones definidas en ICriticalEventLogService      |

#### Atributos

| **Nombre**                  | **Tipo de dato**              | **Visibilidad** | **Descripción**                                       |
|-----------------------------|-------------------------------|-----------------|-------------------------------------------------------|
| criticalEventLogRepository  | ICriticalEventLogRepository   | Private         | Repositorio para acceder a los datos de casos críticos |

#### Métodos

| **Nombre**              | **Tipo de retorno**                               | **Visibilidad** | **Descripción**                                             |
|-------------------------|---------------------------------------------------|-----------------|-------------------------------------------------------------|
| createCriticalEventLog  | CriticalEventLogResponseDto                       | Public          | Crea un nuevo caso crítico                                  |
| getCriticalEventLog     | CriticalEventLogResponseDto                       | Public          | Obtiene un caso crítico por su ID                           |
| getAllCriticalEventLogs | List&lt;CriticalEventLogResponseDto&gt;           | Public          | Obtiene todos los casos críticos                            |
  
### IVehicleService
| **Nombre**     | **Categoría** | **Propósito**                                               |
|----------------|---------------|-------------------------------------------------------------|
| IVehicleService | Service       | Define las operaciones para gestionar los vehículos en el estacionamiento |

#### Métodos

| **Nombre**           | **Tipo de retorno**        | **Descripción**                                      |
|----------------------|----------------------------|------------------------------------------------------|
| getVehicleStatus     | VehicleDto                 | Obtiene el estado actual de un vehículo por su placa |
| getAllVehiclesStatus | List<VehicleDto>           | Obtiene el estado de todos los vehículos             |

### VehicleServiceImpl 
| **Nombre**             | **Categoría** | **Propósito**                                               |
|------------------------|---------------|-------------------------------------------------------------|
| VehicleServiceImpl     | Service       | Implementa las operaciones definidas en IVehicleService     |

#### Atributos

| **Nombre**         | **Tipo de dato** | **Visibilidad** | **Descripción**                                 |
|--------------------|------------------|-----------------|-------------------------------------------------|
| vehicleRepository  | IVehicleRepository | Private         | Repositorio para acceder a los datos de los vehículos |

#### Métodos

| **Nombre**           | **Tipo de retorno**        | **Visibilidad** | **Descripción**                                      |
|----------------------|----------------------------|-----------------|------------------------------------------------------|
| getVehicleStatus     | VehicleDto                 | Public          | Obtiene el estado actual de un vehículo por su placa |
| getAllVehiclesStatus | List<VehicleDto>           | Public          | Obtiene el estado de todos los vehículos             |


### IDeviceService
| **Nombre**     | **Categoría** | **Propósito**                                               |
|----------------|---------------|-------------------------------------------------------------|
| IDeviceService | Service       | Define las operaciones para gestionar los dispositivos de monitoreo en el estacionamiento |

#### Métodos

| **Nombre**           | **Tipo de retorno**        | **Descripción**                                      |
|----------------------|----------------------------|------------------------------------------------------|
| getDeviceStatus      | DeviceDto                  | Obtiene el estado actual de un dispositivo por su ID |
| getAllDevicesStatus  | List<DeviceDto>            | Obtiene el estado de todos los dispositivos          |

### DeviceServiceImpl    
| **Nombre**             | **Categoría** | **Propósito**                                               |
|------------------------|---------------|-------------------------------------------------------------|
| DeviceServiceImpl      | Service       | Implementa las operaciones definidas en IDeviceService      |

#### Atributos

| **Nombre**         | **Tipo de dato** | **Visibilidad** | **Descripción**                                 |
|--------------------|------------------|-----------------|-------------------------------------------------|
| deviceRepository   | IDeviceRepository | Private         | Repositorio para acceder a los datos de los dispositivos |

#### Métodos

| **Nombre**           | **Tipo de retorno**        | **Visibilidad** | **Descripción**                                      |
|----------------------|----------------------------|-----------------|------------------------------------------------------|
| getDeviceStatus      | DeviceDto                  | Public          | Obtiene el estado actual de un dispositivo por su ID |
| getAllDevicesStatus  | List<DeviceDto>            | Public          | Obtiene el estado de todos los dispositivos          |


### 4.2.6.4. Infrastructure Layer

### ICriticalEventLogRepository  
| **Nombre**                  | **Categoría** | **Propósito**                                               |
|-----------------------------|---------------|-------------------------------------------------------------|
| ICriticalEventLogRepository | Repository    | Define las operaciones de acceso a datos para casos críticos |

#### Métodos

| **Nombre**   | **Tipo de retorno**                         | **Descripción**                                  |
|--------------|---------------------------------------------|--------------------------------------------------|
| findById     | Optional&lt;CriticalEventLog&gt;            | Encuentra un caso crítico por su ID              |
| findAll      | List&lt;CriticalEventLog&gt;                | Encuentra todos los casos críticos               |
| save         | CriticalEventLog                            | Guarda un nuevo caso crítico                     |
| deleteById   | void                                        | Elimina un caso crítico por su ID                |

### IVehicleRepository  
| **Nombre**           | **Categoría** | **Propósito**                                               |
|----------------------|---------------|-------------------------------------------------------------|
| IVehicleRepository   | Repository    | Define las operaciones de acceso a datos para los vehículos |

#### Métodos

| **Nombre**           | **Tipo de retorno**        | **Descripción**                                      |
|----------------------|----------------------------|------------------------------------------------------|
| findByLicensePlate   | VehicleDto                 | Encuentra un vehículo por su placa                   |
| findAll              | List<VehicleDto>           | Encuentra todos los vehículos                        |

### IDeviceRepository  
| **Nombre**             | **Categoría** | **Propósito**                                               |
|------------------------|---------------|-------------------------------------------------------------|
| IDeviceRepository      | Repository    | Define las operaciones de acceso a datos para los dispositivos de monitoreo |

### Métodos

| **Nombre**           | **Tipo de retorno**        | **Descripción**                                      |
|----------------------|----------------------------|------------------------------------------------------|
| findByDeviceId       | DeviceDto                  | Encuentra un dispositivo por su ID                   |
| findAll              | List<DeviceDto>            | Encuentra todos los dispositivos                     |

### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.6.5-Monitoring-ComponentDiagram.png" alt="Component Diagram Monitoring"/></p>

### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.6.6.1-Monitoring-ClassDiagram.jpg" alt="Monitoring Class Diagram"/></p>

#### 4.2.6.6.2. Bounded Context Database Design Diagram

<p align="center"><img src="assets/capitulo-4/4.2.6.6.2-MonitoringDatabase.jpg" alt="Monitoring DB Diagram"/></p>

## 4.2.7. Bounded Context: Ticket validation

### 4.2.7.1. Domain Layer

#### Entidad: Ticket

| **Nombre**     | **Categoría** | **Propósito**                                               |
|----------------|---------------|--------------------------------------------------------------|
| Ticket   | Entity        | Registro de un ticket que indica la entrada y salida de un vehiculo del estacionamiento, asi como el pago.  |

#### Atributos

| **Nombre**        | **Tipo de dato** | **Visibilidad** | **Descripción**                          |
|-------------------|------------------|------------------|-------------------------------------------|
| id                | Long             | Private          | Identificador único para el ticket                       |
| userId   | string           | Private          | Id de usuario que utilizo la app para entrar al estacionamiento |
| vehiclePlate      | string           | Private          | Placa del vehículo que ingreso al estacionamiento |
| entryTime         | Time             | Private          | Hora de entrada del vehiculo     |
| status        | Long             | Private          | Estado del ticket   |
| amountCharged            | string           | Private          | Cantidad que pago el usuario por su estancia en el estacionamiento     |
| paymentStatus     | string           | Private          | Estado actual del pago                   |
| totalDuration | string | Private | Duración total de la estancia del vehiculo en el estacionamiento |

### 4.2.7.2. Interface Layer

### Entidad: TicketsController

| **Nombre**           | **Categoría** | **Propósito**                                              |
|----------------------|---------------|------------------------------------------------------------|
| TicketsController    | Controller    | Endpoints para la gestión de tickets                       |

### Atributos

| **Nombre**       | **Tipo de dato** | **Visibilidad** | **Descripción**                        |
|------------------|------------------|-----------------|----------------------------------------|
| ticketService    | ITicketService   | Private         | Servicio de gestión de tickets         |

### Métodos

| **Nombre**       | **Tipo de retorno**                          | **Visibilidad** | **Descripción**                                              |
|------------------|----------------------------------------------|-----------------|--------------------------------------------------------------|
| Constructor      | Void                                         | Public          | Constructor del controlador                                   |
| getTicket        | ResponseEntity<TicketResponseDto>      | Public          | Obtener un ticket por su ID                                   |
| createTicket     | ResponseEntity<TicketResponseDto>        | Public          | Crear un nuevo ticket                                         |
| getTicketHistory | ResponseEntity<Array<TicketResponseDto>> | Public          | Obtener el historial de tickets de un usuario por su Id       |
  
### Entidad: TicketRequestDto

| **Nombre**       | **Categoría** | **Propósito**                                               |
|------------------|---------------|-------------------------------------------------------------|
| TicketRequestDto | DTO           | Datos necesarios para crear un nuevo ticket en el sistema   |

### Atributos

| **Nombre**       | **Tipo de dato** | **Visibilidad** | **Descripción**                                             |
|------------------|------------------|-----------------|-------------------------------------------------------------|
| vehiclePlate     | string           | Private         | Placa del vehículo que ingresará al estacionamiento         |
| userId           | string           | Private         | ID del usuario que utilizará la app para ingresar           |
   
### Entidad: TicketResponseDto

| **Nombre**         | **Categoría** | **Propósito**                                               |
|--------------------|---------------|-------------------------------------------------------------|
| TicketResponseDto  | DTO           | Representación de un ticket con los detalles de entrada, salida y pago |

### Atributos

| **Nombre**        | **Tipo de dato** | **Visibilidad** | **Descripción**                                                                 |
|-------------------|------------------|-----------------|---------------------------------------------------------------------------------|
| id                | Long             | Private         | Identificador único del ticket                                                  |
| userId            | string           | Private         | ID del usuario que utilizó la app para ingresar al estacionamiento              |
| vehiclePlate      | string           | Private         | Placa del vehículo que ingresó al estacionamiento                               |
| entryTime         | Time             | Private         | Hora de entrada del vehículo al estacionamiento                                 |
| status            | Long             | Private         | Estado actual del ticket                                                        |
| amountCharged     | string           | Private         | Monto que pagó el usuario por su estancia en el estacionamiento                  |
| paymentStatus     | string           | Private         | Estado actual del pago (ej. "Pagado", "Pendiente")                              |
| totalDuration     | string           | Private         | Duración total de la estancia del vehículo en el estacionamiento                 |
  
### 4.2.7.3. Application Layer
  
### Entidad: ITicketService

| **Nombre**     | **Categoría** | **Propósito**                                               |
|----------------|---------------|-------------------------------------------------------------|
| ITicketService | Interface     | Define las operaciones para la gestión de tickets           |

### Métodos

| **Nombre**        | **Tipo de retorno**                          | **Descripción**                                              |
|-------------------|----------------------------------------------|--------------------------------------------------------------|
| createTicket      | TicketResponseDto                            | Crea un nuevo ticket con la placa del vehículo y el ID del usuario |
| getTicket         | TicketResponseDto                            | Obtiene un ticket por su ID                                   |
| getTicketHistory  | List<TicketResponseDto>                         | Obtiene el historial de eventos de un ticket                  |
  
  
### Entidad: TicketServiceImpl

| **Nombre**        | **Categoría** | **Propósito**                                               |
|-------------------|---------------|-------------------------------------------------------------|
| TicketServiceImpl | Service       | Implementa las operaciones para la gestión de tickets       |

### Atributos

| **Nombre**        | **Tipo de dato** | **Visibilidad** | **Descripción**                                             |
|-------------------|------------------|-----------------|-------------------------------------------------------------|
| ticketRepository  | ITicketRepository| Private         | Repositorio para acceder a los datos de los tickets         |
| modelMapper       | ModelMapper      | Private         | Mapper para convertir entre entidades y DTOs                |

### Métodos

| **Nombre**        | **Tipo de retorno**                          | **Visibilidad** | **Descripción**                                              |
|-------------------|----------------------------------------------|-----------------|--------------------------------------------------------------|
| Constructor       | void                                         | Public          | Constructor de la clase                                      |
| createTicket      | TicketResponseDto                            | Public          | Crea un nuevo ticket con la placa del vehículo y el ID del usuario |
| getTicket         | TicketResponseDto                            | Public          | Obtiene un ticket por su ID                                   |
| getTicketHistory  | List<TicketResponseDto>                         | Public          | Obtiene el historial de eventos de un ticket                  |
  
### 4.2.7.4. Infrastructure Layer

### Repository Interface

| **Nombre**              | **Categoría** | **Propósito**                                               |
|-------------------------|---------------|-------------------------------------------------------------|
| ITicketRepository       | Repository    | Repositorio JPA para la entidad Ticket                      |

### Atributos

| **Nombre**             | **Tipo de retorno** | **Visibilidad** | **Descripción**                                             |
|------------------------|---------------------|-----------------|-------------------------------------------------------------|
| findByVehiclePlate     | List<Ticket>  | Public          | Encontrar tickets por la placa del vehículo                 |
| findByUserId           | List<Ticket>  | Public          | Encontrar tickets por el ID del usuario                     |
| findByStatus           | List<Ticket>  | Public          | Encontrar tickets por su estado (por ejemplo, "Activo")     |
| findByEntryTimeBetween | List<Ticket>  | Public          | Encontrar tickets por rango de tiempo de entrada            |

### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.7.5-TicketValidation-ComponentDiagram.png" alt="Ticket Validation Component Diagram"/></p>

### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.7.6.1-TicketValidation-ClassDiagram.jpg" alt="Ticket Validation Class Diagram"/></p>

#### 4.2.7.6.2. Bounded Context Database Design Diagram
  
<p align="center"><img src="assets/capitulo-4/4.2.7.6.2-TicketValidationDatabase.jpg" alt="Ticket Validation DB Diagram"/></p>

## 4.2.8. Bounded Context: Notifications

### 4.2.8.1. Domain Layer

**Entity: Notification**

| Nombre      | Categoría | Propósito                                      |
|-------------|-----------|------------------------------------------------|
| Notification| Entity    | Representa una notificación que será enviada al usuario. |

**Atributos:**
| Nombre        | Tipo de dato | Visibilidad | Descripción                                                |
|---------------|--------------|-------------|------------------------------------------------------------|
| id            | Long         | Private     | Identificador único de la notificación.                    |
| message       | String       | Private     | Contenido del mensaje de la notificación.                 |
| status        | String       | Private     | Estado de la notificación (enviado, pendiente, fallido).   |
| recipient     | String       | Private     | Usuario al que se le envía la notificación.               |
| timestamp     | LocalDate    | Private     | Fecha y hora en que se generó la notificación.            |

### 4.2.8.2. Interface Layer

**Controller: NotificationController**

| Nombre                   | Categoría   | Propósito                                                        |
|--------------------------|-------------|------------------------------------------------------------------|
| NotificationController    | Controller  | Endpoints para gestionar las notificaciones.                     |

**Atributos:**

| Nombre                  | Tipo de dato          | Visibilidad | Descripción                                                   |
|-------------------------|-----------------------|-------------|---------------------------------------------------------------|
| notificationService      | INotificationService  | Private     | Servicio para gestionar operaciones de notificación.          |

**Métodos:**

| Nombre                         | Tipo de retorno                          | Visibilidad | Descripción                                                       |
|---------------------------------|------------------------------------------|-------------|-------------------------------------------------------------------|
| Constructor                    | Void                                     | Public      | Constructor del controlador.                                       |              |
| getNotificationByUserId            | ResponseEntity<NotificationResponseDto>  | Public      | Obtener una notificación específica por el user ID.                   |
| createNotification             | ResponseEntity<NotificationResponseDto>  | Public      | Crear una nueva notificación.                                     |
| deleteNotification             | ResponseEntity<Void>                    | Public      | Eliminar una notificación específica.                            |

---

**DTO: NotificationRequestDto**

| Nombre                   | Categoría   | Propósito                                                       |
|--------------------------|-------------|---------------------------------------------------------------|
| NotificationRequestDto    | DTO         | Clase para crear una notificación.                             |

**Atributos:**

| Nombre              | Tipo de dato | Visibilidad | Descripción                                                |
|---------------------|--------------|-------------|------------------------------------------------------------|
| message             | String       | Private     | Mensaje de la notificación.                                |
| recipient           | String       | Private     | Usuario destinatario de la notificación.                   |
| deliveryMethod      | String       | Private     | Método de entrega (ej., SMS, Email, Push Notification).    |

---

**DTO: NotificationResponseDto**

| Nombre                   | Categoría   | Propósito                                                        |
|--------------------------|-------------|------------------------------------------------------------------|
| NotificationResponseDto   | DTO         | Clase para devolver la respuesta de la notificación.             |

**Atributos:**

| Nombre              | Tipo de dato      | Visibilidad | Descripción                                                |
|---------------------|-------------------|-------------|------------------------------------------------------------|
| id                  | Long              | Private     | Identificador único de la notificación.                    |
| message             | String            | Private     | Mensaje de la notificación.                                |
| recipient           | String            | Private     | Usuario destinatario de la notificación.                   |
| status              | String            | Private     | Estado de la notificación (enviado, pendiente, fallido).   |
| timestamp           | LocalDateTime     | Private     | Fecha y hora de creación de la notificación.               |


### 4.2.8.3. Application Layer

**Service Interface: INotificationService**

| Nombre                | Categoría | Propósito                                                      |
|-----------------------|-----------|----------------------------------------------------------------|
| INotificationService   | Service   | Operaciones para la gestión de las notificaciones.             |

**Métodos:**

| Nombre                  | Tipo de retorno                      | Visibilidad | Descripción                                                     |
|-------------------------|--------------------------------------|-------------|-----------------------------------------------------------------|
| sendNotification        | Void                                 | Public      | Envía una notificación a un usuario.                            |
| getNotificationStatus   | String                               | Public      | Obtiene el estado de entrega de la notificación.                |
| getNotificationsHistory | List<Notification>                   | Public      | Obtiene el historial de notificaciones enviadas.                |
| updateNotificationStatus| Void                                 | Public      | Actualiza el estado de una notificación (ej., fallida, exitosa).|

---

**Service Implementation: NotificationServiceImpl**

| Nombre                | Categoría | Propósito                                                      |
|-----------------------|-----------|----------------------------------------------------------------|
| NotificationServiceImpl | Service   | Implementación de la lógica de negocio para las notificaciones. |

**Atributos:**

| Nombre                 | Tipo de dato      | Visibilidad | Descripción                                                   |
|------------------------|-------------------|-------------|---------------------------------------------------------------|
| notificationRepository | INotificationRepository | Private     | Repositorio para acceder a los datos de notificaciones.      |
| modelMapper            | ModelMapper       | Private     | Mapper para transformar entidades y DTOs.                     |
| restTemplate           | RestTemplate      | Private     | Cliente para hacer llamadas HTTP a servicios externos.        |

**Métodos:**

| Nombre                    | Tipo de retorno                      | Visibilidad | Descripción                                                     |
|---------------------------|--------------------------------------|-------------|-----------------------------------------------------------------|
| Constructor                | Void                                 | Public      | Constructor que inyecta dependencias.                           |
| sendNotification           | Void                                 | Public      | Envía una notificación a través de los servicios externos.      |
| getNotificationStatus      | String                               | Public      | Obtiene el estado actual de la notificación.                    |
| getNotificationsHistory    | List<Notification>                   | Public      | Obtiene todas las notificaciones previas.                       |
| updateNotificationStatus   | Void                                 | Public      | Actualiza el estado de la notificación en la base de datos.    |

---

### 4.2.8.4. Infrastructure Layer

**Repository Interface: INotificationRepository**

| Nombre                 | Categoría   | Propósito                                                      |
|------------------------|-------------|----------------------------------------------------------------|
| INotificationRepository | Repository  | Repositorio para manejar las notificaciones almacenadas.       |

**Métodos:**

| Nombre                    | Tipo de retorno           | Visibilidad | Descripción                                                   |
|---------------------------|---------------------------|-------------|---------------------------------------------------------------|
| saveNotification           | Notification              | Public      | Guarda una nueva notificación en la base de datos.            |
| findById                   | Optional<Notification>    | Public      | Encuentra una notificación específica por su ID.              |
| findByRecipient            | List<Notification>        | Public      | Encuentra todas las notificaciones de un usuario específico.   |
| findByStatus               | List<Notification>        | Public      | Encuentra las notificaciones por su estado (enviado, pendiente).|
| deleteNotification         | Void                      | Public      | Elimina una notificación de la base de datos.                 |

---

### 4.2.8.5. Bounded Context Software Architecture Component Level Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.8.5-Notifications-Component-Diagram.PNG" alt="Notifications Class Diagram"/></p>

### 4.2.8.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.8.6.1. Bounded Context Domain Layer Class Diagrams

<p align="center"><img src="assets/capitulo-4/4.2.8.6.1-Notifications-Class-Diagram.PNG" alt="Notifications Class Diagram"/></p>


#### 4.2.8.6.2. Bounded Context Database Design Diagram
<p align="center"><img src="assets/capitulo-4/4.2.8.6.2-Notifications-Database-Model.PNG" alt="Notifications DB Diagram"/></p>

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

<div align="justify">

En esta sección se definirán las guías visuales clave para el diseño de **ParkUp**, incluyendo colores, tipografía, logotipo y tono de comunicación. Estos lineamentos asegurarán una identidad coherente y profesional que refleje los valores de confianza e innovación de la marca.

</div>

### 5.1.1. General Style Guidelines

<div align="justify">

Es fundamental considerar las decisiones y elementos visuales que respaldan los principios generales de diseño para **ParkUp**. Por esta razón, resulta esencial definir aspectos clave como la identidad de marca, la paleta de colores y la tipografía. Además, es necesario establecer el tono de comunicación y el lenguaje utilizado, que abarcan características como divertido o serio, formal o casual, respetuoso o irreverente, y entusiasta o sereno.

**Branding:**

<p align="center">
  <img src="assets/capitulo-5/ParkUp.jpg" alt="Imagen extraída de Figma" width="700  "/>
</p>


**ParkUp** representa innovación, confianza y eficiencia en la gestión y vigilancia inteligente de parqueos. Nuestra esencia radica en ofrecer soluciones tecnológicas modernas que permiten monitorear, optimizar y mejorar la seguridad en los espacios de estacionamiento. La marca es sinónimo de precisión, confiabilidad y una experiencia de usuario simplificada, orientada a un entorno urbano inteligente.

**Logotipo:**
El logotipo de **ParkUp** refleja la identidad de una marca moderna, segura y tecnológica. Mediante una combinación de colores vivos y un diseño minimalista pero sofisticado, el logo simboliza la eficiencia, la confianza y el uso de tecnología de vanguardia en la vigilancia de parqueo. Este logotipo debe transmitir una imagen clara de control, innovación y accesibilidad para usuarios y operadores.
<br>
**Colores:**

<p align="center">
  <img src="assets/capitulo-5/paleta.png" alt="Imagen extraída de Figma" width="700"/>
</p>
<br>
Se ha utilizado los colores blanco, negro y azul oscuro como colores principales para nuestro diseño.

🔵 Azul oscuro (#2E3447):
El color azul oscuro se utiliza como color principal de la marca, aportando confianza, seguridad y modernidad. Representa la tecnología y la eficiencia que caracterizan a ParkUp en su enfoque hacia la optimización del estacionamiento urbano. Es protagonista en los botones principales, encabezados y elementos destacados de la interfaz.

⚪ Blanco (#FFFFFF):
El blanco se emplea como color de fondo predominante, transmitiendo limpieza, claridad y simplicidad en la experiencia del usuario. Sirve como base para resaltar los demás colores y garantizar una lectura fluida, orden visual y una navegación intuitiva.

⚫ Gris (#4F566B / #8E9099):
Los tonos grises se utilizan para los textos secundarios, bordes de campos de entrada, íconos y elementos informativos. Brindan equilibrio visual, profesionalismo y elegancia. Este color apoya al azul oscuro sin competir con él, manteniendo una estética sobria y tecnológica.

**Tipografía:**

<p align="center">
  <img src="assets/capitulo-5/tipografia.png" alt="Imagen extraída de Figma" width="700"/>
</p>

La tipografía utilizada para **ParkUp** es **Inter** , la cual es, moderna y legible, con líneas limpias y claras. Se ha elegido una fuente que refleje la tecnología y la seguridad de la marca, mientras mantiene un aspecto novedoso y actual. Usaremos las variantes Regular, Medium, Semi-Bold y Bold.

**Tonos de Comunicación:**

- **Formal / Confiable:**
En **ParkUp** adoptamos un tono formal y profesional que transmite confianza y responsabilidad, especialmente en lo relacionado a la seguridad del usuario y la gestión de sus reservas. Sin embargo, mantenemos una comunicación cercana y comprensible, accesible para todos los usuarios que buscan una solución eficiente para estacionar.
<br>

- **Respetuoso / Cercano:**
Siempre nos comunicamos con respeto, claridad y empatía. Entendemos las frustraciones comunes en la búsqueda de estacionamiento y respondemos con soluciones y mensajes que conectan con las verdaderas necesidades de nuestros usuarios, manteniendo una relación transparente y honesta.
<br>

- **Entusiasta / Sereno:**
Transmitimos entusiasmo por cambiar la forma en que las personas se estacionan en la ciudad, destacando nuestra innovación tecnológica y eficiencia. Al mismo tiempo, mantenemos un tono sereno y confiable que le brinda al usuario la tranquilidad de saber que su experiencia con **ParkUp** será rápida, segura y sin complicaciones.
<br>

</div>

### 5.1.2. Web, Mobile and IoT Style Guidelines

<div align="justify">

**ParkUp** contempla integraciones con sensores de parqueo, barreras automáticas y señalización inteligente. Para esto, se plantean las siguientes guías:

- Estándares abiertos: Comunicación basada en protocolos como MQTT o REST para interoperabilidad con sensores de disponibilidad o control de acceso.

- Feedback visual en tiempo real: Integración con señaléticas LED en los estacionamientos para indicar espacios libres, reservados o en uso, sincronizados con la app.

- Autenticación con QR/NFC: Permitir que los usuarios puedan ingresar a espacios reservados escaneando un código QR o utilizando tecnología NFC desde su móvil.

- Integración de Pagos: Incorporación de métodos de pago como Yape, Plin y tarjetas de crédito o débito, con el objetivo de agilizar el proceso de pago por estacionamiento y eliminar la necesidad de hacer colas.

</div>

## 5.2. Information Architecture
### 5.2.1. Organization Systems

<div align="justify">

La aplicación **ParkUp** ofrecerá una interfaz clara e intuitiva gracias a una estructura organizativa lógica que facilitará la gestión de estacionamientos tanto para conductores como para operadores. Los principios de organización de la información asegurarán que los usuarios puedan navegar fácilmente entre ubicaciones, reservas, reportes y configuraciones, maximizando la eficiencia en la experiencia de estacionamiento inteligente.

Jerarquía visual (Visual Hierarchy): En la página principal del usuario, **ParkUp** presentará un tablero con métricas clave como el número de reservas activas, espacios disponibles cercanos y tiempo restante en el estacionamiento actual. Esta jerarquía visual resaltará los datos más relevantes mediante gráficos de ocupación, íconos llamativos y colores de estado (verde, amarillo, rojo), facilitando una comprensión rápida del estado de uso sin necesidad de navegación adicional.

Organización secuencial (Step-by-step): Flujos como la creación de una reserva, selección de estacionamiento y confirmación de pago seguirán un esquema paso a paso, guiando al usuario de forma clara y sin ambigüedades. Este enfoque minimizará errores y mejorará la experiencia, especialmente en situaciones de movilidad.

Esquemas de categorización del contenido:

Por ubicación: Los estacionamientos se organizarán por zonas geográficas, lo cual facilitará la búsqueda del espacio más conveniente para cada usuario.

Por tipo de usuario: Conductores frecuentes, visitantes esporádicos y operadores del sistema tendrán interfaces y accesos distintos. Por ejemplo, un operador podrá acceder a estadísticas de ocupación y reportes, mientras que un conductor verá sus reservas, historial y espacios disponibles.

Cronológico: Las reservas, historial de uso y pagos estarán organizados cronológicamente, permitiendo a los usuarios visualizar la evolución de su actividad y acceder rápidamente a tickets anteriores.

Alfabético: Las listas de estacionamientos, configuraciones de cuenta o términos del servicio estarán organizadas alfabéticamente para una navegación más eficiente en secciones estáticas.

Con esta estructura organizativa, **ParkUp** garantizará que los usuarios completen sus procesos de forma eficiente, fluida y estructurada, promoviendo una movilidad urbana más inteligente y colaborativa.

</div>

### 5.2.2. Labeling Systems

<div align="justify">

En esta sección se presenta el sistema de etiquetado que **ParkUp** utilizará para facilitar la comprensión y navegación dentro de la plataforma, tanto en la aplicación como en la landing page. Los encabezados estarán organizados de forma clara, accesible y adaptada a los distintos perfiles de usuarios.

**Inicio/Home:** Vista principal con acceso a funcionalidades clave, como búsqueda de estacionamientos, reservas activas, historial y notificaciones importantes. Se presentará una introducción breve sobre la misión de **ParkUp**: facilitar el acceso y gestión de parqueo urbano en tiempo real.

**Beneficios/Features:** Se describirán los principales beneficios, como la reserva anticipada, la visualización de espacios disponibles, pagos digitales seguros, y gestión en tiempo real para operadores. También se destacará el valor agregado de la integración con mapas y la experiencia sin fricciones.

**Preguntas Frecuentes/FAQs:** Se responderán preguntas comunes sobre cómo registrarse, realizar reservas, cambiar métodos de pago, cancelar una reserva, etc.

**Contáctanos/Contact Us:** Incluirá canales de atención como correo electrónico, WhatsApp y un formulario de contacto directo para soporte técnico o consultas comerciales.

</div>

### 5.2.3. SEO Tags and Meta Tags

<div align="justify">

Para optimizar la visibilidad de **ParkUp** en los motores de búsqueda, se definirán las siguientes etiquetas SEO y metadatos para su landing page:

Title: **ParkUp** | Tu estacionamiento inteligente en un clic.

Description: **ParkUp** - Encuentra, paga, reserva tu espacio de parqueo en segundos con tu celular.

Keywords: estacionamiento, parqueo inteligente, reserva de parqueo, movilidad urbana, **ParkUp** app.

Author: **ParkUp** Team

Canonical: ....

</div>

### 5.2.4. Searching Systems

<div align="justify">

Para mejorar la experiencia de búsqueda dentro de **ParkUp**, se implementará un sistema que combine rapidez, precisión y facilidad de uso:

Búsqueda básica: Campo de búsqueda simple disponible en la pantalla principal, donde los usuarios pueden ingresar direcciones, nombres de estacionamientos o distritos.

Filtros avanzados: Los usuarios podrán filtrar por horario, tipo de vehículo (auto, moto, bicicleta), precios, espacios disponibles, acceso para discapacitados, entre otros.

Ordenación de resultados: Los resultados podrán ordenarse por proximidad, precio (ascendente/descendente), calificación de usuarios o disponibilidad inmediata.

</div>

### 5.2.5. Navigation Systems

<div align="justify">

La navegación en **ParkUp** se diseñará para ofrecer una experiencia fluida, intuitiva y centrada en las tareas más frecuentes del usuario.

Menú de navegación principal: Disponible en la parte superior o inferior (según dispositivo), con acceso directo a secciones como "Inicio", "Promociones", "Historial", "Rutas", "Sitios", "Perfil".

Búsqueda centralizada: Campo de búsqueda destacado para localizar espacios de parqueo rápidamente según la ubicación actual o una dirección específica.

Botones de acción estratégicos (CTAs): Botones como “Reservar Ahora”, “Ver Mapa”, “Confirmar Pago” y “Finalizar Estancia” estarán claramente identificados y ubicados en lugares clave dentro de cada flujo.

Navegación coherente y simplificada: Toda la plataforma mantendrá un esquema de navegación consistente, con menús de retroceso, iconografía uniforme y rutas claras, tanto para nuevos usuarios como para conductores frecuentes u operadores.

</div>


## 5.3. Landing Page UI Design

**Hero Section**

<p align="center">
  <img src="assets/capitulo-5/Hero.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**About Us**

<p align="center">
  <img src="assets/capitulo-5/Aboutus.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Our Product**

<p align="center">
  <img src="assets/capitulo-5/OurProduct.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Description of the Product**

<p align="center">
  <img src="assets/capitulo-5/Details.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Endorsed By**

<p align="center">
  <img src="assets/capitulo-5/EndorsedBy.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**F&A**

<p align="center">
  <img src="assets/capitulo-5/F&A.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Testimonials**

<p align="center">
  <img src="assets/capitulo-5/Testimonials.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Contact US**

<p align="center">
  <img src="assets/capitulo-5/ContactUs.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>


**Footer**

<p align="center">
  <img src="assets/capitulo-5/Footer.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

### 5.3.1. Landing Page Wireframe


**Hero Section**

<p align="center">
  <img src="assets/capitulo-5/1wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**About Us**

<p align="center">
  <img src="assets/capitulo-5/2wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Our Product**

<p align="center">
  <img src="assets/capitulo-5/3wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Description of the Product**

<p align="center">
  <img src="assets/capitulo-5/4wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Endorsed By**

<p align="center">
  <img src="assets/capitulo-5/endorsedbywireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

**F&A**

<p align="center">
  <img src="assets/capitulo-5/5wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Testimonials**

<p align="center">
  <img src="assets/capitulo-5/testimonialwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Contact US**

<p align="center">
  <img src="assets/capitulo-5/6wireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**Footer**

<p align="center">
  <img src="assets/capitulo-5/footerwireframe&apos;.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design

*WEB APPLICATION*

**LOG IN**

<p align="center">
  <img src="assets/capitulo-5/Login.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**REGISTER**

<p align="center">
  <img src="assets/capitulo-5/Register.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**REGISTER MALL**

<p align="center">
  <img src="assets/capitulo-5/mall.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**DASHBOARD**

<p align="center">
  <img src="assets/capitulo-5/dashboard.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**MONITORING**

<p align="center">
  <img src="assets/capitulo-5/monitoring.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**PARKING LOT**

<p align="center">
  <img src="assets/capitulo-5/allotment.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**PARKING FEE ADMINISTRATION**

<p align="center">
  <img src="assets/capitulo-5/parkingfee.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**STATISTICS**

<p align="center">
  <img src="assets/capitulo-5/statistics.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>


**MOBILE APPLICATION**

*REGISTER MALL*

<br>

**SPLASH SCREEN**

<p align="center">
  <img src="assets/capitulo-5/splashscreen.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**SIGN IN**

<p align="center">
  <img src="assets/capitulo-5/Loginin.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**SING UP**

<p align="center">
  <img src="assets/capitulo-5/signup.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**QR CODE SCANNER**

<p align="center">
  <img src="assets/capitulo-5/QrCode.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**SPOT FINDER**

<p align="center">
  <img src="assets/capitulo-5/Spot.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>



**SCAN VOUCHER**

<p align="center">
  <img src="assets/capitulo-5/scanvoucher.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**PAYMENT DETAILS**

<p align="center">
  <img src="assets/capitulo-5/details1.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>

**FINAL SCREEN**

<p align="center">
  <img src="assets/capitulo-5/thanks.png" alt="Imagen extraída de Figma" width="400"/>
</p>

<br>


### 5.4.1. Applications Wireframes

*WEB APPLICATION*

**LOG IN**

<p align="center">
  <img src="assets/capitulo-5/loginwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**REGISTER**

<p align="center">
  <img src="assets/capitulo-5/registerwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**REGISTER MALL**

<p align="center">
  <img src="assets/capitulo-5/mallwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**DASHBOARD**

<p align="center">
  <img src="assets/capitulo-5/dashboardwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**MONITORING**

<p align="center">
  <img src="assets/capitulo-5/monitoringwireframe].png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**PARKING LOT**

<p align="center">
  <img src="assets/capitulo-5/allotmentwireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**PARKING FEE ADMINISTRATION**

<p align="center">
  <img src="assets/capitulo-5/parkingfee.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

**STATISTICS**

<p align="center">
  <img src="assets/capitulo-5/statswireframe.png" alt="Imagen extraída de Figma" width="900"/>
</p>

<br>

### 5.4.2. Applications Wireflow Diagrams

### 5.4.3. Applications User Flow Diagrams

## 5.5. Applications Prototyping


# Capítulo VI: Product Implementation & Validation

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

#### Project Management

Trello: www.trello.com   
Esta herramienta es para la gestión del proyecto, donde en tableros se organizan las tasks de cada sprint y observar el avanza y estado de cada una de ellas.

#### Product UX/UI Design

Miro: www.miro.com 
Se utilizó para simular una pizarra para los brainstoriming y así, elaborar los As-Is y To-Be Scenarios Mapping.
  
Figma: www.figma.com 
En esta herramienta se elaboraron los Wireframes, Mock-ups y Prototypes.

#### Software Development

Angular: angular.dev
Es un framework frontend que permite el desarrollo de aplicaciones web de una sola página utilizando HTML, CSS y TypeScript.

Spring Boot: spring.io
Es un framework backend para el desarrollo de aplicaciones en Java.

GitHub: github.com 
Fue utilizado para guardar los repositorios de nuestros sitios web y tener un control de versiones.
  
#### Software Testing

Appium: appium.io
Herramienta de automatización de código abierto que permite probar aplicaciones nativas, híbridas y web en dispositivos Android e iOS.

Selenium: www.selenium.dev 
Es un IDE que facilita las pruebas para aplicaciones web. Por ejemplo, permite grabar, editar y depurar casos de prueba.

#### Software Deployment

Flutter SDK: flutter.dev
Permite la preparación para el despleigue de aplicación moviles hechas con Flutter.

Firebase: firebase.com
Permite el despliegue gratuito de paginas web.

#### Software Documentation

Structurizr: structurizr.com
Es un diseñador del modelo C4 para visualizar la arquitectura del software.

LucidChart: www.lucidchart.com 
Es una herramienta para crear y compartir diagramas y lo utilizamos para los diagramas de código UML.

Draw.io: app.diagrams.net
Software gratuito en línea para crear diagramas de flujo, diagramas de procesos, organigramas, diagramas UML, diagramas ER y diagramas de red. 

Vertabelo: vertabelo.com
Es un modelador de base de datos, el cual lo utilizamos para elaborar le diagrama de base de datos.

Swagger: swagger.io
Es una herramienta para diseñar, construir, documentar y consumir servicios web RESTful. En nuestro backend, generó la documentación interactiva de la API.
  
### 6.1.2. Source Code Management

Para el control de versiones de nuestro proyecto de software se utiliza la plataforma GitHub, en la cual se creó la organización con los respectivos repositorios:
- Organización: https://github.com/SolucionesIoT-FindAndPark-UPC  
- Landing Page: https://github.com/SolucionesIoT-FindAndPark-UPC/landing-page.git   
- Reporte Markdown: https://github.com/SolucionesIoT-FindAndPark-UPC/markdown-report.git  
  
Además, se implementa GitFlow como Workflow de control de versiones:
- La rama principal es ‘main’ la cual representa la versión estable del software.
- Cada feature desarrollado, ya sea en el informe o de una funcionalidad se desarrolla en una rama diferente. Estas ramas son especificadas con el formato "feature" y se hace merge de sus avances a la rama main una vez validados
- Las ramas de feature deben seguir un formato claro y descriptivo que identifique la funcionalidad en desarrollo. Es recomendable utilizar prefijos que distingan la característica específica, y emplear separadores como guiones (‘-’) o barras (‘/’) para mejorar la organización y legibilidad de los nombres de las ramas. Este enfoque facilita una estructura consistente que optimiza la comprensión de cada rama dentro del proyecto.

### 6.1.3. Source Code Style Guide & Conventions

Flutter: (file).dart
Descripción: Framework de desarrollo de aplicaciones móviles creado por Google. Utiliza el lenguaje de programación Dart y permite crear interfaces de usuario nativas.
Convenciones: En Flutter, se recomienda utilizar el idioma inglés para nombrar clases, funciones y archivos, ya que es el estándar en la programación. Los nombres de clases, enumeraciones y extensiones deben seguir el formato UpperCamelCase, mientras que los nombres de variables, funciones, parámetros y constantes deben utilizar lowerCamelCase. Los archivos y directorios deben nombrarse en snake_case (minúsculas separadas por guiones bajos). Se debe evitar el uso de prefijos innecesarios como Widget en los nombres de clases y componentes.  

HTML: (file).html
Descripción: Hypertext Makeup Language es el lenguaje estándar que se utiliza para crear y estructurar el contenido de páginas web. Consiste en una serie de etiquetas y elementos que definen diferentes partes del contenido para que se vean o comporten de una determinada manera. 
Convenciones:  De acuerdo con MDN Web Docs (s.f.), para facilitar la lectura y la coherencia en el código, es necesario usar espacios o tabulaciones de manera consistente, escribir los nombres de las etiquetas y de los archivos en minúsculas, usar comillas dobles para definir atributos en las etiquetas, usar el elemento "link" y "script" para relacion el archivo html con los archivos css y javascript respectivamente. Asimismo, es importante que cada elemento esté cerrado y que se agreguen solo comentarios significativos (“<!-” para iniciar un comentario y “->” para cerrarlo).

CSS: (file).css
Descripción: Cascading Style Sheets en un lenguaje de hojas de estilo que es utilizado para dar formato y diseño a las páginas web.
Convenciones: De acuerdo con MDN Web Docs (s.f.), para mejorar la legibilidad, se debe mantener los espacios adecuados, se usarán nombres de clases y selectores en minúscula y claros que reflejen su función, se debe procurar agrupar propiedades relacionadas juntas en el mismo bloque, y se usarán los id’s para poder modificar algún atributo en específico.

JavaScript: (file).js
Descripción: Lenguaje de programación que se usa para poder darle funcionalidades a las páginas web y que permita manipular su contenido y responder a acciones del usuario.
Convenciones: De acuerdo con MDN Web Docs (s.f.), para mejorar la comprensión del código, se utilizarán nombre de variables y funciones en minúscula, no abreviados y que describan su propósito. Asimismo, se dividirán funciones largas en funciones más pequeñas para facilitar la lectura.

Angular:
Descripción: Framework de desarrollo de apliciones web escalables y dinámicas, se basa en TypeScript.
Convenciones: De acuerdo con Angular (s.f.), la nomenclatura se hace con nombres descriptivos y para separar palabras se utilizan guiones. Se debe utilizar una estructura de carpeta para separar los componentes, módulos y servicios.

Java:
Convenciones de nomenclatura:
-	Nombres de clases: Deben comenzar con mayúscula y utilizar PascalCase. Por ejemplo, MiClase.
-	Nombres de interfaces: Deben comenzar con mayúscula y utilizar PascalCase. Por ejemplo, MiInterfaz.
-	Nombres de métodos: Deben comenzar con minúscula y utilizar camelCase. Por ejemplo, miMetodo().
-	Nombres de variables: Deben comenzar con minúscula y utilizar camelCase. Por ejemplo, miVariable.
-	Constantes: Deben estar en mayúsculas con palabras separadas por guiones bajos. Por ejemplo, MI_CONSTANTE.
-	Paquetes: Deben estar en minúsculas y utilizar nombres de dominio invertidos. Por ejemplo, com.miempresa.miproyecto.
Convenciones de formato:
-	Indentación: Usar cuatro espacios para cada nivel de indentación.
-	Líneas en blanco: Usar líneas en blanco para separar lógicamente secciones de código.
-	Longitud de línea: No exceder los 80-120 caracteres por línea para mantener la legibilidad.
-	Llaves: Colocar las llaves en la misma línea que la declaración o en la siguiente línea, con la misma indentación.
-	Comentarios: Usar comentarios descriptivos para explicar el propósito del código, evitando los comentarios obvios o redundantes.

### 6.1.4. Software Deployment Configuration

#### Despliegue Backend

#### Despliegue Frontend Web

#### Despliegue Mobile App 

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1

#### 6.2.1.2. Aspect Leaders and Collaborators

#### 6.2.1.3. Sprint Backlog 1

#### 6.2.1.4. Development Evidence for Sprint Review

#### 6.2.1.5. Testing Suite Evidence for Sprint Review

#### 6.2.1.6. Execution Evidence for Sprint Review

#### 6.2.1.7. Services Documentation Evidence for Sprint Review

#### 6.2.1.8. Software Deployment Evidence for Sprint Review

#### 6.2.1.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews

### 6.3.1. Diseño de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones según Heurísticas

## 6.4. Video About the Product


# Conclusiones

## Conclusiones y Recomendaciones

- El needfinding y desarrollo de entrevistas mejoro nuestro entendimiento de las necesidades reales y requisitos de los usuarios, y valido que la solución propuesta brinde el valor necesario a los stakeholders.  
- El planteamiento de épics, historias de usuario detalladas para cada segmento objetivo e historias técnicas no solo aseguran que la solución de software esté alineada con las expectativas y necesidades de los usuarios finales, sino que también facilitan la gestión de los aspectos técnicos a lo largo del desarrollo y mantenimiento del software.  
- Investigar la competencia nos revelo las cualidades que nuestra solución debe tener para competir en el mercado y nos da idea de las estrategias y tácticas que tenemos que seguir para garantizar nuestro éxito.  
- Se concluye que el uso de los dispositivos Iot en la planteación de la solución permitio expandir las capacidades que somos capaces de ofrecer a los stakeholders.  

## Video About-the-Team


# Bibliografía

- Mozilla Developer Network. (s.f.). HTML. Recuperado el 20 de abril de 2025, de https://developer.mozilla.org/en-US/docs/Web/HTML

- Mozilla Developer Network. (s.f.). CSS. Recuperado el 20 de abril de 2025, de https://developer.mozilla.org/en-US/docs/Web/CSS

- Mozilla Developer Network. (s.f.). JavaScript. Recuperado el 20 de abril de 2025, de https://developer.mozilla.org/en-US/docs/Web/JavaScript

- Angular. (s.f.). Overview. Recuperado el 20 de abril de 2025, de https://angular.dev/overview

# Anexos



