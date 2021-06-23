# Delay Finder

## A website designed to calculate the exact chance of a delay or cancelation of your flight.

## Site architecture

### Frontend
The frontend of the site will be built on Vuetify.JS with Typescript class-based components. 
    -Simple design. No login, no accounts
    
FRONT PAGE
The front page will describe our service to the user and have a clearly marked input for the users' flight information

After calculation, the site will display a clearly calculated value for cancelation % and delay %. 
-Eventually this will have a breakdown of this calculation, but for now, we will include a "Need more info?" link to a description of our calculation algorithms.

### Backend
The backend will be designed in Java and will contain all of the calculation functions
    -The backend will need to take data from the consumer airline report
    -The backend will need to search through that data given a certain query
    -(EVENTUALLY) The backend will also take weather into account and calculate conditions for probable delays or cancelations.
