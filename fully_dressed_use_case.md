## Fully Dressed Use Case ##

This document is the fully dressed use case of the check out function.  

### 1. Use case number 7: Check Out (Customer) ###


**Description:**
Allows a customer to complete their transaction by checking out. This could be with a basket of products or with a single product. User will process the transaction the same way and will be required to fill out their payment details exactly the same way. 
Details of user will be saved for future transactions and for details about the payment.


**Level:**
User-Level goal (EBP level)


**Primary Actor:**
Customer


**Stakeholders and interests:**

<u>Administrator:</u> Wants customer to use this function and purchase products to generate income

<u>Customer:</u> Wants a fast and easy to use application to buy their desired products
Accountant: Wants a record of each transaction that occurs


**Success guarantee:**
<ul>
	<li>User's payment method had sufficient funds</li>
	<li>Products stock level must be altered</li>
</ul>

**Main Success Scenario:**
User has used the ‘Check Out’ function to purchase all the items in their basket. The transaction has been completed without error and all parties are happy


**Extensions:**
<ul>
	<li>User entered wrong payment details and was displayed with an error message when they tried to finish the transaction.</li>
	<li>Products that customer tried to buy did not have stock</li>
	<ul><li>Products could have been bought after customer added them to basket</li></ul>
	<li>Customer decided they did not want to buy certain product so had to use the ‘Remove Product From Basket’ function.</li>
</ul>

**Preconditions:**
<ul>
	<li>In order for this use case to work the user must enter the correct details required of them.</li> 
	<li>The product or products they wish to buy must be in stock.</li> 
	<li>The payment details given must be valid</li> 
</ul>

**Frequency of Occurrence:**
This function should be used very frequently. This is the only way for a customer to purchase products so ideally every customer that uses the application should use this function


**Complexity:**
Function should be moderate enough to develop. No aspect is too difficult. With a good design there should not be any problems. Easiest solution would be to identify all the requirements before coding begins.




2 functions chosen are ‘Waste Product’ and ‘Check Out’
