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


# Tabla de Contenidos

* [Capítulo I: Presentación](#capítulo-i-presentación)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)

      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)
    * [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
  * [2.4. Requirements specification](#24-requirements-specification)

    * [2.4.1. User Stories](#241-user-stories)
    * [2.4.2. Impact Mapping](#242-impact-mapping)
    * [2.4.3. Product Backlog](#243-product-backlog)
  * [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)

    * [2.5.1. EventStorming](#251-eventstorming)

      * [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
      * [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      * [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    * [2.5.2. Context Mapping](#252-context-mapping)
    * [2.5.3. Software Architecture](#253-software-architecture)

      * [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      * [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      * [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  * [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)

    * [2.6.1. Bounded Context 1](#261-bounded-context-1)

      * [2.6.1.1. Domain Layer](#2611-domain-layer)
      * [2.6.1.2. Interface Layer](#2612-interface-layer)
      * [2.6.1.3. Application Layer](#2613-application-layer)
      * [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
      * [2.6.1.5. Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
      * [2.6.1.6. Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)

        * [2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
        * [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)

* [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)

  * [3.1. Product design](#31-product-design)

    * [3.1.1. Style Guidelines](#311-style-guidelines)

      * [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    * [3.1.2. Information Architecture](#312-information-architecture)

      * [3.1.2.1. Organization Systems](#3121-organization-systems)
      * [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      * [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      * [3.1.2.4. Searching Systems](#3124-searching-systems)
      * [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    * [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)

      * [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      * [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    * [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)

      * [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      * [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      * [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      * [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      * [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)

* [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)

  * [4.1. Software Configuration Management](#41-software-configuration-management)

    * [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    * [4.1.2. Source Code Management](#412-source-code-management)
    * [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
    * [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  * [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)

    * [4.2.1. Sprint 1 (TB1. Sprint Review) — Semana 4](#421-sprint-1-tb1-sprint-review--semana-4)

      * [4.2.1.1. Sprint Planning 1](#4211-sprint-planning-1)
      * [4.2.1.2. Sprint Backlog 1](#4212-sprint-backlog-1)
      * [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
      * [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
      * [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
      * [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
      * [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
      * [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)
      * [Contenido y entregables específicos del Hito (Semana 4)](#contenido-y-entregables-específicos-del-hito-semana-4)
    * [4.2.2. Sprint 2 (TP1. Stage Review) — Semana 7](#422-sprint-2-tp1-stage-review--semana-7)

      * [4.2.2.1. Sprint Planning 2](#4221-sprint-planning-2)
      * [4.2.2.2. Sprint Backlog 2](#4222-sprint-backlog-2)
      * [4.2.2.3. Development Evidence for Sprint Review](#4223-development-evidence-for-sprint-review)
      * [4.2.2.4. Testing Suite Evidence for Sprint Review](#4224-testing-suite-evidence-for-sprint-review)
      * [4.2.2.5. Execution Evidence for Sprint Review](#4225-execution-evidence-for-sprint-review)
      * [4.2.2.6. Services Documentation Evidence for Sprint Review](#4226-services-documentation-evidence-for-sprint-review)
      * [4.2.2.7. Software Deployment Evidence for Sprint Review](#4227-software-deployment-evidence-for-sprint-review)
      * [4.2.2.8. Team Collaboration Insights during Sprint](#4228-team-collaboration-insights-during-sprint)
      * [Contenido y entregables específicos del Hito (Semana 7)](#contenido-y-entregables-específicos-del-hito-semana-7)
    * [4.2.3. Sprint 3 (TB2. Sprint Review) — Semana 12](#423-sprint-3-tb2-sprint-review--semana-12)

      * [4.2.3.1. Sprint Planning 3](#4231-sprint-planning-3)
      * [4.2.3.2. Sprint Backlog 3](#4232-sprint-backlog-3)
      * [4.2.3.3. Development Evidence for Sprint Review](#4233-development-evidence-for-sprint-review)
      * [4.2.3.4. Testing Suite Evidence for Sprint Review](#4234-testing-suite-evidence-for-sprint-review)
      * [4.2.3.5. Execution Evidence for Sprint Review](#4235-execution-evidence-for-sprint-review)
      * [4.2.3.6. Services Documentation Evidence for Sprint Review](#4236-services-documentation-evidence-for-sprint-review)
      * [4.2.3.7. Software Deployment Evidence for Sprint Review](#4237-software-deployment-evidence-for-sprint-review)
      * [4.2.3.8. Team Collaboration Insights during Sprint](#4238-team-collaboration-insights-during-sprint)
      * [Contenido y entregables específicos del Hito (Semana 12)](#contenido-y-entregables-específicos-del-hito-semana-12)
    * [4.2.4. Sprint 4 (TF1. Release Review) — Semana 15](#424-sprint-4-tf1-release-review--semana-15)

      * [4.2.4.1. Sprint Planning 4](#4241-sprint-planning-4)
      * [4.2.4.2. Sprint Backlog 4](#4242-sprint-backlog-4)
      * [4.2.4.3. Development Evidence for Sprint Review](#4243-development-evidence-for-sprint-review)
      * [4.2.4.4. Testing Suite Evidence for Sprint Review](#4244-testing-suite-evidence-for-sprint-review)
      * [4.2.4.5. Execution Evidence for Sprint Review](#4245-execution-evidence-for-sprint-review)
      * [4.2.4.6. Services Documentation Evidence for Sprint Review](#4246-services-documentation-evidence-for-sprint-review)
      * [4.2.4.7. Software Deployment Evidence for Sprint Review](#4247-software-deployment-evidence-for-sprint-review)
      * [4.2.4.8. Team Collaboration Insights during Sprint](#4248-team-collaboration-insights-during-sprint)
      * [Contenido y entregables específicos del Hito (Semana 15)](#contenido-y-entregables-específicos-del-hito-semana-15)
  * [4.3. Validation Interviews](#43-validation-interviews)

    * [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    * [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    * [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)

* [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video App Validation](#video-app-validation)

* [Video About the product](#video-about-the-product)

* [Video About the team](#video-about-the-team)

* [Glosario](#glosario)

* [Bibliografía](#bibliografía)

* [Anexos](#anexos)

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
| Nombre: Oblitas Dávila, Mariano Moisés  |  <img src="imgs/Mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :---- | :---- |
| **Código:** U202310222 |  |
| **Carrera:** Ingeniería en software |  |
| **Habilidades:** Estudiante de 19 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, eficacia y capacidad para resolver problemas de manera racional. Apasionado por la programación y el desarrollo de software, busco constantemente innovar y aprender nuevas tecnologías. |  || Nombre: Cacho Seminario, Diego Alonso |   |

| Nombre: Cacho Seminario, Diego Alonso  | <img src="imgs/DiegoC.png" alt="DiegoC" title="Foto de Diego Cacho" /> |
| :---- | :---- |
| **Código:** U202223990 |  |
| **Carrera:** Ingeniería de Software |  |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 7mo ciclo de mi carrera en la UPC y tengo 20 años. Me considero una persona tranquila y diligente, intentó realizar mis tareas y trabajos lo antes posible para evitar contratiempos en un futuro, especialmente si son actividades que consumen mucho tiempo. Como miembro de equipo buscaré ayudar a mis compañeros cuando lo necesiten, realizando además mis entregas lo más temprano posible. Habilidades en C++, C\#, Python, Unity 2D/3D, html/css/js. |  |

| Nombre: Allca Guerrero, Irving  |  <img src="imgs/Irving.jpg" alt="Irving" title="Foto de Irving" width="320"/> |
| :---- | :---- |
| **Código:** U202213241 |  |
| **Carrera:** Ingeniería en software |  |
| **Habilidades:** Mi nombre es Irving Allca Guerrero, tengo 20 años y actualmente estudio Ingeniería de Software en la UPC, cursando el sexto ciclo de la carrera. Me considero una persona proactiva, con un enfoque orientado a la eficiencia, especialmente al enfrentar proyectos extensos o de alta complejidad. Disfruto trabajar en equipo y siempre busco colaborar y brindar apoyo a mis compañeros. |  || Nombre: Allca Guerrero, Irving |   |

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

# Capítulo II: Requirements Development and Software Solution Design
## 2.1. Competidores
Los competidores que hemos identificado para GigU son las plataformas freelancer, aunque no existen plataformas que estén 100% enfocadas en estudiantes como lo realiza GigU, si presenta productos con mucha similaridad lo que genera una competencia directa.

### 2.1.1. Análisis competitivo
<img src="imgs/Competidores1.png" alt="Competidores1" title="Competidores1"/>
<img src="imgs/Competidores2.png" alt="Competidores2" title="Competidores2"/>
<img src="imgs/Competidores3.png" alt="Competidores3" title="Competidores3"/>
<img src="imgs/Competidores4.png" alt="Competidores4" title="Competidores4"/>
<img src="imgs/Competidores5.png" alt="Competidores5" title="Competidores5"/>
<img src="imgs/Competidores6.png" alt="Competidores6" title="Competidores6"/>

### 2.1.2. Estrategias y tácticas frente a competidores
GigU aplicará una estrategia de diferenciación enfocada en el talento universitario, destacando por su enfoque educativo, precios accesibles y alianzas con instituciones académicas. Frente a los grandes competidores del mercado freelance, GigU se posiciona como una alternativa confiable y de propósito social, conectando clientes con estudiantes verificados. Su valor está en ofrecer soluciones personalizadas, soporte en español y una experiencia centrada en el desarrollo profesional de los jóvenes. Aprovechará las debilidades de otras plataformas como su falta de personalización o enfoque regional, mientras mitiga amenazas como la falta de experiencia estudiantil con garantías y filtros de calidad

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
User Persona del Usuario estudiante Freelancer
<img src="imgs/UserPersona1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>
User Persona del Usuario Persona o emprendimiento
<img src="imgs/UserPersona2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

### 2.3.2. User Task Matrix
En esta se presenta el user task matrix, herramienta centrada en los segmentos objetivos que nos permitirá identificar las tareas y objetivos claves de los usuarios.

| USER TASK  | Julio Bernal |  | Luisa Fuentes |  |
| :---- | ----- | :---- | ----- | :---- |
|  | Frequency | Importance | Frequency | Importance |
| Publicar servicios y mostrar habilidades | Often | High | Sometimes | High |
| Cotizar precios fácilmente según tipo de trabajo | Sometimes | High | Often | High |
| Encontrar oportunidades mediante una app centralizada | Sometimes | High | Often  | Medium |
| Procesar pagos seguros a través de la plataforma | Always  | High | Always | High |
| Mostrar historial de trabajos realizados | Sometimes | Medium | Often | Medium |
| Negociar precios dentro de un rango flexible | Sometimes | Medium | Always | High |
| Establecer acuerdos y comunicación en la plataforma | Often | High | Always | High |

### 2.3.3. User Journey Mapping
User Journey estudiante freelance
<img src="imgs/JourneyMapping1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

User Journey persona o empresa:
<img src="imgs/JourneyMapping2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

### 2.3.4. Empathy Mapping
En esta sección se presenta el Empathy Mapping, herramienta para crear un perfil detallado de los user personas y desarrollar una comprensión profunda de su perspectiva y experiencia. Para cada user persona, se incluyen cinco elementos clave: lo que el usuario ve, lo que el usuario escucha, lo que el usuario dice, lo que el usuario hace y lo que el usuario siente. Además, se incluyen los pains y gains identificados en base a las preguntas: ¿Qué le preocupa?

Empathy mapping de estudiante freelance:
<img src="imgs/Empathymap1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

Empathy mapping de persona o empresa:
<img src="imgs/Empathymap2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

### 2.3.5. Ubiquitous Language

* **Freelancer:** Estudiante que ofrece servicios a través de la plataforma.
* **Cliente:** Persona o emprendimiento que contrata servicios dentro de la plataforma.
* **Servicio:** Habilidad o trabajo ofrecido por un freelancer.
* **Perfil:** Información pública de un freelancer, incluyendo habilidades y experiencia.
* **Proyecto:** Trabajo definido que necesita ser realizado por un freelancer.
* **Solicitud de Proyecto:** Pedido que realiza un cliente para contratar un servicio.
* **Oferta:** Propuesta de precio y condiciones que un freelancer presenta para un proyecto.
* **Acuerdo:** Confirmación del cliente y freelancer sobre las condiciones de un proyecto.
* **Resumen de Servicio:** Descripción formal de lo que se entregará en un proyecto.
* **Entrega:** Resultado final que el freelancer entrega al cliente.
* **Estado del Proyecto:** Etapa actual de un proyecto (pendiente, en progreso, entregado, finalizado).
* **Calificación:** Puntuación que refleja la calidad del servicio entregado.
* **Comentario:** Reseña escrita sobre la experiencia de trabajo en un proyecto.
* **Historial:** Registro de proyectos completados por freelancers y clientes.
* **Notificación:** Mensaje generado por el sistema para informar sobre acciones relevantes.
* **Ámbito:** Categoría profesional que agrupa servicios similares.
* **Método de Pago:** Sistema mediante el cual se realiza la transacción económica.
* **Reputación:** Indicador basado en calificaciones y comentarios de proyectos finalizados.
* **Negociación:** Interacción en la que cliente y freelancer ajustan precio y condiciones.
* **Plataforma:** Espacio digital donde se conectan clientes y freelancers.
* **Gig:** Trabajo o servicio freelance ofrecido por un freelancer, generalmente de naturaleza específica y autónoma.
* **Pull:** Proceso o instancia de negociación directa entre un freelancer y un cliente para acordar detalles, precio y condiciones del gig.

## 2.4. Requirements specification
### 2.4.1. User Stories
* EPICS
Las epics definidas para el proyecto GigU están orientadas a cubrir las necesidades principales tanto de los estudiantes de la UPC como de los usuarios que buscan contratar servicios freelance. Estas epics abordan funcionalidades esenciales para el funcionamiento de la plataforma, asegurando una experiencia fluida y efectiva desde la publicación de habilidades por parte de los estudiantes hasta la contratación por parte de clientes o emprendimientos. Desde la interfaz de la landing page, donde los usuarios conocen la propuesta de valor de GigU, hasta la gestión técnica del backend, frontend y servicios web, las epics actúan como una guía estructurada que facilita el desarrollo progresivo y coherente del sistema, alineándose con los objetivos académicos y de empleabilidad del proyecto.

| Epic / Story ID | Título | Descripción |
| :---: | ----- | ----- |
| EP01 | Navegación en Landing Page | Como visitante de GigU, deseo poder navegar de forma intuitiva por la landing page para conocer los beneficios de contratar o publicar servicios. |
| EP02 | Autenticación y Registro de Usuarios | Como usuario nuevo, deseo registrarme e iniciar sesión utilizando correo o redes sociales para acceder a mi cuenta de manera rápida y segura. |
| EP03 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña fácilmente para poder acceder nuevamente en caso de olvidarla. |
| EP04 | Visualización de Servicios y Beneficios | Como visitante, deseo conocer los tipos de servicios disponibles y cómo funciona GigU para saber cómo puede ayudarme a contratar o ser contratado. |
| EP05 | Soporte y FAQ | Como visitante, deseo acceder a una sección de preguntas frecuentes y soporte para resolver mis dudas de forma autónoma y rápida. |
| EP06 | Gestión de Perfil Freelance | Como estudiante, deseo crear y editar mi perfil público con información, habilidades y precios para que posibles clientes conozcan mis servicios. |
| EP07 | Publicación y Edición de Servicios | Como estudiante, deseo publicar servicios personalizados con precios, plazos y descripciones claras para atraer clientes interesados. |
| EP08 | Búsqueda y Filtro de Freelancers | Como cliente, deseo buscar freelancers y filtrar por habilidades, precio o disponibilidad para encontrar al más adecuado para mi proyecto. |
| EP09 | Sistema de Contratación Directa | Como cliente, deseo contratar directamente a un freelancer desde su perfil para simplificar el proceso de contratación. |
| EP10 | Gestión de Proyectos y Solicitudes | Como freelancer, deseo gestionar las solicitudes recibidas y proyectos activos para poder organizar mejor mi trabajo y tiempos. |
| EP11 | Calificaciones y Opiniones | Como usuario, deseo dejar y ver calificaciones y comentarios sobre los freelancers para tomar decisiones más informadas. |
| EP12 | Sistema de Mensajería Interna | Como usuario, deseo comunicarme directamente dentro de la plataforma con el otro usuario para coordinar detalles antes o durante un proyecto. |
| EP13 | Cálculo Inteligente de Precio del Servicio | Como usuario, deseo que la plataforma sugiera un precio justo basado en la propuesta del freelancer, la oferta del cliente, el tipo y tamaño del servicio, y la experiencia del freelancer, para facilitar acuerdos equilibrados entre ambas partes. |

* User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| US01 | Navegación Intuitiva en la Landing Page | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | **Escenario 01:** Given que estoy en la landing page, When hago clic en el menú, Then debería ver opciones como “Inicio”, “Buscar Freelancer”, “Publicar Proyecto” y “Sobre Nosotros”. **Escenario 02:** Given que paso el cursor sobre un ítem, When el ítem está activo, Then debería resaltarse. | EP01 |
| US02 | Acceso rápido a funcionalidades clave | Como visitante, deseo acceder desde la landing page a secciones clave como “Publicar proyecto” o “Registrarse” para actuar rápidamente. | **Escenario 01:** Given que estoy en la landing, When hago scroll, Then debería ver botones CTA como “Empieza a contratar” o “Regístrate como freelancer”. **Escenario 02:** Given que estoy en la landing, When hago clic en un botón CTA como “Regístrate como freelancer”, Then debería ser redirigido al formulario de registro. | EP01 |
| US03 | Registro con Correo y Contraseña | Como nuevo usuario, deseo poder registrarme en la plataforma con mi correo y contraseña para acceder a las funcionalidades de GigU. | **Escenario 01:** Given que estoy en la sección de registro, When ingreso un correo válido y contraseña, Then debería registrarme correctamente. **Escenario 02:** Given que intento registrarme con datos inválidos, When presiono “Register”, Then debería recibir un mensaje de error. | EP02 |
| US04 | Iniciar sesión como Freelancer o Cliente | Como usuario registrado, deseo poder iniciar sesión para acceder a mi cuenta y funcionalidades específicas según mi rol. | **Escenario 01:** Given que tengo una cuenta, When ingreso mis credenciales, Then debería entrar como Freelancer o Cliente dependiendo del rol configurado. **Escenario 02**: Given que ingreso credenciales incorrectas, When presiono “Login”, Then debería recibir un mensaje de error indicando acceso denegado. | EP02 |
| US05 | Registro con redes sociales | Como visitante, deseo registrarme con Google para agilizar el proceso de creación de cuenta. | **Escenario 01:** Given que estoy en la vista de registro, When hago clic en “Registrarse con Google”, Then debería autenticarme y crear mi cuenta automáticamente. **Escenario 02**: Given que mi cuenta de Google ya está vinculada, When intento registrarme nuevamente con Google, Then debería mostrar un mensaje indicando que la cuenta ya existe. | EP02 |
| US06 | Solicitar recuperación de contraseña | Como usuario, deseo solicitar la recuperación de mi contraseña para volver a acceder si la olvido. | **Escenario 01:** Given que olvidé mi contraseña, When ingreso mi correo en la sección “Forgot your password”, Then debería recibir un correo con un enlace de recuperación. **Escenario 02**: Given que ingreso un correo no registrado, When presiono “Recuperar contraseña”, Then debería mostrar un mensaje indicando que el correo no existe en el sistema. | EP03 |
| US07 | Restablecer contraseña vía correo | Como usuario, deseo poder restablecer mi contraseña desde un enlace de recuperación enviado a mi correo. | **Escenario 01**: Given que he recibido el correo de recuperación, When hago clic en el enlace, Then debería poder establecer una nueva contraseña válida. **Escenario 02**: Given que ingreso una nueva contraseña que no cumple con los requisitos, When intento guardarla, Then debería mostrarse un mensaje de validación indicando el error. | EP03 |
| US08 | Conocer los beneficios de GigU | Como visitante, deseo conocer los beneficios de usar GigU para saber por qué debería usar esta plataforma. | **Escenario 01:** Given que estoy en la landing, When accedo a “About us”, Then debería ver beneficios como flexibilidad, soporte al talento joven y precios accesibles. **Escenario 02**: Given que veo los beneficios, When hago clic en uno de ellos, Then debería abrirse un pequeño resumen explicativo o una ventana emergente con más información. | EP04 |
| US09 | Diferencias entre roles (freelancer / cliente)	 | Como visitante, deseo saber las diferencias entre registrarme como freelancer o cliente para elegir el rol adecuado. | **Escenario 01**: Given que estoy revisando roles, When veo la sección de “Roles”, Then debería ver descripciones separadas y sus beneficios. **Escenario 02**: Given que estoy revisando la sección de roles, When hago click en “Freelancer” o “Customer”, Then debería desplegarse información adicional sobre el flujo de cada tipo de usuario. | EP04 |
| US10 | Experiencias de otros usuarios | Como visitante, deseo ver testimonios de usuarios anteriores para confiar en la plataforma. | **Escenario 01:** Given que estoy en la sección de experiencias, When visualizo un testimonio, Then debería ver nombre, rol y comentario del usuario. **Escenario 02**: Given que estoy en la sección de experiencias, When hago clic en “Ver más”, Then debería expandirse una lista con testimonios adicionales. | EP04 |
| US11 | Detalles sobre tipos de servicios | Como visitante, deseo conocer los tipos de servicios que puedo contratar o brindar en GigU. | **Escenario 01:** Given que accedo a la sección “Tipos de servicios”, When selecciono uno, Then debería ver una descripción detallada y ejemplos de ese servicio. **Escenario 02**: Given que estoy viendo la descripción de un tipo de servicio, When hago clic en “About This Gig”, Then debería ver casos prácticos de ese tipo de servicio realizado por otros freelancers. | EP04 |
| US12 | Acceso a Preguntas Frecuentes | Como visitante, deseo ver una sección de preguntas frecuentes para resolver mis dudas comunes sin ayuda externa. | **Escenario 01:** Given que estoy en la sección de ayuda, When hago clic en "FAQ", Then debería ver un listado de preguntas comunes con sus respuestas. **Escenario 02**: Given que veo el listado de preguntas, When hago clic en una respuesta, Then debería poder colapsar nuevamente la respuesta para limpiar la vista. | EP05 |
| US13 | Búsqueda dentro de Preguntas Frecuentes | Como usuario, deseo buscar palabras clave en la sección de FAQ para encontrar respuestas más rápido. | **Escenario 01:** Given que estoy en la sección FAQ, When ingreso una palabra en el buscador, Then debería mostrar solo las preguntas relacionadas. **Escenario 02**: Given que la búsqueda no devuelve resultados, When ingreso un término no encontrado, Then debería mostrarse un mensaje que diga “Didn’t found results”. | EP05 |
| US14 | Envío de Ticket de Soporte | Como usuario, deseo enviar un mensaje de soporte si no encuentro mi duda en la FAQ para recibir asistencia personalizada. | **Escenario 01:** Given que no encontré mi respuesta en FAQ, When hago clic en “Send Ticket”, Then debería poder completar un formulario con mi consulta. **Escenario 02**: Given que envío el formulario, When falta un campo obligatorio, Then debería impedir el envío y mostrar un mensaje de error indicando qué falta completar. | EP05 |
| US15 | Creación de Perfil Freelance | Como estudiante, deseo crear mi perfil freelance con mi nombre, carrera y universidad para que los clientes conozcan mi identidad profesional. | **Escenario 01:** Given que soy nuevo en la plataforma, When accedo a "Wanna Sell?", Then debería poder llenar campos como nombre, universidad y carrera. **Escenario 02**: Given que completé el formulario, When presiono “Guardar”, Then debería mostrarse un mensaje de confirmación y redirigirme al perfil creado. | EP06 |
| US16 | Añadir Habilidades y Descripción Personal | Como freelancer, deseo añadir habilidades y una descripción personal a mi perfil para destacar mis fortalezas. | **Escenario 01:** Given que estoy editando mi perfil, When ingreso habilidades y descripción, Then debería guardarse correctamente y verse en mi perfil público. **Escenario 02**: Given que edité mis habilidades, When regreso a mi perfil público, Then debería mostrarse la información actualizada en la sección de habilidades. | EP06 |
| US17 | Establecer Tarifas por Servicio | Como freelancer, deseo establecer mis tarifas por tipo de servicio para que los clientes vean cuánto cobro. | **Escenario 01:** Given que accedo a mi perfil, When ingreso una tarifa para un servicio, Then debería guardarse y mostrarse al público. **Escenario 02**: Given que ingreso un valor fuera del rango permitido, When intento guardar, Then debería mostrarse un mensaje de error de validación. | EP06 |
| US18 | Subir Portafolio de Proyectos | Como freelancer, deseo subir muestras de trabajos anteriores para mostrar mi experiencia a los clientes. | **Escenario 01:** Given que estoy en la sección de portafolio, When subo un archivo o enlace, Then debería verse en mi perfil con título y descripción. **Escenario 02**: Given que subo un archivo no permitido, When intento guardar el portafolio, Then debería mostrarse un mensaje de error indicando el tipo de archivo permitido. | EP06 |
| US19 | Editar y Actualizar Perfil en Cualquier Momento | Como freelancer, deseo poder actualizar mi perfil cuando quiera para mantener mi información al día. | **Escenario 01:** Given que accedo a “Edit Profile”, When modifico algún dato, Then debería guardarse correctamente sin errores. **Escenario 02**: Given que edité mi perfil exitosamente, When regreso a la vista pública, Then debería visualizar los cambios aplicados sin necesidad de recargar. | EP06 |
| US20 | Publicar un Servicio Personalizado | Como freelancer, deseo publicar un servicio con título, descripción y precio para ofrecerlo a potenciales clientes. | **Escenario 01:** Given que soy freelancer, When accedo a “Publish Service”, Then debería poder completar un formulario con título, descripción, categoría y precio. **Escenario 02**: Given que omití un campo obligatorio, When intento guardar el servicio, Then debería mostrarse un mensaje de error indicando qué debe completarse. | EP07 |
| US21 | Establecer Plazos de Entrega | Como freelancer, deseo definir el tiempo de entrega estimado para cada servicio para que el cliente tenga expectativas claras. | **Escenario 01:** Given que estoy publicando un servicio, When selecciono un plazo de entrega, Then debería mostrarse junto al resto de detalles del servicio. **Escenario 02**: Given que seleccioné un plazo, When se muestra públicamente, Then debería incluir el número de días junto a la descripción del servicio. | EP07 |
| US22 | Editar Servicios Publicados | Como freelancer, deseo poder editar los servicios que ya publiqué para corregir errores o actualizar precios y descripciones. | **Escenario 01:** Given que tengo un servicio publicado, When ingreso a "Edit service", Then debería poder modificar campos y guardar los cambios. **Escenario 02**: Given que edité un campo del servicio, When guardo los cambios, Then debería aparecer un mensaje de confirmación y el servicio actualizado debería estar disponible públicamente. | EP07 |
| US23 | Pausar o Eliminar Servicios Publicados | Como freelancer, deseo pausar o eliminar mis servicios si ya no los ofrezco o deseo ocultarlos temporalmente. | **Escenario 01:** Given que tengo servicios publicados, When presiono “Pause Service” o “Eliminate Service”, Then el servicio debería dejar de mostrarse públicamente. **Escenario 02**: Given que pausé un servicio, When regreso al listado de mis servicios, Then debería ver el estado actualizado como "Paused" y poder reactivarlo desde ahí. | EP07 |
| US24 | Añadir Imágenes o Archivos al Servicio | Como freelancer, deseo subir imágenes o archivos de muestra a mis servicios para ayudar al cliente a visualizar mejor lo que ofrezco. | **Escenario 01:** Given que estoy publicando un servicio, When adjunto una imagen o archivo, Then debería visualizarse como parte de la publicación. **Escenario 02**: Given que adjunto varias imágenes, When visualizo el servicio publicado, Then debería poder navegar entre las imágenes en un visor tipo carrusel. | EP07 |
| US25 | Buscar Freelancers por Palabra Clave | Como cliente, deseo buscar freelancers usando palabras clave para encontrar rápidamente quienes ofrecen lo que necesito. | **Escenario 01:** Given que soy cliente, When ingreso una palabra clave en el buscador, Then debería ver freelancers cuyos servicios coincidan con esa palabra. **Escenario 02**: Given que ingreso varias palabras clave, When presiono "Search", Then los resultados deberían mostrar coincidencias que incluyan al menos una de las palabras. | EP08 |
| US26 | Filtrar Freelancers por Habilidad | Como cliente, deseo filtrar freelancers según sus habilidades para encontrar al más apto para mi proyecto. | **Escenario 01:** Given que estoy buscando freelancers, When selecciono una habilidad del filtro, Then solo deberían mostrarse aquellos que la tienen registrada. **Escenario 02**: Given que selecciono varias habilidades, When aplico el filtro, Then debería mostrarse la combinación de freelancers que cumplan con al menos una de ellas. | EP08 |
| US27 | Filtrar por Rango de Precios | Como cliente, deseo establecer un rango de precios para ver freelancers que cobren dentro de mi presupuesto. | **Escenario 01:** Given que establezco un rango de precios, When aplico el filtro, Then debería ver resultados ajustados al presupuesto indicado. **Escenario 02**: Given que no hay freelancers en el rango seleccionado, When aplico el filtro, Then debería mostrarse un mensaje indicando “No se encontraron resultados en este rango de precios”. | EP08 |
| US28 | Filtrar por Nivel de Experiencia | Como cliente, deseo filtrar freelancers según su experiencia (básica, intermedia, avanzada) para elegir el nivel adecuado para mi necesidad. | **Escenario 01:** Given que uso el filtro de experiencia, When selecciono un nivel, Then deberían aparecer freelancers con ese nivel en su perfil. **Escenario 02**: Given que selecciono el nivel "Advanced", When veo los resultados, Then cada freelancer debería mostrar su nivel de experiencia en su tarjeta resumen. | EP08 |
| US29 | Ordenar Resultados por Relevancia o Calificación | Como cliente, deseo ordenar los resultados de búsqueda por calificación o relevancia para facilitar la comparación de perfiles. | **Escenario 01:** Given que busco freelancers, When elijo una opción de ordenamiento, Then la lista debería reordenarse de acuerdo al criterio seleccionado. **Escenario 02**: Given que cambio el criterio de ordenamiento de "Relevance" a "Qualification", When la página se actualiza, Then debería reflejar el nuevo orden y mantener los filtros seleccionados. | EP08 |
| US30 | Contratar desde el Perfil del Freelancer | Como cliente, deseo poder contratar a un freelancer directamente desde su perfil para ahorrar tiempo en el proceso de negociación. | **Escenario 01:** Given que estoy en el perfil de un freelancer, When hago clic en “Hire”, Then debería abrirse un formulario para confirmar la contratación y condiciones. **Escenario 02**: Given que contrato a un freelancer desde su perfil, When confirmo la solicitud, Then debería agregarse un registro en mi historial de contrataciones. | EP09 |
| US31 | Confirmación de Contratación Exitosa | Como cliente, deseo recibir una confirmación visual y por correo al contratar a un freelancer para saber que el proceso fue exitoso. | **Escenario 01:** Given que contrato un freelancer, When confirmo la acción, Then debería ver una notificación en pantalla y recibir un correo con los detalles del proyecto. **Escenario 02**: Given que recibo la confirmación, When reviso mi correo, Then debería encontrar un mensaje con el nombre del freelancer y los términos acordados. | EP09 |
| US32 | Rechazar o Aceptar una Solicitud de Contrato | Como freelancer, deseo tener la opción de aceptar o rechazar una contratación directa para mantener el control sobre mi disponibilidad. | **Escenario 01:** Given que recibo una solicitud de contrato, When reviso los detalles, Then debería poder aceptarla o rechazarla desde mi panel de notificaciones. **Escenario 02**: Given que rechazo una contratación, When el cliente revisa el estado, Then debería ver la notificación con el motivo (si se brindó). | EP09 |
| US33 | Ver Historial de Contrataciones Realizadas | Como cliente, deseo ver un historial de las contrataciones directas realizadas para tener un registro de mis actividades. | **Escenario 01:** Given que he contratado freelancers, When accedo a mi historial, Then debería ver una lista con nombres, fechas y estados de cada contratación. **Escenario 02**: Given que accedo a mi historial, When selecciono una contratación, Then debería poder ver detalles como fecha, nombre del freelancer y monto acordado. | EP09 |
| US34 | Visualizar Proyectos Activos | Como freelancer, deseo ver una lista de mis proyectos activos para organizarme y darles seguimiento. | **Escenario 01:** Given que estoy en mi dashboard, When accedo a “Mis Proyectos”, Then debería ver una lista con el título, cliente, y estado de cada proyecto activo. **Escenario 02**: Given que tengo múltiples proyectos activos, When ingreso al panel, Then debería poder ordenarlos por fecha de inicio o estado del proyecto. | EP10 |
| US35 | Gestionar Solicitudes Recibidas | Como freelancer, deseo revisar y gestionar solicitudes de nuevos proyectos para aceptar solo las que se ajusten a mi disponibilidad. | **Escenario 01:** Given que tengo solicitudes pendientes, When entro al panel de notificaciones, Then debería poder ver detalles y aceptar o rechazar cada una. **Escenario 02**: Given que rechazo una solicitud, When regreso al panel de solicitudes, Then la solicitud rechazada debería mostrarse con un estado “Rechazado” y opción de comentario. | EP10 |
| US36 | Marcar Proyecto como Finalizado | Como freelancer, deseo marcar un proyecto como finalizado para indicar que mi trabajo ha sido completado. | **Escenario 01:** Given que he terminado un proyecto, When entro al detalle del proyecto, Then debería poder marcarlo como “Finalizado”. **Escenario 02**: Given que marco un proyecto como finalizado, When el cliente revisa el proyecto, Then debería aparecer el estado actualizado como “Finalized by the Freelancer”. | EP10 |
| US37 | Seguimiento del Estado del Proyecto | Como cliente, deseo ver el estado de mis proyectos en curso para saber si están en espera, en proceso o finalizados. | **Escenario 01:** Given que contraté un freelancer, When accedo a “My hires”, Then debería ver el estado actualizado de cada proyecto. **Escenario 02**: Given que el proyecto cambia de estado, When ingreso al detalle del mismo, Then debería poder ver un historial con los cambios de estado y fechas correspondientes. | EP10 |
| US38 | Calificar al Freelancer Finalizado el Proyecto | Como cliente, deseo dejar una calificación al freelancer al finalizar el proyecto para compartir mi experiencia con otros usuarios. | **Escenario 01:** Given que finalizó un proyecto, When accedo a la sección de calificación, Then debería poder seleccionar una puntuación del 1 al 5 y escribir un comentario. **Escenario 02**: Given que ya califiqué al freelancer, When reviso el proyecto, Then debería ver el comentario que dejé y la calificación asignada. | EP11 |
| US39 | Ver Calificaciones en Perfil de Freelancer | Como cliente, deseo ver las calificaciones que otros clientes han dejado en el perfil del freelancer para tomar una decisión informada. | **Escenario 01:** Given que visito el perfil de un freelancer, When reviso la sección de reseñas, Then debería ver las calificaciones promedio y comentarios anteriores. **Escenario 02**: Given que estoy viendo las reseñas, When hago clic en una calificación, Then debería poder expandirla para ver el comentario completo si está truncado. | EP11 |
| US40 | Editar Calificación Después de Proyecto | Como cliente, deseo poder editar mi calificación si he cometido un error o si hubo una mejora significativa tras el feedback. | **Escenario 01:** Given que ya dejé una calificación, When hago clic en “Edit Review”, Then debería poder modificar el puntaje y/o comentario. **Escenario 02**: Given que edito una reseña, When la guardo, Then debería aparecer una etiqueta indicando “Review edited” con la nueva fecha. | EP11 |
| US41 | Calificar al Cliente | Como freelancer, deseo calificar al cliente luego de terminar un proyecto para que otros freelancers conozcan su reputación. | **Escenario 01:** Given que terminé un proyecto, When accedo a la sección de calificaciones, Then debería poder puntuar al cliente y dejar un comentario. **Escenario 02**: Given que califico al cliente, When regreso a mi historial de proyectos, Then debería ver un ícono o mensaje indicando que ya he calificado ese proyecto. | EP11 |
| US42 | Enviar Mensaje a Usuario desde Perfil | Como usuario, deseo enviar un mensaje a otro usuario desde su perfil para coordinar antes de contratar o aceptar un proyecto. | **Escenario 01:** Given que estoy en el perfil de un usuario, When hago clic en "Send Message", Then debería abrirse una ventana de chat para iniciar la conversación. **Escenario 02**: Given que inicio una conversación, When el otro usuario responde, Then debería mostrarse una notificación dentro del ícono de mensajes. | EP12 |
| US43 | Ver Historial de Conversaciones | Como usuario, deseo ver el historial de mis conversaciones previas para recordar acuerdos y detalles importantes. | **Escenario 01:** Given que tengo mensajes anteriores, When ingreso a la sección de “Messages”, Then debería ver una lista de chats recientes con sus respectivos nombres y fechas. **Escenario 02**: Given que abro un chat antiguo, When hago scroll hacia arriba, Then debería cargarse el historial completo de mensajes anteriores automáticamente. | EP12 |
| US44 | Notificación de Nuevo Mensaje | Como usuario, deseo recibir una notificación cuando me envíen un nuevo mensaje para no perderme ninguna comunicación importante. | **Escenario 01:** Given que me enviaron un mensaje, When estoy dentro o fuera de la plataforma, Then debería recibir una notificación visual. **Escenario 02**: Given que recibo un mensaje nuevo, When estoy dentro de la conversación, Then el nuevo mensaje debería aparecer automáticamente sin necesidad de recargar. | EP12 |
| US45 | Bloquear o Reportar Usuario desde Chat | Como usuario, deseo poder bloquear o reportar a alguien desde el chat si recibo mensajes inapropiados o spam. | **Escenario 01:** Given que estoy en una conversación, When hago clic en "Report User", Then debería aparecer un formulario con motivo y botón para enviar el reporte. **Escenario 02**: Given que bloqueé a un usuario, When intento enviarle otro mensaje, Then debería recibir una notificación indicando que no puedo interactuar con ese usuario. | EP12 |
| US46 | Sugerencia de Precio Inteligente | Como usuario, deseo recibir una sugerencia automática de precio al momento de negociar, para basarme en un valor justo según experiencia y tipo de servicio. | **Escenario 01:** Given que estoy creando una propuesta, When selecciono tipo de servicio y nivel de experiencia, Then debería mostrarse una sugerencia de precio calculada automáticamente. **Escenario 02**: Given que ya tengo una tarifa sugerida, When modifico el tipo de servicio, Then el sistema debería actualizar automáticamente la sugerencia con el nuevo valor. | EP13 |
| US47 | Ajuste Manual sobre Precio Sugerido | Como usuario, deseo poder modificar manualmente el precio sugerido para adaptarlo a mis propias condiciones. | **Escenario 01:** Given que veo la sugerencia de precio, When edito el campo manualmente, Then debería permitir cambiarlo sin perder la base de cálculo previa. **Escenario 02**: Given que ya ingresé un nuevo valor, When regreso a la sección de precios, Then debería verse el valor manual ingresado como definitivo. | EP13 |
| US48 | Detalle del Cálculo del Precio | Como usuario, deseo ver una explicación breve de cómo se calculó el precio sugerido para tener mayor confianza en su lógica. | **Escenario 01**: Given que recibo una sugerencia de precio, When hago clic en "View Details", Then debería mostrarse un resumen con factores como experiencia, tipo y tamaño del servicio. **Escenario 02**: Given que veo los factores del cálculo, When paso el cursor por cada uno, Then debería mostrarse una breve descripción de cómo influye en el precio. | EP13 |
| US49 | Comparación entre Propuesta y Oferta | Como usuario, deseo comparar mi propuesta con la oferta del otro usuario para llegar más fácilmente a un acuerdo. | **Escenario 01:** Given que ambos usuarios hicieron una propuesta, When estoy en la sección de negociación, Then debería verse una tabla comparativa entre los dos valores. **Escenario 02**: Given que hay una diferencia significativa entre ambas partes, When abro la tabla comparativa, Then debería verse un mensaje sugerente para negociar o ajustar. | EP13 |
| US50 | Historial de Precios de Servicios Similares | Como usuario, deseo ver precios promedios de servicios similares contratados anteriormente para decidir mejor mi tarifa. | **Escenario 01:** Given que estoy creando una propuesta, When hago clic en "See price history", Then debería verse un gráfico o listado con precios de trabajos similares. **Escenario 02**: Given que estoy viendo precios anteriores, When selecciono una categoría distinta, Then debería actualizarse el historial mostrado según la nueva categoría. | EP13 |

### 2.4.2. Impact Mapping

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: [LINK Impact Mapping](https://miro.com/app/board/uXjVIE5Pk5Q=/?share_link_id=296495865120)

**Impact Map Segmento 1:** Estudiantes Universitarios Freelancers  
El impact map de GigU para los estudiantes universitarios freelancers busca proporcionar un sistema robusto con alta posibilidad de personalización para la expresión creativa y profesional de los freelancers con la posibilidad de subir portafolios completos, publicar diversos tipos de servicios y editar o personalizar los perfiles junto a los servicios del freelancer.  
<img src="imgs/ImpactMap1.png" alt="ImpactMapping" title="ImpactMapping"/>

**Impact Map Segmento 2:** Personas y Emprendimientos que buscan contratar servicios freelance  
El impact map de GigU para las personas y emprendimientos que buscan contratar servicios freelance busca optimizar el proceso del contratado de freelancers por medio de un sistema de búsqueda completo que permite encontrar al freelancer indicado teniendo en cuenta sus servicios disponibles, la media de costos que propone y su nivel de experiencia.  
<img src="imgs/ImpactMap2.png" alt="ImpactMapping" title="ImpactMapping"/>

### 2.4.3. Product Backlog
Se utilizó la escala Fibonacci para la estimación de los Story Points. En total se tuvieron **197** Story Points.

| \# Orden | Epic / Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :---: | ----- | ----- | :---: |
| 1 | US01 | Navegación Intuitiva en la Landing Page | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | 3 |
| 2 | US02 | Acceso rápido a funcionalidades clave | Como visitante, deseo acceder desde la landing page a secciones clave como “Publicar proyecto” o “Registrarse” para actuar rápidamente. | 3 |
| 3 | US03 | Registro con Correo y Contraseña | Como nuevo usuario, deseo poder registrarme en la plataforma con mi correo y contraseña para acceder a las funcionalidades de GigU. | 3 |
| 4 | US04 | Iniciar sesión como Freelancer o Cliente | Como usuario registrado, deseo poder iniciar sesión para acceder a mi cuenta y funcionalidades específicas según mi rol. | 5 |
| 5 | US05 | Registro con redes sociales | Como visitante, deseo registrarme con Google para agilizar el proceso de creación de cuenta. | 2 |
| 6 | US06 | Solicitar recuperación de contraseña | Como usuario, deseo solicitar la recuperación de mi contraseña para volver a acceder si la olvido. | 2 |
| 7 | US07 | Restablecer contraseña vía correo | Como usuario, deseo poder restablecer mi contraseña desde un enlace de recuperación enviado a mi correo. | 2 |
| 8 | US08 | Conocer los beneficios de GigU | Como visitante, deseo conocer los beneficios de usar GigU para saber por qué debería usar esta plataforma. | 1 |
| 9 | US09 | Diferencias entre roles (freelancer / cliente)	 | Como visitante, deseo saber las diferencias entre registrarme como freelancer o cliente para elegir el rol adecuado. | 8 |
| 10 | US10 | Experiencias de otros usuarios | Como visitante, deseo ver testimonios de usuarios anteriores para confiar en la plataforma. | 5 |
| 11 | US11 | Detalles sobre tipos de servicios | Como visitante, deseo conocer los tipos de servicios que puedo contratar o brindar en GigU. | 5 |
| 12 | US12 | Acceso a Preguntas Frecuentes | Como visitante, deseo ver una sección de preguntas frecuentes para resolver mis dudas comunes sin ayuda externa. | 3 |
| 13 | US13 | Búsqueda dentro de Preguntas Frecuentes | Como usuario, deseo buscar palabras clave en la sección de FAQ para encontrar respuestas más rápido. | 3 |
| 14 | US14 | Envío de Ticket de Soporte | Como usuario, deseo enviar un mensaje de soporte si no encuentro mi duda en la FAQ para recibir asistencia personalizada. | 3 |
| 15 | US15 | Creación de Perfil Freelance | Como estudiante, deseo crear mi perfil freelance con mi nombre, carrera y universidad para que los clientes conozcan mi identidad profesional. | 5 |
| 16 | US16 | Añadir Habilidades y Descripción Personal | Como freelancer, deseo añadir habilidades y una descripción personal a mi perfil para destacar mis fortalezas. | 8 |
| 17 | US17 | Establecer Tarifas por Servicio | Como freelancer, deseo establecer mis tarifas por tipo de servicio para que los clientes vean cuánto cobro. | 8 |
| 18 | US18 | Subir Portafolio de Proyectos | Como freelancer, deseo subir muestras de trabajos anteriores para mostrar mi experiencia a los clientes. | 5 |
| 19 | US19 | Editar y Actualizar Perfil en Cualquier Momento | Como freelancer, deseo poder actualizar mi perfil cuando quiera para mantener mi información al día. | 3 |
| 20 | US20 | Publicar un Servicio Personalizado | Como freelancer, deseo publicar un servicio con título, descripción y precio para ofrecerlo a potenciales clientes. | 5 |
| 21 | US21 | Establecer Plazos de Entrega | Como freelancer, deseo definir el tiempo de entrega estimado para cada servicio para que el cliente tenga expectativas claras. | 5 |
| 22 | US22 | Editar Servicios Publicados | Como freelancer, deseo poder editar los servicios que ya publiqué para corregir errores o actualizar precios y descripciones. | 5 |
| 23 | US23 | Pausar o Eliminar Servicios Publicados | Como freelancer, deseo pausar o eliminar mis servicios si ya no los ofrezco o deseo ocultarlos temporalmente. | 5 |
| 24 | US24 | Añadir Imágenes o Archivos al Servicio | Como freelancer, deseo subir imágenes o archivos de muestra a mis servicios para ayudar al cliente a visualizar mejor lo que ofrezco. | 3 |
| 25 | US25 | Buscar Freelancers por Palabra Clave | Como cliente, deseo buscar freelancers usando palabras clave para encontrar rápidamente quienes ofrecen lo que necesito. | 3 |
| 26 | US26 | Filtrar Freelancers por Habilidad | Como cliente, deseo filtrar freelancers según sus habilidades para encontrar al más apto para mi proyecto. | 3 |
| 27 | US27 | Filtrar por Rango de Precios | Como cliente, deseo establecer un rango de precios para ver freelancers que cobren dentro de mi presupuesto. | 5 |
| 28 | US28 | Filtrar por Nivel de Experiencia | Como cliente, deseo filtrar freelancers según su experiencia (básica, intermedia, avanzada) para elegir el nivel adecuado para mi necesidad. | 5 |
| 29 | US29 | Ordenar Resultados por Relevancia o Calificación | Como cliente, deseo ordenar los resultados de búsqueda por calificación o relevancia para facilitar la comparación de perfiles. | 3 |
| 30 | US30 | Contratar desde el Perfil del Freelancer | Como cliente, deseo poder contratar a un freelancer directamente desde su perfil para ahorrar tiempo en el proceso de negociación. | 5 |
| 31 | US31 | Confirmación de Contratación Exitosa | Como cliente, deseo recibir una confirmación visual y por correo al contratar a un freelancer para saber que el proceso fue exitoso. | 3 |
| 32 | US32 | Rechazar o Aceptar una Solicitud de Contrato | Como freelancer, deseo tener la opción de aceptar o rechazar una contratación directa para mantener el control sobre mi disponibilidad. | 3 |
| 33 | US33 | Ver Historial de Contrataciones Realizadas | Como cliente, deseo ver un historial de las contrataciones directas realizadas para tener un registro de mis actividades. | 2 |
| 34 | US34 | Visualizar Proyectos Activos | Como freelancer, deseo ver una lista de mis proyectos activos para organizarme y darles seguimiento. | 5 |
| 35 | US35 | Gestionar Solicitudes Recibidas | Como freelancer, deseo revisar y gestionar solicitudes de nuevos proyectos para aceptar solo las que se ajusten a mi disponibilidad. | 3 |
| 36 | US36 | Marcar Proyecto como Finalizado | Como freelancer, deseo marcar un proyecto como finalizado para indicar que mi trabajo ha sido completado. | 3 |
| 37 | US37 | Seguimiento del Estado del Proyecto | Como cliente, deseo ver el estado de mis proyectos en curso para saber si están en espera, en proceso o finalizados. | 5 |
| 38 | US38 | Calificar al Freelancer Finalizado el Proyecto | Como cliente, deseo dejar una calificación al freelancer al finalizar el proyecto para compartir mi experiencia con otros usuarios. | 3 |
| 39 | US39 | Ver Calificaciones en Perfil de Freelancer | Como cliente, deseo ver las calificaciones que otros clientes han dejado en el perfil del freelancer para tomar una decisión informada. | 5 |
| 40 | US40 | Editar Calificación Después de Proyecto | Como cliente, deseo poder editar mi calificación si he cometido un error o si hubo una mejora significativa tras el feedback. | 5 |
| 41 | US41 | Calificar al Cliente | Como freelancer, deseo calificar al cliente luego de terminar un proyecto para que otros freelancers conozcan su reputación. | 5 |
| 42 | US42 | Enviar Mensaje a Usuario desde Perfil | Como usuario, deseo enviar un mensaje a otro usuario desde su perfil para coordinar antes de contratar o aceptar un proyecto. | 3 |
| 43 | US43 | Ver Historial de Conversaciones | Como usuario, deseo ver el historial de mis conversaciones previas para recordar acuerdos y detalles importantes. | 2 |
| 44 | US44 | Notificación de Nuevo Mensaje | Como usuario, deseo recibir una notificación cuando me envíen un nuevo mensaje para no perderme ninguna comunicación importante. | 1 |
| 45 | US45 | Bloquear o Reportar Usuario desde Chat | Como usuario, deseo poder bloquear o reportar a alguien desde el chat si recibo mensajes inapropiados o spam. | 2 |
| 46 | US46 | Sugerencia de Precio Inteligente | Como usuario, deseo recibir una sugerencia automática de precio al momento de negociar, para basarme en un valor justo según experiencia y tipo de servicio. | 8 |
| 47 | US47 | Ajuste Manual sobre Precio Sugerido | Como usuario, deseo poder modificar manualmente el precio sugerido para adaptarlo a mis propias condiciones. | 5 |
| 48 | US48 | Detalle del Cálculo del Precio | Como usuario, deseo ver una explicación breve de cómo se calculó el precio sugerido para tener mayor confianza en su lógica. | 5 |
| 49 | US49 | Comparación entre Propuesta y Oferta | Como usuario, deseo comparar mi propuesta con la oferta del otro usuario para llegar más fácilmente a un acuerdo. | 3 |
| 50 | US50 | Historial de Precios de Servicios Similares | Como usuario, deseo ver precios promedios de servicios similares contratados anteriormente para decidir mejor mi tarifa. | 2 |

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams
## 2.6. Tactical-Level Domain-Driven Design
### 2.6.1. Bounded Context 1
#### 2.6.1.1. Domain Layer
#### 2.6.1.2. Interface Layer
#### 2.6.1.3. Application Layer
#### 2.6.1.4. Infrastructure Layer
#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.1.6.2. Bounded Context Database Design Diagram

# Capítulo III: Solution UI/UX Design
## 3.1. Product design
### 3.1.1. Style Guidelines
#### 3.1.1.1. General Style Guidelines
### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems
#### 3.1.2.2. Labelling Systems
#### 3.1.2.3. SEO Tags and Meta Tags
#### 3.1.2.4. Searching Systems
#### 3.1.2.5. Navigation Systems
### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe
#### 3.1.3.2. Landing Page Mock-up
### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes
#### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### 3.1.4.3. Mobile Applications Mock-ups
#### 3.1.4.4. Mobile Applications User Flow Diagrams
#### 3.1.4.5. Mobile Applications Prototyping

# Capítulo IV: Product Implementation & Validation
## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration
### 4.1.2. Source Code Management
### 4.1.3. Source Code Style Guide & Conventions
### 4.1.4. Software Deployment Configuration
## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint 1
#### 4.2.1.1. Sprint Planning 1
#### 4.2.1.2. Sprint Backlog 1
#### 4.2.1.3. Development Evidence for Sprint Review
#### 4.2.1.4. Testing Suite Evidence for Sprint Review
#### 4.2.1.5. Execution Evidence for Sprint Review
#### 4.2.1.6. Services Documentation Evidence for Sprint Review
#### 4.2.1.7. Software Deployment Evidence for Sprint Review
#### 4.2.1.8. Team Collaboration Insights during Sprint
### 4.2.2. Sprint 2
#### 4.2.2.1. Sprint Planning 2
#### 4.2.2.2. Sprint Backlog 2
#### 4.2.2.3. Development Evidence for Sprint Review
#### 4.2.2.4. Testing Suite Evidence for Sprint Review
#### 4.2.2.5. Execution Evidence for Sprint Review
#### 4.2.2.6. Services Documentation Evidence for Sprint Review
#### 4.2.2.7. Software Deployment Evidence for Sprint Review
#### 4.2.2.8. Team Collaboration Insights during Sprint
### 4.2.3. Sprint 3
#### 4.2.3.1. Sprint Planning 3
#### 4.2.3.2. Sprint Backlog 3
#### 4.2.3.3. Development Evidence for Sprint Review
#### 4.2.3.4. Testing Suite Evidence for Sprint Review
#### 4.2.3.5. Execution Evidence for Sprint Review
#### 4.2.3.6. Services Documentation Evidence for Sprint Review
#### 4.2.3.7. Software Deployment Evidence for Sprint Review
#### 4.2.3.8. Team Collaboration Insights during Sprint
### 4.2.4. Sprint 4
#### 4.2.4.1. Sprint Planning 4
#### 4.2.4.2. Sprint Backlog 4
#### 4.2.4.3. Development Evidence for Sprint Review
#### 4.2.4.4. Testing Suite Evidence for Sprint Review
#### 4.2.4.5. Execution Evidence for Sprint Review
#### 4.2.4.6. Services Documentation Evidence for Sprint Review
#### 4.2.4.7. Software Deployment Evidence for Sprint Review
#### 4.2.4.8. Team Collaboration Insights during Sprint
## 4.3. Validation Interviews
### 4.3.1. Diseño de Entrevistas
### 4.3.2. Registro de Entrevistas
### 4.3.3. Evaluaciones según heurísticas

# Conclusiones y recomendaciones
# Video App Validation
# Video About the product
# Video About the team
# Glosario
# Bibliografía
# Anexos
