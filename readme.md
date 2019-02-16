Steps to use GitHub code:

Clone the repository in your local directory. 
Open the project in command prompt, go inside the root of the project, and then run "composer install" to install the dependencies and after that run "composer update" to update the installed latest dependencies.
After that copy the contents of .env.example to .env.
After that create a database in MySql and edit the database credentials in .env.
Run php artisan key:generate to generate a unique key for the application.
Now, run php artisan migrate to migrate the tables to the database.
After that create an account from  https://mailtrap.io/register/signup which is used for testing email notifications without sending them to the real users for your applications.
After that create a new inbox.
Click on the newly created inbox, copy the credentials and update on the .env file.
