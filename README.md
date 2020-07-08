# learning-react-auth0

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Learning to add Auth0 to a React app.

Tutorial: <https://auth0.com/docs/quickstart/spa/react/01-login>

YouTube video to get a quick visual idea of the steps: <https://www.youtube.com/watch?v=GuxEO8gfcZw> (but not exactly the same steps as those I did following the official tutorial)

1. Quick setup of [React app template](https://github.com/facebook/create-react-app) and [Auth0 SDK](https://github.com/auth0/auth0-react):

   ```bash
   npx create-react-app my-app; cd my-app
   yarn add @auth0/auth0-react
   ```

2. Create an Auth0 account at <https://auth0.com>
3. Create an SPA app and go to settings.
4. Copy `http://localhost:3000` into 3 fields: Allowed Callback URLs, Allowed Logout URLs, and Allowed Web Origins.
5. Save changes.
6. Copy the Domain and Client ID for use inside your React JS code (`YOUR_DOMAIN` and `YOUR_CLIENT_ID).
7. Make the edits you see in this repo for `index.js` (edit) -> `App.js` (edit) -> `LoginButton.js` (create)
   - Example of such edits here: <https://github.com/hchiam/learning-react-auth0/commit/5f681ea4d3b676bf6b59866039e52837466c60c2>
8. Replace `YOUR_DOMAIN` and `YOUR_CLIENT_ID` with the strings you copied in an earlier step.
9. You can run the app inside `my-app` and see that clicking on the Login button redirects you to Auth0:

   ```bash
   yarn start
   ```

## Where to go from here

- `<Router>` to an authenticated page.
- Logout.
