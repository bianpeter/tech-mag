# Tech Magazine

Project made with React, Node.js and News Api
The landing page only loads once. If you want to visit again, remove key(alreadyVisited) from browser local storage.

To run the project:
1. npm install (frontend)
2. npm install cors (backend)
3. create app-env file in backend
4. In app-env file write: export API_KEY="INSERT API KEY HERE"
5. source app-env (backend)
6. node server.js (backend)
7. npm start (frontend)

You can get an api key from:
https://newsapi.org/


#############################################################################################################################################################

installed:
npm install cors (backend)
npm install --save react-router-dom (frontend)

# api key from enviormental variable

1. backendbe kell egy app-env file
2. app-env file-ba : export API_KEY="ide kell az api key"
3. server.js-ben :
   const api_key = process.env.API_KEY;
   const newsapi = new NewsAPI(api_key);
4. backend mappában(futtatni): source app-env
5. backend gitignorban: app-env

