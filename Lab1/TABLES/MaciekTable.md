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
