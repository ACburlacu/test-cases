# LOGIN
## 1. Log in with correct credentials
### Description
Check if a user can log in using the right credentials.
### Steps to reproduce
1. Visit https://www.udemy.com/
2. Click on "Login" at the top right
3. Follow all steps for passwordless authentication
### Expected result
User is logged in to their Udemy account.
### Pre-conditions
User must have a valid account.

## 2. Check for errors using wrong credentials
### Description
Check if a user can log in using invalid credentials.
### Steps to reproduce
1. Do the first two steps from Case 1
2. Repeat step 3 from Case 1 using an invalid email
### Expected result
User does not receive a confirmation email.
### Test data
Email: `example@email.com`

## 3. Authentiate with no credentials
### Description
Check if a user can log in without using credentials.
### Steps to reproduce
1. Do the first two steps from Case 1
2. Click "Continue with email"
### Expected result
User is warned to fill out an email address.

# SEARCH<br/>
## 4. Get search results
### Description
Check if a user gets results relevant to their search.
### Steps to reproduce
1. Visit https://www2.hm.com/en_us/index.html
2. Click the "🔍" icon at the top right
3. Type something and click on a suggestion
### Expected result
User sees relevant products on the search page.
### Test data
Search: `onesie`

## 5. Auto-fill search
### Description
Check if a user sees product suggestions as they type.
### Steps to reproduce
1. Do the first two steps from Case 4
2. Type something and look for any suggestions
### Expected result
User receives suggestions relevant to the desired item.
### Test data
Search: `lan`

## 6. Look for something invalid
### Description
Check if a user can look for an invalid item.
### Steps to reproduce
1. Do the first two steps from Case 4
2. Type something random in the search box
### Expected result
User does not see product suggestions.
### Test data
Search `jeprotiy`
