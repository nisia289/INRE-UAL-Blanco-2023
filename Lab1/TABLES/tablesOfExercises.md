
**Scenario 1: Timetables**

![image](https://github.com/nisia289/INRE-UAL-Blanco-2023/assets/146172835/8b1ba024-d3de-43d1-834b-3aa70b4e56bd)

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





**Scenario 2: Purchasing System**

<img width="719" alt="ex4" src="https://github.com/nisia289/INRE-UAL-Blanco-2023/assets/81264277/cccfd6e5-59c0-45b2-88ba-a4a3bcb0d110">

| Nombre            | Adding product to a basket in purchasing system                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                                                                                                                                                        |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | Buyers can add products to the basket in purchasing system                                                                                                                                                                               |
| Actores           | Buyer                                                                                                                                                                                                                                    |
| Precondiciones    | Buyer must be registered in a system                                                                                                                                                                                                     |
| Flujo Normal      | 1.	Actor adds a product to his basket in the system  2.	Product is added to the basket  3.	Product is blocked to other user                                                                                                           |
| Flujo Alternativo | ----                                                                                                                                                                                                                                     |
| Poscondiciones    | Product is added to buyer’s basket and blocked to other users                                                                                                                                                                            |


| Nombre            | Consulting prices                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 4.10.2023                                                                                                  |
| Descripción       | Buyer can consult product prices                                                                           |
| Actores           | Buyer                                                                                                      |
| Precondiciones    | Buyer must be registered in a system                                                                       |
| Flujo Normal      | 1.	Actor checks the offer in a system 2.	Actor sends request 3.	Request is accepted 4.	Price is changed |
| Flujo Alternativo | 3.If there is no agreement with changing the price, it doesn’t change                                      |
| Poscondiciones    | Price is changed reggarding to buyer’s request                                                             |


| Nombre            | Finalize the purchase                                                                                      |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 4.10.2023                                                                                                  |
| Descripción       | Buyer can finalize and buy the product                                                                     |
| Actores           | Buyer                                                                                                      |
| Precondiciones    | Buyer must be registered in a system                                                                       |
| Flujo Normal      | 1.	Buyer makes action to finalize the purchase 2.	Buyer pays for product 3.	Product is sent to buyer 4.	Transaction is closed                                                                                                                           | 
| Flujo Alternativo | 3.If there was a payment issue transaction can be done once again                                          |
| Poscondiciones    | Buyer finalize the purchase and pay for a product                                                          |

| Nombre            | Making sales                                                                                               |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Buyers same as sellers can making sale offers in the system                                                |
| Actores           | Buyer, Seller                                                                                              |
| Precondiciones    | Buyer and seller must be registered and verified in a system                                               |
| Flujo Normal      | 1.	Buyer or Seller select product type 2.	Buyer or Seller fill the data form 3.	Buyer or Seller upload picture of the product 4.	Offer is put into the system                                                                                         |
| Flujo Alternativo | 4. If creating offer wasn’t successfull, procedure can be done once again                                  |
| Poscondiciones    | Offer is visible for each user in the system                                                               |


| Nombre            | Checking prices                                                                                            |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Buyers, Sellers and Suppliers can check offer prices                                                       |
| Actores           | Buyer, Seller                                                                                              |
| Precondiciones    | Buyer and seller must be registered and verified in a system                                               |
| Flujo Normal      | 1.	Actor search for a product in a system 2.	Actor selects one of available products 3.	Product’s price displayes on the screen                                                                                                                           |
| Flujo Alternatico | ----                                  |
| Poscondiciones    | Price is visible after enter the offer details                                                             |


| Nombre            | Checking offers                                                                                            |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Buyers, Sellers and Suppliers can check offers from offers list                                                                                                           |
| Actores           | Buyer, Seller, Supplier                                                                                    |
| Precondiciones    | Buyers, Sellers and Suppliers can check offers from offers list                                            |
| Flujo Normal      | 1.	Actor runs the application 2.	Actor can filter offers using different options 3.	Products list displayes to the actor|
| Flujo Alternatico | 4. If creating offer wasn’t successfull, procedure can be done once again                                  |
| Poscondiciones    | Offer is visible for each user in the system                                                               |

| Nombre            | Notifycating the end of an offer                                                                           |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Supplier can notificate the end of an offer before deleting it                                             |
| Actores           | Supplier                                                                                                   |
| Precondiciones    | Supplier must be registered and verified in a system                                                       |
| Flujo Normal      | 1.	Actor checks the offer 2.	Actor selects reason about ending the offer 3.	Actor sends notification about ending the offer                                                                                                                            |
| Flujo Alternatico | If supplier does not have access to the offer, he can’t send a notification                                |
| Poscondiciones    | Notification is visible in the system                                                                      |


| Nombre            | Deleting the offer                                                                                         |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Supplier can delete offer from the system                                                                  |
| Actores           | Supplier                                                                                                   |
| Precondiciones    | Supplier must be registered in a system                                                                    |
| Flujo Normal      | 1.	Actor selects the offer from offers list 2.	Actor deletes the offer 3.	Offer is deleted from the list |
| Flujo Alternatico | 2.If supplier does not have access to offer, he can’t delete it                                            |
| Poscondiciones    | Offer is deleted from the system                                                                           |

| Nombre            | Notifycating of new products                                                                               |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Supplier can notificate the new products in the system                                                     |
| Actores           | Supplier                                                                                                   |
| Precondiciones    | Supplier must be registered and verified in a system                                                       |
| Flujo Normal      | 1.	Actor runs the system 2.	Actor selects the product type 3.	Actor fills the data form 4.	Actor adds new product to the system 5.	Notification about new product is sent                                                                             |
| Flujo Alternatico | ----                                                                                                       |
| Poscondiciones    | Notification is visible in the system                                                                           |


| Nombre            | Deleting the product                                                                                       |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 11.10.2023                                                                                                 |
| Descripción       | Administrator can delete products from specific offer                                                      |
| Actores           | Administrator                                                                                              |
| Precondiciones    | User must be logged in as an administrator in the system                                                   |
| Flujo Normal      | 1.	Administrator displays the products list 2.	Administrator checks the offer from products list 3.	Administrator checks the specific product 4.	Administrator deletes the product                                                                        |
| Flujo Alternatico | ----                                                                                                       |
| Poscondiciones    | Product is deleted from the offer                                                                          |


| Nombre            | Deleting the product                                                                                       |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 11.10.2023                                                                                                 |
| Descripción       | Administrator can delete products from specific offer                                                      |
| Actores           | Administrator                                                                                              |
| Precondiciones    | User must be logged in as an administrator in the system                                                   |
| Flujo Normal      | 1.	Administrator displays the products list 2.	Administrator checks the offer from products list 3.	Administrator checks the specific product 4.	Administrator deletes the product                                                                        |
| Flujo Alternatico | ----                                                                                                       |
| Poscondiciones    | Product is deleted from the offer                                                                          |

