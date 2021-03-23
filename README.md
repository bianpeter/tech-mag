# Tech Magazine

Project made with React, Node.js and News Api


########################

install:
npm install (frontend)
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

