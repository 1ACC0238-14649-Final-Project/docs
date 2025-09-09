# <p align="center">Informe de TB1</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" />
</div>

<p align="center">Ingeniería de Software</p>
<p align="center">Aplicaciones para Dispositivos Móviles - 14649</p>
<p align="center"><strong>Docente:</strong> David Gerardo Quevedo Velasco</p>
<p align="center"><strong>Startup:</strong> GigU</p>
<p align="center"><strong>Producto:</strong> GigU</p>

# Team members:

| Nombre                            | Código     |
| --------------------------------- | ---------- |
|  Irving Washington Allcca Guerrero| U202213241 |
| Diego Alonso Cacho Seminario      | U202223990 |
| Adrian Ricardo Donayre Alvarez    | U202310187 |
| Mariano Moises Oblitas Davila     | U202310222 |
| Carlos Fredy Fernandez Camayo     | U202320083 |


<p align="center"><strong>Ciclo 2025-20</strong></p>

# Registro de versiones del informe
| Versión | Fecha | Autores | Descripción |
| :---- | :---- | :---- | :---- |
| TB1 | 18/09/2025 | Irving Allcca Diego Cacho Adrian Donayre Mariano Oblitas Carlos Fernandez | Capítulo I: Presentación Capítulo II: Requirements Elicitation & Analysis Capítulo III: Requirements Specification Capítulo IV: Solution Software Design Avance de Conclusiones, Bibliografía y Anexos |

September 8, 2025


# Student Outcomes

ABET – EAC - Student Outcome 7: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

| Criterio específico | Acciones realizadas | Conclusiones |
| ----- | ----- | ----- |
| **7.c1. Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de ingeniería de software** | **Irving Allcca** TB1:  <br>**Diego Cacho** TB1:  <br>**Adrian Donayre** TB1:  <br>**Mariano Oblitas** TB1:  <br>**Carlos Fernandez** TB1:  |  |
| **7.c2. Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de tecnologías de ingeniería de software** | **Irving Allcca** TB1:  <br>**Diego Cacho** TB1:  <br>**Adrian Donayre** TB1:  <br>**Mariano Oblitas** TB1:  <br>**Carlos Fernandez** TB1: |  |


### Tabla de Contenidos

#### [Capítulo I: Presentación](#capítulo-i-presentación)
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

#### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

#### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

#### [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
    - [4.1.3.2. Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
    - [4.1.3.3. Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
    - [4.2.X.1. Domain Layer](#42x1-domain-layer)
    - [4.2.X.2. Interface Layer](#42x2-interface-layer)
    - [4.2.X.3. Application Layer](#42x3-application-layer)
    - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
    - [4.2.X.5. Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.X.6. Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1. Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2. Database Design Diagram](#42x62-bounded-context-database-design-diagram)

#### [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Product Design](#51-product-design)
  - [5.1.1. Style Guidelines](#511-style-guidelines)
    - [5.1.1.1. General Style Guidelines](#5111-general-style-guidelines)
  - [5.1.2. Information Architecture](#512-information-architecture)
    - [5.1.2.1. Organization Systems](#5121-organization-systems)
    - [5.1.2.2. Labelling Systems](#5122-labelling-systems)
    - [5.1.2.3. SEO Tags and Meta Tags](#5123-seo-tags-and-meta-tags)
    - [5.1.2.4. Searching Systems](#5124-searching-systems)
    - [5.1.2.5. Navigation Systems](#5125-navigation-systems)
  - [5.1.3. Landing Page UI Design](#513-landing-page-ui-design)
    - [5.1.3.1. Wireframe](#5131-landing-page-wireframe)
    - [5.1.3.2. Mock-up](#5132-landing-page-mock-up)
  - [5.1.4. Mobile Applications UX/UI Design](#514-mobile-applications-uxui-design)
    - [5.1.4.1. Wireframes](#5141-mobile-applications-wireframes)
    - [5.1.4.2. Wireflow Diagrams](#5142-mobile-applications-wireflow-diagrams)
    - [5.1.4.3. Mock-ups](#5143-mobile-applications-mock-ups)
    - [5.1.4.4. User Flow Diagrams](#5144-mobile-applications-user-flow-diagrams)
    - [5.1.4.5. Prototyping](#5145-mobile-applications-prototyping)

#### [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)

* [6.1. Software Configuration Management](#61-software-configuration-management)

  * [6.1.1. Development Environment Configuration](#611-software-development-environment-configuration)
  * [6.1.2. Source Code Management](#612-source-code-management)
  * [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  * [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
* [6.2. Landing Page & Mobile Application Implementation](#62-landing-page--mobile-application-implementation)

  * [6.2.0. Sprint 0 – Primer Hito (Semana 4)](#620-sprint-0--primer-hito-semana-4)

    * [6.2.0.1. Sprint Planning 0](#6201-sprint-planning-0)
    * [6.2.0.2. Sprint Backlog 0](#6202-sprint-backlog-0)
    * [6.2.0.3. Development Evidence](#6203-development-evidence-for-sprint-review)
    * [6.2.0.4. Execution Evidence](#6204-execution-evidence-for-sprint-review)
    * [6.2.0.5. Services Documentation](#6205-services-documentation-evidence-for-sprint-review)
    * [6.2.0.6. Deployment Evidence](#6206-software-deployment-evidence-for-sprint-review)
    * [6.2.0.7. Team Collaboration Insights](#6207-team-collaboration-insights-during-sprint)
  * [6.2.1. Sprint 1 – Segundo Hito (Semana 7)](#621-sprint-1--segundo-hito-semana-7)

    * [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
    * [6.2.1.2. Sprint Backlog 1](#6212-sprint-backlog-1)
    * [6.2.1.3. Development Evidence](#6213-development-evidence-for-sprint-review)
    * [6.2.1.4. Testing Suite Evidence](#6214-testing-suite-evidence-for-sprint-review)
    * [6.2.1.5. Execution Evidence](#6215-execution-evidence-for-sprint-review)
    * [6.2.1.6. Services Documentation](#6216-services-documentation-evidence-for-sprint-review)
    * [6.2.1.7. Deployment Evidence](#6217-software-deployment-evidence-for-sprint-review)
    * [6.2.1.8. Team Collaboration Insights](#6218-team-collaboration-insights-during-sprint)
  * [6.2.2. Sprint 2 – Tercer Hito (Semana 12)](#622-sprint-2--tercer-hito-semana-12)

    * [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
    * [6.2.2.2. Sprint Backlog 2](#6222-sprint-backlog-2)
    * [6.2.2.3. Development Evidence](#6223-development-evidence-for-sprint-review)
    * [6.2.2.4. Testing Suite Evidence](#6224-testing-suite-evidence-for-sprint-review)
    * [6.2.2.5. Execution Evidence](#6225-execution-evidence-for-sprint-review)
    * [6.2.2.6. Services Documentation](#6226-services-documentation-evidence-for-sprint-review)
    * [6.2.2.7. Deployment Evidence](#6227-software-deployment-evidence-for-sprint-review)
    * [6.2.2.8. Team Collaboration Insights](#6228-team-collaboration-insights-during-sprint)
  * [6.2.3. Sprint 3 – Cuarto Hito (Semana 15)](#623-sprint-3--cuarto-hito-semana-15)

    * [6.2.3.1. Sprint Planning 3](#6231-sprint-planning-3)
    * [6.2.3.2. Sprint Backlog 3](#6232-sprint-backlog-3)
    * [6.2.3.3. Development Evidence](#6233-development-evidence-for-sprint-review)
    * [6.2.3.4. Testing Suite Evidence](#6234-testing-suite-evidence-for-sprint-review)
    * [6.2.3.5. Execution Evidence](#6235-execution-evidence-for-sprint-review)
    * [6.2.3.6. Services Documentation](#6236-services-documentation-evidence-for-sprint-review)
    * [6.2.3.7. Deployment Evidence](#6237-software-deployment-evidence-for-sprint-review)
    * [6.2.3.8. Team Collaboration Insights](#6238-team-collaboration-insights-during-sprint)
* [6.3. Validation Interviews](#63-validation-interviews)

  * [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  * [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  * [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
* [6.4. Video About-the-Product](#64-video-about-the-product)

#### [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

#### [Video About-the-Team](#video-about-the-team)

#### [Bibliografía](#bibliografía)

#### [Anexos](#anexos)


---

# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Somos GigU, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con la innovación tecnológica y la creación de oportunidades para nuestra comunidad universitaria.

Nuestra misión es ofrecer una plataforma que permita a los estudiantes universitarios ofrecer sus habilidades y conocimientos a través de servicios freelance, generando ingresos adicionales mientras desarrollan experiencia profesional en su campo.

Nuestra visión es convertirnos en la principal plataforma de trabajo freelance para estudiantes en Perú y Latinoamérica, facilitando la conexión entre talento joven y clientes que buscan soluciones creativas y eficientes en múltiples áreas como desarrollo de software, diseño, tutorías, gestión empresarial, entre otros.

Nuestro producto principal es GigU, una plataforma que conecta a estudiantes con clientes interesados en servicios freelance. Los freelancers pueden publicar sus servicios, definir tarifas y cotizar precios de manera inteligente con base en factores como el tiempo estimado de trabajo, la complejidad del servicio y las tarifas del mercado. La plataforma también proporciona comunicación con clientes y procesamiento seguro de pagos.

GigU no solo ayuda a los estudiantes a generar ingresos mientras estudian, sino que también les permite desarrollar habilidades clave como la gestión del tiempo, la negociación, la resolución de problemas y el trato con clientes reales, preparándose así para la vida profesional.

Además, con GigU, los estudiantes tienen una forma flexible, accesible y efectiva de adquirir experiencia laboral y construir una red de clientes y contactos profesionales desde el inicio de su carrera.

### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
##### **¿Cuál es el problema?**  
Muchos estudiantes universitarios enfrentan serias dificultades para generar ingresos y adquirir experiencia profesional mientras cursan sus estudios. Esta carencia de oportunidades laborales adecuadas no solo limita su independencia económica, sino también el desarrollo temprano de habilidades prácticas y su inserción competitiva en el mercado laboral. Según datos del Ministerio de Educación del Perú (2020), aproximadamente el 20% de los estudiantes universitarios de entre 17 y 21 años combina estudios y trabajo de manera simultánea, reflejando que una parte importante de la población estudiantil se ve obligada a buscar ingresos mientras completa su formación. Sin embargo, a pesar de contar con talentos y conocimientos valiosos, la mayoría no dispone de una plataforma accesible, segura y adaptada que les permita ofrecer sus servicios de forma organizada y profesional, especialmente bajo la modalidad freelance.

##### **¿Cuándo ocurre el problema?**  
El problema se presenta a lo largo de toda la etapa universitaria, con mayor énfasis a partir del segundo o tercer año de carrera, cuando los estudiantes ya han adquirido capacidades técnicas, académicas o creativas que podrían ser aplicadas en el ámbito laboral. La necesidad de generar ingresos se intensifica en periodos críticos como matrículas, proyectos finales o gastos personales, momentos en los que la presión financiera se convierte en un factor determinante para su permanencia y rendimiento académico.

##### **¿Dónde ocurre el problema?**  
Esta problemática es evidente en el contexto universitario peruano y latinoamericano, especialmente en instituciones donde las políticas de empleabilidad son limitadas o inexistentes, y donde los programas de prácticas preprofesionales o los vínculos con el mercado freelance son insuficientes o inaccesibles. Asimismo, en el entorno digital persiste la falta de una plataforma centralizada y especializada que facilite a los estudiantes la oferta de servicios freelance de manera organizada, validada y segura.

##### **¿A quién afecta el problema?**  
El problema impacta directamente a estudiantes universitarios que buscan generar ingresos, adquirir experiencia laboral temprana y construir un portafolio real antes de egresar. Esta situación también afecta a microempresas, emprendedores y particulares que requieren servicios profesionales accesibles, confiables y de calidad, y que a menudo no logran encontrar talento joven disponible y verificado en su entorno inmediato.

##### **¿Por qué sucede el problema?**  
El problema radica en la falta de plataformas diseñadas específicamente para conectar estudiantes con clientes potenciales, considerando sus limitaciones de tiempo, experiencia y recursos. Las plataformas freelance tradicionales imponen barreras de entrada significativas, como comisiones elevadas, competencia global desproporcionada y escasa validación académica de perfiles, lo que desalienta la participación de estudiantes y perpetúa su informalidad laboral.

##### **¿Cómo sucede el problema?**  
En ausencia de alternativas formales y especializadas, los estudiantes optan por ofrecer sus servicios a través de redes sociales, contactos personales o plataformas genéricas que no garantizan seguridad, visibilidad ni condiciones laborales justas. Esta informalidad expone a los estudiantes a malas prácticas, incumplimientos de pago, sobreexplotación de tiempo y escaso reconocimiento de sus capacidades, lo que frecuentemente deriva en frustración, desmotivación y experiencias laborales negativas.

##### **¿Cuán grande es el impacto de este problema?**  
El impacto es considerable tanto en el plano individual como en el social. En el Perú, el 85.3% de jóvenes menores de 25 años trabaja en condiciones de informalidad, lo que evidencia una fuerte precarización del empleo juvenil y una limitada protección social (INEI, 2023). Además, la tasa de desempleo en jóvenes de 14 a 24 años alcanza el 10.1%, superando al promedio nacional y posicionando a este grupo como uno de los más vulnerables del mercado laboral (INEI, 2023). Esta realidad afecta directamente su desarrollo personal y profesional, retrasa su independencia económica y limita su proyección laboral futura.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
En el contexto universitario peruano, los estudiantes enfrentan grandes desafíos para insertarse en el mercado laboral mientras cursan sus estudios. La mayoría se enfrenta a condiciones de informalidad o desempleo, lo cual limita su desarrollo profesional desde una etapa temprana.  
 Hemos observado que no existen plataformas efectivas y especializadas que conectan directamente a estudiantes universitarios con oportunidades laborales formales, flexibles y alineadas a sus carreras, lo cual perpetúa la falta de experiencia profesional al egresar.  
 ¿Cómo podemos ayudar a los estudiantes universitarios en el Perú a insertarse en el mercado laboral de forma formal, flexible y segura durante su etapa académica, permitiéndoles desarrollar habilidades prácticas, generar ingresos y mejorar su empleabilidad desde los primeros ciclos?
 
#### 1.2.2.2. Lean UX Assumptions

¿Quién es el usuario?  
 Estudiantes universitarios peruanos, principalmente entre los 17 y 24 años, que buscan generar ingresos y experiencia profesional compatible con sus horarios académicos.

¿Dónde encaja nuestro producto en su vida?  
Gigu se integra como una herramienta esencial para complementar su formación académica con experiencia laboral real, generar ingresos, y conectarse con profesionales, clientes o mentores, sin sacrificar su rendimiento académico.

¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

* Posible desconfianza hacia la formalidad de las oportunidades.  
   → Solución: verificación de empleadores/clientes y contratos inteligentes.

* Dificultad para encontrar tareas relacionadas a su carrera.  
   → Solución: sistema de categorización inteligente por carreras y habilidades.

* Baja retención o uso esporádico.  
   → Solución: gamificación, badges y recompensas por participación activa.

¿Cómo y cuándo es usado nuestro producto?  
El producto es usado principalmente durante los tiempos libres o entre clases. Los estudiantes lo utilizan para buscar encargos, postular a proyectos freelance, recibir feedback, y conectarse con mentores o empresas pequeñas que necesitan apoyo técnico o creativo.

¿Qué características son importantes?

* Perfiles profesionales con historial académico y de proyectos.

* Oportunidades freelance o part-time verificadas.

* Inteligencia artificial para emparejar tareas con habilidades.

* Retroalimentación entre estudiantes y clientes.

* Panel de seguimiento de experiencia acumulada.

* Integración con LinkedIn y portafolios.

* Sistema de reputación y badges.

* Chat seguro entre clientes y postulantes.

* Acceso a micro cursos gratuitos recomendados según proyectos.

¿Cómo debe verse nuestro producto y cómo comportarse?  
 Debe tener un diseño moderno, amigable y responsivo. Su comportamiento debe ser fluido, con tiempos de carga bajos y navegación clara. La experiencia de usuario debe motivar la interacción constante, con notificaciones relevantes y recomendaciones que generen valor real para el usuario.

#### 1.2.2.3. Lean UX Hypothesis Statements
* Creemos que al conectar estudiantes universitarios con oportunidades laborales compatibles con sus carreras y horarios, lograremos que desarrollen experiencia profesional antes de egresar.  
   Sabremos que hemos tenido éxito cuando más del 50% de los usuarios activos complete al menos una tarea remunerada en su primer mes.

* Creemos que implementar un sistema de reputación y gamificación aumentará la participación y compromiso con la plataforma.  
   Sabremos que hemos tenido éxito cuando el tiempo promedio de uso semanal supere los 45 minutos por usuario activo.

* Creemos que ofrecer oportunidades relacionadas a sus habilidades y carrera aumentará su satisfacción y fidelización.  
   Sabremos que hemos tenido éxito cuando al menos el 70% de los usuarios califique la relevancia de las recomendaciones como “alta” o “muy alta”.

#### 1.2.2.4. Lean UX Canvas
<img src="imgs/LeanUX_canvas_Freelance.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

## 1.3. Segmentos objetivo
#### **Estudiantes Universitarios Freelancers**
Estudiantes de cualquier ciclo universitario que buscan ofrecer sus servicios de manera independiente para adquirir experiencia laboral, generar ingresos y construir una red de clientes. Estos estudiantes pueden pertenecer a diversas especialidades como diseño gráfico, programación, marketing digital, redacción, tutorías académicas, entre otros.

Características:
* Buscan oportunidades de trabajo flexible que les permitan combinar sus estudios con el trabajo freelance.
* Necesitan herramientas que los ayuden a promocionar sus habilidades y construir una cartera de clientes.
* Valoran la facilidad de pago y la seguridad en la gestión de contratos.

#### **Personas y Emprendimientos  que buscan contratar servicios freelance**
Individuos o empresas que requieren servicios especializados sin la necesidad de contratar empleados a tiempo completo. Esto incluye emprendedores, startups, pequeñas empresas y particulares que buscan soluciones rápidas y accesibles para sus proyectos.

Características:

* Buscan talento accesible y de calidad para tareas específicas.
* Prefieren plataformas que garanticen la seguridad en la contratación y el cumplimiento del trabajo.
* Valoran las recomendaciones y validaciones de otros clientes para elegir freelancers confiables.
  
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
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
#### 4.1.3.1. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams
## 4.2. Tactical-Level Domain-Driven Design
### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solution UI/UX Design
## 5.1. Product Design
### 5.1.1. Style Guidelines
#### 5.1.1.1. General Style Guidelines
### 5.1.2. Information Architecture
#### 5.1.2.1. Organization Systems
#### 5.1.2.2. Labelling Systems
#### 5.1.2.3. SEO Tags and Meta Tags
#### 5.1.2.4. Searching Systems
#### 5.1.2.5. Navigation Systems
### 5.1.3. Landing Page UI Design
#### 5.1.3.1. Landing Page Wireframe
#### 5.1.3.2. Landing Page Mock-up
### 5.1.4. Mobile Applications UX/UI Design
#### 5.1.4.1. Mobile Applications Wireframes
#### 5.1.4.2. Mobile Applications Wireflow Diagrams
#### 5.1.4.3. Mobile Applications Mock-ups
#### 5.1.4.4. Mobile Applications User Flow Diagrams
#### 5.1.4.5. Mobile Applications Prototyping

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration
## 6.2. Landing Page & Mobile Application Implementation
### 6.2.0. Sprint 0 – Primer Hito (Semana 4)
#### 6.2.0.1. Sprint Planning 0
#### 6.2.0.2. Sprint Backlog 0
#### 6.2.0.3. Development Evidence for Sprint Review
#### 6.2.0.4. Execution Evidence for Sprint Review
#### 6.2.0.5. Services Documentation Evidence for Sprint Review
#### 6.2.0.6. Software Deployment Evidence for Sprint Review
#### 6.2.0.7. Team Collaboration Insights during Sprint
### 6.2.1. Sprint 1 – Segundo Hito (Semana 7)
#### 6.2.1.1. Sprint Planning 1
#### 6.2.1.2. Sprint Backlog 1
#### 6.2.1.3. Development Evidence for Sprint Review
#### 6.2.1.4. Testing Suite Evidence for Sprint Review
#### 6.2.1.5. Execution Evidence for Sprint Review
#### 6.2.1.6. Services Documentation Evidence for Sprint Review
#### 6.2.1.7. Software Deployment Evidence for Sprint Review
#### 6.2.1.8. Team Collaboration Insights during Sprint
### 6.2.2. Sprint 2 – Tercer Hito (Semana 12)
#### 6.2.2.1. Sprint Planning 2
#### 6.2.2.2. Sprint Backlog 2
#### 6.2.2.3. Development Evidence for Sprint Review
#### 6.2.2.4. Testing Suite Evidence for Sprint Review
#### 6.2.2.5. Execution Evidence for Sprint Review
#### 6.2.2.6. Services Documentation Evidence for Sprint Review
#### 6.2.2.7. Software Deployment Evidence for Sprint Review
#### 6.2.2.8. Team Collaboration Insights during Sprint
### 6.2.3. Sprint 3 – Cuarto Hito (Semana 15)
#### 6.2.3.1. Sprint Planning 3
#### 6.2.3.2. Sprint Backlog 3
#### 6.2.3.3. Development Evidence for Sprint Review
#### 6.2.3.4. Testing Suite Evidence for Sprint Review
#### 6.2.3.5. Execution Evidence for Sprint Review
#### 6.2.3.6. Services Documentation Evidence for Sprint Review
#### 6.2.3.7. Software Deployment Evidence for Sprint Review
#### 6.2.3.8. Team Collaboration Insights during Sprint
## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
### 6.3.2. Registro de Entrevistas
### 6.3.3. Evaluaciones según heurísticas
## 6.4. Video About-the-Product

# Conclusiones
## Conclusiones y recomendaciones

# Video About-the-Team

# Bibliografía

# Anexos

