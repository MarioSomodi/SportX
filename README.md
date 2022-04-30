# SportX
## Setup
You have to setup a MYSQL database with the SQL for that provided in the root directory, also change DB_HOST in wp-config.php if needed.
After that you are ready to go.
## Description of the project
This is a wordpress website that uses a REST API to collect football teams, fixtures, venues, leauges and connects it all in a modern interface for viewing. It has filtering options to find what you are looking for.
## Technologies used
* Wordpress
* PHP
* JavaScript
* CSS
* Curl
## Things I learned
* Wordpress
  * Adding custom post types, taxonomies.
  * Custom fields on custom post types.
  * Inserting custom post types and taxonomies with code.
  * Adding filtering and paging options.
  * Scheduling cron jobs.
* Fetching data from the REST API with curl.
```
REST API used in this project: https://v3.football.api-sports.io
REST API's docs : https://www.api-football.com/documentation-v3
```
