# FriendFinder

## **Overview**
Friend Finder implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). This full-stack site takes in results from users' surveys, then compare their answers with those from other users. When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined. The app will then display the name and picture of the user with the best overall match.

The compatibility-based "FriendFinder" application -- basically a dating app. The application is implemented using a Node.js and Express server on the back end and the Materialize CSS framework on the front end.

### **Demo**
Friend Finder is deployed to Heroku. Please check it out [here](https://stormy-garden-56463.herokuapp.com).

### **Instructions**
Below you will find a guide to help you get started and teach you how to clone and run this repo.

1. Open your terminal such as Bash.

2. Clone the repository

3. Run npm install to download the following Node dependencies/packages:

    - body-parser
    - express
    - path

### **Built With:**
- Node.js
- JavaScript
- HTML
- CSS
- Heroku
- Twitter Bootstrap
- APIs
