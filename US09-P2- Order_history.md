#  Order history 
Priority 2
## Description 
After successful checkout user is able to see all purchases in order history page.  
## Acceptance criteria
1.	After checkout add new row in Order history grid 
2.	Grid has pagination
3.	Grid contains info 
* Order ID - unique id
* Customer – first and second name 
* No. of Products – count of products
* Status 
* Total – sum in $
* Date Added – date in format dd/mm/yyyy
* Button View – open page with order information 

### Order information page 
* Order information page contains all order details, addresses, payment method, shiping details and etc. 
* Each product in grid have buttons “Return” and “Reorder”
* Reorder – create new order with same information

Return – open page “Products return” with order info + “Reason for return” check box, mandatory field, LOV -
1.	Dead On Arrival
2.	Faulty, please supply details
3.	Payment Error
4.	Other, please supply details
5.	Received Wrong Item

## Highlights for testing
