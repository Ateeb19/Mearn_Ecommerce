# MearnStack_Ecommerce
An ecommerce webapp developed in react and node. 
The Mongodb Atlas Database is used in this web app.
First open file in terminal and write 'npm i' and hit enter.
Go to the frontend file by 'cd frontend' and write 'npm i' and hit enter.
Now go to backend file and open config folder, open config.env file.
In config.env file add your mongodb Atlas Database url to connect with it.
Now go to frontend file and open package.json file. in that at last there is a proxey change that url to your local host url.
Then go to second terminal of backend and write 'npm run dev' and hit enter.
Now your backend server is started now note your backend server localhost address.
In frontend the package.json file, in that where proxey is applied in that url change the last localadderss of '3000' with your backend server '4000'.
In frontend terminal write 'npm start' and hit enter. The ecommerce app will be started.
Now add the items from your postman. 
