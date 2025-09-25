# Teamable-Application-Project
This is a demo project for the IT begginers course from Techworld with Nana. <br>
Link to the course description: https://www.techworld-with-nana.com/it-beginners-course <br>
To keep the project up to date with the latest versions, libraries are updated periodically.

## 📌 Technologies Used
- HTML
- CSS
- Javascript
- Vue.js
- Node.js
- MongoDB
- Git

## Prerequisites
- Have NPM (Node Package Manager) installed on your computer
- Have MongoDB Compass installed on your computer

## 🧭 Steps to Reproduce to check this project on your computer

### 1. ✅ Clone the Github repository
```bash
git clone https://github.com/JuanMiguelVC/Teamable-Application-Project.git
```
Optional: Remove the .git folder of the cloned repository. This is an optional step, it is not requiered to perform in order to see how the code works

### 2. 💻 Create MongoDB database and collection
On your local MongoDB Compass, create the database **company_db**. On the **company_db database**, create a collection named **employees** to save the data of the application

### 3. 📚 Install the libraries locally
The repository already has the package.json and the package-lock.json files. You can install the libraries on your local machine, using the following comand
```bash
npm install
```

### 4. 👟 Run the application
Before running the application, it is needed to execute the commands indicated below.<br>
First, the comand to execute is to serve the application
```bash
npm run serve
```
After executing the serve command, it is time to build the project
```bash
npm run build
```
After building the project, execute the command below
```bash
npm run start
```
Or this command
```bash
node server.js
```
The application runs on port 3000

### 5. 💻 Check the application
On your web browser, type the following: localhost:3000 to see the application running
Also, you can edit the information clicking on the **Edit Profile** button. Once you have finnished editing the information or checked the values shown on the brower, click on the **Update Profile** button to save the changes. The changes will be saved on the MongoDB database in order to be shown on the browser

## 📌 Other usefull NPM (Node Package Manager) commands

### To run the tests, execute the following command

    npm run test

### To package the application, execute the following command

    npm pack
    
### To update the application libraries, execute the following command

    npm update   
