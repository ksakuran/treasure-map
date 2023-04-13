# Treasure Map
is a single page web application that utilizes the Leaflet API to allow users to create lists of points to save to specific maps. An example would be a map with a list of their favourite coffee shops!

Users can create their own maps, "favourite" maps, they can contribute to shared maps with other users.

Treasure map was built as a midterm project for the Lighthouse Labs Web Development Bootcamp. 




## Getting Setup

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information 
  - username: `labber` 
  - password: `labber` 
  - database: `midterm`
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Reset database: `npm run db:reset`
  - Check the db folder to see what gets created and seeded in the SDB
7. Run the server: `npm run local`
  - Note: nodemon is used, so you should not have to restart your server
8. Visit `http://localhost:8080/`
9. To view full functionallity we added a simplified login, just enter a user number of 8 or 10.

