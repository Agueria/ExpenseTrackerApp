# ExpenTra App


## About
Expenditure Tracking Application, my one of the first full stack projects. The application will simply make it easier for you to keep track of your expenses.



## How To
-> Do npm i in the root directory and in the "/client" folder. The React App lives in the "/client" directory
-> In the "/client" directory there is a .env.example file. Rename it to .env and change the variable to your url/api
-> In the root directory there is a .env.example file too. Rename it to .env and put your DATABASE_URL ie the postgresql connection URL. The port variable is optional.
-> Run npm run buildClient to build the react app (at the root folder). A clientBuild folder will be created.
-> Run "npx prisma generate" and "npx prisma migrate dev" to generate the prisma client and apply the migrations to the db
See here : https://www.prisma.io/docs/reference/database-reference/connection-urls
Example : DATABASE_URL=postgresql://janedoe:mypassword@localhost:4000/mydb
