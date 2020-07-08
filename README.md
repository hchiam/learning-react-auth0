# learning-react-auth0

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Learning to add Auth0 to a React app.

Tutorial: <https://auth0.com/docs/quickstart/spa/react/01-login>

YouTube video to get a quick visual idea of the steps: <https://www.youtube.com/watch?v=GuxEO8gfcZw> (but not exactly the same steps as those I did following the official tutorial)

1. Create an Auth0 account at <https://auth0.com>
2. Create an SPA app and go to settings.
3. Copy `http://localhost:3000` into Allowed Callback URLs, Allowed Logout URLs, and Allowed Web Origins.
4. Save changes.
5. Copy the Domain and Client ID for use inside your React JS code.
6. Make the edits you see here for index.js (edit) -> App.js (edit) -> Login.js (create)

```bash
npx create-react-app test-auth0; cd test-auth0
yarn add @auth0/auth0-react
yarn start
```
