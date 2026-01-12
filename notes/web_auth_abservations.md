# Web authorization observations

- Login form sends POST request to authorization endpoint
- Client-side validation prevents request for invalid format
- Server-side validation returns 400 for incorrect input
- UI error messages correspond to server response
- Console warnings (CSP, ads) do not affect authorization flow
