# AgroGes
---

# Carátula
- **Universidad**: UPC
- **Carrera**: Ingeniería de Software
- **Ciclo**: 5
- **Curso**: Desarrollo de Aplicaciones Open Source
- **Sección**: SW51
- **Profesor**: Ángel Augusto Velásquez Núñez

---

# Informe de Trabajo Final
- **Nombre del Startup**: Lux
- **Nombre del Producto**: AgroGes
- **Relación de Integrantes**:
  - Pecan Pariona, Sergio Joel (u20201a938)
  - Landeo Simeón, Favio Sebastián (u202119588)
- **Ciclo**: 2024-1

---

# Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| **Versión** | **Fecha** | **Autor** | **Descripción de Modificación** |
|-------------|-----------|-----------|---------------------------------|
| 1.0         | [22/03/24]   | Andrea Cabanillas Gora  | [Capitulo 1] |
| 1.1         | [25/03/24]   | [Autor]   | [Descripción de modificaciones relevantes] |
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
            - [1.2.2.3 Lean UX Hypothesis Statements](#1211-lean-ux-hyphotesis-statements)
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
Nuestro proyecto se centra en proporcionar una solución que optimice la gestión de productos agrícolas, mejore la calidad de la producción y facilite las operaciones para los productores en la industria agrícola.
![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/130100844/5ba0d247-84f1-4b44-b38b-d1cad0d2f0b8)

### 1.1.1 Descripción de la Startup
AgroGes us una startup que busca poder apoyar a pequeños y medianos agricultores en el desarrollo de sus cultivos. En nuestro compromiso por fortalecer el sector agrícola, ofrecemos una plataforma integral que proporciona información técnica y asesoramiento especializado para optimizar la producción.Nuestro equipo está conformado por profesionales altamente capacitados, listos para brindar orientación sobre las mejores prácticas agrícolas, incluyendo recomendaciones sobre las temporadas ideales para el cultivo, los períodos óptimos de riego, así como consejos sobre el manejo de plagas y enfermedades.Además, facilitamos a los agricultores la posibilidad de programar visitas de nuestros profecionales a sus terrenos para realizar evaluaciones específicas y ofrecer recomendaciones personalizadas. Creemos firmemente en la importancia de la atención individualizada para garantizar un mejor desempeño en sus cultivos.
En resumen, en nuestra plataforma encontrarás el respaldo necesario para impulsar tu producción agrícola, con acceso a información precisa y la asistencia de expertos que te acompañarán en cada etapa del proceso. Juntos, trabajaremos para alcanzar el éxito en tu actividad agrícola.  


### 1.1.2 Perfiles de integrantes del equipo
#### - Favio Sebastián Landeo Simeón
Mi nombre es Favio, tengo 20 años y actualmente estoy cursando el séptimo ciclo de la carrera de Ingeniería de Software. Estoy disponible para ayudar siempre a mis compañeros y además tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo. Tengo experiencia en los lenguajes de programación C++ y Python. En mis tiempos libres me gusta escuchar música, jugar videojuegos y editar videos.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/390b1ef9-ec7f-45c7-9e14-dee2de631e2c" width="300"/>

#### - Gustavo Arturo Poma Espinoza
Mi nombre es Gustavo, actualmente estoy cursando el quinto ciclo de la carrera de Ingeniería de Software. Disfruto escuchando música, ya que siento que esta actividad me inspira creatividad. Salir a caminar con mis mascotas me ayuda a relajarme y meditar. Además, soy aficionado a las artes marciales, las cuales me han inculcado disciplina y perseverancia. Mi color favorito es el azul. Estoy disponible para ayudar siempre a mis compañeros y tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/a107ed14-ee65-463d-b996-8666f02a1297" width="300"/>



#### - Daniel Mateo Del Castillo Bueno
Me encuentro cursando el quinto ciclo de la carrera de Ingeniería de Software. Desde que soy pequeño siempre me he sentido atraído por la tecnología, lo que evolucionó en mi vocación por la programación de software. Tengo conocimientos en Linux, SQL, C++, Python, HTML, CSS y JavaScript. Considero que el mayor aporte que puedo brindar a mi equipo es mi compañerismo y compromiso por ayudar y solucionar problemas para poder brindar un trabajo idóneo.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/d400d572-2e9f-458f-8d13-dd8e70e51387" width="300"/>

### - Sergio Joel Pecan
Soy Sergio Joel Pecan, un estudiante de Ingeniería de Software en la UPC, actualmente en mi quinto ciclo. Desde pequeño, siempre he sentido una gran curiosidad por la tecnología y una pasión por la innovación que me impulsa constantemente a explorar y aprender nuevas cosas. Lo admito, soy un chico difícil de quedarme quieto, pero esa inquietud es mi mayor ventaja. Me encanta estar siempre en movimiento, buscando nuevas formas de innovar y aplicar lo que aprendo en el desarrollo de software. La UPC me ha brindado un entorno perfecto para nutrir mi curiosidad y ampliar mis horizontes tecnológicos.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/4a9fc240-68c7-4b1b-8e8b-2b41a01dfc1a" width="300"/>


### - Andrea Milagros Cabanillas Gora
Soy Andrea, actualmente soy una estudiante de Ingeniería de software, me gusta diseñar paginas web, dibujar y bailar marinera.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/f5173526-5f9c-40cc-92b7-16327f8a5be9" width="300"/>

---

## 1.2 Solution Profile
En un mundo donde la agricultura desempeña un papel importante, la necesidad de herramientas innovadoras que optimicen la gestión y la calidad de la producción agrícola es necesaria. Por eso presentamos un software revolucionario diseñado para transformar la forma en que los productores de cultivos interactúan y gestionan sus operaciones.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/130100844/75561662-33f1-4660-be32-063574f4ead4" width="300"/>

### 1.2.1 Antecedentes y problemática

Los agricultores enfrentan una variedad de problemáticas en diferentes partes del mundo y en diferentes etapas de la cadena de producción agrícola, estos son:
Cambio climático: El cambio climático genera sequías, inundaciones, y cambios en los patrones de temperatura, lo que afecta la productividad de los cultivos y el ganado.
Escasez de agua: En muchas regiones, la disponibilidad de agua para riego es limitada, lo que dificulta la producción agrícola, especialmente en áreas áridas o semiáridas.
Pérdida de suelo: La deforestación, la erosión del suelo y la mala gestión de la tierra pueden llevar a la pérdida de la fertilidad del suelo y a la desertificación, reduciendo la productividad agrícola a largo plazo.
Plagas y enfermedades: Las plagas de insectos, enfermedades de las plantas y malezas pueden dañar los cultivos y reducir los cultivos, lo que resulta en pérdidas económicas para los agricultores.
<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/130100844/42b17f45-d235-4eaf-8794-ee09eb0fb47b" width="300"/>
### 1.2.2 Lean UX Process
Nuestro software ofrece un sistema de gestión agrícola que aborda los desafíos que enfrentan los agricultores. Dirigido principalmente a los productores de cultivos, nuestro proyecto proporciona herramientas para la planificación de cultivos, la gestión de insumos. Además, ofrece un detallado de cultivos que permite a los agricultores realizar un seguimiento de sus operaciones y tomar decisiones informadas para mejorar la calidad y la productividad de sus cultivos.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/130100844/fa430c2b-d955-451e-910e-e04abc24aded" width="300"/>

#### 1.2.2.1 Lean UX Problem Statements
Algunos desafios que podemos enfrentar como grupo son la adopción y capacitación ya que no podemos asegurar que los usuarios,adopten la aplicación y comprendan cómo usarla de manera efectiva, tambien garantizar que los usuarios tengan acceso a la tecnología necesaria, como dispositivos móviles o computadoras y conexión a internet, por ultimo garantizar la seguridad y privacidad de los datos de los usuarios, especialmente cuando se trata de información sobre la producción agrícola.


#### 1.2.2.2 Lean UX Assumptions
Los usuarios están abiertos a la idea de utilizar una aplicación para gestionar sus operaciones agrícolas, en lugar de los métodos tradicionales.
La aplicación resolverá problemas reales ya que abordará desafíos concretos que enfrentan los agricultores,como la planificación de cultivos, la gestión de insumos y la optimización de la cadena de suministro
los usuarios comprenderán rápidamente cómo utilizar la aplicación y verán su valor para mejorar la eficiencia y la calidad en sus operaciones agrícolas.
La aplicación podrá adaptarse fácilmente a diferentes entornos agrícolas, desde pequeñas granjas familiares hasta grandes operaciones comerciales, y satisfacer las necesidades específicas de cada usuario.

#### 1.2.2.3 Lean UX Hypothesis Statements

Esperamos que la aplicación aumente la productividad agrícola.
Esperamos mejorar la calidad de los productos.
 Esperamos reducir las pérdidas de los cultivos.
Esperamos que los agricultores se adapten a la tecnología y se modernicen.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/8fc1bada-3b36-4cb8-af0b-28aae21a446b" width="300"/>

#### 1.2.2.4 Lean UX Canvas
<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/d39d3b40-da81-48cb-9bbd-3738bfab9b88" width="500"/>


---

## 1.3 Segmentos objetivo
El software está dirigido a los usuarios dentro del sector agrícola, incluyendo productores de cultivos individuales, agricultores familiares, empresas agrícolas, cooperativas agrícolas, exportadores de productos agrícolas, organizaciones sin fines de lucro , consultores agrícolas y cualquier persona novata que desee aprender sobre agricultura.

<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/130100844/5ba1adc0-97a6-4fb3-9bb3-0f1a1e1f163a" width="500"/>

---
# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
Dentro del mercado al que planeamos brindar una solución, pudimos identificar varios competidores que ofrecen una solución con un enfoque similar para la gestión agrícola. A continuación, resumiremos su solución de Software:

**Agrobit:** Agrobit es una herramienta de gestión de gestión agrícola y ganadera que busca nuevas formas de producir alimentos de manera sustentable y rentable. Esta solución tiene como enfoque las grandes empresas. Su plataforma cuenta con funciones como, control de actividades, evolución de cultivos y monitoreo predictivo y trazabilidad y huella de carbono. <br>
**Efemis:** Efemis es una plataforma digital para la gestión agricola, utiliza imagenes satelitales, predicciones del clima y sensores para controlar los costes y optimizar los costes de operaciones agricolas. Es una iniciativa creada por hispatec que cuenta con soluciones diferentes para el sector agrícola para tareas más especificas, sin embargo, Efemis es la principal.<br>
**Agri:** Agri es un software especializado en el sector agrícola que permite gestionar órdenes de aplicación, control de faenas, cosecha y riego, entre otras funciones. Para acceder a sus servicios, el territorio agrícola debe ser revisado y categorizado por el tamaño del mismo, posteriormente se hace un cobro mensual que va desde 320 dólares para las pequeñas empresas agrícolas hasta 715 dólares para las empresas agrícolas grandes.<br>
### 2.1.1 Análisis competitivo

¿Por que llevar a cabo este análisis? 
Debemos llevar a cabo este análisis para poder saber en que se especializan nuestros competidores directos y poder encontrar algún aspecto en el que podamos destacar y llamar la atención del mercado objetivo

| Nombre | [Agroges] | [Agrobit] | [Efemis] | [Agri] |
|--------- |-----------|-----------|----------|-----------|
| Overview | Software de gestión agricola centrado en la capacitación del usuario que puede adaptarse a sus necesidades  | Software enfocado en la gestión de procesos agrícolas y ganaderos con ayuda de herramientas de alta gama | Software de hispatec que gestiona procesos agrícolas utilizando herramientas de alta gama  | Agri es una solución de software latina que permite gestionar campos de cultivo de forma centralizada  | 
| Ventaja Competitiva | Esta aplicación está entrada en el usuario y su adaptabilidad, brindandole a este una opción cómoda al alcane de sus manos | Uso de herramientas de alta gama como imagenes satelitales que son una alternativa que brinda una seguridad total | Este software modular, está diseñado para que el usuario quiera añadir más funcionalidades que se acoplen a sus necesidades | Empresa latinoamericana con la que los usuarios se sienten más cómodos|
| Mercado Objetivo | Nos enfocaremos en los pequeños y grandes agricultores que no hayan implementado tecnología para aligerar su carga laboral | Se centra en el sector ganadero y agrícola que buscan implementar una solucion tecnológica con herramientas de gama alta, como imagenes satelitales | Sector agrícola grande que busca una solución de software para agilizar procesos | Está centrado en pequeñas, medianas y grandes empresas agrícolas  | 
| Estrategias de marketing | Nos acercaremos a los empresarios agrícolas que no confían en la tecnología para que podamos demostrar la eficacia de esta | Se promociona mediante publicidad como google ads, correos,etc. | Utiliza publicidad y estrategias de marketing | Agri usa sus redes sociales como Instagram y Linkedin para poder difundir sus propuestas de valor| 
| Productos y Servicios| Ofrecemos una amplia variedad de recursos para el usuario como, control de inventario, predicciones del clima, sensores de humedad y temperatura, monitoreo de ventas, predicciones para las cosechas y un control de ventas| Cuenta con dos versiones, la ECO, una versión dedicada para una producción netamente sostenible, y la Enterprise, dedicada a conseguir el mayor beneficio económico para la empresa. Ambas opciones cuentan con planes de pago diferentes que varían, dandole a las grandes empresas agricolas más ventajas que a las más pequeñas | Efemis cuenta con un control de costos de operaciones, monitoreos de cumplimiento de normativas,gestion de actividades, tratamientos y riegos,entre otras | Agri cuenta con controles de faenas, compras y bodegaje, control de riego, entre otros. | 
| Precios y Costos| Planeamos cobrar una comisión por venta de productos, los usuarios podrán acceder a nuestros servicios sin mayor problema | Agrobit cuenta con planes mensuales que rondan los 250 hasta los 1100 dólares | Cuenta con planes principalmente desde los 300 hasta los 900 euros mensuales | Cuenta con 3 planes para los pequeños, medianos y grandes agricultores cuyos costos van desde los 320 hasta los 750 dólares | 
| Fortalezas | Contamos con un software ágil, que se verá sujetos a cambios rápidos para acomodarnos a las necesidades del usuario | Cuenta con una reputación y una clientela fiel | Es parte de una corporación grande que facilita acceso a herramientas de gama alta | Cuenta con clientes en todo latinoamerica sobre todo Chile y Perú | 
| Debilidades | Sujeta a pruebas | Está cerrada a sus clientes habituales y los clientes nuevos no parecen interesados en su producto | No cuenta con una gran cantidad de clientes, las reseñas no son buenas y está siendo dejada de lado | No parece querer modernizarse más allá de su estado actual | 
| Oportunidades| Muchas de las gestiones agrícolas en nuestro país son deficientes y gran parte de las cosechas son desperdiciadas, por ello el Perú es un país ideal para implementar agroges  | Dadas sus herramientas presenta una estabilidad que les permitiría desarrollarse más | Cuenta con acceso a herramientas de gama alta que permiten el recopilado de información detallada para beneficio del usuario |    Cuenta con el apoyo de clientes de más de un país por ello pueden expandirse por todo latinoamerica | 
| Amenazas| La implementación de herramientas costosas por parte de la competencia | Dado que el proceso de cotización es lento, muchos clientes prefieren buscar otras opciones | Sus ventas se han visto reducidas  | La creciente tecnología y el uso de la inteligencia artificial puede desplazar a muchas soluciones de software | 

### 2.1.2 Estrategias y tácticas frente a competidores

Nos enfocaremos en el sector que no cuenta con tecnología, brindando una solución accesible e intuitiva para que personas que no están familiarizadas con el apartado tecnológico puedan dominar para el uso eficiente de sus recursos.
<br><br>
**Estrategia general**: Diferenciacición <br>
**Objetivo principal:** Destacar ante la competencia enfocandonos en hacer un producto que pueda satisfacer necesidades específicas de nuestros segmentos objetivos.
<br> <br>
**Estrategias Clave:**<br>
<ul>
    <li>Enfoque al usuario: Concentrarse en hacer mejoras basadas en lo que nuestros clientes soliciten </li>
    <li>Control de usuarios: Nuestra aplicación contará con una red interconectada de 
        usuarios en las que se puede llevar un control de los trabajadores bajo el mando del usuario administrador</li>
</ul>

## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas
**Segmento 1: Pequeños agricultores**<br>
¿Cúal es su nombre?<br>
¿Qué produce?<br>
¿Cúanto lleva trabajando en el sector agrícola?<br>
¿Considera que la gestión de sus huertas de cultivo es una tarea pesada?<br>
¿Usa alguna herramienta tecnológica para ayudarse?<br>
¿Estaría dispuesto a incluir una solución de Software para agilizar sus procesos?<br>
¿Que caracteristicas cree que debería implementar el Software?<br>

**Segmento 2: Grandes agricultores**<br>
¿Cuál es el su nombre y Razón Social de su empresa?<br>
¿Qué produce?<br>
¿Cúanto tiempo lleva trbajando en el negocio agrícola?<br>
¿Considera que la gestión de sus hectáreas de cultivo es una tarea pesada?<br>
¿Cómo gestiona sus actividades agrícolas, Cuenta con alguna herramienta tecnológica para ayudarse?<br>
¿Qué características buscó en el software para elegirlo?<br>
¿Consideraría cambiar los software que usa por uno solo en el que pueda hacer todo el trabajo?<br>
¿Qué características adicionales cree que debería tener nuestra nueva herramienta?<br>

### 2.2.2 Registro de entrevistas
### 2.2.3 Análisis de entrevistas

---

## 2.3 Needfinding
### 2.3.1 User Personas
![Brainstorming User Persona Experiencia De Usuario Estético Lila](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/3f8f9cd5-b6ff-46b6-970c-5f39c9e95ab4)

![Brainstorming User Persona Experiencia De Usuario Estético Lila (2)](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/b350c893-1ea9-4e10-87b6-84f42f2e54a6)



### 2.3.2 User Task Matrix
[Poner información aquí]

### 2.3.3 User Journey Mapping
[Poner información aquí]

### 2.3.4 Empathy Mapping
[Poner información aquí]

### 2.3.5 As-is Scenario Mapping
User persona 1: <br>

| Fases | Iniciar sesión | Revisar el progreso de las cosechas | Revisar el progreso de mis trabajadores | Revisar el pronostico de cosechas |
|-------|-----------------|--|--|--|
| Doing |  |  |  |  |
| Thinking |  |  |  |  |
| Feeling |  |  |  |  |

User persona 2: <br>

| Fases | Iniciar sesión | Revisar el progreso de las cosechas | Revisar el progreso de mis trabajadores | Revisar el pronostico de cosechas |
|-------|-----------------|--|--|--|
| Doing |  |  |  |  |
| Thinking |  |  |  |  |
| Feeling |  |  |  |  |

---

## 2.4 Ubiquitous Language
[Poner información aquí]

---

# Capítulo III: Requirements Specification
## 3.1 To-Be Scenario Mapping
<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/bb941e93-3157-4f28-b29a-a3c0b2f3c380" width="500"/>

| **Epic ID** | **Título** |
|--------|-----------|
|EPIC001|Planificación de Cultivos y Gestión de Insumos|
|EPIC002|Seguimiento de Operaciones y Toma de Decisiones|
|EPIC003|Comunicación y Colaboración|
|EPIC004|Evaluación y Adaptación|

## 3.2 User Stories

| **Epic ID** | **Título** |
|--------|-----------|
|EPIC001|Planificación de Cultivos y Gestión de Insumos|
|EPIC002|Seguimiento de Operaciones y Toma de Decisiones|
|EPIC003|Comunicación y Colaboración|
|EPIC004|Evaluación y Adaptación|


| **ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|--------|-----------|-----------------|-----------------------------|---------------------------------|
| US001 | Planificar la Temporada de Cultivo | Como agricultor, quiero crear un plan de cultivo detallado para la próxima temporada, asignando recursos como semillas, fertilizantes y agua a cada cultivo. | - **Dado** que accedo a la aplicación, **Cuando** planifico la próxima temporada de cultivo, **Entonces** puedo crear un **calendario de siembra** que especifique las fechas de siembra para cada cultivo. - **Dado** que asigno recursos a los cultivos, **Cuando** especifico **recursos específicos** como semillas, fertilizantes y agua para cada tipo de cultivo dentro del plan, **Entonces** la aplicación me permite guardar y editar mi plan de cultivo. - **Dado** que establezco metas de producción, **Cuando** considero las **condiciones climáticas** y la **disponibilidad de insumos**, **Entonces** puedo ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. | EPIC001 |
| US002 | Definir Objetivos de Rendimiento | Como agricultor, quiero establecer metas de producción específicas para cada tipo de cultivo, considerando las condiciones climáticas y la disponibilidad de insumos. | - **Dado** que accedo a la aplicación, **Cuando** establezco objetivos de rendimiento para cada cultivo, **Entonces** la aplicación permite ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. - **Dado** que considero las **condiciones climáticas** y la **disponibilidad de insumos**, **Cuando** establezco metas de producción, **Entonces** puedo ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. | EPIC001 |
| US003 | Seguimiento Detallado de Actividades Agrícolas | Como agricultor, quiero registrar datos diarios sobre las operaciones realizadas en cada cultivo, como riego, fertilización y control de plagas. | - **Dado** que accedo a la aplicación, **Cuando** registro datos diarios sobre las operaciones agrícolas, **Entonces** puedo incluir información sobre **riego, fertilización y tratamientos fitosanitarios** para cada cultivo. - **Dado** que registro datos diarios, **Cuando** agrego detalles específicos sobre cada actividad, como la cantidad de agua utilizada o el tipo de fertilizante aplicado, **Entonces** la aplicación me permite guardar y visualizar estos registros. - **Dado** que registro datos diarios, **Cuando** incluyo información sobre las operaciones realizadas en cada cultivo, **Entonces** la aplicación me permite agregar detalles específicos sobre cada actividad. | EPIC002 |
| US004 | Visualización de Métricas de Rendimiento | Como agricultor, quiero visualizar gráficos y métricas que muestren el progreso de mis cultivos para evaluar su rendimiento y tomar decisiones informadas. | - **Dado** que accedo a la aplicación, **Cuando** visualizo gráficos y métricas sobre el crecimiento y rendimiento de mis cultivos, **Entonces** la aplicación muestra gráficos claros y métricas relevantes sobre el crecimiento y rendimiento de mis cultivos. - **Dado** que comparo el rendimiento actual con mis objetivos de producción establecidos, **Cuando** identifico áreas de mejora basadas en los datos históricos, **Entonces** puedo tomar medidas correctivas para optimizar futuras temporadas de cultivo. | EPIC002 |
| US005 | Mensajes Internos y Notificaciones | Como agricultor, quiero enviar mensajes a otros usuarios dentro de la aplicación para coordinar con mi equipo, proveedores y compradores. |- **Dado** que accedo a la aplicación, **Cuando** envío mensajes a otros usuarios registrados en la aplicación, **Entonces** puedo coordinar con mi equipo, proveedores y compradores. - **Dado** que envío mensajes, **Cuando** recibo notificaciones sobre ofertas de compra o venta, **Entonces** puedo considerar oportunidades de negocio y tomar decisiones informadas. - **Dado** que accedo a la aplicación, **Cuando** accedo a información actualizada sobre precios de mercado y demanda, **Entonces** puedo tomar decisiones estratégicas basadas en datos en tiempo real.| EPIC003 |
| US006 | Precios y Demandas en Tiempo Real | Como agricultor, quiero recibir notificaciones sobre ofertas de compra o venta, y acceder a información actualizada sobre precios y demanda. | - **Dado** que accedo a la aplicación, **Cuando** la aplicación muestra información actualizada sobre precios de mercado y demanda de productos agrícolas, **Entonces** puedo tomar decisiones informadas sobre mis cultivos. - **Dado** que configuro notificaciones, **Cuando** recibo alertas sobre cambios significativos en los precios o demanda, **Entonces** puedo reaccionar rápidamente a las oportunidades del mercado. - **Dado** que accedo a la aplicación, **Cuando** accedo a información actualizada sobre precios de mercado y demanda, **Entonces** puedo tomar decisiones estratégicas basadas en datos en tiempo real. | EPIC003 |
| US007 | Informe de Rendimiento Histórico | Como agricultor, quiero generar informes que resuman el rendimiento de mis cultivos en temporadas anteriores para identificar áreas de mejora. | - **Dado** que accedo a la aplicación, **Cuando** genero informes detallados sobre el rendimiento de mis cultivos en temporadas anteriores, **Entonces** los informes incluyen métricas clave como rendimiento por cultivo, costos y ganancias. - **Dado** que reviso los informes, **Cuando** identifico áreas de mejora basadas en los datos históricos, **Entonces** puedo tomar medidas correctivas para optimizar futuras temporadas de cultivo. - **Dado** que accedo a los informes, **Cuando** evalúo el rendimiento pasado, **Entonces** reflexiono sobre las decisiones tomadas y busco oportunidades de mejora. | EPIC004 |
| US008 | Adaptación a Cambios | Como agricultor, quiero adaptar mi estrategia según los cambios en el entorno o las condiciones climáticas, reflexionando sobre las decisiones tomadas. | - **Dado** que accedo a la aplicación, **Cuando** realizo ajustes en mi plan de cultivo en función de cambios en el clima, disponibilidad de insumos o resultados del rendimiento pasado, **Entonces** puedo adaptar mi estrategia de cultivo de manera ágil y efectiva. - **Dado** que considero las **condiciones climáticas** y la **disponibilidad de insumos**, **Cuando** ajusto mi plan de cultivo, **Entonces** la aplicación me proporciona sugerencias o consejos basados en análisis de datos para ayudar en la toma de decisiones de adaptación. - **Dado** que accedo a la aplicación, **Cuando** reflexiono sobre las decisiones tomadas y busco oportunidades de mejora, **Entonces** puedo tomar medidas correctivas para optimizar futuras temporadas de cultivo. | EPIC004 |

### Technical Stories


| **ID** | **Título** |
|--------|------------|
| TEPIC001 | Landing Page |
| TEPIC002 | RESTful API |
:

| **ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|--------|------------|----------------|-----------------------------|-------------------------------|
| T01    | Explorar la Página de Inicio | Como visitante, quiero explorar la página de inicio para obtener una visión general del sitio web y sus secciones. | - Dado que soy un visitante, cuando ingreso a la página de inicio, entonces debo ver una breve descripción del propósito del sitio. - Dado que soy un visitante, cuando navego por la página de inicio, entonces debo encontrar enlaces o botones que dirijan a las diferentes secciones del sitio. - Dado que soy un visitante, cuando hago clic en un enlace de una sección, entonces debo ser llevado a la página correspondiente. | TEPIC001 |
| T02    | Ver Información de Productos/Servicios | Como visitante, quiero ver información detallada sobre los productos o servicios ofrecidos. | - Dado que soy un visitante, cuando accedo a la página de un producto/servicio, entonces debo ver una descripción detallada, imágenes y detalles relevantes. - Dado que soy un visitante, cuando busco información sobre un producto/servicio, entonces debo encontrar la información fácilmente. - Dado que soy un visitante, cuando navego por la página de un producto/servicio, entonces debo poder regresar a la página de inicio con facilidad. | TEPIC001 |
| T03    | Contactar al Equipo de Ventas | Como visitante interesado, quiero encontrar una forma de contactar al equipo de ventas. | - Dado que soy un visitante interesado, cuando busco información de contacto, entonces debo encontrar un formulario de contacto o información clara de contacto. - Dado que soy un visitante interesado, cuando lleno el formulario de contacto, entonces debo recibir una confirmación de que mi mensaje fue enviado correctamente. - Dado que soy un visitante interesado, cuando envío un mensaje al equipo de ventas, entonces debo recibir una respuesta dentro de las 24 horas. | TEPIC001 |
| T04    | Explorar Testimonios o Casos de Éxito | Como visitante, quiero leer testimonios o casos de éxito para evaluar la confiabilidad del sitio. | - Dado que soy un visitante, cuando busco testimonios o casos de éxito, entonces debo encontrar testimonios reales o estudios de caso. - Dado que soy un visitante, cuando leo un testimonio o caso de éxito, entonces debo encontrar información relevante y convincente. - Dado que soy un visitante, cuando leo los testimonios o casos de éxito, entonces debo sentir confianza en el sitio y sus productos/servicios. | TEPIC001 |
| T05    | Configurar el Entorno de Desarrollo | Como desarrollador, necesito configurar el entorno de desarrollo local para trabajar en el sitio web. | - Dado que soy un desarrollador, cuando configuro el servidor local, entonces debo asegurarme de tener instaladas las herramientas de desarrollo necesarias. - Dado que soy un desarrollador, cuando configuro las variables de entorno, entonces debo asegurarme de que estén correctamente configuradas para mi entorno local. - Dado que soy un desarrollador, cuando ejecuto el servidor local, entonces debo asegurarme de que el sitio web se cargue correctamente en mi navegador. | TEPIC002 |
| T06    | Crear Componentes Reutilizables | Como desarrollador, quiero crear componentes reutilizables (por ejemplo, encabezado, pie de página) para mantener la consistencia en todo el sitio. | - Dado que soy un desarrollador, cuando creo componentes reutilizables, entonces debo asegurarme de que estén bien estructurados y documentados. - Dado que soy un desarrollador, cuando uso los componentes reutilizables en diferentes partes del sitio, entonces debo garantizar la consistencia visual y funcional en todo el sitio. - Dado que soy un desarrollador, cuando necesito realizar cambios en un componente reutilizable, entonces debo poder hacerlo de manera rápida y eficiente sin afectar otras partes del sitio. | TEPIC002 |
| T07    | Implementar Rutas y Navegación | Como desarrollador, necesito implementar rutas y navegación para que los visitantes puedan acceder a diferentes secciones del sitio. | - Dado que soy un desarrollador, cuando implemento las rutas de navegación, entonces debo asegurarme de que los enlaces funcionen correctamente y lleven a las páginas correspondientes. - Dado que soy un desarrollador, cuando navego por el sitio, entonces debo poder regresar a la página anterior utilizando el botón de retroceso del navegador. - Dado que soy un desarrollador, cuando implemento la navegación entre páginas, entonces debo asegurarme de que sea intuitiva y fácil de usar para los visitantes. | TEPIC002 |
| T08    | Desarrollar el RESTful API | Como desarrollador, necesito implementar las funciones del RESTful API para manejar solicitudes y respuestas. | - Dado que soy un desarrollador, cuando desarrollo el RESTful API, entonces debo crear endpoints para obtener información de productos/servicios, enviar formularios de contacto, etc. - Dado que soy un desarrollador, cuando desarrollo el RESTful API, entonces debo documentar los endpoints utilizando Gherkin para escenarios de interacción request/response. - Dado que soy un desarrollador, cuando desarrollo el RESTful API, entonces debo asegurarme de que los endpoints estén protegidos contra ataques de seguridad, como inyecciones SQL o XSS. | TEPIC002 |
## 3.3 Impact Mapping

| **Business Goals** | **Actors/Personas** | **Impact** | **Deliverables** | **User Stories** |
|--------------------|---------------------|------------|------------------|------------------|
| Alcanzar 600 usuarios suscritos al plan A en el lapso de 8 meses | Aldo Gomez | Aldo debe aprender a utilizar la tecnología para administrar su negocio y monitorear sus cultivos. | Una solución de software fácil de usar que permita a Aldo administrar su negocio y monitorear sus cultivos. | "Como Aldo, deseo poder monitorear mis cultivos a través de una aplicación para mejorar la eficiencia de mi negocio." |
| Monitorear más sus cultivos | Aldo Gomez | Aldo debe aprender a utilizar la tecnología para administrar su negocio y monitorear sus cultivos. | Una solución de software fácil de usar que permita a Aldo administrar su negocio y monitorear sus cultivos. | "Como Aldo, deseo poder monitorear mis cultivos a través de una aplicación para mejorar la eficiencia de mi negocio." |
| Expandir la marca para llegar a mercados extranjeros | Antonio Herrera | Antonio necesita encontrar una herramienta confiable que satisfaga todas sus necesidades y le permita expandir su negocio. | Una solución de software integral que permita a Antonio gestionar todos los aspectos de su negocio agrícola. | "Como Antonio, deseo tener una herramienta que me permita gestionar todos los aspectos de mi negocio para poder expandir mi marca a mercados extranjeros." |
| Buscar herramientas nuevas que satisfagan las necesidades | Antonio Herrera | Antonio necesita encontrar una herramienta confiable que satisfaga todas sus necesidades y le permita expandir su negocio. | Una solución de software integral que permita a Antonio gestionar todos los aspectos de su negocio agrícola. | "Como Antonio, deseo tener una herramienta que me permita gestionar todos los aspectos de mi negocio para poder expandir mi marca a mercados extranjeros." |
| Ser más eficiente | Antonio Herrera | Antonio necesita encontrar una herramienta confiable que satisfaga todas sus necesidades y le permita expandir su negocio. | Una solución de software integral que permita a Antonio gestionar todos los aspectos de su negocio agrícola. | "Como Antonio, deseo tener una herramienta que me permita gestionar todos los aspectos de mi negocio para poder expandir mi marca a mercados extranjeros." |


## 3.4 Product Backlog
| **#Order** | **User Story Id** | **Título** | **Descripción** |  **Story Points (1 / 2 / 3 / 5 / 8)** |
|------------|-------------------|------------|-----------------|-------------------------------------|
| 1          | US001              | Planificar la Temporada de Cultivo | "Como agricultor, quiero crear un plan de cultivo detallado para la próxima temporada, asignando recursos como semillas, fertilizantes y agua a cada cultivo." | 3 |
| 2          | US002              | Definir Objetivos de Rendimiento |  "Como agricultor, quiero establecer metas de producción específicas para cada tipo de cultivo, considerando las condiciones climáticas y la disponibilidad de insumos." | 2 |
| 3          | US003              | Seguimiento Detallado de Actividades Agrícolas |  "Como agricultor, quiero registrar datos diarios sobre las operaciones realizadas en cada cultivo, como riego, fertilización y control de plagas." | 5 |
| 4          | US004              | Visualización de Métricas de Rendimiento | "Como agricultor, quiero visualizar gráficos y métricas que muestren el progreso de mis cultivos para evaluar su rendimiento y tomar decisiones informadas." | 3 |
| 5          | US005              | Mensajes Internos y Notificaciones |  "Como agricultor, quiero enviar mensajes a otros usuarios dentro de la aplicación para coordinar con mi equipo, proveedores y compradores." | 3 |
| 6          | US006              | Precios y Demandas en Tiempo Real |  "Como agricultor, quiero recibir notificaciones sobre ofertas de compra o venta, y acceder a información actualizada sobre precios y demanda." | 5 |
| 7          | US007              | Informe de Rendimiento Histórico | "Como agricultor, quiero generar informes que resuman el rendimiento de mis cultivos en temporadas anteriores para identificar áreas de mejora." | 3 |
| 8          | US008              | Adaptación a Cambios |  "Como agricultor, quiero adaptar mi estrategia según los cambios en el entorno o las condiciones climáticas, reflexionando sobre las decisiones tomadas." | 5 |



---
# Capítulo IV: Product Design
## 4.1 Style Guidelines
En esta sección, diseñaremos las guías de estilo que son los patrones a seguir para 
construir nuestro producto desde cero, establecer un estándar en la tipografía, tamaño 
y paleta de colores necesarios para que nuestra aplicación web se pueda diseñar de una 
manera más rápida y efectiva desde el inicio del proceso de prototipado. Todo esto
desarrollándolo bajo un repositorio común en GitHub.

- ### 4.1.1 General Style Guidelines
A continuación, se mostrará la paleta general de colores para la aplicación, iconos, logo 
y tipografía que hemos escogido para nuestra aplicación web.

Decidimos que para nuestra aplicación apliquemos una interfaz simple y fácil de entender con colores vivos que capten la
atención del usuario. También esta característica ayuda en el rendimiento de la aplicación, por lo que el tiempo de espera del usuario será el mínimo.

- ### 4.1.2 Web Style Guidelines
Hemos escogido optar por un tono de comunicación y un lenguaje serio y casual con palabras simples 
para que cualquier usuario puedan entender fácilmente las funcionalidades de nuestra aplicación. 
Además, nosotros hemos decidido desarrollar una landing page y una aplicación web con interacción responsiva para 
adaptarse a diferentes dispositivos facilitando la comprensión y adaptabilidad del contenido.


## 4.2 Information Architecture
- ### 4.2.1 Organization Systems
En esta parte sintetizamos la estructura del sistema en dos partes: la landing page y la aplicación web.
La primera está destinada a contener la información sobre el proyecto y nuestro equipo; mientras que la segunda tratará
las funcionalidades y la lógica de negocio.
 
 
- ### 4.2.2 Labeling Systems
Como anteriormente hemos explicado, se presenta el contenido con un lenguaje serio y casual para garantizar una mayor comprensión. 
A continuación explicaremos los conjuntos de información dentro de nuestra landing page.

| **Título** | **Descripción** |
|------------|-----------------|
| Inicio     | Aquí se expone un vistazo general de lo que ofrece nuestro proyecto |
| Servicios  | Se presentan algunas de las funcionalidades y características que ofrece nuestra aplicación web |
| Equipo     | En esta sección los visitantes pueden conocer a los miembros del equipo de desarrollo de AgroGes |
| Tarifas    | Se exponen los planes de suscripción que ofrecemos |
| Contacto   | En esta parte se encuentran las redes sociales de nuestro proyecto |
   
- ### 4.2.3 SEO Tags and Meta Tags
Para ayudar a destacar y diferenciar a nuestro sitio web se tienen que tener ciertas etiquetas específicas para ayudarnos a tener mejor exposición en diferentes
motores de búsqueda.
  - Título de Landing Page y Web Application: AgroGes.
  - Descripción: Agroges servicio de consultoría y planeamiento agrícola.
  - Palabras clave: agricultura, planeación, cultivo, plantas.
  - Autores: Equipo Lux.
  
- ### 4.2.4 Searching Systems
Dentro de nuestra landing page el usuario tiene la libertad de observar y conocer las características del proyecto y el equipo de desarrollo. 
También se podra acceder a la aplicación web donde ofrecemos las funcionalidades que nuestro segmento objetivo necesita. Algunas de las funcionalidades que
nuestro usuario puede encontrar luego de realizar la búsqueda dentro de nuestra aplicación web son:
 - Registrar tipo de cultivo
 - Listado de cultivos
 - Ajustes de notificaciones
 - Seguimiento de cultivo
 - Visualización de perfil
 - Visualizar consejos
  
  
- ### 4.2.5 Navigation Systems
El visitante o usuario dentro de nuestra landing page podrán explorar el contenido mediante la barra de desplazamiento ubicada en la parte derecha. Además,
los encabezados funcionan como botones que ayudan a explorar la página de manera más precisa. Esto ayuda a que nuestro sitio web tenga una interacción intuitiva y simple.

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

  ![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/94254725-59fd-4cec-814d-fc1bec11d1a5)

  
- ### 4.7.2 Class Dictionary

  Company: Empresas a las que se les brinda el servicio.
  Crop: Es el cultivo al cual se le monitorea y administra.
  Worker: Personas que trabajan en las diferentes compañías agrícolas.
  Equipment: Conjunto de Workers encargados de un Crop
  Collection pending: Son las cobranzas pendientes de una empresa por los productos o servicios que ofrece.
  Pending payment: Son las deudas pendientes de una Company.
  Balance: Esta clase se crea mensualmente y determina las ganancias de la Company.

  
## 4.8 Database Design
- ### 4.8.1 Database Diagram

   ![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/49e99b2d-0e83-4f81-8212-26e32d032e54)

  
---

## 5.1 Software Configuration Management
- ### Software Development Environment Configuration

 **HTML (HyperText Markup Language):** Para estructurar el contenido de la página web.
 
 **CSS (Cascading Style Sheets):** Para diseñar y dar estilo al contenido HTML.
 
 **JavaScript:** Para agregar interactividad y funcionalidad a la página web.
 
 **C# (C Sharp):** Para el desarrollo del backend de la aplicación.
 
 **SQL Server:** Como sistema de gestión de bases de datos relacionales para almacenar y manejar los datos de la aplicación.
 
 **Visual Studio:** Como entorno de desarrollo integrado (IDE) para el desarrollo de la aplicación web, especialmente para el desarrollo en C# y la gestión de la base de 
 datos SQL Server.
 
 **Visual Studio Code:** Como editor de código ligero y altamente personalizable que también puede ser utilizado para el desarrollo web, incluyendo soporte para HTML, CSS, 
 JavaScript y C#.
 
 **Git y GitHub:** Para el control de versiones y la colaboración en el desarrollo del proyecto.
 
 **ASP.NET:** Un framework de desarrollo web como para facilitar el desarrollo del backend en C#
   
- ### Source Code Management

 Repositorio del Landing Page : 

 https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes

En el marco de este proyecto, se implementarán tres ramas principales: "master", "develop" y "feature branches".

La rama "feature branches" se destinará específicamente para la creación de nuevas funcionalidades, clases u otros elementos que añadirán nuevas capacidades al proyecto. Esta rama servirá como un entorno aislado para el desarrollo de estas características, permitiendo un trabajo paralelo sin afectar la estabilidad del código principal.

La rama "develop" funcionará como el entorno de integración continua, donde se unificarán y probarán los cambios provenientes de las ramas de características. En este entorno, los cambios deben ser integrados y asegurados para garantizar el funcionamiento cohesivo del proyecto.

Finalmente, la rama "master" será la rama principal y estable del repositorio. Aquí se fusionarán todos los cambios provenientes de la rama "develop", generando así nuevas versiones del sistema. Esta rama representa el estado más actualizado y confiable del proyecto, adecuado para su despliegue en entornos de producción.

Este enfoque de ramificación permite una gestión eficiente del desarrollo, facilitando la colaboración entre equipos y asegurando la estabilidad y calidad del software en cada etapa del ciclo de vida del proyecto.
  
- ### Source Code Style Guide & Conventions

En el proceso de realizar commits, hemos optado por seguir el estándar de "Conventional Commits". Esta práctica nos brinda una estructura definida para nuestros mensajes de commit, lo que facilita la comprensión y la gestión de cambios en el repositorio.

Además, hemos establecido el uso de terminología en inglés para las diferentes declaraciones en nuestras líneas de código en todos los lenguajes de programación empleados en el proyecto. Esta decisión busca promover la coherencia y la claridad en la comunicación del código, facilitando la colaboración entre miembros del equipo y mejorando la legibilidad del código fuente en general.
  
- ### Software Deployment Configuration

Requisitos del sistema: Especifica los requisitos mínimos para ejecutar el proyecto 
  Hardward:
  Procesador	Intel Xeon E-2324G 
  Disco duro	10TB
  Memoria	64GB DDR4
  
  Sistema Operativo: 
  Windows server 
  
Plataforma de alojamiento: La plataforma de alojamiento que utilizarás para desplegar la página web 
  Microsoft Azure 

Configuración del servidor: Configuración del servidor necesario para alojar el sistema
  Node.js
  Angular
  SQL server 
Configuración de la base de datos: Configuración necesaria para instalar y configurar la base de datos
 Istalar SQL server 
 Crear la base de datos de AgroGes
 Crear las tablas de las entidades mensionadas 


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

