# Authorization test cases

## TC-01 Login with valid credentials
Preconditions:
- User is registered

Steps:
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click "Login"

Expected result:
- User is logged in successfully

---

## TC-02 Login with empty password
Steps:
1. Open login page
2. Enter valid email
3. Leave password empty
4. Click "Login"

Expected result:
- Validation message is displayed
