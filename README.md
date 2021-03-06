# Meet Native : Find a Language Partner

Cross-platform mobile app for Android and iOS written with React Native.

![Big Beautiful Picture](https://i.imgur.com/w8ykgid.png)

<a target="_blank" href='https://play.google.com/store/apps/details?id=tech.equipage.meetnative'><img width="200" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>
<a target="_blank" href='https://itunes.apple.com/us/app/id1458711190'><img width="200" alt='Download on App Store' src='https://i.imgur.com/7IxtMV0.png'/></a>

# Technologies inside
- [React Native](https://facebook.github.io/react-native/) 0.58.6 to build an app for both Android and iOS
- [ECMAScript 2018](https://en.wikipedia.org/wiki/ECMAScript#9th_Edition_-_ECMAScript_2018) and [Typescript](https://github.com/Microsoft/TypeScript-React-Native-Starter) to add typing and [Node.js](https://nodejs.org/en/) for server side
- [Redux](https://redux.js.org/) and [Saga](https://github.com/redux-saga/redux-saga) for state management using [Ducks](https://github.com/erikras/ducks-modular-redux) to isolate modules
- [Jest](https://jestjs.io/), [Enzyme](https://airbnb.io/enzyme/docs/guides/jest.html), [jsdom](https://github.com/jsdom/jsdom) and [Redux Saga Test Plan](https://github.com/jfairbank/redux-saga-test-plan) to test the code with delight
- [Storybook](https://github.com/storybooks/storybook) to develop UI components in isolation
- [Firestore](https://firebase.google.com/docs/firestore/) a cloud NoSQL database with realtime update and offline support. Trigger are implemented inside [Firebase Cloud Functions](https://firebase.google.com/docs/functions/) 
- [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) is a cross-platform messaging solution
- [Firebase Authentication](https://firebase.google.com/docs/auth/) to handle authentication flow
- [Google App Engine](https://cloud.google.com/appengine/) the serverless platform using Node.js 
- [Graphql](https://graphql.org/) with [Apollo](https://www.apollographql.com/) (server & client) to query data and [Apollo link state](https://www.apollographql.com/docs/link/links/state) to manage states and cache data
- [React Native FBSDK](https://github.com/facebook/react-native-fbsdk) for authentication and analytics
- [Eslint](https://github.com/eslint/eslint) and [Prietter](https://github.com/prettier/prettier) to format the code and detect errors
- [CircleCI](https://circleci.com/) for continuous integration
- [FramerX](https://www.framer.com/) to design interactive UI for smartphones
- [Styled Components](https://github.com/styled-components/styled-components) to style the app without stress
- [NativeBase](https://github.com/GeekyAnts/NativeBase) a cross-platform UI components and theming
- [React Navigation](https://github.com/react-navigation/react-navigation) an extensible navigation solution
- [Formik](https://github.com/jaredpalmer/formik) to build forms without tears and [Yup](https://github.com/jquense/yup) to validate the fields 
- [RNLocalize](https://github.com/react-native-community/react-native-localize) and  [MessageFormat](https://github.com/messageformat/messageformat) for internationalization
- [typesafe-actions](https://github.com/piotrwitek/typesafe-actions) to create Flux Standard Action
- [yarn](https://yarnpkg.com/) to manage dependencies
- [VBox](https://www.virtualbox.org/) to compile and run app for IOs
 
# External Tools
- [WebStorm](https://www.jetbrains.com/webstorm/) as IDE
- [React Native Debugger](https://github.com/jhen0409/react-native-debugger)

# Features
We believe a friendly face-to-face meeting is the best way to learn a new language.

On Meet Native, you publish the languages ??????you wish to learn and the languages ??????you are able to teach. The app locates people around you who match your language skills and learning wishes.

Your partner found, make an appointment at a caf?? terrace or in a park, etc. The goal is above all to converse as much as possible and whatever the subject :-)

# Try it yourself
## 1. Clone and Install
```bash
# Clone the repo
git clone https://github.com/JSAdmin/RN-MeetNative-App.git

# Install dependencies
cd react-native
yarn install
```
## 2. Run it Android
Meetnative is built on React Native and therefore assumes you have node installed. Yarn is preferred over NPM as a package manager.
- Configure your Firebase project following this [guide](https://rnfirebase.io/docs/v5.x.x/installation/initial-setup)
- To configure the Facebook SDK use this [guide](https://developers.facebook.com/docs/android/getting-started/)
- To set up the Google Places Autocomplete Component read this [guide](https://github.com/FaridSafi/react-native-google-places-autocomplete)

```bash
yarn run android
```

