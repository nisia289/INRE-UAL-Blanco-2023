
**Scenario 1: Timetables**

| Nombre            | Check Schedules                                                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Karolina Malik                                                                                                                                                                                                                           |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | This use case allows PDI staff, PAS staff, and students to check schedules at the university                                                                                                                                             |
| Actores           | PDI staff, PAS staff, students                                                                                                                                                                                                           |
| Precondiciones    | ----                                                                                                                                                                                                                                     |
| Flujo Normal      | 1. PDI staff access the schedule system. 2. PAS staff access the schedule system. 3. PAS staff may modify schedules if needed. 4. PAS staff may register students. 5. PDI propose changes in schedules. 6. Students access the schedule. |
| Flujo Alternatico | 6. If there's a problem with accessing the schedule, right people should be contacted                                                                                                                                                    |
| Poscondiciones    | The schedule has been checked.                                                                                                                                                                                                           |


| Nombre            | Verification of Students                                                                              |
|-------------------|-------------------------------------------------------------------------------------------------------|
| Autor             | Karolina Malik                                                                                        |
| Fecha             | 4.10.2023                                                                                             |
| Descripción       | This use case involves verifying student data during registration process for both PAS and PDI staff. |
| Actores           | PDI staff, PAS staff                                                                                  |
| Precondiciones    | Before verification we need the student data to verify.                                               |
| Flujo Normal      | 1. PDI staff register students. 2. PAS staff register students. 3. Verification of the students data. |
| Flujo Alternatico | 3. If there is a problem with the verification, check in the students registration system.            |
| Poscondiciones    | The verification has been performed.                                                                  |


| Nombre            | Search Class List                                                                                    |
|-------------------|------------------------------------------------------------------------------------------------------|
| Autor             | Karolina Malik                                                                                       |
| Fecha             | 4.10.2023                                                                                            |
| Descripción       | This use case allows PDI staff to search for students in lass lists during the registration process. |
| Actores           | PDI staff                                                                                            |
| Precondiciones    | Existing class list to search through.                                                               |
| Flujo Normal      | 1. PDI staff access the class list. 2. PDI staff searches the class list.                            |
| Flujo Alternatico | ----                                                                                                 |
| Poscondiciones    | The Class List Search has been performed.   


|
| Nombre            | Propose Changes to schedule                                                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Emilia Sobolewska                                                                                                                                                                                                                           |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | Allows PDI staff propose changes to student’s schedule                                                                                                                           |
| Actores           | PDI                                                                                                                                                                                                          |
| Precondiciones    | The PDI staff must me authenticated in the system.                                                                                                                                                                                                                                      |
| Flujo Normal      | 1. The PDI staff member logs into the university system. 2. The system displays the schedule management interface. 3. The PDI staff member selects the ‘Propose Changes’ option. 4. The system presents a form with fields to enter the changes. 5. The PDI member fills the necessary information for the proposed change. 6. The system verifies the data. 7. If the data is correct, the system allows to submit the changes. 8. The proposed change is stored in a system to review. |
| Flujo Alternatico | 6. If the data is not correct or incomplete, the system notifies the staff member, allowing them to correct it. |
| Poscondiciones    | The schedule has been stored in the system.                                                                                                                                                                                                           |

| Nombre            | Register Students                                                                                                                                                                                                                       |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Emilia Sobolewska                                                                                                                                                                                                                           |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | Allows PDI and PAS staff register students for the subjects.                                                                                                                                              |
| Actores           | PDI staff, PAS staff                                                                                                                                                                                                           |
| Precondiciones    | The PDI and PAS staff must me authenticated in the system.                                                                                                                                                                                                                                      |
| Flujo Normal      | 1. PDI or PAS staff members log into the university system.  2. The system displays the subject registration interface. 3. PDI or PAS staff members select the ‘Register Students’ option. 4. The system presents a form with fields to enter student information and select subjects. 5. PDI or PAS members fill in the necessary information for registration. 6. The system verifies the data, checking for any conflicts or eligibility requirements. 7. The system allows submitting the registration. |
| Flujo Alternatico | 6. 6a. If the data is not correct or incomplete, the system notifies the staff member, allowing them to correct it.|
| Poscondiciones    | The student has been registered                                                                                                                                                                                                           |

| Nombre            | Modify Schedules                                                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Emilia Sobolewska                                                                                                                                                                                                                           |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | Allows PAS staff modify student’s schedule                                                                                                                                              |
| Actores           | PAS staff                                                                                                                                                                                                         |
| Precondiciones    | The PAS staff must me authenticated in the system.                                                                                                                                                                                                                                     |
| Flujo Normal      | 1. PAS staff members log into the university system. 2. The system displays the schedule management interface. 3. The PDI staff member selects the ‘Modify Student Schedule’ option. 4.The system presents a search form for PAS staff to look up the student whose schedule needs modification. 5. PDI propose changes in schedules. 6.  PAS staff members make the required modifications to the student’s schedule, such as adding or removing courses or changing course timings. 7. The system verifies the modified data|
| Flujo Alternatico | 6. If the system detects conflicts or errors in the proposed schedule modifications, it notifies the PAS staff.                     |
| Poscondiciones    | The schedule has been modified.                                                                                                                                                                                                           |

<!--Scenario 2-->





<!--Scenario3-->
