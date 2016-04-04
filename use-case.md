| Title  | Details  |
|--------|--------|
| Name  | buy item with credit  |
| Actor  | buyer  |
| Purpose  | find a item and credit payment  |
| Scope  | online shopping site  |
| Level  | user  |
| Stakeholders and interests  | 1) buyer- buy an item  |
|   | 2) seller- sell an item  |
|   | 3) site managers- activities in the site and serve customers  |
| Trigger  | buyer search for item he wants to buy  |
| Prerequisites  | buyer log-in to the shopping site  |
| Successful completion conditions  | the payment compelete and the item ordered successfully  |
| Terms of failure  | the order not complete successfully  |
| Scenario major success  | 1) buyer search for the item  |
|   | 2) the system displays the result to the buyer   |
|   | 3) buyer choose the item he wants   |
|   | 4) the system displays all the details of the item   |
|   | 5) the buyer add the item to the cart   |
|   | 6) the buyer click on his cart icon   |
|   | 7) the system displays all the items that the buyer choose   |
|   | 8) the buyer click on the payment button   |
|   | 9) the system displays credit card information form   |
|   | 10) the buyer fill the fields and press done   |
|   | 11) the system accept the information and performs payment   |
|   | 12) the system displays a success message to the buyer   |
| Extensions (Errors)  | 1. the log-in time is over  |
|   | -- 1.a. the system displays login page   |
|   | -- 1.b. the buyer insert login information again   |
|   | 2. there is no result to the search   |
|   | -- 2.a. the system displays page with item not found   |
|   | -- 2.b. the buyer try different search input   |
|   | 3. credit card information incorrect   |
|   | -- 3.a. the system displays page message fro the buyer that the information incorrect   |
|   | -- 3.b. the buyer put the credit information again   |
|   | -- 3.c. the buyer press done   |
| Alternative scenarios  | 1) the buyer find the item in browse and not search - after find the item continue to (4)  |
|   | 2) the buyer wants to select few items in one payment - after (5) go to (1) when finish go to (6)  |
|   | 3) the buyer is new and does not have account- register - after register start from (1)  |
