# CoBox  
## Producto: CoBox
# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

<p align="center">
  <img src="./assets/upc-logo.png" alt="UPC Logo" width="200"/>
</p>

### Carrera: Ingeniería de Software  
### Ciclo: 7° ciclo  
### Curso: Fundamentos de Arquitectura de Software  
### NRC: 6336  
### Profesor: Jorge Luis Delgado Vite

## Informe de Trabajo Final  
**"CoBox"**  
**Producto: "CoBox"**

### Integrantes:
- Ramiro Alexander Guzmán Chávez – U202217062  
- David Alexander Pérez García – U202222942  
- XXXX – U202219657  
- XXXX – U202310345  
- XXXX – U202217212  

**Septiembre, 2025**  
**URL del proyecto:** [https://github.com/G1-FundamentosArqui-6336](https://github.com/G1-FundamentosArqui-6336)

---

## Registro de Versiones del Informe

| Versión | Fecha       | Autor | Descripción |
|---------|-------------|-------|-------------|
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |
|         |             |       |             |

---

## Project Report Collaboration Insights

- **URL de la organización del proyecto:**  
  [https://github.com/G1-FundamentosArqui-6336](https://github.com/G1-FundamentosArqui-6336)
- **URL del repositorio del informe:**  
 [https://github.com/G1-FundamentosArqui-6336/Report](https://github.com/G1-FundamentosArqui-6336/Report)

 
---
## Contenido
#### Tabla de contenidos

- [Carátula](#carátula)
  - [Universidad, carrera, ciclo](#universidad-peruana-de-ciencias-aplicadas)
  - [Nombre del Startup](#cobox)
  - [Nombre del Producto](#cobox)
  - [Relación de Integrantes](#integrantes)
  - [Mes y Año](#mes-y-año)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Nombre del producto](#121-nombre-del-producto)
    - [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
    - [1.2.3. Lean UX Process](#123-lean-ux-process)
      - [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
      - [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
      - [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
      - [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)
  - [2.1. Competidores](#21-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Maps](#233-empathy-maps)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Map](#33-impact-map)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)
  - [4.1. Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)
    - [4.1.1. Principles Statements](#411-principles-statements)
    - [4.1.2. Approaches Statements](#412-approaches-statements)
    - [4.1.3. Architectural Styles & Patterns](#413-architectural-styles--patterns)
    - [4.1.4. Context Diagram](#414-context-diagram)
    - [4.1.5. Approach Driven ViewPoints Diagrams](#415-approach-driven-viewpoints-diagrams)
    - [4.1.6. Relational/Non Relational Database Diagram](#416-relationalnon-relational-database-diagram)
    - [4.1.7. Design Patterns](#417-design-patterns)
    - [4.1.8. Tactics](#418-tactics)
  - [4.2. Architectural Drivers](#42-architectural-drivers)
    - [4.2.1. Design Purpose](#421-design-purpose)
    - [4.2.2. Primary Functionality (User Stories)](#422-primary-functionality-user-stories)
    - [4.2.3. Quality Attribute Scenarios](#423-quality-attribute-scenarios)
    - [4.2.4. Constraints](#424-constraints)
    - [4.2.5. Architectural Concerns](#425-architectural-concerns)
  - [4.3. ADD Iterations](#43-add-iterations)
    - [4.3.X Iteration N](#43x-iteration-n)
      - [4.3.X.1. Architectural Design Backlog](#43x1-architectural-design-backlog)
      - [4.3.X.2. Establish Iteration Goal](#43x2-establish-iteration-goal)
      - [4.3.X.3. Choose Elements to Refine](#43x3-choose-elements-to-refine)
      - [4.3.X.4. Choose Design Concepts](#43x4-choose-design-concepts)
      - [4.3.X.5. Allocate Responsibilities & Define Interfaces](#43x5-allocate-responsibilities--define-interfaces)
      - [4.3.X.6. Sketch Views & Record Design Decisions](#43x6-sketch-views--record-design-decisions)
      - [4.3.X.7. Analysis & Review (Kanban Board)](#43x7-analysis--review-kanban-board)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Testing Suites & General Patterns](#51-testing-suites--general-patterns)
    - [5.1.1. Backend Application Core Testing Suite](#511-backend-application-core-testing-suite)
    - [5.1.2. Pattern Based Backend Application(s)](#512-pattern-based-backend-applications)
    - [5.1.3. Pattern Based Custom Software Library](#513-pattern-based-custom-software-library)
    - [5.1.4. Framework Pattern Driven Refactoring Report](#514-framework-pattern-driven-refactoring-report)
  - [5.2. Software Configuration Management](#52-software-configuration-management)
    - [5.2.1. Software Development Environment Configuration](#521-software-development-environment-configuration)
    - [5.2.2. Source Code Management](#522-source-code-management)
    - [5.2.3. Source Code Style Guide & Conventions](#523-source-code-style-guide--conventions)
    - [5.2.4. Software Deployment Configuration](#524-software-deployment-configuration)
  - [5.3. Microservices Implementation](#53-microservices-implementation)
    - [5.3.1. Sprint 1](#531-sprint-1)
      - [5.3.1.1. Sprint Backlog 1](#5311-sprint-backlog-1)
      - [5.3.1.2. Development Evidence](#5312-development-evidence)
      - [5.3.1.3. Testing Suite Evidence](#5313-testing-suite-evidence)
      - [5.3.1.4. Execution Evidence](#5314-execution-evidence)
      - [5.3.1.5. Microservices Documentation](#5315-microservices-documentation)
      - [5.3.1.6. Software Deployment Evidence](#5316-software-deployment-evidence)
      - [5.3.1.7. Team Collaboration Insights](#5317-team-collaboration-insights)
      - [5.3.1.8. Kanban Board](#5318-kanban-board)
    - [5.3.2. Sprint 2](#532-sprint-2)
      - [5.3.2.1. Sprint Backlog 2](#5321-sprint-backlog-2)
      - [5.3.2.2. Development Evidence](#5322-development-evidence)
      - [5.3.2.3. Testing Suite Evidence](#5323-testing-suite-evidence)
      - [5.3.2.4. Execution Evidence](#5324-execution-evidence)
      - [5.3.2.5. Microservices Documentation](#5325-microservices-documentation)
      - [5.3.2.6. Software Deployment Evidence](#5326-software-deployment-evidence)
      - [5.3.2.7. Team Collaboration Insights](#5327-team-collaboration-insights)
      - [5.3.2.8. Kanban Board ](#5328-kanban-board)
    - [5.3.3. Sprint 3](#533-sprint-3)
      - [5.3.3.1. Sprint Backlog 3](#5331-sprint-backlog-3)
      - [5.3.3.2. Development Evidence](#5332-development-evidence)
      - [5.3.3.3. Testing Suite Evidence](#5333-testing-suite-evidence)
      - [5.3.3.4. Execution Evidence](#5334-execution-evidence)
      - [5.3.3.5. Microservices Documentation](#5335-microservices-documentation)
      - [5.3.3.6. Software Deployment Evidence](#5336-software-deployment-evidence)
      - [5.3.3.7. Team Collaboration Insights](#5337-team-collaboration-insights)
      - [5.3.3.8. Kanban Board ](#5338-kanban-board)
    - [5.3.4. Sprint 4](#534-sprint-4)
      - [5.3.4.1. Sprint Backlog 4](#5341-sprint-backlog-4)
      - [5.3.4.2. Development Evidence](#5342-development-evidence)
      - [5.3.4.3. Testing Suite Evidence](#5343-testing-suite-evidence)
      - [5.3.4.4. Execution Evidence](#5344-execution-evidence)
      - [5.3.4.5. Microservices Documentation](#5345-microservices-documentation)
      - [5.3.4.6. Software Deployment Evidence](#5346-software-deployment-evidence)
      - [5.3.4.7. Team Collaboration Insights](#5347-team-collaboration-insights)
      - [5.3.4.8. Kanban Board](#5348-kanban-board)
  - [5.4. Microservices Deployment](#54-microservices-deployment)
    - [5.4.1. Cloud Architecture Diagram](#541-cloud-architecture-diagram)
    - [5.4.2. Cloud Deployment (AWS, Azure o GCP)](#542-cloud-deployment-aws-azure-o-gcp)

- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-The-Team](#video-about-the-team)
- [Referencias Bibliográficas](#referencias-bibliográficas)
- [Anexos ](#anexos)
- [Links](#links)


## Student Outcome

---

**ABET – EAC - Student Outcome 7**  
**Aprendizaje Continuo y Autónomo**  
**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del equipo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome:

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | <strong>David Alexander Pérez García</strong> </br> <strong>TB1:</strong></br>Durante el desarrollo del proyecto Co-box logistic participé activamente en la investigación y análisis de los requerimientos, lo que permitió definir las funcionalidades críticas de la plataforma, como el registro de kilometraje, la geolocalización en tiempo real, la captura de evidencias fotográficas y la generación de reportes. Además, me encargué de diseñar la arquitectura del sistema considerando criterios de escalabilidad y buenas prácticas de desarrollo. |<strong>David Alexander Pérez García</strong> </br> <strong>TB1:</strong></br> Esta participación me permitió aplicar de manera práctica mis conocimientos en el desarrollo de software, reforzando mis habilidades en diseño de sistemas, programación y gestión de bases de datos geoespaciales. |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | <strong>David Alexander Pérez García</strong> </br> <strong>TB1:</strong></br>Conscientemente actualicé mis conocimientos en el uso de frameworks modernos para el desarrollo de aplicaciones web, como React, Next.js y Spring Boot, así como en el manejo de bases de datos con capacidades geoespaciales mediante PostGIS. También investigué estándares de seguridad y mejores prácticas para el tratamiento de datos sensibles y evidencias digitales | <strong>David Alexander Pérez García</strong> </br> <strong>TB1:</strong></br>Reconozco que el aprendizaje permanente es esencial para mantenerme actualizado en un sector tan dinámico como el tecnológico y para responder adecuadamente a las exigencias de proyectos innovadores. |


---


## Capítulo I: Introducción

### 1.1. Startup Profile

El perfil de la startup es un pilar fundamental para articular la identidad y la hoja de ruta de una nueva empresa. Este apartado desglosa no solo su ambición y los principios que rigen sus acciones, sino que también clarifica su oferta única y cómo se distingue en el panorama competitivo. En esta sección, se detallarán los componentes cruciales que definen el carácter de la startup, incluyendo su génesis, los impulsos que motivaron su fundación, el desafío específico que se propone abordar y cómo su perspectiva innovadora le otorga una ventaja competitiva. Asimismo, se explorarán sus objetivos a corto, mediano y largo plazo, junto con las tácticas empleadas para su expansión y consolidación en su nicho de mercado. Entender estos aspectos es vital para apreciar el potencial inherente al perfil de la startup y la influencia que puede ejercer en su ecosistema.

#### 1.1.1. Descripción de la Startup
Co-box logistic es una plataforma web innovadora diseñada para revolucionar el sector del transporte de carga, ofreciendo una solución integral y tecnológica para la gestión de operaciones logísticas. La aplicación conecta a empresas de transporte con herramientas inteligentes que permiten el control preciso de cada servicio realizado. Entre sus funcionalidades se destacan el registro automatizado del kilometraje, la captura de evidencia fotográfica al momento de las entregas, y la geolocalización en tiempo real. Además, la generación automática de reportes e indicadores de desempeño facilita la toma de decisiones, optimizando la eficiencia operativa y reduciendo costos innecesarios.

Esta solución está pensada tanto para compañías de transporte que buscan mejorar la trazabilidad de sus operaciones, como para empresas logísticas que requieren de un control detallado y eficiente de sus servicios. Al digitalizar y potenciar cada etapa del proceso, Co-box logistic asegura una mayor transparencia y calidad en la entrega de productos, contribuyendo a fortalecer la confianza del cliente final.

Misión: Nuestra misión en Co-box logistic es transformar la gestión del transporte de carga a través de soluciones tecnológicas inteligentes, permitiendo a nuestros clientes operar de manera más eficiente, reducir costos y mejorar la trazabilidad de sus servicios.

Visión: Aspiramos a ser líderes en la innovación logística, impulsando un futuro en el que el transporte de carga sea cada vez más transparente, eficiente y sostenible, expandiendo nuestra presencia a nivel nacional e internacional.


#### 1.1.2. Perfiles de los integrantes del equipo

---

#### **XXXX – Ingeniería de Software – U202217212**  
<img src="./assets/RAMIROGUZMAN.png" alt="RAMIROGUZMAN" height="200"/>

XXXXX.

---

#### **Ramiro Alexander Guzman Chavez – Ingeniería de Software – U202217062**  
<img src="./assets/RAMIROGUZMAN.png" alt="RAMIROGUZMAN" height="200"/>

Mi perfil se basa en ser una persona responsable, disciplinada en todo aspecto y comprometida con las actividades que me puedan tocar.
Considero que tengo una experiencia altamente capacitada para este tipo de tareas. Suelo desarrollarme de manera positiva en los trabajos grupales y tengo conocimientos en bases de datos, lo cual puede aportar de manera importante al equipo.
Además, cuento con conocimientos en lenguajes de programación como Java y JavaScript, lo que me permite desarrollar soluciones tanto del lado del backend como del frontend, contribuyendo a proyectos de desarrollo de software de manera integral.

---

#### **David Alexander Pérez García – Ingeniería de Software – U202222942**  
<img src="./assets/PEREZGARCIA.jpg" alt="PEREZGARCIA" height="200"/>

Hola, soy David, estudiante de Ingeniería de Software en el octavo ciclo. Me considero una persona responsable, perseverante y apasionada por la tecnología. Tengo experiencia en el desarrollo de aplicaciones web utilizando lenguajes como TypeScript, Java y PHP, y frameworks modernos como React, Next.js, Spring Boot, Express y Laravel. Creo que puedo aportar al grupo brindando soluciones técnicas eficientes, apoyando en el desarrollo del sistema y proponiendo mejoras continuas para alcanzar los objetivos del proyecto con calidad y compromiso.

---

#### **XXXX – Ingeniería de Software - U202219657**

<img src="./assets/RAMIROGUZMAN.png" alt="RAMIROGUZMAN" height="200"/>

XXXX.

---

#### **XXXX – U20221B490**  
<img src="./assets/RAMIROGUZMAN.png" alt="RAMIROGUZMAN" height="200"/>

XXXX.


---


### 1.2. Solution Profile

#### 1.2.1. Nombre del producto
XXXX


#### 1.2.2. Antecedentes y problemática

| Elemento     | Descripción |
|--------------|-------------|
| **Who (Quién)**      | Empresas de transporte de carga, operadores logísticos, despachadores y choferes que necesitan controlar, supervisar y reportar sus operaciones de manera precisa y eficiente. |
| **What (Qué)**       | Plataforma web que digitaliza y automatiza la gestión logística del transporte de carga, incluyendo planificación de servicios, registro de kilometraje, consumo de combustible, evidencia fotográfica, geolocalización y generación de reportes. |
| **Where (Dónde)**    | En oficinas de operación logística, empresas de transporte, y en campo a través de dispositivos móviles utilizados por los choferes. |
| **When (Cuándo)**    | Durante todas las etapas del proceso logístico: planificación previa, ejecución del servicio y post-servicio (análisis e informes). |
| **Why (Por qué)**    | Actualmente, muchas empresas gestionan sus operaciones en papel o Excel, lo cual implica errores, pérdida de información, falta de trazabilidad y un uso ineficiente de los recursos. Esto limita la capacidad de tomar decisiones basadas en datos en tiempo real y reduce la confianza del cliente. |
| **How (Cómo)**       | A través de una plataforma digital que permite crear servicios, registrar recorridos y consumos en tiempo real, visualizar la ubicación GPS de los vehículos, y generar reportes automáticos con métricas clave para mejorar el desempeño operativo. |
| **How Much (Cuánto)**| El acceso a la plataforma se brinda mediante planes de suscripción mensual, dependiendo del número de usuarios, vehículos y funcionalidades activadas por empresa. |



#### 1.2.3. Lean UX Process

##### 1.2.3.1. Lean UX Problem Statement

Co-box logistic es una plataforma creada para digitalizar por completo la gestión del transporte de carga, eliminando procesos manuales y mejorando la eficiencia operativa. Actualmente, muchas empresas aún dependen de formularios físicos, reportes en papel y hojas de cálculo, lo que genera pérdida de tiempo, errores humanos y falta de trazabilidad.

Nuestro mayor desafío es lograr que las empresas adopten esta solución digital como una herramienta confiable, intuitiva y transformadora. Aunque la propuesta tecnológica representa una mejora significativa, algunas compañías pueden mostrarse reacias al cambio por temor a la complejidad o por depender de procesos tradicionales.

¿Cómo podríamos facilitar la adopción de Co-box logistic como una herramienta confiable, simple y efectiva para transformar digitalmente la gestión del transporte de carga y optimizar los procesos logísticos?

##### 1.2.3.2. Lean UX Assumptions


##### 1.2.3.3. Lean UX Hypothesis

Creemos que al ofrecer una plataforma digital integral que centraliza todas las operaciones logísticas, mejoraremos la eficiencia y trazabilidad del transporte de carga. Sabremos que estamos en lo correcto cuando observemos una reducción en errores operativos y una mejora en los tiempos de entrega y gestión.

Creemos que al incluir geolocalización en tiempo real y evidencia fotográfica de entregas, aumentaremos la confianza del cliente final y mejoraremos la transparencia. Sabremos que estamos en lo correcto cuando se reduzcan las incidencias reportadas y aumente la satisfacción de los clientes.

Creemos que al automatizar los reportes e indicadores, facilitaremos la toma de decisiones basada en datos. Sabremos que estamos en lo correcto cuando los gestores logren tomar acciones correctivas más rápidamente y reporten mejoras en sus KPIs logísticos.

Creemos que al ofrecer una interfaz simple, junto con capacitación para los usuarios, incrementaremos la adopción de la plataforma incluso en equipos con poca experiencia digital. Sabremos que estamos en lo correcto cuando disminuya la necesidad de soporte técnico y se mantenga una alta tasa de uso activo.

Creemos que al permitir la gestión de roles y accesos diferenciados, aumentaremos la seguridad y eficiencia interna. Sabremos que estamos en lo correcto cuando se eviten manipulaciones no autorizadas de datos y los usuarios valoren positivamente la organización del sistema.

##### 1.2.3.4. Lean UX Canvas

---

### 1.3. Segmentos Objetivo

Nuestros segmentos objetivos son los siguientes grupos:

Empresas de transporte de carga: Pequeñas y medianas empresas que buscan digitalizar su operación para competir con grandes operadores, mejorar el control interno y ofrecer mayor trazabilidad a sus clientes.

Conductores de unidades de carga: Usuarios de campo encargados de registrar eventos logísticos (kilometraje, combustible, entregas), interactuar con la app y proporcionar evidencia de las operaciones.


## Capítulo II: Requirements & Analysis

### 2.1. Competidores
Competidor 1: Samsara
Samsara es una plataforma de IoT y telemática para gestión de flotas que ofrece GPS en tiempo real, registro automático de odómetro y combustible, programación de rutas, alertas de mantenimiento y reportes detallados de eficiencia operativa. Está presente en LATAM y cuenta con integraciones fáciles de desplegar en vehículos.

Competidor 2: Fleet Complete
Fleet Complete proporciona soluciones de rastreo GPS, monitoreo de consumo de combustible, gestión de conductores y planificación de servicios. Su enfoque está en la eficiencia de la operación diaria, con dashboards personalizables y API para conectar con ERPs.

Competidor 3: Sendd
Sendd es una startup peruana de última milla que permite programar rutas de entrega, hacer seguimiento en tiempo real y capturar prueba de entrega (fotos, firmas). Aunque no controla combustible, su fortaleza está en la experiencia local y en la usabilidad de su app móvil.

#### 2.1.1. Análisis competitivo

### Competitive Analysis Landscape

**¿Por qué llevar a cabo este análisis?**  
Para identificar cómo otras soluciones gestionan rutas, odómetro, combustible, prueba fotográfica y reportes, y descubrir oportunidades de diferenciación para **CO-BOX LOGISTICS**.

---

### Comparativa de Productos

| Productos            | **CO-BOX Logistic**                                                                 | **Samsara**                                                                 | **Fleet Complete**                                                            | **Sendd**                                                                 |
|----------------------|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------|--------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Perfil**           | Programación de servicios, captura de odómetro (foto), registro de combustible y geolocalización, reportes web & móvil. | IoT + telemática: GPS en tiempo real, odómetro automático, control de combustible, alertas de mantenimiento. | Rastreo GPS, monitoreo de combustible, gestión de conductores, planificación de rutas. | Rutas de última milla, seguimiento en tiempo real, proof of delivery (foto/firmas). |
| **Ventaja competitiva** | Flujo completo: unifica foto del odómetro, combustible y ruta en un solo proceso adaptado a transporte de carga. | Madurez de producto y hardware plug-and-play fácil de instalar. | Dashboards personalizables y API robusta para integraciones. | Experiencia local en Perú y UX optimizada para conductores. |

---

### Perfil de Marketing

| Aspecto                   | **CO-BOX Logistic**                                                              | **Samsara**                                   | **Fleet Complete**                                         | **Sendd**                                                 |
|---------------------------|----------------------------------------------------------------------------------|-----------------------------------------------|-------------------------------------------------------------|------------------------------------------------------------|
| **Mercado Objetivo**      | Empresas de transporte de carga refrigerada o seca, supermercados, laboratorios y distribución general. | Flotas medianas y grandes de transporte en LATAM. | Flotas corporativas que requieren integración con ERPs.    | Negocios de e‑commerce y paquetería en Lima y alrededores. |
| **Estrategias de Marketing** | Marketing B2B digital, demos gratuitas, alianzas con talleres y gremios de transporte. | Ferias de logística y partnerships con fabricantes de vehículos. | Partnerships con proveedores de ERP y consultoras.         | Promociones locales y boca a boca en cooperativas de delivery. |

---

### Perfil de Producto

| Aspecto                 | **CO-BOX Logistic**                                         | **Samsara**                                                  | **Fleet Complete**                                                  | **Sendd**                                               |
|-------------------------|-------------------------------------------------------------|---------------------------------------------------------------|---------------------------------------------------------------------|----------------------------------------------------------|
| **Productos & Servicios** | Programación de viajes, captura de odómetro, combustible y temperatura, reportes analíticos. | GPS tracking, scheduling, alertas de mantenimiento, reporte de combustible. | Rastreo GPS, monitoreo de combustible, gestión de conductores, planificación de rutas. | Prueba de entrega con foto/firmas, seguimiento en ruta. |
| **Precios & Costos**     | USD 25/equipo/mes + USD 100 instalación única.             | Desde USD 30/vehículo/mes, hardware incluido.                 | Desde USD 28/vehículo/mes, descuentos anuales.                      | USD 5/entrega + comisión, sin hardware ni suscripción fija. |
| **Canales de distribución** | Web & App móvil (iOS/Android).                            | Web, App móvil y dispositivo plug‑and‑play.                   | Web, App móvil e integraciones API.                                 | App móvil y portal web liviano.                         |

---

### Análisis SWOT

|                        | **CO-BOX Logistic**                                          | **Samsara**                                    | **Fleet Complete**                                 | **Sendd**                                      |
|------------------------|--------------------------------------------------------------|------------------------------------------------|---------------------------------------------------|------------------------------------------------|
| **Fortalezas**         | Integración odómetro + combustible + geolocalización en un solo sistema. | Hardware plug‑and‑play y ecosistema IoT completo. | Dashboards a medida y API robusta.                | Proof of delivery con foto y firmas.          |
| **Debilidades**        | MVP en fase temprana; base de usuarios pequeña.              | Costo inicial alto y curva de configuración.    | Requiere integración técnica y tiempo de onboarding. | No registra combustible ni odómetro.          |
| **Oportunidades**      | Integrar alertas predictivas y expandir a flotas generales.  | Añadir módulos de foto del odómetro y proof of delivery. | Ofrecer paquetes para pymes sin ERP.              | Expandir a gestión de combustible.            |
| **Amenazas**           | Competidores consolidados añadiendo funciones similares.     | Startups más ágiles con UX simplificado.       | Soluciones todo‑en‑uno emergentes.                | Plataformas integrales en LATAM.              |

---

### 2.2. Entrevistas

#### 2.2.1 Diseño de entrevistas
#### 2.2.2 Registro de entrevistas
#### 2.2.3 Análisis de entrevistas

Segmento 1: Gerentes/encargados de flota

¿Cuál es su rol y responsabilidades principales?
¿Cuántos vehículos administra y qué tipos de rutas realiza?
¿Cómo registra hoy el odómetro y el consumo de combustible?
¿Utiliza software o formularios en papel para programar y reportar servicios?
¿Qué problemas más frecuentes encuentra en la gestión de rutas y consumo?
¿Con qué frecuencia revisa los reportes de eficiencia de su flota?
¿Qué datos le gustaría recibir automáticamente después de cada viaje?
¿Cómo impactan las discrepancias de kilometraje o combustible en su operación diaria?
¿Qué tan dispuesto estaría a adoptar una app que integre fotos de odómetro y reportes automáticos?
¿Cuál es el presupuesto mensual aproximado que invertiría en este tipo de herramienta?
Segmento 2: Conductores/operadores de ruta

¿Cuál es su experiencia conduciendo rutas de carga?
¿Cómo registra actualmente el inicio y fin de cada viaje?
¿Toma fotos del odómetro o anota el kilometraje manualmente?
¿Cuánto tiempo le toma completar el registro de combustible y odómetro hoy?
¿Qué dificultades tiene al usar apps o formularios para reportar su viaje?
¿Preferiría usar una app móvil con botones claros para “Iniciar”, “Foto odómetro” y “Fin”?
¿Qué tan útil le resultaría una geolocalización automática de cada parada?
¿Le preocupa la precisión del kilometraje que ingresa?
¿Qué comentarios o sugerencias tendría para que la app sea fácil de usar en ruta?
¿Qué incentivos podrían motivarlo a completar su reporte diario a tiempo?


### 2.3. Needfinding

#### 2.3.1. User Personas

Un user persona es una representación ficticia y detallada de un grupo de usuarios que comparten características, necesidades y comportamientos similares. Se utiliza para comprender mejor las motivaciones, objetivos y problemas de los usuarios, ayudando a diseñar productos o servicios que satisfagan sus expectativas. El user persona se basa en datos reales obtenidos de investigaciones y entrevistas, pero se presenta de manera resumida para facilitar la toma de decisiones en el diseño. A continuacón presentamos las User Personas de nuestro proyecto Coo-box logistic:

Segmento 1: Gestor de flota
imagen
Segmento 2: Conductor de vehiculos de transporte
imagen


#### 2.3.2. User Task Matrix

| Tareas / User Persona     | Jorge Perez (Frec.) | Jorge Perez (Imp.) | Darikson Brito (Frec.) | Darikson Brito (Imp.) |
|---------------------------|---------------------|---------------------|-------------------------|------------------------|
| **Planificar rutas**      | Alta                | Alta                | N/A                     | N/A                    |
| **Coordinar entregas**    | Alta                | Alta                | Media                   | Alta                   |
| **Registrar kilometraje** | Media               | Alta                | Alta                    | Alta                   |
| **Reportar combustible**  | Media               | Alta                | Alta                    | Alta                   |
| **Consolidar datos**      | Alta                | Alta                | N/A                     | N/A                    |
| **Generar reportes**      | Media               | Alta                | N/A                     | N/A                    |
| **Foto del odómetro**     | Baja                | Media               | Media                   | Alta                   |
| **Usar apps móviles**     | Media               | Alta                | Baja                    | Alta                   |
| **Verificar entregas**    | Alta                | Alta                | Media                   | Alta                   |
| **Atender reclamos**      | Media               | Alta                | Baja                    | Media                  |

---

### Conclusiones:
- Ambos valoran **registrar kilometraje y consumo de combustible**.
- **Jorge Perez** (frecuente e importante) se enfoca en **análisis y consolidación**.
- **Darikson Brito** (frecuente e importante) se enfoca en **ejecución operativa**.
- La app debe enfocarse en **tareas compartidas y críticas**, optimizando especialmente la experiencia de registro de kilometraje, combustible y verificación de entregas.


#### 2.3.3. Empathy Maps
El Empathy Mapping es una herramienta utilizada para comprender mejor a los usuarios o clientes al explorar sus pensamientos, sentimientos, comportamientos y necesidades. Se organiza en secciones como ¿Qué escucha?, ¿Qué ve?, ¿Qué piensa y siente?, ¿Qué dice y hace?, Frustraciones y Motivaciones. Ayuda a los equipos de diseño a crear soluciones más alineadas con las experiencias y perspectivas de los usuarios. A continuación los mapas de empatía de los dos segmento de nuestro proyecto Coo-box Logistic:

Segmento: Gestor de flota:

Segmento: Conductor de vehiculos de transporte


#### 2.3.4. As-is Scenario Mapping


---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

Segmento 1: Gestores de Flota
Segmento 2: Conductores de Transporte


### 3.2. User Stories

## Epics

| Epic ID   | Título                   | Descripción                                                                 |
|-----------|--------------------------|------------------------------------------------------------------------------|
| EP01      | Gestión de flota         | Como gestor quiero tener control total de las unidades de transporte, rutas y mantenimientos. |
| EP02      | Gestión de entregas      | Como conductor quiero registrar y visualizar mis entregas para tener claridad en mis tareas. |
| EP03      | Gestión de incidencias   | Como conductor o gestor quiero reportar y visualizar incidencias para actuar rápidamente. |
| EP04      | Gestión de mantenimiento | Como gestor quiero planificar y llevar control de los mantenimientos de cada vehículo. |
| EP05      | Gestión de indicadores   | Como gestor quiero ver reportes e indicadores automáticos para evaluar el desempeño diario. |
| EP-LP     | Sitio web estático       | Como visitante quiero conocer los servicios y características de la plataforma para decidir si contratar. |
| EP-API    | API RESTful              | Como desarrollador quiero acceder a los servicios mediante endpoints para integrarlos con otras aplicaciones. |

---

## User Stories

### EP01 - Gestión de flota

- **US-01**: Consultar rutas asignadas  
  _Como gestor, quiero conocer las rutas asignadas a cada unidad para supervisar su cumplimiento operativo._  
  **Criterios**: Acceso al módulo de unidades → selección de unidad → información de ruta, horarios y destinos.

- **US-02**: Asignar unidades a rutas  
  _Como gestor, quiero asignar unidades de transporte a rutas específicas para controlar la operación._  
  **Criterios**: Acceso a sección de asignaciones → selección de ruta y unidad → registro exitoso.

- **US-03**: Actualizar estado de unidad  
  _Como gestor, quiero marcar una unidad como disponible o en mantenimiento._  
  **Criterios**: Selección de unidad → modificación de estado → actualización visible.

- **US-04**: Consultar historial de movimientos  
  _Como gestor, quiero revisar el historial de movimientos de una unidad._  
  **Criterios**: Acceso a detalles de unidad → historial con fechas y tipos de movimiento.

---

### EP02 - Gestión de entregas

- **US-05**: Consultar entregas asignadas  
  _Como conductor, quiero conocer las entregas asignadas del día._  
  **Criterios**: Login → acceso a entregas → detalles con hora, cliente y dirección.

- **US-06**: Registrar evidencia de entrega  
  _Como conductor, quiero dejar constancia de entregas mediante evidencia._  
  **Criterios**: Entrega finalizada → adjuntar evidencia → registro con fecha, hora, ubicación.

- **US-07**: Revisar entregas completadas  
  _Como conductor, quiero consultar mis entregas pasadas._  
  **Criterios**: Acceso a módulo → filtro por fecha → visualización de entregas anteriores.

- **US-08**: Registrar inicio de ruta  
  _Como conductor, quiero confirmar el inicio de mi ruta._  
  **Criterios**: Entregas asignadas → inicio de jornada → registro de hora de salida.

---

### EP03 - Gestión de incidencias

- **US-09**: Reportar incidente  
  _Como conductor, quiero reportar incidentes durante la entrega._  
  **Criterios**: Reporte con evidencia → notificación automática al responsable.

- **US-10**: Consultar incidencias  
  _Como gestor, quiero revisar incidencias activas._  
  **Criterios**: Acceso a información → visualización con unidad, fecha y gravedad.

- **US-11**: Filtrar incidencias  
  _Como gestor, quiero filtrar incidencias por gravedad._  
  **Criterios**: Aplicación de filtro → lista de incidencias relevantes.

- **US-12**: Revisar historial de incidencias  
  _Como gestor, quiero analizar incidencias pasadas._  
  **Criterios**: Filtro por fechas → visualización con estado de resolución.

---

### EP04 - Gestión de mantenimiento

- **US-13**: Programar mantenimiento  
  _Como gestor, quiero definir mantenimientos periódicos._  
  **Criterios**: Selección de unidad → definición de frecuencia → agenda programada.

- **US-14**: Registrar mantenimiento  
  _Como técnico, quiero documentar mantenimiento realizado._  
  **Criterios**: Documentación → almacenamiento en historial.

- **US-15**: Consultar mantenimientos próximos  
  _Como gestor, quiero conocer las próximas fechas de mantenimiento._  
  **Criterios**: Consulta en calendario → fechas por unidad.

- **US-16**: Recibir alertas de mantenimiento  
  _Como gestor, quiero recibir alertas de mantenimiento próximo._  
  **Criterios**: Faltan 3 días → alerta automática.

---

### EP05 - Gestión de indicadores

- **US-17**: Generar reporte semanal  
  _Como gestor, quiero ver reportes semanales de entregas._  
  **Criterios**: Semana concluida → estadísticas de cumplimiento por conductor.

- **US-18**: Evaluar eficiencia por unidad  
  _Como gestor, quiero conocer rendimiento por unidad._  
  **Criterios**: Acceso a datos → análisis → métricas de eficiencia.

- **US-19**: Comparar desempeño entre conductores  
  _Como gestor, quiero comparar conductores._  
  **Criterios**: Período seleccionado → ranking con métricas.

- **US-20**: Monitorear alertas críticas  
  _Como gestor, quiero visualizar alertas críticas del sistema._  
  **Criterios**: Acceso a panel → alertas de mayor prioridad destacadas.

---

### EP-LP - Sitio web estático

- **US-21**: Consultar información de servicios  
- **US-22**: Solicitar demostración  
- **US-23**: Consultar planes y precios  
- **US-24**: Solicitar asistencia  
- **US-25**: Consultar casos de éxito

Cada historia de esta sección sigue una estructura con 2 escenarios: interacción exitosa y fallida (cuando aplica), asegurando una experiencia de usuario clara y consistente.

---

### EP-API - API RESTful

- **TS-01**: Autenticación API (con JWT)
- **TS-02**: Gestión de unidades vía API
- **TS-03**: Gestión de entregas vía API
- **TS-04**: Gestión de incidencias vía API
- **TS-05**: Consulta de estadísticas vía API

Cada historia técnica contempla:
- Escenario de éxito (200 o 201)
- Escenario de error (401, 400)
- Casos de expiración, validación o fallas lógicas

---

## Notas adicionales

- El **Epic ID** está relacionado con las historias mediante el campo "Relacionada con (Epic ID)".
- Se sugiere utilizar estos IDs como base para gestión en herramientas ágiles como **Jira**, **ClickUp**, **Azure DevOps** o **Notion**.



### 3.3. Impact Map


  

### 3.4. Product Backlog


| #  | User Story ID | Título                                      | Descripción                                                                                   | Story Points |
|----|---------------|---------------------------------------------|-----------------------------------------------------------------------------------------------|--------------|
| 1  | US-05         | Consultar entregas pendientes               | Como conductor, quiero ver las entregas asignadas del día, para planificar mi ruta.           | 8            |
| 2  | US-01         | Visualizar rutas asignadas                  | Como gestor, quiero ver las rutas asignadas a cada unidad, para hacer seguimiento efectivo.   | 8            |
| 3  | US-09         | Reportar incidente durante entrega          | Como conductor, quiero reportar un incidente, para alertar al gestor y agilizar la solución.  | 8            |
| 4  | US-13         | Programar mantenimiento preventivo          | Como gestor, quiero programar mantenimientos regulares, para evitar fallas inesperadas.       | 8            |
| 5  | US-17         | Ver reporte semanal de entregas             | Como gestor, quiero ver un reporte semanal por conductor, para evaluar su rendimiento.        | 5            |
| 6  | US-03         | Registrar disponibilidad de unidad          | Como gestor, quiero marcar una unidad como disponible o en mantenimiento, para gestionar eficientemente. | 5     |
| 7  | US-08         | Confirmar inicio de ruta                    | Como conductor, quiero confirmar el inicio de mi ruta, para registrar la hora de salida.      | 5            |
| 8  | US-12         | Visualizar historial de incidencias         | Como gestor, quiero revisar el historial de incidencias pasadas, para tomar decisiones preventivas. | 5       |
| 9  | US-04         | Visualizar historial de movimientos         | Como gestor, quiero ver el historial de movimientos de una unidad, para rastrear sus actividades. | 5         |
| 10 | US-16         | Notificación de mantenimiento pendiente     | Como gestor, quiero recibir alertas de mantenimiento próximo, para actuar con anticipación.   | 5            |
| 11 | US-07         | Visualizar entregas completadas             | Como conductor, quiero ver un historial de entregas completadas, para llevar control de mis actividades. | 5     |
| 12 | US-10         | Visualizar estado de incidencias            | Como gestor, quiero ver un listado de incidencias activas, para tomar acción rápidamente.     | 5            |
| 13 | US-14         | Registrar mantenimiento realizado           | Como técnico, quiero registrar el mantenimiento con detalles, para dejar constancia de lo realizado. | 3      |
| 14 | US-19         | Comparar rendimiento entre conductores      | Como gestor, quiero comparar eficiencia entre conductores, para fomentar buenas prácticas.    | 3            |
| 15 | US-06         | Registrar entrega con evidencia             | Como conductor, quiero registrar entregas con foto y firma, para validar su cumplimiento.     | 3            |
| 16 | US-11         | Filtrar incidencias por gravedad            | Como gestor, quiero filtrar las incidencias según su gravedad, para priorizar las más urgentes. | 3         |
| 17 | US-02         | Asignar unidades a rutas                    | Como gestor, quiero asignar unidades de transporte a rutas específicas, para controlar la operación. | 2        |
| 18 | US-18         | Ver eficiencia por unidad                   | Como gestor, quiero ver rendimiento por unidad, para tomar decisiones sobre el uso de la flota. | 2          |
| 19 | US-15         | Ver próximas fechas de mantenimiento        | Como gestor, quiero ver en un calendario las fechas de mantenimiento, para no olvidar los programados. | 2      |
| 20 | US-20         | Visualizar alertas críticas en dashboard    | Como gestor, quiero ver alertas prioritarias en el dashboard, para atender eventos críticos.  | 1            |
| 21 | US-21         | Visualizar información de servicio          | Como visitante, quiero conocer los servicios de gestión de flotas ofrecidos, para evaluar si satisface mis necesidades. | 3 |
| 22 | US-22         | Registrar solicitud de demo                 | Como visitante, quiero solicitar una demostración del sistema, para conocer la plataforma antes de contratar. | 5     |
| 23 | US-23         | Visualizar planes y precios                 | Como visitante, quiero conocer los diferentes planes disponibles y sus precios, para seleccionar el más adecuado. | 3   |
| 24 | US-24         | Contactar con soporte                       | Como visitante, quiero contactar con el equipo de soporte, para resolver dudas sobre el servicio. | 2        |
| 25 | US-25         | Visualizar casos de éxito                   | Como visitante, quiero ver testimonios y casos de éxito, para evaluar la efectividad del sistema en casos reales. | 5   |
| 26 | TS-01         | Autenticación API                           | Como desarrollador, quiero implementar un sistema de autenticación JWT, para asegurar el acceso a la API. | 8     |
| 27 | TS-02         | Endpoints de unidades                       | Como desarrollador, quiero implementar endpoints CRUD para unidades de transporte, para gestionar la flota desde aplicaciones externas. | 5 |
| 28 | TS-03         | Endpoints de entregas                       | Como desarrollador, quiero implementar endpoints para gestionar entregas desde apps móviles.   | 5            |
| 29 | TS-04         | Endpoints de incidencias                    | Como desarrollador, quiero implementar endpoints para gestionar incidencias.                  | 5            |
| 30 | TS-05         | Endpoints de estadísticas                   | Como desarrollador, quiero implementar endpoints para obtener métricas y estadísticas.        | 8            |

---

**Notas:**
- Las historias están priorizadas del 1 al 30 según valor al usuario y esfuerzo estimado.
- El campo **Story Points** sigue una escala tipo Fibonacci: 1, 2, 3, 5, 8.
- Puedes usar esta tabla como base para tu tablero en herramientas como **Jira**, **Trello**, **Asana**, **Azure DevOps**, o una hoja de cálculo.



---
