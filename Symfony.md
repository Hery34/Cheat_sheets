# Symfony Cheat Sheet


## Commands

Command | Description
---|---
composer create-project symfony/website-skeleton my-project | Creates a new Symfony project.
symfony serve | Starts the Symfony development server.
symfony console | Opens the Symfony command-line interface.
symfony make:controller my_controller | Creates a new controller.
symfony make:crud my_entity | Creates a CRUD controller for an entity.
symfony make:migration my_migration | Creates a new database migration.
symfony doctrine:migrations:migrate | Migrates the database to the latest version.
symfony fixtures:load | Loads the fixtures into the database.
symfony test:unit | Runs the unit tests.
symfony test:integration | Runs the integration tests.
symfony test:functional | Runs the functional tests.

## Tips

* You can use the up and down arrow keys to scroll through your command history.
* You can use the Tab key to auto-complete filenames and commands.
* You can use the following keyboard shortcuts:
    * Ctrl+C: Cancels the current command.
    * Ctrl+D: Exits the Symfony command-line interface.
    * Ctrl+Z: Suspends the current command.
* You can use the following shell variables:
    * APP_ENV: The environment of the application (dev, prod, test).
    * APP_SECRET: The secret key of the application.
    * DATABASE_URL: The URL of the database.


