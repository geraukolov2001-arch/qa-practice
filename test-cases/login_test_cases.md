# Login test cases

## TC-01 Login with invalid email format
Preconditions:
- Login page is opened

Steps:
1. Enter invalid email (without "@")
2. Enter any password
3. Click "Login"

Expected result:
- Error message is displayed
- Request returns 400 Bad Request
- Response contains user_message about invalid format

---

## TC-02 Login with valid email and invalid password
Steps:
1. Enter valid email
2. Enter invalid password
3. Click "Login"

Expected result:
- Error message is displayed
- Server response indicates authentication failure
