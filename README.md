# NodeJS-ExpressStaticPassportLocal
Example of access control to the 'public' directory via Passport-Local using the NodeJS Express framework.

This code is based on the passport-local authentication example (https://github.com/passport/express-4.x-local-example). The code has been modified to provide an example of access control to the 'public' directory where static web pages may exist. If user authentication is successful, access to the contents of 'public' will be granted. Otherwise, the user will be redirected to the login page.

To start project, run the following commands:


```
npm install
npm start
```
