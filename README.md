# SERVO APP <a href="https://servo-app-heroku.herokuapp.com/"> Demo </a>
## Find your local Petrol stations
### Restful App Built by : JavaScript, Node.JS, Express, PostgreSQL, HTML, CSS by Bootstrap5
### Google Maps API and publicly accessible Australian Petrol station dataset for 2012

- at window.onload: App asks permission for users location, given permission, map centers on users location, and reflects users latitude, longitude and address on the right panel under current location.
- at window.onload: map shows all petrol stations accross Australia as markers(5243). Clicking on markers opens info window containing stations name and address. also current location on right panel will be changed to servo's details.
- 

- Dataset downloaded from <a href="https://data.gov.au/"> Data.GOV.AU </a> , also can be found in .data/PetrolStasions.CSV









### ScreenShot
![Screenshot](screenshot_space.png)


## seeding the database

You can seed the database with the data from the `./data/PetrolStations_v1.csv` using the seeder script.

1. create the database by executing the `create-database.sql` on `psql` first.
2. Seed the database by executing `npm run seed_db`.


