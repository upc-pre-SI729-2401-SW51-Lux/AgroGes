<p align="center">
AgroGes
</p>
 <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
Ingeniería de Software

Desarrollo de Aplicaciones Open Source - SW51

Profesor: Ángel Augusto Velásquez Núñez

<p align="center">
# Informe 
- *Startup**: Lux
- **Producto**: AgroGes
- **Relación de Integrantes**:
  - Pecan Pariona, Sergio Joel (u20201a938)
  - Landeo Simeón, Favio Sebastián (u202119588)
  - Cabanillas Gora, Andrea Milagros (u202211711)
  - Poma Espinoza, Gustavo Arturo (u20221c138)
  - Del Castillo, Bueno Daniel Mateo (u202211212)
- **Ciclo**: 2024-1
</p>

- <div>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Pecan Pariona, Sergio Joel</td>
            <td>u20201a938</td>
        </tr>
        <tr>
            <td>Landeo Simeón, Favio Sebastián</td>
            <td>u202119588</td>
        </tr>
        <tr>
            <td>Cabanillas Gora, Andrea Milagros</td>
            <td>u202211711</td>
        </tr>
        <tr>
            <td>Poma Espinoza, Gustavo Arturo</td>
            <td>u20221c138</td>
        </tr>
         <tr>
            <td>Del Castillo, Bueno Daniel Mateo</td>
            <td>u202211212</td>
        </tr>
    </table>
</div>


---

# Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| **Versión** | **Fecha** | **Autor** | **Descripción de Modificación** |
|-------------|-----------|-----------|---------------------------------|
| 1.0         | [22/03/24]   | Andrea Cabanillas Gora  | [Capitulo 1] |
| 1.1          |  [01/04/24] |        Daniel del Castillo      |        [Capitulo 2]|
| 1.2           |  [02/04/24] |       Sergio Pecan         |        [Capitulo 3] |
| 1.3           |  [03/04/24] |       Favio Landeo y Gustavo Poma        |        [Capitulo 4] |
| 1.4           |  [09/04/24] |       Favio Landeo, Andrea Cabanillas, Gustavo Poma, Daniel del Castillo, Sergio Pecan       |      [Capitulo 5] |

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

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1 Software Configuration Management](#51-software-configuration-management)
        - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2 Source Code Management](#512-source-code-management)
        - [5.1.3 Software Development Environment Configuration](#513-source-code-style-guide--conventions)
        - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
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
**Segmento 1: Agricultores**<br>
¿Cuál es tu nombre, cuántos años tienes y a qué te dedicas?<br/>
¿Cómo consideras que es tu personalidad (extrovertido, introvertido, Racional, Idealista,etc.)?<br/>
¿Cuanto tiempo llevas trabajando como agricultor?<br/>
¿Existe algo que te frustre de la agricultura,algo que se te dificulte?<br/>
¿Que te motiva a seguir trabajando?<br/>
¿Que habilidades desarollaste en tu trabajo?<br/>
¿Que navegador web usa más?<br/>
¿Cuentas con alguna marca preferida para los productos de software que utilizas (Excel, word,etc.)?<br/>
¿Podría brindarnos una frase que describa su situación?<br/>
¿Tienes alguna meta que te gustaría cumplir en tu rubro?<br/>

**Segmento 2: Consultores**<br>
¿Cuál es tu nombre, cuantos años tienes y a que te dedicas?<br/>
¿Cómo consideras que es tu personalidad (extrovertido, introvertido, Racional, Idealista,etc.)?<br/>
¿Cuanto tiempo llevas trabajando en el rubro de la consultoría?<br/>
¿Existe algo que te frustre de tu trabajo como consultor?<br/>
¿Que te motiva a seguir trabajando?<br/>
¿Que habilidades desarrollaste a lo largo de tu labor como consultor?<br/>
¿Que navegadores usa frecuentemente, hay uno que uses más que los demás?<br/>
¿Cuentas con alguna marca preferida para los productos de software que utilizas (Excel, word,etc.)?<br/>
¿Tienes alguna meta que te gustaría cumplir en tu rubro?<br/>

### 2.2.2 Registro de entrevistas

Segmento 1: Pymes Agrícolas <br/>
**Link:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211212_upc_edu_pe/Edx3xkDKW8FLkz7rlFUToxsB3CrkBqPzBfs67F99S_8i8w?e=j6bgfj<br/>

**Entrevistado 1:** Roberto Hoyos Gutierrez <br/>
**Resumen:** El entrevistado es un hombre de 45 años lleva 5 años trabajando en el sector agrícola plantando y cosechando manzana golden. Él considera que su labor en el campo es relajante, por lo que no representa una dificultad para él. Acerca de la tecnología usada en su trabajo, menciona que usa un sistema de riego y curaciónes con unos motores estacionarios. Cuando le preguntamos sobre las caracteristicas que debería tener el software mencionó que le gustaría tener una opción para administrar el riego con una computadora para ya no tener que activar su motor estacionario manualmente.  <br/>

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/52e7323b-cf1d-4dfd-8cba-07e29adff6dd)


**Entrevistado 2:** Hernan Delgado <br/>
**Resumen:** El entrevistado es un agricultor especializado en maíz y papa que lleva en el sector desde hace 10 años. Él considera que el cuidado de las plantas es una tarea de sumo cuidado, ya que implica una dedicación especial a cada tipo de cultivo. El considera que nuestro software sería una ayuda a la planificación y gestión de los cultivos, centrado en el agricultor para hacerlo más fácil y practico<br/>

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/b991f330-0226-4307-a1a0-f9cebacefb10)


**Entrevistado 3:** Tony Pariona Quispe <br/>
**Resumen:** Tony es un hombre que lleva 5 años en el negocio agrícola. Pudimos observar que él está entusiasmado por implementar un software que le permita ayudar a su gestión agrícola. Tony considera que el software debe tener las funciones de cuidado de riego, consulta meteorologica, control de plagas. Gracias a su entrevista pudimos denotar que le gustaría incorporar en un futuro  

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/6601b9d0-fba4-4dc4-aaa4-53ef2b68fc88)

<br/>




Segmento 2: Medianas y Grandes Empresas agrícolas 
**Link:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211212_upc_edu_pe/Eeyk1ycTEE1FpiiYioLJHzABH_JJkAgTjxBpdhGxxWI6Cw?e=dYl2l0 <br/>




**Entrevistado 1:** Luis Carlos Cruz <br/>
**Resumen:** Luis es un hombre mayor nos comenta que lleva alrededor de 10 años de experiencia en el sector agrícola, nos menciona que cada cultivo es diferente y que este se aplica artesanalmente en sus campos. Él opina que la herramienta de software debería tener un indicador de un control meteorológico para saber cuando lloverá y así planear mejor los riegos. Durante la entrevista pudimos entender que las personas en su entorno laboral no usaban tanta tecnología por lo que podemos ver como oportunidad de negocio ya que los competidores no estan llegando la gente aledaña Luis

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/b6e732d7-9d2e-4c40-91b0-204a4b68715c)

<br/> <br/>


**Entrevistado 2:** Jesus Alvarado  <br/>
**Resumen:**  Jesus es un ingeniero ambiental de 28 años que tiene un terreno en huaura. El nos relata que cultivan palta,yuca y camote debido a que el clima calido lo favore. Jesus también nos contó que él trabaja con formulas en excel y que le consume bastante tiempo. Cuando se le preguntó a Jesus sobre su disposición en cuanto a agregar una herramienta de software a su negocio, nos comentó que le gustaría ver dicha herramienta y comprobar su funcionalidad por lo que pudimos notar que es una persona analitica debido a que consideró que el trabajo está en una etapa inicial. Él considera que para que un software llame su atención debe ser editable de modo que cuente con un catálogo de opciones para escoger su interfaz y funciones <br/>

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/31d85574-3d67-4879-8572-2889e14862c5)






### 2.2.3 Análisis de entrevistas

Despues de haber realizado las entrevistas pudimos observar un par de datos interesantes que mostraremos a continuación
<ul>
  <li> El 100% de los entrevistados son hombres </li>
  <li> El 100% de los entrevistados del segmento 2 usan excel para sus cultivos </li>
  <li> Un 32% de los usuarios del segundo segmento cultivan tuberculos</li>
  <li>  Todos los entrevistados se vieron intrigados por la implementación de nuestra solución agroges</li>
  <li> Pudimos ver que el 32% de nuestros entrevistados del segmento 2 han observado detenidamente el crecimiento agrícola de otros países y lo han relacionado a la modernización en estos procesos </li>
 
  
</ul>

Luego de el analisis de los datos recolectados por nuestras entrevistas pudimos determinar cuales son las preocupaciones,gustos y caracteristicas generales del publico al que queremos dirigirnos, el cual plasmaremos a continuación en el apartado de las user personas, dentro de ellas podremos observar una amalgama de información de cada uno de los individuos entrevistados.
---

## 2.3 Needfinding
### 2.3.1 User Personas

![1](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/0da430d1-ff31-4d9c-a514-85a2ed7f2ef3)

![2](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/a9a7755c-50e8-4626-9a6a-eb5db9ab1fa3)



### 2.3.2 User Task Matrix

Usuario: Aldo

| Tareas  | Frecuencia | Importancia | 
|---------|------------|-------------|
| Planificar el cultivo de una temporada | Media | Alta | 
| Comunicarse con trabajadores | Media | Alta |
| Seguimiento de cultivos | Alta | Alta |
| Revisión de pronostico del clima | Alta | Media |
| Riego de plantas | Media | Alta |
| Control de pestes | Baja | Alta |
| Pesaje de cosechas | Baja | Alta |

<br/>
<br/>
Usuario: Antonio <br/>

| Tareas  | Frecuencia | Importancia | 
|---------|------------|-------------|
| Planificar el cultivo de una temporada | Alta | Alta | 
| Comunicarse con trabajadores | Alta | Alta |
| Seguimiento de cultivos | Alta | Alta |
| Revisión de pronostico del clima | Alta | Alta |
| Riego de plantas | Alta | Alta |
| Control de pestes | Media | Alta |
| Pesaje de cosechas | Baja | Alta |

### 2.3.3 User Journey Mapping

![Whiteboard1](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/ab895260-b51f-4295-bc2f-e544bc72863c)

![Whiteboard](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/9ca4690e-4c76-460f-9135-aa70335e996e)


### 2.3.4 Empathy Mapping

![1](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/0a4a6b2e-5077-4316-bdd3-5a3ccc6a6c61)

![2](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/129196278/d1427b1a-00d4-48d9-8b3c-2aece05fa55b)




### 2.3.5 As-is Scenario Mapping
User persona 1: <br>

| Fases | Planificación de cultivos y gestión de insumos | Seguimiento de operaciones y toma de decisiones | Comunicación y colaboración | Evaluación y adaptación |
|-------|-----------------|--|--|--|
| Doing | Los agricultores se rigen por las temporadas y hacen cultivos esperando que no hayan imprevistos | Los agricultores registran el seguimiento de los cultivos en un cuaderno o algún registro manual que puede perderse o en caso sea digital este puede corromperse y perderse tambien | Los agricultores se comunican con otros miembros del equipo por telefono o por algun tipo de radio | Los agricultores analizan sus cultivos y se preparan para las siguientes temporadas luego de las cosechas |
| Thinking | Los agricultores quieren que la cosecha de frutos pero su incertidumbre acaba con su esperanza | Los agricultores piensan que el seguimiento escrito a mano es mas confiable que uno modernizado | Los agricultores consideran que el sistema de radio es más rentable | Los agricultores consideran que adaptarse en base a experiencias pasadas sin cuidado de eventos repentinos como fenomenos y deslizamiento de rocas |
| Feeling | Los agricultores se sienten desesperados por comenzar ya la temporada y cosechar lo mas pronto posible | Los agricultores se sienten conformes con los registros analogicos | Los agricultores se sienten conformes con las radios pero no quieren usar pilas para cada equipo | Los agricultores se sienten ansiosos de que no haya algún imprevisto durante la siguiente cosecha |


---

## 2.4 Ubiquitous Language

Ubiquitous language o lenguaje ubicuo hace referencia al lenguaje que puede ser entendido en cualquier parte, esta sección tiene como intención permitirle a personas sin vocabulario de un Ingeniero de software puedan entender. A continuación, mostraremos un glosario con contenido de este proyecto:
<ul>
  <li> Api: Una "Application Programming Interface" sirve como un puente ente diferentes softwares, generalmente son utilizados para recaudar información del exterior para mostrarlas en el interior del documento </li>
  <li> Catalogue: Es una sección sistematica y organizada de elementos, información o recursos disponibles para el usuario siendo esta una manera en la que el usuario tiene más libertad de elección. </li>
  <li> User: Es el individuo que interactua con la plataforma y para la que ha sido diseñada la misma. Los usuarios representan una gran variedad de grupos de personas, siendo que estos aportan una retroalimentación util de cada punto de vista para la mejora constante del proyecto.  </li>
  <li>Library: Una librería dentro del contexto del trabajo viene a ser un grupo de herramientas que cumplen funciones variadas que ayudan a organizar de mejor manera tareas específicas, el aspecto más relevante de los API es que es modular y puede incorporarse y retirarse del proyecto en cuanto sea pertinente. </li>

</ul>


---

# Capítulo III: Requirements Specification
## 3.1 To-Be Scenario Mapping
<img src="https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/145626151/bb941e93-3157-4f28-b29a-a3c0b2f3c380" width="500"/>


## 3.2 User Stories

| **ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|--------|-----------|-----------------|-----------------------------|---------------------------------|
| EPIC001 | Planificación de Cultivos y Gestión de Insumos | Como agricultor, quiero poder planificar mis cultivos y gestionar mis insumos para maximizar la eficiencia y la productividad de mi granja. |||
| EPIC002 | Seguimiento de Operaciones y Toma de Decisiones | Como gerente de granja, quiero poder seguir las operaciones en tiempo real y tomar decisiones basadas en datos para mejorar la gestión de la granja. |||
| EPIC003 | Comunicación y Colaboración | Como miembro del equipo de la granja, quiero poder comunicarme y colaborar eficazmente con mis compañeros para asegurar que todos estamos trabajando hacia los mismos objetivos. |||
| EPIC004 | Evaluación y Adaptación | Como propietario de una granja, quiero poder evaluar el rendimiento de mis operaciones y adaptar mis estrategias según sea necesario para garantizar la sostenibilidad a largo plazo de mi granja. |||
| TEPIC001 | Landing Page | Como visitante, quiero poder navegar por la página de inicio para obtener una visión general de lo que la plataforma ofrece y cómo puede beneficiarme. |||
| TEPIC002 | RESTful API | Como desarrollador, quiero poder interactuar con la API RESTful para crear, leer, actualizar y eliminar datos en la plataforma de manera eficiente. |||
| US001 | Planificar la Temporada de Cultivo | Como agricultor, quiero crear un plan de cultivo detallado para la próxima temporada, asignando recursos como semillas, fertilizantes y agua a cada cultivo. | - Dado que el agricultor accede a la aplicación, Cuando planifica la próxima temporada de cultivo, Entonces puede crear un calendario de siembra que especifique las fechas de siembra para cada cultivo. - Dado que el agricultor asigna recursos a los cultivos, Cuando especifica recursos específicos como semillas, fertilizantes y agua para cada tipo de cultivo dentro del plan, Entonces la aplicación le permite guardar y editar su plan de cultivo. - Dado que el agricultor establece metas de producción, Cuando considera las condiciones climáticas y la disponibilidad de insumos, Entonces puede ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. | EPIC001 |
| US002 | Definir Objetivos de Rendimiento | Como agricultor, quiero establecer metas de producción específicas para cada tipo de cultivo, considerando las condiciones climáticas y la disponibilidad de insumos. | - Dado que el agricultor accede a la aplicación, Cuando establece objetivos de rendimiento para cada cultivo, Entonces la aplicación permite ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. - Dado que el agricultor considera las condiciones climáticas y la disponibilidad de insumos, Cuando establece metas de producción, Entonces puede ajustar las metas en función de cambios en las condiciones climáticas o disponibilidad de insumos. | EPIC001 | | US003 | Seguimiento Detallado de Actividades Agrícolas | Como agricultor, quiero registrar datos diarios sobre las operaciones realizadas en cada cultivo, como riego, fertilización y control de plagas. | - Dado que el agricultor accede a la aplicación, Cuando registra datos diarios sobre las operaciones agrícolas, Entonces puede incluir información sobre riego, fertilización y tratamientos fitosanitarios para cada cultivo. - Dado que el agricultor registra datos diarios, Cuando agrega detalles específicos sobre cada actividad, como la cantidad de agua utilizada o el tipo de fertilizante aplicado, Entonces la aplicación le permite guardar y visualizar estos registros. - Dado que el agricultor registra datos diarios, Cuando incluye información sobre las operaciones realizadas en cada cultivo, Entonces la aplicación le permite agregar detalles específicos sobre cada actividad. | EPIC002 |
| US004 | Visualización de Métricas de Rendimiento | Como agricultor, quiero visualizar gráficos y métricas que muestren el progreso de mis cultivos para evaluar su rendimiento y tomar decisiones informadas. | - Dado que el agricultor accede a la aplicación, Cuando visualiza gráficos y métricas sobre el crecimiento y rendimiento de sus cultivos, Entonces la aplicación muestra gráficos claros y métricas relevantes sobre el crecimiento y rendimiento de sus cultivos. - Dado que el agricultor compara el rendimiento actual con sus objetivos de producción establecidos, Cuando identifica áreas de mejora basadas en los datos históricos, Entonces puede tomar medidas correctivas para optimizar futuras temporadas de cultivo. | EPIC002 | | US005 | Mensajes Internos y Notificaciones | Como agricultor, quiero enviar mensajes a otros usuarios dentro de la aplicación para coordinar con mi equipo, proveedores y compradores. |- Dado que el agricultor accede a la aplicación, Cuando envía mensajes a otros usuarios registrados en la aplicación, Entonces puede coordinar con su equipo, proveedores y compradores. - Dado que el agricultor envía mensajes, Cuando recibe notificaciones sobre ofertas de compra o venta, Entonces puede considerar oportunidades de negocio y tomar decisiones informadas. - Dado que el agricultor accede a la aplicación, Cuando accede a información actualizada sobre precios de mercado y demanda, Entonces puede tomar decisiones estratégicas basadas en datos en tiempo real.| EPIC003 | | US006 | Precios y Demandas en Tiempo Real | Como agricultor, quiero recibir notificaciones sobre ofertas de compra o venta, y acceder a información actualizada sobre precios y demanda. | - Dado que el agricultor accede a la aplicación, Cuando la aplicación muestra información actualizada sobre precios de mercado y demanda de productos agrícolas, Entonces puede tomar decisiones informadas sobre sus cultivos. - Dado que el agricultor configura notificaciones, Cuando recibe alertas sobre cambios significativos en los precios o demanda, Entonces puede reaccionar rápidamente a las oportunidades del mercado. - Dado que el agricultor accede a la aplicación, Cuando accede a información actualizada sobre precios de mercado y demanda, Entonces puede tomar decisiones estratégicas basadas en datos en tiempo real. | EPIC003 |
| US007 | Informe de Rendimiento Histórico | Como agricultor, quiero generar informes que resuman el rendimiento de mis cultivos en temporadas anteriores para identificar áreas de mejora. | - Dado que el agricultor accede a la aplicación, Cuando genera informes detallados sobre el rendimiento de sus cultivos en temporadas anteriores, Entonces los informes incluyen métricas clave como rendimiento por cultivo, costos y ganancias. - Dado que el agricultor revisa los informes, Cuando identifica áreas de mejora basadas en los datos históricos, Entonces puede tomar medidas correctivas para optimizar futuras temporadas de cultivo. - Dado que el agricultor accede a los informes, Cuando evalúa el rendimiento pasado, Entonces reflexiona sobre las decisiones tomadas y busca oportunidades de mejora. | EPIC004 | | US008 | Adaptación a Cambios | Como agricultor, quiero adaptar mi estrategia según los cambios en el entorno o las condiciones climáticas, reflexionando sobre las decisiones tomadas. | - Dado que el agricultor accede a la aplicación, Cuando realiza ajustes en su plan de cultivo en función de cambios en el clima, disponibilidad de insumos o resultados del rendimiento pasado, Entonces puede adaptar su estrategia de cultivo de manera ágil y efectiva. - Dado que el agricultor considera las condiciones climáticas y la disponibilidad de insumos, Cuando ajusta su plan de cultivo, Entonces la aplicación le proporciona sugerencias o consejos basados en análisis de datos para ayudar en la toma de decisiones de adaptación. - Dado que el agricultor accede a la aplicación, Cuando reflexiona sobre las decisiones tomadas y busca oportunidades de mejora, Entonces puede tomar medidas correctivas para optimizar futuras temporadas de cultivo. | EPIC004 |
| T01    | Explorar la Página de Inicio | Como visitante, quiero explorar la página de inicio para obtener una visión general del sitio web y sus secciones. | - Dado que soy un visitante, cuando ingreso a la página de inicio, entonces debo ver una breve descripción del propósito del sitio. - Dado que soy un visitante, cuando navego por la página de inicio, entonces debo encontrar enlaces o botones que dirijan a las diferentes secciones del sitio. - Dado que soy un visitante, cuando hago clic en un enlace de una sección, entonces debo ser llevado a la página correspondiente. | TEPIC001 |
| T02    | Ver Información de Productos/Servicios | Como visitante, quiero ver información detallada sobre los productos o servicios ofrecidos. | - Dado que soy un visitante, cuando accedo a la página de un producto/servicio, entonces debo ver una descripción detallada, imágenes y detalles relevantes. - Dado que soy un visitante, cuando busco información sobre un producto/servicio, entonces debo encontrar la información fácilmente. - Dado que soy un visitante, cuando navego por la página de un producto/servicio, entonces debo poder regresar a la página de inicio con facilidad. | TEPIC001 |
| T03    | Contactar al Equipo de Ventas | Como visitante interesado, quiero encontrar una forma de contactar al equipo de ventas. | - Dado que soy un visitante interesado, cuando busco información de contacto, entonces debo encontrar un formulario de contacto o información clara de contacto. - Dado que soy un visitante interesado, cuando lleno el formulario de contacto, entonces debo recibir una confirmación de que mi mensaje fue enviado correctamente. - Dado que soy un visitante interesado, cuando envío un mensaje al equipo de ventas, entonces debo recibir una respuesta dentro de las 24 horas. | TEPIC001 |
| T04    | Explorar Testimonios o Casos de Éxito | Como visitante, quiero leer testimonios o casos de éxito para evaluar la confiabilidad del sitio. | - Dado que soy un visitante, cuando busco testimonios o casos de éxito, entonces debo encontrar testimonios reales o estudios de caso. - Dado que soy un visitante, cuando leo un testimonio o caso de éxito, entonces debo encontrar información relevante y convincente. - Dado que soy un visitante, cuando leo los testimonios o casos de éxito, entonces debo sentir confianza en el sitio y sus productos/servicios. | TEPIC001 |
| T05 | Consultar Recursos | Como desarrollador, quiero poder consultar recursos para interactuar con la base de datos. | - Dado que se es un desarrollador, cuando se envía una solicitud GET a la API, entonces se debe recibir una respuesta con los recursos solicitados. - Dado que se es un desarrollador, cuando se envía una solicitud GET a un recurso inexistente, entonces se debe recibir un mensaje de error. - Dado que se es un desarrollador, cuando se envía una solicitud GET a la API, entonces la respuesta debe estar en formato JSON. | TEPIC002 |
| T06 | Crear Recursos | Como desarrollador, quiero poder crear recursos para agregar datos a la base de datos. | - Dado que se es un desarrollador, cuando se envía una solicitud POST a la API, entonces se debe recibir una confirmación de que el recurso fue creado. - Dado que se es un desarrollador, cuando se envía una solicitud POST sin los datos necesarios, entonces se debe recibir un mensaje de error. - Dado que se es un desarrollador, cuando se envía una solicitud POST a la API, entonces la respuesta debe incluir el ID del recurso creado. | TEPIC002 |
| T07 | Actualizar Recursos | Como desarrollador, quiero poder actualizar recursos para modificar datos en la base de datos. | - Dado que se es un desarrollador, cuando se envía una solicitud PUT a la API, entonces se debe recibir una confirmación de que el recurso fue actualizado. - Dado que se es un desarrollador, cuando se envía una solicitud PUT a un recurso inexistente, entonces se debe recibir un mensaje de error. - Dado que se es un desarrollador, cuando se envía una solicitud PUT a la API, entonces la respuesta debe confirmar que los cambios se han realizado correctamente. | TEPIC002 |
| T08 | Eliminar Recursos | Como desarrollador, quiero poder eliminar recursos para eliminar datos de la base de datos. | - Dado que se es un desarrollador, cuando se envía una solicitud DELETE a la API, entonces se debe recibir una confirmación de que el recurso fue eliminado. - Dado que se es un desarrollador, cuando se envía una solicitud DELETE a un recurso inexistente, entonces se debe recibir un mensaje de error. - Dado que se es un desarrollador, cuando se envía una solicitud DELETE a la API, entonces la respuesta debe confirmar que el recurso ya no existe en la base de datos. | TEPIC002 |

## 3.3 Impact Mapping

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/blob/main/AgroGes/Images/impact%20mapping.png)

## 3.4 Product Backlog
| **#Order** | **User Story Id** | **Título** | **Descripción** |  **Story Points (1 / 2 / 3 / 5 / 8)** |
|------------|-------------------|------------|-----------------|-------------------------------------|
| 1 | T01 | Explorar la Página de Inicio | Como visitante, quiero explorar la página de inicio para obtener una visión general del sitio web y sus secciones. | 1 |
| 2 | T02 | Ver Información de Productos/Servicios | Como visitante, quiero ver información detallada sobre los productos o servicios ofrecidos. | 1 |
| 3 | T03 | Contactar al Equipo de Ventas | Como visitante interesado, quiero encontrar una forma de contactar al equipo de ventas. | 2 |
| 4 | T04 | Explorar Testimonios o Casos de Éxito | Como visitante, quiero leer testimonios o casos de éxito para evaluar la confiabilidad del sitio. | 1 |
| 5 | US003 | Seguimiento Detallado de Actividades Agrícolas | Como agricultor, registrarás datos diarios sobre las operaciones realizadas en cada cultivo, como riego, fertilización y control de plagas. Esto te permitirá llevar un seguimiento preciso de las actividades agrícolas. | 5 |
| 6 | US001 | Planificar la Temporada de Cultivo | Como agricultor, crearás un plan de cultivo detallado para la próxima temporada. Asignarás recursos como semillas, fertilizantes y agua a cada cultivo. Esto te ayudará a optimizar la producción y la gestión de recursos. | 5 |
| 7 | US008 | Adaptación a Cambios | Como agricultor, adaptarás tu estrategia según los cambios en el entorno o las condiciones climáticas. Reflexionarás sobre las decisiones tomadas y ajustarás tus acciones en consecuencia. | 3 |
| 8 | US004 | Visualización de Métricas de Rendimiento | Como agricultor, visualizarás gráficos y métricas que muestren el progreso de tus cultivos. Esto te permitirá evaluar su rendimiento y tomar decisiones informadas. | 5 |
| 9 | US002 | Definir Objetivos de Rendimiento | Como agricultor, establecerás metas de producción específicas para cada tipo de cultivo. Considerarás las condiciones climáticas y la disponibilidad de insumos para definir tus objetivos. |3 |
| 10 | US007 | Informe de Rendimiento Histórico | Como agricultor, generarás informes que resuman el rendimiento de tus cultivos en temporadas anteriores. Esto te ayudará a identificar áreas de mejora y a tomar decisiones estratégicas. | 3 |
| 11 | US006 | Mensajes Internos y Notificaciones | Como agricultor, enviarás mensajes a otros usuarios dentro de la aplicación para coordinar con tu equipo, proveedores y compradores. La comunicación eficiente es esencial para el éxito. | 3 |
| 12 | US005 | Precios y Demandas en Tiempo Real | Como agricultor, recibirás notificaciones sobre ofertas de compra o venta, y accederás a información actualizada sobre precios y demanda. Esto te ayudará a tomar decisiones comerciales acertadas. | 5 |
| 12 | T05 | Consultar Recursos | Como desarrollador, recibirás una respuesta con los recursos solicitados cuando envíes una solicitud GET a la API. Esto te ayudará a interactuar con la base de datos de manera eficiente. | 1|
| 13 | T06 | Crear Recursos | Como desarrollador, recibirás una confirmación de que el recurso fue creado cuando envíes una solicitud POST a la API. Esto te permitirá agregar datos a la base de datos de manera eficiente. | 3|
| 14 | T07 | Actualizar Recursos | Como desarrollador, recibirás una confirmación de que el recurso fue actualizado cuando envíes una solicitud PUT a la API. Esto te permitirá modificar datos en la base de datos de manera eficiente. | 5|
| 15 | T08 | Eliminar Recursos | Como desarrollador, recibirás una confirmación de que el recurso fue eliminado cuando envíes una solicitud DELETE a la API. Esto te permitirá eliminar datos de la base de datos de manera eficiente. | 3|



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

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/bece0942-1add-435e-aaf0-7e0734f45643)

Decidimos que para nuestra aplicación apliquemos una interfaz simple y fácil de entender con colores vivos que capten la
atención del usuario. También esta característica ayuda en el rendimiento de la aplicación, por lo que el tiempo de espera del usuario será el mínimo.

- ### 4.1.2 Web Style Guidelines
Hemos escogido optar por un tono de comunicación y un lenguaje serio y casual con palabras simples 
para que cualquier usuario puedan entender fácilmente las funcionalidades de nuestra aplicación. 
Además, nosotros hemos decidido desarrollar una landing page y una aplicación web con interacción responsiva para 
adaptarse a diferentes dispositivos facilitando la comprensión y adaptabilidad del contenido.

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/e4de51c2-0f6b-411a-bac9-111b76e0b35e)

## 4.2 Information Architecture
- ### 4.2.1 Organization Systems
En esta parte sintetizamos la estructura del sistema en dos partes: la landing page y la aplicación web.
La primera está destinada a contener la información sobre el proyecto y nuestro equipo; mientras que la segunda tratará
las funcionalidades y la lógica de negocio.

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/5b3fbf5e-2d1a-4499-a7ee-96b819e06126)

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

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/5afda3de-144b-46b5-ad3b-e25fcc42027f)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/01f083af-fe92-4a7b-877c-179a5223a813)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/ec6605f9-2e3b-49f5-8bcb-9e9b4fd74fc1)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/597eb932-a7a8-4bb9-8127-62789ffe165a)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/5715041a-d46b-4265-9a87-5cb73246302f)

- ### 4.3.2 Landing Page Mock-up

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/54683278-f360-4077-8c19-6f66709cc0db)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/50fd1ee9-2557-44de-80e5-2922f39366dd)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/83df525e-898a-4c6e-a7bb-6080a8311c7e)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/b39838b7-b679-475c-98e3-9c1262519838)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/6a83d6e7-eecd-43c2-ad43-5ae084617f29)

## 4.4 Web Applications UX/UI Design
- ### 4.4.1 Web Applications Wireframes

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/d38f259c-98a3-43e1-af4a-4dba73811ecb)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/2e76e6e9-c749-4f56-8dcb-d9f778c60f61)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/e8b15922-61b3-43c9-a418-ed19e7692830)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/8e27a1d0-5dcb-4026-92ac-d9cfc9422b83)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/85fd100b-e59d-4462-a737-147e25f72241)

- ### 4.4.2 Web Applications Wireflow Diagrams

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/6fa9628b-71f1-46cf-b782-dacdd7f4e4b8)

- ### 4.4.3 Web Applications Mock-ups

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/32d74b6f-5ca9-488a-a76e-744a88d105bf)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/9786306d-10af-49de-af23-858e32dbb0cd)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/15064e9d-bca5-43e6-9d0b-3a5f24d65d33)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/8af1b6f5-efe7-4a1e-bbef-810f55d2f381)

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/31c0305b-e342-4602-85d1-00cad74e9ae1)

- ### 4.4.4 Web Applications User Flow Diagrams

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/c310f9ee-c780-4568-a731-a7bc2dc83a80)

## 4.5 Web Applications Prototyping

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/102195498/65999122-793c-4593-881c-cda16fc5da6f)

Link al prototipo en Figma:
https://www.figma.com/file/wbJAAapAaZJPASC5AD399M/Lux-AgroGes?type=design&node-id=0%3A1&mode=design&t=NJ27qusj7UOMi0s4-1

## 4.6 Domain-Driven Software Architecture
- ### 4.6.1 Software Architecture Context Diagram
 
![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/18dafe6a-3f8c-449e-b657-92926ba0fb7c)
  
- ### 4.6.2 Software Architecture Container Diagrams

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/1e048065-8b3f-45e1-9062-1fdd86c91533)

- ### 4.6.3 Software Architecture Components Diagrams

![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/3d829c3c-48ee-4e25-9418-e640acc477f5)
  
## 4.7 Software Object-Oriented Design
- ### 4.7.1 Class Diagrams

  ![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/94254725-59fd-4cec-814d-fc1bec11d1a5)

  
- ### 4.7.2 Class Dictionary

  Company: Empresas a las que se les brinda el servicio.
-RUC: Código de la empresa
-Password: Contraseña con la que se accede a la cuenta
-Company_name: El nombre de una compañía
-Phone: Teléfono de la empresa
-Mail: Correo de la empresa
-Create_company(): Es el método por el cual se crea las nuevas empresas
-Update_data(): El método por el cual se actualizan los datos de una empresa

Crop: Es el cultivo al cual se le monitorea y administra.
-Crop_code: Código del cultivo
-Area: Área del terreno
-Product: Alimento que produce el cultivo
-State: El estado en que se encuentra el alimento
-Cost: Costo de producir ese cultivo
-Location: El lugar geográfico donde se encuentra el producto
-Return: El costo aproximado que se espera ganar por el cultivo
-Update_status(): Actualización del estado
-Add_expense(): Registra un nuevo gasto para el cultivo
-Decrease_expenditure(): Elimina un gasto

Worker: Personas que trabajan en las diferentes compañías agrícolas.
-DNI: Documento de identificación de los trabajadores
-Name: Nombre del trabajador
-Last_name: Apellido
-Post: Cargo dentro de la empresa
-Salary: Dinero que gana el trabajador
-Phone: Teléfono de la empresa
-Age: Edad
-Estado: Dentro de la empresa
-Hire_employee(): Contrata a los empleados
-Vacations(): Para cuando un empleado salga de vacaciones
-Update_data(): Permite actualizar los datos de los trabajadores

Equipment: Conjunto de Workers encargados de un Crop
-equipment_code: Código del equipo
-number_members: Dice la cantidad de integrantes de un equipo
-Manager_code: Indica quién es el líder del equipo
-crop_code: El código del cultivo en que trabaja el equipo
-create_team(): Crea un nuevo equipo
-Add_member(): Agrega a un nuevo miembro
-Remove_member(): Quitar a un miembro del equipo

Collection pending: Son las cobranzas pendientes de una empresa por los productos o servicios que ofrece.
-Collection_id: Código de la deuda a cobrar
-RUC: Código de la empresa que es la deuda a cobrar
-Type: Qué tipo de cobranza es
-Amount: Monto a cobrar
-Description: Explica el origen de la deuda
-State: Indica si pagó o no
-Create_pending_collection(): Crea una nueva deuda a cobrar
-Update_status(): Actualiza si ya se pagó la deuda

Pending payment: Son las deudas pendientes de una Company.
-Collection_id: Código de la deuda a pagar
-RUC: Código de la empresa que es la deuda a pagar
-Type: Qué tipo de cobranza es
-Amount: Monto a pagar
-Description: Explica el origen de la deuda
-State: Indica si pagó o no
-Create_pending_collection(): Crea una nueva deuda a pagar
-Update_status(): Actualiza si ya se pagó la deuda

Balance: Esta clase se crea mensualmente y determina las ganancias de la Company.
-Month: El mes del que se calcula el balance
-Spent: Gastos generados por la empresa
-Ingreso: Lo que generó la empresa
-Revenue: Ganancia de la empresa
-Ruc_company: El código de la empresa que se está sacando el balance
-Create_balance: Calcula las ganancias de la empresa

  
## 4.8 Database Design
- ### 4.8.1 Database Diagram

   ![image](https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes/assets/157068395/49e99b2d-0e83-4f81-8212-26e32d032e54)


---
# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
- ### 5.1.1 Software Development Environment Configuration

 **Miro :** Es una plataforma en línea que permite la colaboración en tiempo real y la creación de tableros virtuales, diagramar procesos, crear mapas mentales, hacer lluvias de ideas, diseñar wireframes y mucho más. Utilizamos esta herramienta para poder realizar mapas de escenarios As-Is y To-Be.
 
 **Figma :** Figma es una herramienta de diseño colaborativo basada en la nube que permite a los equipos crear, colaborar y prototipar interfaces de usuario de manera eficiente, Nuestro equipo lo utilizo para el desarrollo Wireframes, Mock-ups y Prototypes.
 
 **Structurizi :**ayuda a dibujar y documentar la arquitectura de tu software. Te permite crear diagramas que muestran cómo funcionan tus sistemas y cómo están conectados entre sí. Nosotros lo utilizamos para la creacion de diagramas c4.

 **IntelliJ IDEA :** Como entorno de desarrollo integrado (IDE) para el desarrollo de aplicaciones de software, especialmente para el desarrollo en Java y otras tecnologías JVM como Kotlin y Groovy. También ofrece soporte para una amplia gama de lenguajes de programación y tecnologías, incluidas las relacionadas con el desarrollo web, como HTML, CSS, JavaScript y frameworks como Spring.
 
 **Java :** Para el desarrollo del backend de la aplicación.

 **Uxspresia :**
 
 **MySQL** Como sistema de gestión de bases de datos relacionales para almacenar y manejar los datos de la aplicación.
 
 **WebStorm :** Como entorno de desarrollo integrado (IDE) para el desarrollo de aplicaciones web, especialmente para el trabajo con tecnologías como JavaScript, HTML, CSS y frameworks como React, Angular y Vue.js.
 
 **Git y GitHub:** Para el control de versiones y la colaboración en el desarrollo del proyecto.
 
 **Angular** Un framework de desarrollo web para facilitar el front end

 **HTML (HyperText Markup Language):** Para estructurar el contenido de la página web.
 
 **CSS (Cascading Style Sheets):** Para diseñar y dar estilo al contenido HTML.
 
 **JavaScript:** Para agregar interactividad y funcionalidad a la página web.
   
- ### 5.1.2 Source Code Management

 Repositorio del Landing Page : 

 https://github.com/upc-pre-SI729-2401-SW51-Lux/AgroGes

En el marco de este proyecto, se implementarán tres ramas principales: "master", "develop" y "feature branches".

La rama "feature branches" se destinará específicamente para la creación de nuevas funcionalidades, clases u otros elementos que añadirán nuevas capacidades al proyecto. Esta rama servirá como un entorno aislado para el desarrollo de estas características, permitiendo un trabajo paralelo sin afectar la estabilidad del código principal.

La rama "develop" funcionará como el entorno de integración continua, donde se unificarán y probarán los cambios provenientes de las ramas de características. En este entorno, los cambios deben ser integrados y asegurados para garantizar el funcionamiento cohesivo del proyecto.

Finalmente, la rama "master" será la rama principal y estable del repositorio. Aquí se fusionarán todos los cambios provenientes de la rama "develop", generando así nuevas versiones del sistema. Esta rama representa el estado más actualizado y confiable del proyecto, adecuado para su despliegue en entornos de producción.

Este enfoque de ramificación permite una gestión eficiente del desarrollo, facilitando la colaboración entre equipos y asegurando la estabilidad y calidad del software en cada etapa del ciclo de vida del proyecto.
  
- ### 5.1.3 Source Code Style Guide & Conventions

En el proceso de realizar commits, hemos optado por seguir el estándar de "Conventional Commits". Esta práctica nos brinda una estructura definida para nuestros mensajes de commit, lo que facilita la comprensión y la gestión de cambios en el repositorio.

Además, hemos establecido el uso de terminología en inglés para las diferentes declaraciones en nuestras líneas de código en todos los lenguajes de programación empleados en el proyecto. Esta decisión busca promover la coherencia y la claridad en la comunicación del código, facilitando la colaboración entre miembros del equipo y mejorando la legibilidad del código fuente en general.
  
- ### 5.1.4 Software Deployment Configuration

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

### 5.2.1 Sprint 1

#### 5.2.1.1. Sprint Planning 1

En este sprint nos enfocaremos en establecer los cimientos para la creación de la landing page de AgroGes utilizando HTML, CSS y JavaScript. Las tareas principales incluyen:

- Diseñar la estructura general de la landing page.
- Seleccionar una paleta de colores y definir estilos visuales.
- Configurar el repositorio en GitHub para el proyecto.

| Sprint # | Sprint 1|
|----------|---------|
| | Sprint Planning Background |
| Date | 2024-04-09 |
| Location | Reunión virtual a través de google meet |
| Prepared By | Andrea Cabanillas, Gustavo Poma |
| Attendees | Andrea Cabanillas, Gustavo Poma, Favio Landeo, Sergio Pecan, Daniel Del Castillo |
| Sprint n - 1 Review Summary | Siendo esta la primera reunión, se repartieron las labores para el trabajo y constante retroalimentación en cuanto a los apartados, todos los miembros pudieron evidenciar su conocimiento y experiencia mediante la mencionada retroalimentación hecha previo a subir el trabajo al repositorio |
| Sprint n - 1 Retrospective Summary| Nuestros miembros opinan que para el desarrollo de la landing page fue necesaria una constante revisión de avances previos a los commits lo cual brinda un mayor enfoque en el producto final pero nos quita libertades creativas y creemos que para una futura entrega debemos trabajar más de cerca en reuniones presenciales para evitar estas situaciones |
| | Sprint Goal & User Stories |
| Sprint 1 Goal | Decidimos que nuestra meta para este sprint sería acabar con la landing page para ello la metrica será cumplir con  |
| Sprint 1 Velocity | Completaremos Story Points de valor 3, debido a que consideramos que es una carga laboral aceptable para un progreso seguro |
| Sum of Story Points | 9 Story points serán los que incluimos en este sprint | 

#### 5.2.1.2. Sprint Backlog 1


El backlog del sprint incluye las siguientes tareas:

1. Crear wireframes para cada sección de la landing page.
2. Seleccionar y aplicar una paleta de colores utilizando CSS.
3. Configurar la estructura básica de la landing page utilizando HTML.
4. Aplicar estilos básicos utilizando CSS para dar formato y diseño a la página.

| User Story Id | Title | Work-Item/Task Id | Title | Description | Estimation(Hours) | Assigned To | Status |
|----|-------|----|-------|-------------|-------------------|-------------|--------|
| T01 | Explorar la página de Inicio | W01 | Estilos adecuados de la landing | En este task diseñaremos la landing page para poder permitirle al usuario poder sentirse atraído por nuestro producto |1| Gustavo Poma, Favio Landeo | Done |
| T02 | Ver Información de Productos/Servicios | W02 | Añadir información de nuestro producto | Añadir más información sobre nuestro producto y los beneficios que este traerá  |1| Andrea Cabanillas, Daniel del Castillo |  Done |
| T03 | Contactar al equipo de ventas | W03 | Añadir un formulario para envio de correo al grupo de ventas | Para la elaboración de este apartado debimos crear una sección de contactenos para que el usuario pueda llenar con su información |1| Gustavo Poma, Sergio Pecan  | Done |

#### 5.2.1.3. Development Evidence for Sprint Review

Durante el sprint, se desarrollaron los siguientes elementos:

- Wireframes detallados de cada sección de la landing page.
- Paleta de colores definida y aplicada utilizando CSS.
- Estructura básica de la landing page creada en HTML.

| Repository | Branch | Commit Id | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|---------------------|--------------------|
| GustavoPoma| main | 8c856 | style: actualización del lenguaje de la landing |  04/09/2024  |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Se llevaron a cabo pruebas preliminares para verificar la correcta visualización y funcionamiento de la landing page en diferentes dispositivos y navegadores.

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante el sprint, se trabajó activamente en el desarrollo de la landing page utilizando HTML y CSS para estructurar y estilizar la página según los wireframes y la paleta de colores definida.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Se elaboró documentación sobre la estructura de la landing page, incluyendo los wireframes y la descripción de la paleta de colores utilizada.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

No se realizó despliegue de software en este sprint, ya que el enfoque se centró en el desarrollo inicial de la landing page.

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el sprint, el equipo colaboró estrechamente en la definición de la estructura y los estilos de la landing page, discutiendo activamente las mejores prácticas de diseño y desarrollo. Se utilizó el repositorio de GitHub para coordinar el trabajo y realizar revisiones de código entre los miembros del equipo.


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

