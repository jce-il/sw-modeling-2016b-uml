Discussion:  
__________
The unique thing about the ZAP online store is that it does not actualy offer any offers of its own,
but collects offers from concreate sotres and helps the consumers to compare them.
This uniquness is reflected in the activity and sequence diagrams where they both ends when the customer is redirected to another, external, site.  

What I have discuvwerd through out the Analysis is that they have built a rather clever interface for achieving that goal.
First, when a user performs a search - it recievs a list of prodcuts that matches the search (e.g. for computers - he might get a list of specifc moduls of PCs, laptops etc..)  
Then - the use may refine the serach and eventualy select a specifc item.  
Once a specifc item (e.g a DELL laptop of model 1234) was selected, the user will recieve a list of offers for the specific product in a varaiaty of stores.  
This was implemented in a rather clever way since the GUI for the list of products and the list of offers looks the same and is very intuitive to the user.  


This observation is reflected in the class diagram, where the consept of an "Abstract product" is itroduced and is used both classes of :
 1. "Criteria result set" (i.e. list of items who matches a specific search)
 2. Offer list (i.e. a concreate product which is a composed of the abstract product, a concreate store and a price)
