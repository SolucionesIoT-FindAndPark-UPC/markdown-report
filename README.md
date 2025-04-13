<p align="center">`
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
|TB1| ----  |  --   | ==                          |
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

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| -                   | -                   | -            |
| -                   | -                   | -            |

</div>

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo


# Capítulo II: Needfinding

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

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

##### Segmento 2: Administradores de parking
- Primera Entrevista:
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

### 2.2.3. Análisis de entrevistas
##### Segmento 1: Conductores

##### Segmento 2: Administradores de parking
- Primera Entrevista: El entrevistado señaló que el monitoreo se realiza principalmente mediante cámaras activas todo el tiempo y rondas presenciales para verificar el estado del parqueo. Ante emergencias, se comunica directamente con el gerente de tienda por radio, sin un protocolo formal establecido. La información más útil para su labor diaria incluye las grabaciones de las cámaras, el ticket del vehículo, la placa y el rostro del conductor. Actualmente no utilizan una plataforma web, ya que el parqueo es gratuito y no considera necesaria una visualización digital; sin embargo, si hubiera cobro, sí vería valor en implementarla. El control de ingreso y salida se realiza de forma manual con tickets y anotaciones en papel.

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog


# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2.X. Bounded Context: 

### 4.2.X.1. Domain Layer

### 4.2.X.2. Interface Layer

### 4.2.X.3. Application Layer

### 4.2.X.4. Infrastructure Layer

### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.X.6.2. Bounded Context Database Design Diagram


# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

### 5.4.3. Applications User Flow Diagrams

## 5.5. Applications Prototyping


# Capítulo VI: Product Implementation & Validation

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

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

## Video About-the-Team


# Bibliografía


# Anexos



