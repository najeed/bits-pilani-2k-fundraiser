# Prototyped with Create React App

These mockups were prototyped with [Create React App](https://github.com/facebook/create-react-app). Made with ❤️ for the BITS Pilani Class of 2000 by [Najeed Khan](https://www.linkedin.com/in/najeed/) and our awesome contributors 🙌:

<a href="https://github.com/najeed/bits-pilani-2k-fundraiser/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=najeed/bits-pilani-2k-fundraiser" />
</a>


Steps to build:
1. Install [Node.js](https://nodejs.org/en/download).
2. Open your terminal or command prompt and run the following commands (steps 3-6):
3. `npx create-react-app bits-pilani-fundraiser`: Create your React app project folder
4. `cd bits-pilani-fundraiser`: Navigate to the root
5. `npm install lucide-react tailwindcss@3 postcss autoprefixer`: Install required dependencies
6. `npx tailwindcss init -p`: Generate tailwind config files (i.e. pre-v4)
7. Open tailwind.config.js and configure it to scan your source files for Tailwind classes: `content: [    "./src/**/*.{js,jsx,ts,tsx}",  ],`
8. Open the src/index.css file, delete its contents, and add the following lines:
`@tailwind base;
@tailwind components;
@tailwind utilities;`
9. Open the src/App.js file in your new project. Replace its contents with src/App.js.x where x is retro or y2k or modern or nostalgia or dark or blueprint based on your preference.
10. Run the Build Command: `npm run build`
11. A new folder named "build" in your root directory contains the plain HTML, CSS, and JavaScript files that can be hosted on any web server. 

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
