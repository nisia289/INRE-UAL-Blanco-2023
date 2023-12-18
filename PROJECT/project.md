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

| RF-02				| Simple way to insert content	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| 	The system should have options for inserting contnet into the website in a simple way to facilitate content management for people who have no programming knowladge	|
| Importance		|	Important	|
| Comentarios			| The view of inserted content should be the same for administrator and users.		|

| RF-03				| Various options for modifying content|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF_01	|
| Description			| The administrator should be able to edit, add or delete content on the website.		|
| Importance		|	Very important	|
| Comentarios			| The view of modified content should be the same for administrator and users		|

| RF-04				| Access to statistics	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|		|
| Description			| The content manager should have access to the necessary statistical information collected in the system.		|
| Importance		|	Very important	|
| Comentarios			| 		|

| RF-05				| Search engine	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| The system must have a search engine that allows you to search for content by keywords		|
| Importance		|	Important	|
| Comentarios			| 		|

| RF-06				| Data security	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| 	The system must ensure a high level of data security, both in terms of access and storage.	|
| Importance		|	Very important	|
| Comentarios			| 		|

| RF-07				| Integration of external multimedia resources	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| 	The system should allow the integration of external multimedia resources, such as images, videos, or audio files.	|
| Importance		|	Not importnat	|
| Comentarios			| 		|

| RF-08				| Mobile responsivness|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| The system should be responsive and optimized for a seamless user experience on mobile devices.		|
| Importance		|	Very important	|
| Comentarios			| 		|

| RF-09				| Social media integration	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| 	The system should integrate with social media platforms for content sharing and engagement.	|
| Importance		|		|
| Comentarios			| 		|

| RF-10				|Multilingual support  |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| 	The system must support multiple lenguages to adjust to a diverse user base.	|
| Importance		|		|
| Comentarios			| 		|

| RF-11				| Real-time collaboration features|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| The system should provide reak-time collabrotaion features for efficient communication and information exchange		|
| Importance		|		|
| Comentarios			| 		|

| RF-12				| Automated backup system |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|	RF-01	|
| Description			| Thye system must have an automated backup system to prevent data loss and ensure data integrity.	|
| Importance		|	Very important	|
| Comentarios			| 		|

| RF-13				| User training and documentation|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	| OBJ-3		|
| Associated requirements	|	Rf-01	|
| Description			| 	The system should provide comprehensive user training and documentation to facilitate effective usage.	|
| Importance		|		|
| Comentarios			| 		|

| RF-14				| Integration with external APIs |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-3	|
| Associated requirements	|		RF-01|
| Description			| The system mjst integrate seamlessly with external APIs to enhance funcionality and t=data exchange.		|
| Importance		|		|
| Comentarios			| 		|

### 4.1.2 Information system


<br>

| RF-01				|Processing of cartographic data |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-1	|
| Associated requirements	|		|
| Description			| 	The system must contain cartographic data on the public transport network in Gran Canaria and have the toold to process it in order to effecrively apply this information on the user portal.	|
| Importance		|	Very important	|
| Comentarios			| 		|

| RF-02				| Determining the most efficient travel route |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-1	|
| Associated requirements	|	RF-01	|
| Description			| Based on the data provided, the system should be able to determine the most efficient route between selected stops.		|
| Importance		|	Very important	|
| Comentarios			| In case of failure of this functionality, it is recommended to add several fixed routes to the destination and information about possible changes in travel times.	|

| RF-03				| Detecting impassable roads and creating alternative routes |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-1	|
| Associated requirements	|	RF-01, RF-02	|
| Description			| The system should be able to create an alternative, most effective route in accordance with Rf-2 in the event of detecting the inability to communicative via the standard route.		|
| Importance		|	Very important	|
| Comentarios			| Alternative route is made with the same algorithms used in RF-02, but with different starting parameters.	|

| RF-04				| Calculating the distance between stops and the total trip distance |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-1|
| Associated requirements	|	RF-01, RF-02	|
| Description			| 	The system must calculate the distance between every two stops depending on the selected route and the total distance of the selected trip.	|
| Importance		|	Very important	|
| Comentarios			| System should calculate every distances to keep them for calculating the most efficient route. The distances visible to the user should only be the distances of the most efficient routes.		|

| RF-05				| Transfers |
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	OBJ-1	|
| Associated requirements	|	RF-01, RF-02	|
| Description			| The system should be able to create transfers if it is not possible to create a direct route between the starting and ending stops.		|
| Importance		| Very important		|
| Comentarios			| System should calculate every disstance to keep them for calculating the most efficient route. The distances visible to the user should only be the distances of the most efficient routes.		|

| RF-06					| Traffic control	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|OBJ-2	|
| Associated requirements	|	RF-02	|
| Description			|The system hsould have access to real-time data including traffic information and other problems on the road.	|
| Importance		|Important|
| Comentarios			| 		|

| RF-07					| Time efficency	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|OBJ-2	|
| Associated requirements	|	RF-06	|
| Description			| Based on the real-time traffic data, the system should be able to show the most time0efficient routes for the user.	|
| Importance		|Very important|
| Comentarios			| 		|

| RF-08					| Select Origin on the Map	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|	Users can enter an origin on the map form which to calculate routes.|
| Importance		|Medium|
| Comentarios			| This function makes the search more user-friendly, especially when the user doesn't know the exact address of where they are.		|

| RF-09					| Display Transport Schedules	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|	RF-02	|
| Description			|The system will display the transport schedules associated with the calculated route. Indicating the frequency of the service.	|
| Importance		|Low|
| Comentarios			| This helps avoid a second search in case the user is late for the first transfer.	|

| RF-10					| Preference Criteria	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system allows users to select preference criteria, such as minimizing time, cost, or transfers when calculating the itinerary solition.	|
| Importance		|Important|
| Comentarios			| 	This option makes the user's experience more customisable	|

| RF-11					| Display Real-time Vehicle Information	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|	RF-06	|
| Description			|The system will show real-time information about vehicle locations, helping users track the progress of their selected transportation.	|
| Importance		|Low|
| Comentarios			| 		|

| RF-12					| Integrate Payment Options	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system will integrate payment options to calculate accurate fare information based on the user's selected payment method.	|
| Importance		|Important|
| Comentarios			| For example: buying a paper ticket will be more expensive thanbuying an electronic one.		|

| RF-13					| Multi Language Support|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system should offer an option to change the language within the app	|
| Importance		|Important|
| Comentarios			| Gran Canaria is a touristic place, so the app should be available to people speaking many different laguages.		|

| RF-14					| Implement Route History Tracking	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system will track and display the user's route history, allowing to view and re-enter their past travel patterns.	|
| Importance		|Medium|
| Comentarios			| 		|

| RF-15					| Allow User Feedback	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system will enable users to provide feedback and ratings on transportation services, contributing to the improvement nof iverall service quality.	|
| Importance		|Important|
| Comentarios			| 		|

| RF-16					| Provide information on Bicycle Accessibility	|
| :---					| :----  	|
| Version				| 1.0	|
| Authors				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources			| Project documentation		|
| Associated objectives	|	|
| Associated requirements	|		|
| Description			|The system will offer information on bicycloe accessibility details about bike-sharing services.	|
| Importance		|Low|
| Comentarios			| 		|
### SMET 


<br>

| RF-01					| Processing and providing data on driver activity		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-02		|
| Associated requirements	| 		|
| Description			| The system should process and deliver the collected location data and driver activity data to SMET	|
| Importance			| Very important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| The system should present location data in the form of an interactive map and text information	|

<br>

<br>

| RF-02					| Alarms		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-02		|
| Associated requirements	| RF-01		|
| Description			| The system should display alarms related to events such as stop delays or advances	|
| Importance			| Important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| Alarms must be implemented using audible or visual signals, text messages or e-mail notifications	|

<br>

<br>

| RF-03					| Show activity on cartography screen		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-01		|
| Associated requirements	| RF-01 (Information System)		|
| Description			| The system should display the activity of operators on the cartography screen, It should also allow the recording of specific situations using photos and continuous periods using movies.	|
| Importance			| Important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| This RF-03 involves visual representation of operator activities and the ability to record states with media. 	|

<br>

<br>

| RF-04					| Examine the real-time operator status		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-02		|
| Associated requirements	| 		|
| Description			| The system should allow examination of the real-time status of each operator individually, collectively or in user-defined combinations.	|
| Importance			| Important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| Thanks to that, there is a flexibility in monitoring operators based on user preferences. 	|

<br>

<br>

| RF-05					| Validate events		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-02		|
| Associated requirements	| 	RF-06	|
| Description			| For stored data, the system should allow the redefinition of alarms and validation of received and processed events. 	|
| Importance			| Important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| Flexibility to adjust alarms and validate historical events as needed.	|

<br>

<br>

| RF-06					| Visualize live and stored data		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Maciej Ignatowicz, Anita Jurkowska, Karolina Malik, Emilia Sobolewska		|
| Sources				| Project documentation 		|
| Associated objectives	| OBJ-02		|
| Associated requirements	|  RF-05		|
| Description			| The system should enable visualization and monitoring of the system based on live data and previously stored data. It should specify data range, time, operator and jump time for stored data.	|
| Importance			| Important		|
| Urgency				|		|
| State				|		|
| Stability			|		|
| Comments			| The system has dual capability to monitor both live and historical data for analysis and review.	|

<br>


## 4.2. Casos de uso.

<br>

### 4.2.1. Lista de diagramas de casos de uso del modelo.

| Código    			| Nombre	|
| :---					| :--  	|
| DCU-01				| Diagrama del Portal del SIIT	|
| DCU-02				| Diagrama de Sistema de información del SIIT	|
| DCU-03				| Diagrama del SMET	|

<br>

### 4.2.2. Diagramas de casos de uso.

#### DCU-01: Diagram of Portal of the SIIT

<br>
<img width="715" alt="Screenshot 2023-12-18 at 10 42 28" src="https://github.com/nisia289/INRE-UAL-Blanco-2023/assets/81264277/6752fa29-cb64-4dc5-b948-ac089038c5d7">

<br> 

#### DCU-02: Diagram of the Sistem of Information of SIIT 

<br>
<img width="641" alt="Screenshot 2023-12-18 at 10 45 24" src="https://github.com/nisia289/INRE-UAL-Blanco-2023/assets/81264277/3ad9b450-ca52-422e-b34f-e3f67fb0f1c3">
<br>

#### DCU-03: Diagram of SMET 
<br> 
![image](https://github.com/nisia289/INRE-UAL-Blanco-2023/blob/main/PROJECT/SMETpoprawiony.png)
<br>


### 4.2.3. Lista general de casos de uso  y actores del proyecto.

<br>

Lista de casos de uso 

<br>

| Código			| Caso de uso 	| Descripción       |
| :---				| :--       	| :--               |
| CU-01				| Search Engline| The user can search for content using the search engine            |
| CU-02             | Browse the content of the pages   | The user can view the content of all pages available to him from the system website   |
| CU-03             | Statistics |Administrator can view all statistic|
| CU-04 | Managing the content| Administrator can manage the content in user portal|
| CU-05 | Modify content | Administrator is able to modify, add and delete content from user portal |
| CU-06| Addind data| Administrator is able to add new data through the information system|
| CU-07| Data deletion | Administrator is able to delete data through the information system|
| CU-08 | View connections and hours | The user and administrator can view available connections and their data (the administrator also has an editing panel that allows him to make changes directly from there)|
| CU-09| Modify data | Administrator is able to modify data directly from information system | 
| CU-10 | View location information | User can view details about available destinations, stops and their locations |
| CU-11| View connections and hours | User can view informations about available connections with additional transfers and informations about the hours and date |
| CU-12  | Select origin and destination| User can choose from available origins and destinations |
| CU-13| Select date and hour | User can choose any departure data and time of his choice|
| CU-14| Select connections| The user can choose from avaiable connections according to the previously entered data|
| CU-15| View results | The user can see available connections according to the previously entered data  |
| CU-16 | Provide data| The user will be able to enter new data into the system |
| CU-17| View alarms (Purchase Operator view)| The user receives an alarm informing of a specific event|
| CU-18 | Examine the state of operation in real time (Purchase Operation view) | The user will be able to examine the status of the operation in real time |
| CU-19 | View alarms (Logged in user view) | The user receives an alarm informing of a specific event |
| CU-20 | View events | The user can see the list of available events |
| CU-21  | Examine the state of operation in real time (Not logged in user view)   | The user will be able to examine the status of the operation in real time for each operator   |
| CU-22  | Generate alarms   | The system generates an alarm that will be received by another user to notify them of something    |
| CU-23  | See warning   | The transport operator can see the list of route warnings  |
| CU-24  | View alarms (Tansport operator view)  | The user receives an alarm informing them of a specific relevant event or event   |

<br>

Lista de actores 

<br>

| Actor			        | Descripción	|
| :---					| :--  	|
| Administrador			| User with all available permissions to manage the application. You must identify yourself in the system using special credentials provided by the corresponding authority to have these functionalities		|
| System      | System in charge of generating the alarms that other users receive |
| User    | Abstract actor that represents the functionalities of both the logged in user and the non-logged in user |
| Logged-in user | User with read and edit permissions who can alter the content of the application in a controlled manner. You must identify yourself using the credentials that you previously created when registering in the system for the first time  |
| User not logged-in  | User with read-only permissions, seen as a guest of the application but without being able to add content to it. You can log in to the system to access Administrator or Logged User permissions depending on the credentials you use. | 
| Transport Operator  | User with operating permits in transport from the AUGT, Single Transport Authority of Gran Canaria | 
| Purchase Operator  | User with administration permissions of the SMET, Transport Operation Monitoring System  | 

<br>



