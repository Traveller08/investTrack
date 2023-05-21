# InvestTrack

## Technologies Used

- Backend: Node.js, Express.js, mysql2
- Frontend: React
- Authentication: JWT (JSON Web Tokens)

## Prerequisites
1. Insert historical_prices data to database
   ```
   # Create table
   create table historicalPrices ( id int not null, date datetime, price int, instrument_name varchar(255) not null, primary key(id, instrument_name) );
   
   # insert data from historical_prices.csv to database
   load data local  infile '..path to file..../historical_prices.csv' into table historicalPrices  fields terminated by ',' lines terminated by '\n' ignore 1 rows;

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Traveller08/investTrack.git
   
2. Install the dependencies for the backend:
   ```bash
   cd investTrack/backend
   npm install
   
3. Install the dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   
4. Start the backend server:
   ```bash
   cd ../backend
   npm start

6. Start the frontend development server:
   ```bash
   cd ../frontend
   npm start


   
   

