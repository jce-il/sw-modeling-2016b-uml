## Detailed Use Case

- see [cockburn](http://alistair.cockburn.us/get/2465) p. 68-9 (74-5) and lecture slides

### Customer buys product for best price:
- Context: The customer uses the site for finding the best price for a specific item
- Scope: The site usage and experience from the view point of a web customer - this is the main goal of the system
- Level: user-goal
- Primary Actor: Customer


- Precondition: the customer has loaded the zap.co.il site (and possibly logged in)
- Minimal Guarantees: In case of no matches / data - a descriptive message will be shown
- Success Guarantees: The customer is redirected to a concreate shop where item can be purchased
                        
- Trigger: customer imputs criteria in the designated location on web page
- Main Success Scenario: 
    1. the zap web page is loaded
    2. the customer inputs a criteria to search by
    3. The system displays a list of items that matches criteria with the price in a notable location
    3. the customer clicks on one of the items in the list.
    4. The system redirects the customer to a shop site where item can be purchased

Extensions:
All items should have been added previously by shops. including links to the appropriate item.
