Prisma with Node-js and Express-js:

yarn add --dev @types/node nodemon prisma ts-node
install all these packages as a devDependencies 

Add the Typescript default configuration that is mentioned on the documentation.

Now add the prisma folder using the CLI:  npx prisma init --datasource-provider psotgres
this will add the basic prisma setup in the app along with the db that we have set as the 
postgres and it will also add .env file with db connection string

Now in the prisma file we have to write code in prisma format and bydefault we have datasource
