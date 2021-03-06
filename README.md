<h1 align="center">RoboFi</h1>

<hr>

```
Types of pages

public: everybody can see them
private: only logged in users can see them
```

- General
  - home
  - not-found
- Auth
  - sign-in
  - sign-up
  - forgot-password
  - forgot-password-email-sent
  - password-reset
  - password-reset-succeeded
  - password-reset-failed
- Settings
  - account
  - appearance
  - billing
  - blocked-Users
  - notifications
  - security
  - security-log
- User
  - my-profile
  - overview
- Features
  - dashboard

## π§± Self-contained components

- footer
- header
- layout

```console
ββββapp
β   ββββ@core
β   β   ββββdirectives
β   β   β   ββββclick-outside
β   β   ββββguards
β   β   ββββinterceptors
β   β   ββββpipes
β   β   β   ββββbytes
β   β   ββββservices
β   β   β   ββββseo
β   β   β   ββββtheme
β   β   ββββutils
β   ββββ@shell
β   β   ββββft
β   β   ββββui (layout components)
β   β       ββββfooter
β   β       ββββheader
β   β       ββββlayout
β   β       ββββnot-found
β   ββββcomponents (generic shared components)
β   ββββpages
β       ββββauth
β       β   ββββpages
β       β   β   ββββforgot-password
β       β   β   ββββforgot-password-email-sent
β       β   β   ββββpassword-reset
β       β   β   ββββpassword-reset-failed
β       β   β   ββββpassword-reset-succeeded
β       β   β   ββββsign-in
β       β   β   ββββsign-up
β       β   ββββservices
β       ββββdashboard
β       ββββhome
β       ββββsettings
β       β   ββββpages
β       β       ββββaccount
β       β       ββββappearance
β       β       ββββbilling
β       β       ββββblocked-users
β       β       ββββnotifications
β       β       ββββsecurity
β       β       ββββsecurity-log
β       ββββuser
β           ββββpages
β               ββββmy-profile
β               ββββoverview
ββββassets
ββββenvironments
ββββtheme
    ββββ01-base
    ββββ02-components
    ββββ03-utilities
```

## π§ββοΈ Commands

| Command       | Description                                                    | NPM                   | Yarn               | Background command                                          |
| ------------- | -------------------------------------------------------------- | --------------------- | ------------------ | ----------------------------------------------------------- |
| ng            | See available commands                                         | npm run ng            | yarn ng            | ng                                                          |
| start         | Run your app in development mode                               | npm start             | yarn start         | ng serve                                                    |
| build         | Build your app for production                                  | npm run build         | yarn build         | ng build                                                    |
| build:stats   | Build your app for production and generate a "stats.json" file | npm run build:stats   | yarn build:stats   | ng build --stats-json                                       |
| watch         | Run build when files change.                                   | npm run watch         | yarn watch         | ng build --watch --configuration development                |
| test:unit     | Run your unit tests                                            | npm run test          | yarn test          | ng test                                                     |
| test:e2e      | Run your e2e tests                                             | npm run e2e           | yarn e2e           | ng e2e                                                      |
| test:coverage | Run your unit tests & generates a coverage report              | npm run test:coverage | yarn test:coverage | ng test --coverage                                          |
| lint          | Use ESLint to lint your app                                    | npm run lint          | yarn lint          | ng lint                                                     |
| analyze       | Open webpack-bundle-analyzer                                   | npm run analyze       | yarn analyze       | webpack-bundle-analyzer dist/angular-boilerplate/stats.json |
