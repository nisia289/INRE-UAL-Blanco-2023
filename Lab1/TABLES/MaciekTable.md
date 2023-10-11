| Nombre            | Adding product to a basket in purchasing system                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                                                                                                                                                        |
| Fecha             | 4.10.2023                                                                                                                                                                                                                                |
| Descripción       | Buyers can add products to the basket in purchasing system                                                                                                                                                                               |
| Actores           | Buyer                                                                                                                                                                                                                                    |
| Precondiciones    | Buyer must be registered in a system                                                                                                                                                                                                     |
| Flujo Normal      | 1.	Actor adds a product to his basket in the system  2.	Product is added to the basket  3.	Product is blocked to other user                                                                                                           |
| Flujo Alternatico | ----                                                                                                                                                                                                                                     |
| Poscondiciones    | Product is added to buyer’s basket and blocked to other users                                                                                                                                                                            |


| Nombre            | Consulting prices                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 4.10.2023                                                                                                  |
| Descripción       | Buyer can consult product prices                                                                           |
| Actores           | Buyer                                                                                                      |
| Precondiciones    | Buyer must be registered in a system                                                                       |
| Flujo Normal      | 1.	Actor checks the offer in a system 2.	Actor sends request 3.	Request is accepted 4.	Price is changed |
| Flujo Alternatico | 3.If there is no agreement with changing the price, it doesn’t change                                      |
| Poscondiciones    | Price is changed reggarding to buyer’s request                                                             |


| Nombre            | Finalize the purchase                                                                                      |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 4.10.2023                                                                                                  |
| Descripción       | Buyer can finalize and buy the product                                                                     |
| Actores           | Buyer                                                                                                      |
| Precondiciones    | Buyer must be registered in a system                                                                       |
| Flujo Normal      | 1.	Buyer makes action to finalize the purchase 2.	Buyer pays for product 3.	Product is sent to buyer 4.	Transaction is closed                                                                                                                           | 
| Flujo Alternatico | 3.If there was a payment issue transaction can be done once again                                          |
| Poscondiciones    | Buyer finalize the purchase and pay for a product                                                          |

| Nombre            | Making sales                                                                                               |
|-------------------|------------------------------------------------------------------------------------------------------------|
| Autor             | Maciej Ignatowicz                                                                                          |
| Fecha             | 09.10.2023                                                                                                 |
| Descripción       | Buyers same as sellers can making sale offers in the system                                                |
| Actores           | Buyer, Seller                                                                                              |
| Precondiciones    | Buyer and seller must be registered and verified in a system                                               |
| Flujo Normal      | 1.	Buyer or Seller select product type 2.	Buyer or Seller fill the data form 3.	Buyer or Seller upload picture of the product 4.	Offer is put into the system                                                                                         |
| Flujo Alternatico | 4. If creating offer wasn’t successfull, procedure can be done once again                                  |
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
| Descripción       |                                                                                                            |
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


