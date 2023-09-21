# Project All for One

#### A store database called 'NorthWind' Database was used to select the necessary information via MySql commands.

* Designed by using MySQL & Docker

### Instructions
* To run the repository locally, clone the project and use the following commands to initialize Docker:
  
  ```
  docker-compose up -d // start application with docker
  docker attach all_for_one
  npm install // install dependencies
  docker-compose down // stop application
  ```

### Tasks

  | Task     | Description |
  | ----------- | ----------- |
  | 1   | Query that only displays `product names` |
  | 2   | Query that displays all `product` information |
  | 3   | Query that displays `primary key` of `product` table |
  | 4   | Query showing total amount of information in `product_name` column |
  | 5   | Query that displays data from `product` table between fourth and thirteenth record |
  | 6   | Query that displays `product_name` and `id` from `products` table in alphabetical order of names |
  | 7   | Query showing the last 5 records in the `products` table |
  | 8   | Query that returns 3 columns, containing the names 'A', 'Trybe' and 'eh' and values of sum `5 + 6`, string `'de'` and sum of `2 + 8`, respectively|
  | 9   | Query showing all non-null values in `notes` column of `purchase_orders` table |
  | 10  | Query that displays all the data in `purchase_orders` table, sorted in descending order of `created_by`, with greater than or equal to `3` |
  | 11  | Query that shows `notes` column of `purchase_orders` table, where 'Purchase generated based on Order #' contains values between 30 and 39 |
  | 12  | Query showing `submitted_date` of `purchase_orders` table on April 26, 2006 |
  | 13  | Query that displays `supplier_id` equivalent to 1 or 3, referring to the `purchase_orders` table |
  | 14  | Query that displays `supplier_id` between 1 and 3, referring to the `purchase_orders` table |
  | 15  | Query that displays only the hour of all records in `submitted_date` column of `purchase_orders` table |
  | 16  |  |
  | 17  |  |
  | 18  |  |
  | 19  |  |
  | 20  |  |
  | 21  |  |
  | 22  |  |
  | 23  |  |
  | 24  |  |
  | 25  |  |
  | 26  |  |
  | 27  |  |
