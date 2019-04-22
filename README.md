# PWAPrueba
Test about application (PWA) with react

CREATE APLICACION IN REACT

1. PUT THAT COMMANT 
npm i create-react-app -g

2. PUT THAT IF YOU WANT CREATE A 

create-react-app react-pwa 

THEN WE NEED RUN THE ELEMENT  NEXT THAT WE NEED TO CREATE.

GENERAL NUEVO 
npm i http-server -D 

New Element 
ADD THE NEXT ELEMENTS:

"start-sw": "http-server ./build" on the file package.json the project
npm run build 
npm run start-sw

If you want put your application offline and keep on cachestorage active 
command on file index.js

serviceWorker.register();
