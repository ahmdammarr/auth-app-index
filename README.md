# auth-app-index
This project is a country-specific authentication system that employs two distinct security strategies for mobile and web applications.

For the web application, we use server-side sessions and API calls. The client only receives the fully rendered HTML, ensuring that both client and server data remain under our control.

For the mobile application, we rely on secure storage to save sensitive data, such as tokens, on the client side.

This System has three parts: 

 - [Simple express server](https://github.com/ahmdammarr/auth-simple-express-server)
 - [Mobile App](https://github.com/ahmdammarr/country-based-auth-app)
 - [Next js web app](https://github.com/ahmdammarr/country-based-web-auth-app)

So I created the express server to simulate an auth server with a different database with a simple JSON file.

To use the app and the web you need to run the server first.

