# Bugs

Below are some bugs discovered on websites that I navigated. 

---------------------

**Title:** 
Cart with same products in multiple rows

**Description:** 
When adding a product twice in the cart list, it appears on two rows (the same product). 

**Steps to reproduce:**
1. Go  to https://www.demoblaze.com/prod.html?idp_=1
2. Choose a product
3. Click on  “Add to cart button” twice 
4. Go to “Cart”

**Expected result:** 
User should be able to see the product in one row even if there are multiple and identical products. 

**Actual result:** 
User sees in the Cart two identical products in two separate rows.

**Test data:**  
Choose any product.

---------------------

**Title:**
Negative values are allowed 

**Description:**
The user can enter negative values in fields from the keyboard. 

**Steps to reproduce:** 
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Type -2 in the first and second field. 

**Expected result:**
User shouldn’t be able to type negative values from the keyboard. Should appear a window/pop-up with an error which specifies that the entered value is negative.  

**Actual result:**
User can introduce negative values from the keyboard. 

**Test data:**
-2, -3, -0. 

---------------------

**Title:** 
The site interface is not responsive

**Description:**
The site interface is not responsive on mobile devices which have displays with small dimensions. Devices like: iphone x, samsung galaxy s5, galaxy fold. 

**Steps to reproduce:**
Using a mobile device like above, go to https://www.primariatechirghiol.ro/  

**Expected result:**
User should be able to see a regular interface on mobile devices.  

**Actual result:**
The site interface is not responsive with mobile devices. 

**Test data:** 

---------------------

**Title:**
Information is not visible 

**Description:**
At the “Acasa” section, the information written with gray colour is not visible on white page because the text is written with a small size.  

**Steps to reproduce:** 
1. Go to https://fieni.ro/
2. See the text at “Acasa” section. 

**Expected result:**
User should be able to see and read the text without much attention.    

**Actual result:**
The text is hard to read on devices with small displays.   

**Test data:** “Acasa” section

---------------------

**Title:** 
Missing 404 page

**Description:** When we want to browse a page and it's not working the 404 site page is not available. 

**Steps to reproduce:** 
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login/

**Expected result:**
User should be able to see the 404 page. 

**Actual result:**
User can not see the 404 page when is necessary. 

**Test data:**

---------------------

**Title:** 
API response  

**Description:** When we want to see API response in romanian language, this is not completely displayed in romanian language.   

**Steps to reproduce:** 
1. Create a GET request using Postman to API endpoint attached in test data.

**Expected result:**
User should be able to see the API response in romanian language when he use 'lang' parameter with 'ro' value. 

**Actual result:**
User can not see the API response in romanian language because this is not complitely displayed in romanian language. 

**Test data:** 
api.openweathermap.org/data/2.5/forecast?zip=10001&appid=2cb2be7f539217809ca133c4f9260046&units=metric&lang=ro

---------------------
