# next-connect and Passport

This example creates a basic [CRUD] app using next-connect and cookie-based authentication with Passport.js. The cookie is securely encrypted using @hapi/iron.

The example shows how to do a sign up, login, logout, and account deactivation. It utilizes [SWR](https://swr.vercel.app/) to fetch the API.

For demo purpose, the users database is stored in the cookie session. replace it with an actual database to store users in [db.js](lib/db.js).

## DeployMENT

DeployED the example using Vercel
