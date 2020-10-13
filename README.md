**LinkUpStudio-Practice-2 <br/>
Educational and technological practice from April 13, 2020 to April 30, 2020**

## **FORMULATION OF THE PROBLEM**
In practice, the following tasks were set:
- Develop a site using cascading style sheets, page markup languages, and JavaScript programming languages using the React framework. Customize page elements for adaptive display
- Using HTTP-Request to output internal information from the JSON file to the page. The page should dynamically change its appearance depending on the contents of the file

## **IMPLEMENTATION REQUIREMENTS**
List of basic requirements:
- JavaScript Framework: React
- CSS Framework: Material-UI
- React-country-flag: React component to display Emoji and SVG country flags
- Google-map-react: Google Maps library for React, which allows you to display components as markers
- Randomuser.me: API, for generating random data and users

## **LIST OF TASKS**
### **Task #1:**
Compose the main page. Display a list of users on the main page. Generate data using randomuser.me. Use the radio button to make it possible to output 100/200/500 users, or input, specifying the exact number. Prohibit input of negative values, letters and symbols, only numbers. Design a list of users at will with responsive under sm (640px), md (768px), lg (1024px), xl (1280px). Add the ability to sort by gender, and a button that groups users by country in alphabetical order

### **Task #2:**
Make a user description. When you click on a user, go to the page with his detailed information. Display the following fields here:
- Avatar: `picture`
- Name: `name.title`, `name.first`, `name.last`
- Nationality: `nat`. Use the *react-country-flag* library to display the country flag
- Year of birth: `dob.date`. Clicking opens the *datepicker*
- Location: `location.country`, `location.city`, `location.street`
- Map: `coordinates.latitude`, `coordinates.longitude`. Use the *google-map-react* library to display the user's coordinates on the map

### **Task #3:**
Make an improved sort on the *main page*. *Button* with the *select* property - select the country and output users only from it. Get data from *location.country*. Print only unique countries. When generating a new list of *users*, *select* must also be updated. To the *user description* use all information about the user from the API "*randomuser.me*"

Tasks include the following steps:
- In-depth study of the JavaScript programming language
- Study of the React framework
- Familiarization with HTTPRequest, receiving, processing and sending data, deleting data
- Introduction to Google Maps API, Material-UI
- Project development

## **INSTALL**
Clone the repo using: `git clone https://github.com/san616mofo/LinkUpStudio-Practice-2.git` <br/>
Go to the folder: `cd LinkUpStudio-Practice-2\task<NUMBER>` <br/>
Install node modules: `yarn install` <br/>
Runs the app in the development mode: `yarn start`. Open http://localhost:3000 to view it in the browser <br/>
Launches the test runner in the interactive watch mode: `yarn test` <br/>
Builds the app for production to the build folder: `yarn build`

## **SCREENSHOTS**
### **Task #1:**
<div align="center">
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task1/1.png?raw=true" height="300px" alt="task1-img1"/>
</div>

### **Task #2:**
<div align="center">
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task2/1.png?raw=true" height="300px" alt="task2-img1"/>
</div>

### **Task #3:**
<div align="center">
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task3/1.png?raw=true" height="300px" alt="task3-img1"/>
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task3/2.png?raw=true" height="300px" alt="task3-img2"/>
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task3/3.png?raw=true" height="300px" alt="task3-img3"/>
  <img src="https://github.com/san616mofo/LinkUpStudio-Practice-2/blob/master/screenshots/task3/4.png?raw=true" height="300px" alt="task3-img4"/>
</div>
