# AgroGes
---

# Carátula
- **Universidad**: UPC
- **Carrera**: Ing de Software
- **Ciclo**: 5
- **Curso**: Desarrollo de Aplicaciones Open Source
- **Sección**: SW51
- **Profesor**: Ángel Augusto Velásquez Núñez

---

# Informe de Trabajo Final
- **Nombre del Startup**: Lux
- **Nombre del Producto**: AgroGes
- **Relación de Integrantes**: Pecan Pariona, Sergio Joel (u20201a938)
- **Mes y Año**: marzo del 2024

---

# Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| **Versión** | **Fecha** | **Autor** | **Descripción de Modificación** |
|-------------|-----------|-----------|---------------------------------|
| 1.0         | [Fecha]   | [Autor]   | [Descripción de la primera versión] |
| 1.1         | [Fecha]   | [Autor]   | [Descripción de modificaciones relevantes] |
| ...         | ...       | ...       | ...                             |

---
# Project Report Collaboration Insights 



---

# Tabla de contenidos
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1 Startup Profile](#11-startup-profile)
        - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2 Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
        - [1.3 Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1 Competidores](#21-competidores)
        - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2 Entrevistas](#22-entrevistas)
        - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3 Needfinding](#23-needfinding)
        - [2.3.1 User Personas](#231-user-personas)
        - [2.3.2 User Task Matrix](#232-user-task-matrix)
        - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4 Empathy Mapping](#234-empathy-mapping)
        - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4 Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2 User Stories](#32-user-stories)
    - [3.3 Impact Mapping](#33-impact-mapping)
    - [3.4 Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1 Style Guidelines](#41-style-guidelines)
        - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
    - [4.2 Information Architecture](#42-information-architecture)
        - [4.2.1 Organization Systems](#421-organization-systems)
        - [4.2.2 Labeling Systems](#422-labeling-systems)
        - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4 Searching Systems](#424-searching-systems)
        - [4.2.5 Navigation Systems](#425-navigation-systems)
    - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1 Class Diagrams](#471-class-diagrams)
        - [4.7.2 Class Dictionary](#472-class-dictionary)
    - [4.8 Database Design](#48-database-design)
        - [4.8.1 Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation-deployment)
    - [5.1 Software Configuration Management](#51-software-configuration-management)
        - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services-applications-implementation)
        - [5.2.1 Sprint 1](#521-sprint-1)
            - [5.2.1.1 Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2 Sprint Backlog 1](#5212-sprint-backlog-1)
            - [5.2.1.3 Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
            - [5.2.1.4 Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
            - [5.2.1.5 Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
                       - [5.2.1.6 Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7 Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8 Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
        - [5.2.2 Sprint 2](#522-sprint-2)
            - [5.2.2.1 Sprint Planning 2](#5221-sprint-planning-2)
            - [5.2.2.2 Sprint Backlog 2](#5222-sprint-backlog-2)
            - [5.2.2.3 Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
            - [5.2.2.4 Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
            - [5.2.2.5 Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
            - [5.2.2.6 Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
            - [5.2.2.7 Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
            - [5.2.2.8 Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
        - [5.2.3 Sprint 3](#523-sprint-3)
            - [5.2.3.1 Sprint Planning 3](#5231-sprint-planning-3)
            - [5.2.3.2 Sprint Backlog 3](#5232-sprint-backlog-3)
            - [5.2.3.3 Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
            - [5.2.3.4 Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
            - [5.2.3.5 Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
            - [5.2.3.6 Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
            - [5.2.3.7 Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
            - [5.2.3.8 Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    - [5.3 Validation Interviews](#53-validation-interviews)
        - [5.3.1 Diseño de Entrevistas](#531-diseño-entrevistas)
        - [5.3.2 Registro de Entrevistas](#532-registro-entrevistas)
        - [5.3.3 Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4 Video About-the-Product](#54-video-about-the-product)


---


# Capítulo I: Introducción
## 1.1 Startup Profile
### 1.1.1 Descripción de la Startup
AgroGes us una startup que busca poder apoyar a pequeños y medianos agricultores en el desarrollo de sus cultivos. En nuestro compromiso por fortalecer el sector agrícola, ofrecemos una plataforma integral que proporciona información técnica y asesoramiento especializado para optimizar la producción.Nuestro equipo está conformado por profesionales altamente capacitados, listos para brindar orientación sobre las mejores prácticas agrícolas, incluyendo recomendaciones sobre las temporadas ideales para el cultivo, los períodos óptimos de riego, así como consejos sobre el manejo de plagas y enfermedades.Además, facilitamos a los agricultores la posibilidad de programar visitas de nuestros profecionales a sus terrenos para realizar evaluaciones específicas y ofrecer recomendaciones personalizadas. Creemos firmemente en la importancia de la atención individualizada para garantizar un mejor desempeño en sus cultivos.
En resumen, en nuestra plataforma encontrarás el respaldo necesario para impulsar tu producción agrícola, con acceso a información precisa y la asistencia de expertos que te acompañarán en cada etapa del proceso. Juntos, trabajaremos para alcanzar el éxito en tu actividad agrícola.  


### 1.1.2 Perfiles de integrantes del equipo
#### - Favio Sebastián Landeo Simeón
Mi nombre es Favio, tengo 20 años y actualmente estoy cursando el séptimo ciclo de la carrera de Ingeniería de Software. Estoy disponible para ayudar siempre a mis  compañeros y además tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad  de trabajo en equipo. Tengo experiencia en los lenguajes de programación C++ y, Python. En mis tiempos libres me gusta escuchar música, jugar videojuegos y editar videos .


#### - Gustavo Arturo Poma Espinoza 
Mi nombre es Gustavo, actualmente estoy cursando el quinto ciclo de la carrera de Ingeniería de Software. Disfruto escuchando música, ya que siento que esta actividad me inspira creatividad. Salir a caminar con mis mascotas me ayuda a relajarme y meditar. Además, soy aficionado a las artes marciales, las cuales me han inculcado disciplina y perseverancia. Mi color favorito es el azul. Estoy disponible para ayudar siempre a mis compañeros y tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo.

#### - Daniel Mateo Del Castillo Bueno
Me encuentro cursando el quinto ciclo de la carrera de Ingeniería de Software. Desde que soy pequeño siempre me he sentido atraído por la tecnología, lo que evolucionó en mi vocación por la programación de software. Tengo conocimientos en Linux, SQL, C++, Python, HTML, CSS y JavaScript. Considero que el mayor aporte que puedo brindar a mi equipo es mi compañerismo y compromiso por ayudar y solucionar problemas para poder brindar un trabajo idóneo.
---

## 1.2 Solution Profile
### 1.2.1 Antecedentes y problemática
[Poner información aquí]

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
[Poner información aquí]

#### 1.2.2.2 Lean UX Assumptions
[Poner información aquí]

#### 1.2.2.3 Lean UX Hypothesis Statements
[Poner información aquí]

#### 1.2.2.4 Lean UX Canvas
[Poner información aquí]

---

## 1.3 Segmentos objetivo
[Poner información aquí]

---
# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
### 2.1.1 Análisis competitivo
[Poner información aquí]

### 2.1.2 Estrategias y tácticas frente a competidores
[Poner información aquí]

---

## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas
[Poner información aquí]

### 2.2.2 Registro de entrevistas
[Poner información aquí]

### 2.2.3 Análisis de entrevistas
[Poner información aquí]

---

## 2.3 Needfinding
### 2.3.1 User Personas
[Poner información aquí]

### 2.3.2 User Task Matrix
[Poner información aquí]

### 2.3.3 User Journey Mapping
[Poner información aquí]

### 2.3.4 Empathy Mapping
[Poner información aquí]

### 2.3.5 As-is Scenario Mapping
[Poner información aquí]

---

## 2.4 Ubiquitous Language
[Poner información aquí]

---

# Capítulo III: Requirements Specification
## 3.1 To-Be Scenario Mapping

## To-Be Scenario Mapping: Entrega de Comida a Domicilio

### Fases:
1. **Análisis y Diagnóstico**
2. **Diseño del Futuro Deseado**
3. **Planificación Estratégica**
4. **Implementación y Desarrollo**
5. **Gestión del Cambio**
6. **Evaluación y Ajuste**

### Acciones:
| Fase | Acción | Pensamientos | Sentimientos |
|------|--------|--------------|--------------|
| 1.   |  |  | Curiosidad |
|      |  |  | Expectativa |
| 2.   |  | | Anticipación |
|      |  | | Confianza |
| 3.   |  | | Eficiencia |
|      |  | | Organización |
| 4.   |  | | Satisfacción |
|      |  | | Logro |



## 3.2 User Stories
| **ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|--------|-----------|-----------------|-----------------------------|---------------------------------|
|        |           |                 |                             |                                 |

## 3.3 Impact Mapping
[Poner información aquí]

## 3.4 Product Backlog
[Poner información aquí]

---
# Capítulo IV: Product Design
## 4.1 Style Guidelines
En esta sección, diseñaremos las guías de estilo que son los patrones a seguir para 
construir nuestro producto desde cero, establecen un estándar en la tipografía, tamaño 
y paleta de colores necesarios para que nuestra aplicación web se pueda diseñar de una 
manera más rápida y efectiva desde el inicio del proceso de prototipado.

- ### 4.1.1 General Style Guidelines
A continuación, se mostrará la paleta general de colores para la aplicación, iconos, logo 
y tipografía que usamos para establecer los estilos a la aplicación web.

- ### 4.1.2 Web Style Guidelines
  [Poner información aquí]

## 4.2 Information Architecture
- ### 4.2.1 Organization Systems
 [Poner información aquí]
 
- ### 4.2.2 Labeling Systems
  [Poner información aquí]
  
- ### 4.2.3 SEO Tags and Meta Tags
  [Poner información aquí]
  
- ### 4.2.4 Searching Systems
  [Poner información aquí]
  
- ### 4.2.5 Navigation Systems
  [Poner información aquí]

## 4.3 Landing Page UI Design
- ### 4.3.1 Landing Page Wireframe
  [Poner información aquí]
  
- ### 4.3.2 Landing Page Mock-up
  [Poner información aquí]

## 4.4 Web Applications UX/UI Design
- ### 4.4.1 Web Applications Wireframes
  [Poner información aquí]
  
- ### 4.4.2 Web Applications Wireflow Diagrams
  [Poner información aquí]
  
- ### 4.4.3 Web Applications Mock-ups
  [Poner información aquí]
  
- ### 4.4.4 Web Applications User Flow Diagrams
  [Poner información aquí]

## 4.5 Web Applications Prototyping

[Poner información aquí]

## 4.6 Domain-Driven Software Architecture
- ### 4.6.1 Software Architecture Context Diagram
  [Poner información aquí]
  
- ### 4.6.2 Software Architecture Container Diagrams
  [Poner información aquí]

- ### 4.6.3 Software Architecture Components Diagrams
  [Poner información aquí]
  
## 4.7 Software Object-Oriented Design
- ### 4.7.1 Class Diagrams
  [Poner información aquí]
  
- ### 4.7.2 Class Dictionary
  [Poner información aquí]
  

## 4.8 Database Design
- ### 4.8.1 Database Diagram
   [Poner información aquí]
  
---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
- ### Software Development Environment Configuration
   [Poner información aquí]
- ### Source Code Management
   [Poner información aquí]
- ### Source Code Style Guide & Conventions
   [Poner información aquí]
- ### Software Deployment Configuration
   [Poner información aquí]
  
## 5.2 Landing Page, Services & Applications Implementation.
- ### 5.2.1 Sprint 1
- #### 5.2.1.1. Sprint Planning 1
   [Poner información aquí]
  
- #### 5.2.1.2. Sprint Backlog 1
   [Poner información aquí]
  
- #### 5.2.1.3. Development Evidence for Sprint Review
   [Poner información aquí]
   
- #### 5.2.1.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
   
- #### 5.2.1.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.1.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.1.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]

- #### 5.2.1.8. Team Collaboration Insights during Sprint
   [Poner información aquí]
  

- ### 5.2.2 Sprint 2
- #### 5.2.2.1. Sprint Planning 2
   [Poner información aquí]
  
- #### 5.2.2.2. Sprint Backlog 2
   [Poner información aquí]
  
- #### 5.2.2.3. Development Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.8. Team Collaboration Insights during Sprint
   [Poner información aquí]
  

- ### 5.2.3 Sprint 3
- #### 5.2.3.1. Sprint Planning 3
   [Poner información aquí]
  
- #### 5.2.3.2. Sprint Backlog 3
   [Poner información aquí]
  
- #### 5.2.3.3. Development Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.8. Team Collaboration Insights during Sprint
   [Poner información aquí]

## 5.3 Validation Interviews
- ### 5.3.1. Diseño de Entrevistas
   [Poner información aquí]
  
- ### 5.3.2. Registro de Entrevistas
   [Poner información aquí]
  
- ### 5.3.3. Evaluaciones según heurísticas
   [Poner información aquí]
  

## 5.4 Video About-the-Product

   [Poner información aquí]

