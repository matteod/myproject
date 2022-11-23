# myproject

You need to update the .env file with your database connection params, and regenerate with `composer dump-env dev`

Create the database (same name that you've used in the .env file)

Create the table with `./bin/console doctrine:schema:create`

Run the Symfony server with `symfony server:start` or `symfony serve -d`

Go to `/api` page
