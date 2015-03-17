========================================================================================
===========================  Test Suite TS#01: REGISTRATION  ===========================
========================================================================================


========================================================================================
==================  TEST CASE TC#01-1: Successful Registration. Step 1  ================
========================================================================================
***Pre-Conditions:***

1. Anonymous user.
2. Open web page: "/registration".

***Steps:***

1. Verify "EVOLUTION 359" logo presence.
2. Verify "Register" and "Log In" links presence to the right from logo.
3. Verify "Registration" title presence.
4. Verify "Username" field presence. Field should be marked as required (*).
5. Verify "Email Address" field presence. Field should be marked as required (*).
6. Verify "Password" field presence. Field should be marked as required (*).
7. Verify "Confirm Password" field presence. Field should be marked as required (*).
8. Verify "First Name" field presence. Field should be marked as required (*).
9. Verify "Last Name" field presence. Field should be marked as required (*).
10. Verify "Gender" radio buttons "Male" and "Female" presence. Radio buttons field should be marked as required (*).
11. Verify "Weight" field presence. Field should be marked as required (*).
12. Verify "Goal Weight" field presence. Field should be marked as required (*).
13. Verify "Height" field presence. Field should be marked as required (*).
14. Verify "Age" field presence. Field should be marked as required (*).
15. Verify "Body Fat" field presence. Field should be marked as required (*).
16. Verify "Don't Know Your Body Fat?" title presence.
17. Verify "body fat calculator" link presence.
18. Verify "Next" button presence.
19. Verify Joe's photo presence at the top-right side of site.
20. Verify "As A Subscriber You Get:" title presence under Joe's photo.
21. Verify list of opportunities presence under "As A Subscriber You Get:" title.
22. Verify green banner with text "ONLY $ 24.99/month" presence under the list.
23. Enter "Username as "test".
24. Enter "Email as "test@gmail.com".
25. Enter "Password/Confirm Password as "password1".
26. Enter "First Name" as "firstname".
27. Enter "Last Name" as "lastname".
28. Choose "Male" radio button from "Gender" block.
29. Enter "Weight" as "105".
30. Enter "Goal Weight" as "85".
31. Enter "Height" as "180" cm.
32. Enter "Age" as "30".
33. Enter "Body Fat" as "17".
34. Press "Next" button.

***Expected Result:***

Web page "/registration/2" successfully opens.

***Post-Conditions:***

None


========================================================================================
======  TEST CASE TC#01-2: Successful Registration (Monthly Subscription). Step 2  =====
========================================================================================
***Pre-Conditions:***

Complete "TEST CASE TC#01-1: Successful Registration. Step 1".
--> Web page "/registration/2" successfully opens.

***Steps:***

1. Verify "EVOLUTION 359" logo presence.
2. Verify "Register" and "Log In" links presence to the right from logo.
3. Verify "Submit Order & Get Started" title presence.
4. Verify Monthly and Annual subscriptions radio buttons presence in "Start Your Program!" block.
5. Verify "Billing Information" title presence.
6. Verify "Accepted Credit Cards" information presence.
7. Verify "Name on Credit Card" field presence. Field should be marked as required (*).
8. Verify "Credit Card Number" field presence. Field should be marked as required (*).
9. Verify "Security Code" field presence. Field should be marked as required (*).
10. Verify "Card Expiration" months drop-down list presence. Drop-down list field should be marked as required (*).
11. Verify "Card Expiration" years drop-down list presence.
12. Verify "Billing Address" title presence. Field should be marked as required (*).
13. Verify "Street Address" field presence. Field should be marked as required (*).
14. Verify "Address Line 2" field presence.
15. Verify "City" field presence. Field should be marked as required (*).
16. Verify "Country" drop-down list presence. Drop-down list field should be marked as required (*).
17. Verify "State" drop-down list presence. Field is required for "United States" Country.
18. Verify "Postal Code" field presence. Field should be marked as required (*).
19. Verify "Place Order" button presence.
20. Verify text presence below the "PLACE ORDER" button: 
	"We will enter your subscription as indicated above to insert name of program and you will be charged first month's charge today.
	...
	By placing your order you agree with our Terms of Service and Privacy Policy."
21. Verify Joe's photo presence at the top-right side of site.
22. Verify "As A Subscriber You Get:" title presence under Joe's photo.
23. Verify list of opportunities presence under "As A Subscriber You Get:" title.
24. Verify green banner with text "ONLY $ 24.99/month" presence under the list.
25. Choose "Monthly subscription" radio button in "Start Your Program!" block.
26. Enter "Name on Credit Card" as "visa".
27. Enter "Credit Card Number" as "4111111111111111".
28. Enter "Security Code" as "321".
29. Choose current month from "Card Expiration" months drop-down list.
30. Choose current year+2 from "Card Expiration" years drop-down list.
31. Enter "Street Address" as "street".
32. Enter "Address Line 2" as "line".
33. Enter "City" as "city".
34. Choose "United States" from Country drop-down list.
35. Choose "California" from State drop-down list.
36. Enter "Postal Code" as "90210".
37. Press "Place Order" button.

***Expected Result:***

1. Web page "/home/success/1" successfully opens.
2. Pop-up "Welcome!" message with welcome video and "All done!" button is appears. 
3. Video is available and could be played.
4. Message about successful purchase is appears:
	"Program Purchased
	 Your purchase has been successfully processed!"
	 
***Post-Conditions:***

1. Press "All done!" button.
2. Close web page "/home/success/1".


========================================================================================
======  TEST CASE TC#01-3: Successful Registration (Annual Subscription). Step 2  ======
========================================================================================
***Pre-Conditions:***

Complete "TEST CASE TC#01-1: Successful Registration. Step 1".
--> Web page "/registration/2" successfully opens.

***Steps:***

1. Verify "EVOLUTION 359" logo presence.
2. Verify "Register" and "Log In" links presence to the right from logo.
3. Verify "Submit Order & Get Started" title presence.
4. Verify Monthly and Annual subscriptions radio buttons presence in "Start Your Program!" block.
5. Verify "Billing Information" title presence.
6. Verify "Accepted Credit Cards" information presence.
7. Verify "Name on Credit Card" field presence. Field should be marked as required (*).
8. Verify "Credit Card Number" field presence. Field should be marked as required (*).
9. Verify "Security Code" field presence. Field should be marked as required (*).
10. Verify "Card Expiration" months drop-down list presence. Drop-down list field should be marked as required (*).
11. Verify "Card Expiration" years drop-down list presence.
12. Verify "Billing Address" title presence. Field should be marked as required (*).
13. Verify "Street Address" field presence. Field should be marked as required (*).
14. Verify "Address Line 2" field presence.
15. Verify "City" field presence. Field should be marked as required (*).
16. Verify "Country" drop-down list presence. Drop-down list field should be marked as required (*).
17. Verify "State" drop-down list presence. Field is required for "United States" Country.
18. Verify "Postal Code" field presence. Field should be marked as required (*).
19. Verify "Place Order" button presence.
20. Verify text presence below the "PLACE ORDER" button: 
	"We will enter your subscription as indicated above to insert name of program and you will be charged first month's charge today.
	...
	By placing your order you agree with our Terms of Service and Privacy Policy."
21. Verify Joe's photo presence at the top-right side of site.
22. Verify "As A Subscriber You Get:" title presence under Joe's photo.
23. Verify list of opportunities presence under "As A Subscriber You Get:" title.
24. Verify green banner with text "ONLY $ 24.99/month" presence under the list.
25. Choose "Annual subscription" radio button in "Start Your Program!" block.
26. Enter "Name on Credit Card" as "visa".
27. Enter "Credit Card Number" as "4111111111111111".
28. Enter "Security Code" as "321".
29. Choose current month from "Card Expiration" months drop-down list.
30. Choose current year+2 from "Card Expiration" years drop-down list.
31. Enter "Street Address" as "street".
32. Enter "Address Line 2" as "line".
33. Enter "City" as "city".
34. Choose "United States" from Country drop-down list.
35. Choose "California" from State drop-down list.
36. Enter "Postal Code" as "90210".
37. Press "Place Order" button.

***Expected Result:***

1. Web page "/home/success/12" successfully opens.
2. Pop-up "Welcome!" message with welcome video and "All done!" button is appears. 
3. Video is available and could be played.
4. Message about successful purchase is appears:
	"Program Purchased
	 Your purchase has been successfully processed!"
	 
***Post-Conditions:***

1. Press "All done!" button.
2. Close web page "/home/success/12".


========================================================================================
===========  TEST CASE TC#01-4: Successful Registration. Email Notifications  ==========
========================================================================================
***Pre-Conditions:***

1. For permission to send emails run this commands:
   "app/console --client=evolution -e=staging programs:send-daily-emails";
   "app/console -e=staging --client=evolution email:send".
2. Complete "TEST CASE TC#01-1: Successful Registration. Step 1". (At this step enter your real email address).
3. Complete "TEST CASE TC#01-2: Successful Registration (Monthly Subscription). Step 2".

***Steps:***

1. Open your real email address inbox that you enter at Registration Step 1 (TC#01-1).
2. Verify email letter #1 from staging@healthycode.com with subject "Welcome to Evolution!".
3. Verify Evolution logo with link to "https://evolution.exercise-staging.com" in letter #1.
4. Verify letter #1 title "Congratulations on taking the first step towards your goal!".
5. Verify welcome text in letter #1 with "Program Settings page" link and "log in to the website" link.		
6. Verify email letter #2 from staging@healthycode.com with subject "Order # <order number>: <program name> Subscription".
7. Verify Evolution logo with link to "https://evolution.exercise-staging.com" in letter #2.
8. Verify first program data column in letter #2:
	"Order: <order number>
	 Receipt Date: <date>
	 Total: <monthly or annual subscription price>"
9. Verify second program data column in letter #2:
	"Billed to: <name on credit card>
	 <street address>, <postal code>
	 <credit card number>   Exp. <expired date>"
10. Verify billing information data in letter #2:
	"Item						Qty	Total
	 Evolution Subscription (<#> months)		1	<monthly or annual subscription price>
							Total	<monthly or annual subscription price>

***Expected Result:***

Email letters #1 and #2 successfully received. Subjects and email text are corresponding to this TC requirements.

***Post-Conditions:***

1. Сlose your mailbox.
2. Press Ctrl+C in console to stop commands entered in pre-conditions.


========================================================================================
====================  TEST CASE TC#01-5: Registration. Empty values  ===================
========================================================================================
***Pre-Conditions:***

1. Anonymous user.
2. Open web page: "/registration".

***Steps:***

1. Don't fill in fields.
2. Press "Next" button.
   --> Verify errors "This value should not be blank." appear for all fields except "Confirm Password".
3. Enter "Username as "test".
4. Enter "Email as "test@gmail.com".
5. Enter "Password/Confirm Password as "password1".
6. Enter "First Name" as "firstname".
7. Enter "Last Name" as "lastname".
8. Choose "Male" radio button from "Gender" block.
9. Enter "Weight" as "105".
10. Enter "Goal Weight" as "85".
11. Enter "Height" as "180" cm.
12. Enter "Age" as "30".
13. Enter "Body Fat" as "17".
14. Press "Next" button.
    --> "/registration/2" web page is opens.
15. Don't fill in fields.
16. Press "Place Order" button.
    --> Verify errors "This value should not be blank." appear for all fields except unneeded to fill "Address Line 2" and pre-filled drop-downs.
17. Choose "Annual subscription" radio button in "Start Your Program" block.
18. Enter "Name on Credit Card" as "visa".
19. Enter "Credit Card Number" as "4111111111111111".
20. Enter "Security Code" as "321".
21. Choose current month from "Card Expiration" months drop-down list.
22. Choose current year+2 from "Card Expiration" years drop-down list.
23. Enter "Street Address" as "street".
24. Enter "Address Line 2" as "line".
25. Enter "City" as "city".
26. Choose "United States" from Country drop-down list.
27. Choose "California" from State drop-down list.
28. Enter "Postal Code" as "90210".
29. Press "PLACE ORDER" button.
    --> web page "/home/success/12" successfully opens.

***Expected Result:***

Specified errors are successfully appear near empty values and disappear when value isn't empty.

***Post-Conditions:***

1. Press "All done!" button on pop-up window.
2. Close web page "/home/success/12".


========================================================================================
=========================  TEST CASE TC#01-6: Validation. Height  ======================
========================================================================================
***Pre-Conditions:*** 

1. Anonymous user.
2. Open web page: "/registration".

***Steps:***

1. Press "Next" button.
   --> Verify error message "This value should not be blank." presence.
2. Enter value "91" and click "Next" button.
   --> Verify error message "This value should be 92 cm or more." presence.
3. Enter value "255" and click "Next" button.
   --> Verify error message "This value should be 254 cm or less." presence.
4. Enter value "1q1" and click "Next" button.
   --> Verify error message "This value should be a valid number" presence.
5. Enter value "92" and click "Next" button.
   --> Verify error message absence.
6. Enter value "254" and click "Next" button.
   --> Verify error message absence.

***Expected Result:***

Correct error messages present. After entering valid values error messages absent.

***Post-Conditions:***

Close "/registration" web page.


========================================================================================
================  TEST CASE TC#01-7: Registration. Non unique username  ================
========================================================================================
***Pre-Conditions:***

1. Register new user with "Username:Password" as "Test:password1" ("Test" with first uppercase letter).
2. Log out.
3. Open web page "/registration".

***Steps:***

1. Complete "TEST CASE TC#01-1: Successful Registration. Step 1". At this step enter Username as "test" ("test" with first lowercase letter).
   --> Verify error message "This username already exists." presence.

***Expected Result:***

1. Error message "This username already exists." present while trying to enter the same name with different case letters (lower- and uppercase).
2. After entering nonexistent username error message absent.

***Post-Conditions:***

Close "/registration" web page.


========================================================================================
==============  TEST CASE TC#01-8: User card charged after registration  ===============
========================================================================================
***Pre-Conditions:***
1. Completed TEST CASE TC#01-1: Successful Registration. Step 1.
2. Try to complete TEST CASE TC#01-2: Successful Registration. Step 2 with credit card number 4111222333444555.
-> Verify error message "The credit card number is invalid."
3. Completed TEST CASE TC#01-2: Successful Registration. Step 2.

***Steps:***
1. Login as "andrey:andrey".
2. Open "/backend/order/list" page.
3. Verify new user order presence.
4. Verify choosen "Is Processed" checkbox for this new user.
5. Set OFF checkbox "Is Processed".
-> Verify message: 
	"System message
	 Order #[number] was unprocessed"
6. Set ON checkbox "Is Processed".
-> Verify message: 
	"System message
	 Order #[number] was processed"

***Expected Result:***
"Is Processed" checkbox is ON after user registration. ON/OFF set works correctly.

***Post-Conditions:***
Close /backend/order/list page.


========================================================================================
Test Case TC#01-9: Registration, non unique email

Pre-Requisite

User1 is already exist(username/password: tester1/test@gmail.com).

Steps:

1. Open "/registration" page.
2. Enter email as "test@gmail.com".
3. Press Continue to Checkout.
4. Verify error "Existing Account with This Email Address" appears.


Test Case TC#01-10: Registration, wrong format email

Pre-Requisite

Anonymous user

Steps:

1. Open "/registration" page.
2. Enter email address as "test" and press Continue to Checkout.
3. Verify error message "Please Enter a Valid Email Address".
4. Repeat 3-4 for enter email as "#@%^%#$@#$@#.com".
5. Repeat 3-4 for enter email as "@gmail.com".
6. Repeat 3-4 for enter email as "test < test@gmail.com>".
7. Repeat 3-4 for enter email as "test.gmail.com".
8. Repeat 3-4 for enter email as "test@gmail@gmail.com".
9. Repeat 3-4 for enter email as "test..s@gmail.com".

Test Case TC#01-11: Registration, invalid username

Pre-Requisite

Anonymous user

Steps:

1. Open "/registration" page.
2. Enter username less than 3 characters.
3. Press Continue to Checkout.
4. Verify error "Please Enter a Valid Username(3+ Characters)" appears.


Test Case TC#01-12: Registration, invalid password

Pre-Requisite

Anonymous user

Steps:

1. Open "/registration" page.
2. Enter password less than 7 characters.
3. Press Continue to Checkout.
4. Verify error "Password must be at least 7 characters long and include at least one alphabetic and numeric character" appears.
5. Enter password more than 7 characters but without alphabetic and press Complete Registration.
6. Verify error "Password must be at least 7 characters long and include at least one alphabetic and numeric character" appears.


Test Case TC#01-13: Registration, passwords don't match

Pre-Requisite

The objected user has not registered yet.

Steps:

1. Open "/registration" page.
2. Enter passwords don't match.
3. Press Continue to Checkout.
4. Verify error "Password's Don't Match!" appears.


