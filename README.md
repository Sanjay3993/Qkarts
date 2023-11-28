# Qkarts
Automate an ecommerce website.


Consider that you are part of the QA team of QKART. What are the top 6 critical test cases you will develop for testing the QKART site. Try to  write 5 Positive test cases and at least 1 negative test case.



Test Cases
the manual testing team needs your help to automate the manual test cases they have provided. Let’s go through this module and deliver automation tests for the given manual test cases. . Let's read the test cases , understand them and manually execute them



QKART Site must be up and running
For automation, ensure suitable driver is downloaded and replaced

Verify the functionality of search text box

1. Navigate to home page

2. Search for text : "yonex" in the search box

3. Ensure that the results shown contain the search text in their name

4. Search for text: "Gesundheit"

5. Ensure that no products found message is displayed

3. All results displayed on the page should contain the name "yonex"

5. There should be a "No products found" message



QKART Site must be up and running
For automation, ensure suitable driver is downloaded and replaced
Verify the existence of size chart for certain items and validate contents of size chart

1. Navigate to home page

2. Search for text: "Running Shoes"

3. Verify that the Size Chart Link Exists

4. Click on the size chart link and check the contents of the size chart

5. Verify the existence of size selection drop down

3. Size chart Link should be present

4. On Click , the size chart should be displayed . The contents of the size chart are correct

5. The Size Selection drop down must be present for items with size chart



QKART Site must be up and running
For automation, ensure suitable driver is downloaded and replaced
Verify that a new user can add multiple products in to the cart and Checkout

1. Register a new user

2. Login using this new user

3. Add the following products in to the cart

YONEX Smash Badminton Racquet x 1

Tan Leatherette Weekender Duffle x1

4. Click on Checkout

5. Add a new address

6. Select the added address using radio button

7. Click on Place order

8 . Ensure that the order is placed

4. The user is redirected to the checkout page

4. The contents of the cart on the checkout page should be correct ( contents , total amount )

8. The user should be redirect to the order success page

9. Order successful message should be displayed



QKART Site must be up and running
For automation, ensure suitable driver is downloaded and replaced
Verify that the contents of the cart can be edited

1. Navigate to the home page

2. Add the following products to the cart

- Xtend Smart Watch x2

- Yarine Floor Lamp x1

3. Remove 1 Qty of The Xtend Smart Watch from the cart

4. Remove 1 Qty of Yarine Floor Lamp from the cart

5. Click on Checkout

6. Verify the contents of cart on the checkout page

7. Log out

6.The Cart on the checkout page should contain the following items

Xtend Smart Watch x1



QKART Site must be up and running
For automation, ensure suitable driver is downloaded and replaced
Verify that insufficient balance error is thrown when the wallet balance is not enough

1. Register a new user
2. Login using the registered user
3. Add the following items in the cart
- Stylecon 9 Seater RHS Sofa Set x10
4. Check out
5. Add a new address

6. Select the added address using radio button

7. Click on Place order
8. Verify if the order is placed

7. There should be an error message: “You do not have enough balance in your wallet for this purchase”
