# App-deployment

Check out the live web-app and have fun!
https://salary-predictor-10.herokuapp.com/

Model deployment
Heroku offers three methods of model deployment: Heroku git, GitHub, and container registry.


Heroku deployment methods
This article shows model deployment using the GitHub method.

Step 1: Upload the project folder to a git repository. Please make sure that the repository is public.


Step 2: Create an account on Heroku. Navigate to New and Click on Create a new app and give the name of the app. Please note that App name should be unique. In this case, the name of the app is salary-predictionmodel.


Create a new app
Step 3: Choose the deployment method, in this case, GitHub. Once Heroku is authenticated to GitHub, then choose the repository to connect.


Choose the repository to connect.
Step 4: After connecting the repository to Heroku, it is time to deploy a repository branch. Heroku also offers automatic deploys, which means Heroku deploys the new version of the app automatically whenever the branch is updated.


Deploy the desired branch of the repository
Start the deployment by clicking on the Deploy branch button. Upon the successful completion of deployment of the app, click on the View button.


Click on the View button to start the app.
The app should be running on the Heroku server. In this case. Check this link

Salary Prediction Model
This is a simple demonstration of ML deployment
salary-predictionmodel.herokuapp.com


Step 5: Install the command-line interface of Heroku to view logs. Once Heroku CLI is installed, run the following commands on the terminal for authentication:

heroku login
Upon successful authentication to Heroku, run the following command to view build logs:

heroku logs --app salary-predictionmodel
