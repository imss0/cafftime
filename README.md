# cafftime

Cafftime is a caffeine intake tracker service. This app will give you answer to these questions!

✔️ How much caffeine does this drink contain?<br/>
✔️ Do I drink too much caffeine than recommended?<br/>
✔️ If I drink coffee at 4p.m, would it affect my sleep? 


## Screenshots
<p float="left">
  <img src="https://i.ibb.co/cg1kb0Y/caff1.gif" width="250">
  <img src="https://i.ibb.co/Yd06XVM/caff2.gif" width="250"> 
  <img src="https://i.ibb.co/3CWmMRh/caff3.gif" width="250">
</p>

## Installation
1. To run this app, MongoDB needs to be installed. (or MongoDB Atlas account) 
2. Clone this repo
3. install dependencies : `npm i`
- in root folder **(cafftime)**
- in **client** folder
- in **server** folder

## Getting Started
1. Create .env file in server folder
2. Copy .env.sample and add your data
3. Upload `storage.csv` file to your database
<br/>This is a file that has a list of caffeinated drink
<br/>The name of data table is **foods**. You can find the schema in **cafftime/server/models/food.js**
4. `node index.js` in **server** folder (If you use nodemon, run `nodemon` instead)
5. `npm run start` in **client** folder


## Tech Stack
### Frontend
- React
- Tailwind CSS
- Chart JS

### Backend
- MongoDB
- Mongoose
- NodeJS
- Koa


