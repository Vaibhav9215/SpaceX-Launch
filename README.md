

## About the project

This is a sample project which can be used to view launch program list of spacex. It uses spacex public API to pull its data.
It is designed to be a singe page application, for which following libraries are used:
- react
- redux
- react-router

The application is served by a node.js server which also renders the initial landing page. Following libraries are used by the node.js server:
- express
- babel

Unit test cases are writen by using following libraries:
- jest
- enzyme

The application is deployed on **Heroku**, and **Travis** is used for CI. It is configured to automatically trigger a build every time something is pushed on the `master` branch following which it is delivered to Heroku for deployment

## Highlights
- This is a progressive web application, which can be installed on any PWA compatible mobile device.
- Application is server-side rendered, which helps in boosting the initial page load time and increasing the SEO scores.
- Fully responsive to covers all range of device
- Uses `container component - dummy component` approach
- Multiple highly reusable dummy components result in easier unit testing
- Uses lazy loading to defer loading off-screen images which results in reduced initial page load time
- Uses infinite scrolling approach to render the launch list in multiple steps, resulting in reduced dom elements on initial page load
- Uses memoizing to prevent unnecessary rerenders, increasing the performance of functional components
- Used best practises and performation optimizations, resulting in a high lighthouse score

**Using Lighthouse in Chrome DevTools**

![lighthouse score]()

**Using [web.dev](https://web.dev/measure)**

![lighthouse score]()

[web.dev report]()

## Available Scripts

To run unit tests, you can use:
### `npm run test`

To run the project on local machine use following commands:

### `npm run build-ssr`
### `npm run start-ssr`


Following this, open [http://localhost:3000](http://localhost:3000) to view it in the browser.
