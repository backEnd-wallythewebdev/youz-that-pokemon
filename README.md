# youz-that-pokemon
Let Node JS tell you which Pokemon you are

**view app at**
https://wtwd-youz-that-pokemon.herokuapp.com/

**Idea**

Started to make Http requests using node, got super excited (geeking out they call it) and wanted to use user input to return the pokemon that they should be based on there input like: 

```
age = evelution
fire sign = element

date of brith (day) = number of chosen pokemon
date of birth (month) = if number is over 30, the devision of number

```

**steps**

1) Either view the app deployed at https://wtwd-youz-that-pokemon.herokuapp.com/
or git pull this respository to your local device and run it with the below instructions: 
2) install node modules required
```
npm install
```
3) aplication is auto run from the package json start script

**DEV runs using nodemon as a global install**

```
npm run dev
```

4) in browser fire up **http://localhost:3000/**

**this is a work in progress and is a base idea for how to generate user Avatars**

**terminal command is**: 
```
node app.js 
```

**or for Front End user inputs**



**Tasks for this app**

- [x] connect to api and retrive pokemon data
- [x] Randomise the returned pokemon for the user
- [x] create a UI ineterface for the user
- [x] Allow user to input custom details to narrow pokemon selection
- [x] return to user pokemon picture

**Optomise**

- [x] added section for error handling
- [x] moved function to utils file for cleaner code

**Dev update**

04/03/2020

Pushed in a massive update with a basic UI for the user to see and make it look a bit better - 
There will be a update made to allow for more details, currently the request will only pull back 
pokemon that are of your star signs element sign, which is a little dull to be honest. 

Somthing to make it more personal would be a good call - 

Also would like to look at adding in a facebook share button for exposure 

05/03/2020

Deployed the app to Heroku and altered the package JSON / src/app.js and public/app.js so that 
the app with load on the port of the ENV server - this will either be Herokus git account or the 
trusty local host: 3000 - 

Issues have been seen from Apple users with the styling not displaying correcty and this will be addressed