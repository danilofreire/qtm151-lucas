# QTM 151 - Introduction to Statistical Computing II

## Quiz 04 - SQL

In this quiz, you will demonstrate your ability to write SQL queries and extract information from tables.

### Instructions

- You are free to use any resources available to you, including the internet, but you are not allowed to discuss the quiz with anyone else.
- You are also free to use any database management system you prefer (pgAdmin, SQLAlchemy, SQLite, etc.), but the queries must be written in SQL.
- Please submit your answers as a `.sql`, `.ipynb`, or `.html` file. If you submit an `.html` file, please include the SQL queries.

### Data

You will work with two tables, one named `cars` and the other named `brand_data`. They are both available as `.csv` files in this repository, or you can create them yourself using the data provided in the `.sql` file or the Jupyter Notebook. The tables have the following columns:

#### `cars` Table

| Column       | Type    | Description                          |
|--------------|---------|--------------------------------------|
| car_id       | INTEGER | Primary key                          |
| make         | TEXT    | Car make and model                   |
| price        | NUMERIC | Price of the car                     |
| mpg          | NUMERIC | Miles per gallon                     |
| rep78        | NUMERIC | Repair record 1978                   |
| headroom     | NUMERIC | Headroom in inches                   |
| trunk        | NUMERIC | Trunk space in cubic feet            |
| weight       | NUMERIC | Weight of the car in pounds          |
| length       | NUMERIC | Length of the car in inches          |
| turn         | NUMERIC | Turning circle in feet               |
| displacement | NUMERIC | Engine displacement in cubic inches  |
| gear_ratio   | NUMERIC | Gear ratio                           |
| brand        | TEXT    | Brand of the car                     |

#### `brand_data` Table

| Column      | Type    | Description                          |
|-------------|---------|--------------------------------------|
| brand_id    | NUMERIC | Primary key                          |
| brand       | TEXT    | Brand name                           |
| origin_type | TEXT    | Origin type (Domestic or Foreign)    |


### Submission

Please submit your answers as a `.sql`, `.ipynb`, or `.html` file. If you submit an `.html` file, please include the SQL queries.

Good luck! 😊
