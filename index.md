# TASK 2 & 3

### TEST CASE

| Test Case ID | Description | Pre-Condition | Test Step | Expected Result | Actual Result | Status |
| ------------ | ----------- | ------------- | --------- | --------------- | ------------- | ------ |
| Login        | Login with valid data | User open Alfacart app | > User click toggle menu > User click Login button > User input valid email / phone number > User input valid password > User click Login button | Login success | As Expected | Pass |
|| Login with invalid data | User open Alfacart app | > User click toggle menu > User click Login button > User input invalid email / phone number > User input invalid password > User click Login button | Error message shown | As Expected | Pass |
|| Login with registered facebook account | User open Alfacart app | > User click ""toggle"" menu > User click ""Login"" button > User click ""facebook"" button > User click ""continue as"" button | Login success | As Expected | Pass |
|| Login with unregistered facebook account | User open Alfacart app | > User click ""toggle"" menu > User click ""Login"" button > User click ""facebook"" button > User click ""continue as"" button | Error message shown | As Expected | Pass |
|| Login with invalid email / phone number | User open Alfacart app | > User click toggle menu > User click Login button > User input invalid email / phone number > User input valid password > User click Login button | Error message shown | As Expected | Pass |
|| Login with invalid password | User open Alfacart app | > User click toggle menu > User click Login button > User input valid email / phone number > User input invalid password > User click Login button | Error message shown | As Expected | Pass |
| Search feature | Search product with relevant keyword | User have logged in alfacart | > User search product, e.g: sari roti > User click ""search"" button | Product founded | As Expected | Pass |
|| Search product with irrelevant keyword | User have logged in alfacart | > User search product, e.g: organ tubuh > User click ""search"" button | Product not found | As Expected | Pass |
|| Search product with symbol keyword | User have logged in alfacart | > User search product, e.g: !@# > User click ""search"" button | Product not found | Product founded: electronic product appeared | Fail | 
|| Search product with random keyword | User have logged in alfacart | > User search product, e.g: aiueoqwerty > User click ""search"" button | Product not found | As Expected | Pass |
| Sort feature | Sort by relevance | User have searched a product | 1. Click "Sort by relevance" button |	Sort by relevance success |	As Expected |	Pass |
|| Sort by promo | User have searched a product |	1. Click "Sort by promo" button |	Sort by promo success |	As Expected |	Pass |
|| Sort by highest rated |	User have searched a product |	1. Click "Sort by highest rate" button |	Sort by highest rated success |	As Expected |	Pass |
|| Sort by name (A-Z) |	User have searched a product |	1. Click "Sort by name(A-Z)" button	| Sort by name(A-Z) success |	As Expected |	Pass |
|| Sort by name (Z-A) |	User have searched a product |	1. Click "Sort by name(Z-A)" button |	Sort by name(Z-A) success |	As Expected |	Pass |
|| Sort by lowest price |	User have searched a product |	1. Click "lowest price" button |	Sort by lowest price success |	As Expected |	Pass |
|| Sort by highest price |	User have searched a product |	1. Click "highest price" button |	Sort by highest price success |	As Expected |	Pass |
|| Sort by new product |	User have searched a product |	1. Click "new product" button	| Sort by new product success |	As Expected |	Pass |
| Add to cart |	Add single product to cart |	User have logged in alfacart | > User search product, e.g: bread > User select product > User click ""add to cart"" button |	1 product added to cart |	As Expected |	Pass |
|| Add 1000 product to cart |	User have logged in alfacart |	> User search product, e.g: bread > User select product > User select 1000 quantity > User click ""add to cart"" button |	Error message shown |	As Expected |	Pass |
| Checkout | Verify checkout page | User have added product to cart | 
