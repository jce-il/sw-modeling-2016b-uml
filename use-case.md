**Use-case name**:
Online shop

**Main actor**:
Shop users (buyers/sellers)

**Goal**:
buyers want to buy an item either in auction or buy-now.
sellers want to sell an item.

**Scope**:
a web service for product's sell/buy.


**Actors/Stakeholders**:

<ul>
<li>buyer - want to buy items</li>
<li>seller - want to sell their items</li>
<li>service managers - to keep fairness between buyers and sellers</li>
<li>credit card/paypal service - vertification and charging users</li>
</ul>

**Trigger**:
User enters the online-shop

**Pre-requirement**:
buyer find an item he wants to purchase
sell select an item he wants to sell.

**Successful Ending Condition**:
user successfully buy/sell an item.

**Failure Condition**:
for example: buyer tries to buy an item that doesnt exists.

**Main successful scenario**:

1. User Enter website to sell/buy item

2. User register as buyer/seller.

3. Seller post a new item to sell

4. Buyer find an item he needs.

5. Buyer click the purchase button

6. Buyer verify his paypal/credit card info

7. Seller receives his money

8. Seller ships the item to the buyer's address.


**More (errors)**:

1. session timeout
<ul>
<li>redirect user to homepage.</li>
<li>user login again or just leaves.</li>
</ul>
2. item is out of stock but site was not updated
<ul>
<li>show the user an error message.</li>
<li>inform the buyer that someone needs the item maybe he has extra.</li>
</ul>
3. seller does not have enough money
<ul>
<li>show the user an error message.</li>
<li>give him an option to change the payment method.</li>
</ul>