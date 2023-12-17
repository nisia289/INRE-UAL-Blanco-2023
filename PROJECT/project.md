# Transporte Gran Canaria
Especificación de los requisitos del software
***
 
<br>

## ***Índice de contenidos***

Hoja de revisión. <br>
Contenidos.
1. Introducción.
2. Información del Dominio del problema. <br>
2.1. Organigrama. <br>
2.2. Glosario de términos.
3. Necesidades del negocio. <br>
3.1. Objetivos del negocio. <br>
3.2. Modelos de Proceso de Negocio. <br>
3.2.1. Sub-procesos. <br>
3.2.2. Tareas. <br>
4. Requisitos del sistema a desarrollar. <br>
4.1. Requisitos. <br>
4.2. Casos de uso. <br>
4.2.1. Lista de diagramas de casos de uso del modelo. <br>
4.2.2. Diagramas de casos de uso. <br>
4.2.3. Lista general de casos de uso y actores del proyecto. <br>
4.2.4. Detalle de los casos de uso. <br>
4.3. Diagramas de clases asociados a los requisitos de información. <br>


# 1. Introducción.


This document contains documentation related to the project carried out by the Blanco group during the course “Requirements Engineering” in the academic year 2023/2024 at the University of Almeria. The project involves designing and modeling software designed to manage the interactive passenger information system for public transportation on the island of Gran Canaria (implement the development of software for an interactive information system for the user of regular public transport on the island of Gran Canaria.). Moreover, it includes the work carried out for the analysis, definition, design, development, fine-tuning and implementation of the software necessary to put into operation an Interactive Information System (SIIT) and a Transport Operation Information and Monitoring System (SMET). ), as well as continuous services for their maintenance.

<br>

# 2. Información del Domino del problema.

## 2.1. Organigrama.

<img width="960" alt="Screenshot 2023-12-17 at 21 09 25" src="https://github.com/emilia-sobolewska/mlproject/assets/81264277/b74f9749-6599-46aa-9c96-6604c99c9080">


<br>

## 2.2. Glosario de términos.

<br>

| Término                  | Descripción                     |
| :---                     | :---                            |
| Cloud tag                | It consists of grouping words (labels, tags) and showing the website visitor which are the most used tags. Also, using styles that allow a better visualization of which has the most activity and which has the least activity.                                                    |
| LOPD                     | Organic Law 15/1999 of 13th of December on Protection of Personal Data. It is a Spanish law that aims to guarantee and protect personal data, public freedoms and fundamental rights of natural persons, especially their honor, intimacy and personal and family privacy.
| AUT                      | Acronym for “Autoridad Única del Transporte”         |
| HelpDesk                 | Set of technological and human resources, to provide services with the possibility of managing and solving all possible incidents in a comprehensive manner, along with addressing requirements related to Information and Communication Technologies (ICT). |
| CEN                      | Acronym for “Comité Europeo de Normalización”  |
| Collaborative environment| Environment focused on facilitating communication and exchange of information both between administrators and users of the system. |
| PDA                      | Personal Digital Assistant, Personal digital assistant. It is a small device that combines a computer, telephone/fax, Internet and network connections.  |
| WYSIWYG                  |  Acronym for "What You See Is What You Get" - a phrase applied to word processors and other formatted text editors (such as HTML editors) that allow you to write a document directly showing the result. final, often the printed result.   |
| SMET                     | Acronym for “Sistema de la Monitorización de la Explotación del Transporte” |
| SIIT                     | Acronym for “Sistema Interactivo de Información del Transporte” |

<br>

# 3. Necesidades del negocio.

<br>

## 3.1. Objetivos del negocio.

<br>

| OBJ-1                 		  | Efficient public transport information system   |
| :---                    		  | :---                          |
| Descripción                     | EDevelop an efficient information system to enhance the public transport experience on the Gran Canaria island.|
| Comentarios                     |                               |

<br>

| OBJ-2                 		  | Real-time monitoring for operational excellence  |
| :---                    		  | :---                          |
| Descripción                     | Implement a real-time monitoring system to track and ensure the compliance of public transport operations with awarded services, extensions and improvements. |
| Comentarios                     |                               |

<br>

| OBJ-3                 		  | User-centered interactive portal   |
| :---                    		  | :---                          |
| Descripción                     | Create an interactive user portal that provides citizens with easy access to integrated public passenger transport services, including tourism, leisure and cultural events.  |
| Comentarios                     |                               |

<br>

| OBJ-4                 		  | Responsibility and accountability   |
| :---                    		  | :---                          |
| Descripción                     |Establish clear responsibilities for successful bidders and emphasize accountability for actions and decisions related to the project.  |
| Comentarios                     |                               |

<br>

| OBJ-5                 		  | Comprehensive work analysis and design   |
| :---                    		  | :---                          |
| Descripción                     |Conduct a thorough analysis, design, development, fine-tuning and implementation of the software required for the interactive information system and monitoring platform.  |
| Comentarios                     |                               |

<br>

| OBJ-6                 		  | Quality controls and collaborative support  |
| :---                    		  | :---                          |
| Descripción                     |Enable quality controls during project development and establish collaborative support from collaborating entities, especially the University of Las Palmas de Gran Canaria.   |
| Comentarios                     |                               |

<br>

| OBJ-7                 		  | Effective training and maintenance |
| :---                    		  | :---                          |
| Descripción                     |Implement a comprehensive training program for the correct execution of the contract, ensuring that personnel are equipped with the necessary skills.   |
| Comentarios                     |                               |

<br>

## 3.2. Modelos de Procesos de Negocio.

<br>

### 3.2.1. Sub-procesos.
### 3.2.2. Tareas.
<br>

| Nombre                  | Descripción                     |
| :---                     | :---                            |
| BPMN-01 (Implement an effective information system)| Develop and deploy a comprehensive information system to enhance the quality and accessibility of public transportation services on the island of Gran Canaria.         |
| BPMN-02 (Develop a central monitor system)         | Create a centralized monitoring system that provides real-time information on the state of the road transport network on Gran Canaria, enabling efficient traffic monitoring and management.
| BPMN-03 (Implement real-time route planning)       | Develop the capability to calculate recommended routes and arrivals in real-time, considering factors such as the least number of transfers, the fastest route, or the lowest cost        |
| BPMN-04 (Ensure integration with SIIT)             | Establish full integration with other Single Transport Authority information systems, particularly the Interactive Passenger Information System (SIIT), to facilitate effective collaboration and information exchange. |
| BPMN-05(Develop SIIT internet portal)              | Create an internet portal (SIIT) to provide passengers with easy access to information about public transportation services, tourist attractions, culture, and other relevant information.  |
| BPMN-06(Ensure long-term maintenance)              | Provide long-term maintenance of the system for at least two years, including technical support, current data information, and development services. |
| BPMN-07(Ensure compatibility and collaboration)    | Ensure that the developed system is compatible with existing AUTGC tools and systems and follows relevant models, protocols, and standards.  |
| BPMN-08(Implement real-time reporting and analysis)|  Enable the Single Transport Authority (AUTGC) to effectively monitor and manage operations by implementing real-time reporting and analysis of archival data.   |

<br>



# 4. Requisitos del sistema a desarrollar.

<br>
- Seach bar - findind any content on the website by entering key terms 
<br>
- Publishing the content of the website 
<br>
- Data modification 
 <br>
- Manual data entry 
<br>
- List of timetables and services 
<br>
- Calculation of recommended routes based on collected data
<br>
- Calculation of distances between bus stops 
<br>
- Locating interesting places 
<br>

## 4.1. Requistos.

<br>

### 4.1.1 User Portal.

<br>

| RF-01					| Content managemnet	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|		|
| Description			|Interactive Information System (SIIT) must have a system responsible for managing the content in the interactive system	|
| Importance		|Very important|
| Comentarios			| 		|
