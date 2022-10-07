# ExpenTra App
One of my first full stack projects.

## About
Expenditure Tracking Application, The application will simply make it easier for you to keep track of your expenses.



## How To

First of all cd into frontEnd , then to backend and do "npm i" into both folders to install node modules\
Second , go to backend/server.js and change the port for the cors if you want to\
Third , go to backend and run "npx prisma generate" and then create an .env file for the DATABASE_URL\
See here : https://www.prisma.io/docs/reference/database-reference/connection-urls \
Example : DATABASE_URL=postgresql://janedoe:mypassword@localhost:5432/mydb


#Scripts
You need to run progresql and provide the correct DATABASE_URL TO PRISMA!!\
cd into backEnd and run "npm run dev" this script will start both the backend and the frontend

