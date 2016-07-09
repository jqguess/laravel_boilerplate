# laravel_boilerplate 
[See it in action here](http://jqguess.net) 
---------------------------------------------------------
A quick Laravel 5 boilerplate. Easily use Gulp/Elixir and PHPUnit
to make unit testing and combining CSS, LESS, SASS files a breeze.
<br />
<br />
#### Start by cloning or dowloading the repo and decide on your local environment ####
 
  [Homestead](https://laravel.com/docs/4.2/homestead) is Laravels Vagrant Box solution if 
  you do not want to install PHP and have a disposable environment. Xampp or Wampp are quick options as well.
  [More installation instructions](https://laravel.com/docs/5.2/installation)
  can be found here. 


#### Fastest option if your not familiar with Homestead, Vagrant ####

* Download and install Xampp with PHP, configure what you want, although it should not be necessary.
  You will need Composer, Bower, and Nodejs for NPM. 
<br />
* Add the file that contains php.exe to your Path  <code>C:\xampp\php</code> on normal installation.
<br />
* Once these are all installed, cd to the file and run
   <code>$ php composer install </code>
   <code>$ npm install </code>
   <code>$ bower install --save </code>
<br />
* To add a database, Start MySQL from the Xampp control panel.
  Edit the .env.example or .env file with your database settings. Basic settings would be
 <code>DB_HOST=127.0.0.1
      DB_DATABASE=Homestead
      DB_USERNAME=User
      DB_PASSWORD=""</code>
* Apply these same settings to the database.php file found in the config folder for your DB type. <br/>
* From the CLI, cd to the app folder,  then run <code>$ php artisan migrate</code> This structures your DB. <br />
* From the CLI run <code>$ php artisan serve</code> which should output server running on <code>http://localhost:8000</code> <br />
* Point your browser and you should see the app's output. If no dice, try Laravels installation guide.  <br />

#### Gulp, Elixer, PHPUnit ####

* Out of the box, boilerplate is setup to mix all CSS/LESS/SASS files with the commands <br />
<code> $ gulp copyfiles </code> and then <code> $ gulp </code> <br />
* Easily run all unit tests with Gulp-Elixir from your cli with <code> $ gulp phpunit </code> <br />
* Profit!




 





