Steps to use GitHub code:

1.  Clone the repository in your local directory. 
2.  Open the project in command prompt, go inside the root of the project, and then run "composer install" to install the dependencies and     after that run "composer update" to update the installed latest dependencies.
3.  Copy the contents of .env.example to .env.
4.  Create a database in MySql and edit the database credentials in .env.
5.  Run php artisan key:generate to generate a unique key for the application.
6.  Now, run php artisan migrate to migrate the tables to the database.
7.  Create an account from  https://mailtrap.io/register/signup which is used for testing email notifications without sending       them       to   the real users for your applications.
8.  After that create a new inbox.
9.  Click on the newly created inbox, copy the credentials and update on the .env file.
10. Now, run php artisan serve to run the serve to run the project locally.
