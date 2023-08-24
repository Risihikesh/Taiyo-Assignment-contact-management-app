#Deployed link-> https://celebrated-platypus-6d878d.netlify.app/

#Application Overview:
The application consists of two main pages:

1. Contacts:
This page empowers you to efficiently manage your contacts. You can seamlessly add new contacts by completing a simple form, and the newly added contact will be seamlessly integrated into your contact list. Additionally, you have the capability to modify or remove existing contacts. Clicking on a contact's name will seamlessly transition you to a dedicated contact details page.

2. Charts and Maps:
On this page, you can explore comprehensive COVID-19 data for various countries. The dynamic presentation includes an insightful line graph, visually representing fluctuations in COVID-19 cases over time. Additionally, an interactive map is showcased, adorned with markers that highlight individual countries. These markers provide key information, including the country's name, the total number of active cases, recovered cases, and unfortunate fatalities. This critical data is presented through informative popups.

API Integration:
To furnish the app with accurate and real-time data, it makes use of the following APIs:

Worldwide COVID-19 Data:
Endpoint: https://disease.sh/v3/covid-19/all
Purpose: This API endpoint provides an encompassing overview of COVID-19 cases globally.

Country-Specific COVID-19 Data:
Endpoint: https://disease.sh/v3/covid-19/countries
Purpose: Utilizing this endpoint, the app gathers specific COVID-19 statistics for individual countries.

Graphical Historical Data for Cases:
Endpoint: https://disease.sh/v3/covid-19/historical/all?lastdays=all
Purpose: This API endpoint serves graphical data, enabling the app to construct informative line graphs depicting the progression of COVID-19 cases over a defined period.

This integration of robust APIs ensures that the app consistently delivers up-to-date and insightful COVID-19 data, fostering a seamless and informative user experience.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
