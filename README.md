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

En el contexto actual de crecimiento urbano y aumento del parque automotor, encontrar estacionamiento se ha convertido en una experiencia tediosa, lenta e ineficiente para miles de conductores en ciudades como Lima. La mayoría de soluciones tradicionales aún dependen de tickets físicos, interacciones manuales y procesos poco claros que afectan directamente la comodidad del usuario.

**ParkUp** nace como una respuesta a este problema. Es una aplicación móvil peruana que transforma por completo la experiencia de estacionamiento, integrando tecnología de lectura de placas, vinculación inteligente entre QR, vehículo y usuario, y un sistema de pago completamente automatizado. Todo esto se realiza sin necesidad de sacar el celular, después del escaneo inicial. ParkUp reduce los tiempos de entrada, elimina errores y simplifica el proceso de estacionarse con una interfaz moderna y centrada en el usuario.

La propuesta de valor de ParkUp se diferencia claramente de otras aplicaciones disponibles en el mercado peruano, ofreciendo una experiencia sin contacto, eficiente y totalmente digital, adaptada a la vida urbana moderna.  
  
Misión:  
Facilitar y modernizar la experiencia de estacionamiento en entornos urbanos mediante soluciones tecnológicas automatizadas, seguras y sin contacto, que integren al usuario con el sistema de manera intuitiva, eficiente y confiable.  

Visión:  
Convertirnos en la plataforma líder de estacionamiento inteligente en Perú, siendo referentes en innovación, automatización y experiencia de usuario, para transformar la manera en que las personas se movilizan y estacionan.  

### 1.1.2. Perfiles de integrantes del equipo  

| |Vargas Revollé, Ariana |
| |Obispo Rios, Lucero Abigail |
| |Cuevas Rios, Eric Fernando |
| |Elsner De La Torre Ugarte, Julio Esteban |
| |Herrera González, Luis Eduardo |  

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

<br><img src=""></img><br>

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
| **Overview**          | Plataforma web que permite a los usuarios registrar y alquilar espacios de estacionamiento privados en Lima, operando principalmente en los distritos de San Isidro y Miraflores. :contentReference[oaicite:1]{index=1} | Aplicación móvil que facilita la búsqueda, reserva y pago de estacionamientos en Lima, ofreciendo opciones de pago como tarjeta de crédito, débito y su monedero digital "Apparka Wallet". :contentReference[oaicite:2]{index=2} | Plataforma que permite a los usuarios encontrar y reservar estacionamientos urbanos, ofreciendo una variedad de opciones para conductores y propietarios de estacionamientos. | Aplicación móvil que automatiza la experiencia de estacionamiento, incluyendo lectura de placas, vinculación con usuarios y pagos automáticos, mejorando la eficiencia y comodidad del proceso. |
| **Mercado Objetivo**  | Conductores en Lima que buscan alquilar espacios de estacionamiento privados, especialmente en áreas con alta demanda como San Isidro y Miraflores. | Usuarios en Lima que requieren estacionamiento en zonas urbanas, incluyendo tanto conductores frecuentes como ocasionales. | Propietarios de estacionamientos y conductores en Lima que buscan soluciones eficientes para encontrar y reservar espacios de estacionamiento. | Conductores en Lima que buscan una experiencia de estacionamiento sin contacto, con procesos automatizados y pagos simplificados. |
| **Estrategias**      | - Permitir a los propietarios de espacios libres registrarlos y establecer precios y tiempos de alquiler. <br> - Ofrecer una plataforma que facilite la búsqueda y reserva de estacionamientos. <br> - Expandirse a otros distritos y países. :contentReference[oaicite:3]{index=3} | - Integración con estacionamientos existentes en Lima. <br> - Ofrecer múltiples métodos de pago, incluyendo su propio monedero digital. <br> - Proporcionar información en tiempo real sobre disponibilidad y tarifas. | - Crear un marketplace que conecte a propietarios de estacionamientos con conductores. <br> - Ofrecer una plataforma fácil de usar para la reserva y gestión de espacios. | - Automatizar el proceso de estacionamiento desde la llegada hasta la salida. <br> - Integrar tecnología de lectura de placas y pagos automáticos. <br> - Mejorar la experiencia del usuario con interfaces intuitivas. |
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

### 2.2.3. Análisis de entrevistas

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



