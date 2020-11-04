
# Advanced Web Engineering

## 9th November 2020

### (275th Day of the Virus)

This is, initially, a repo containing a basic Laravel 8 install,
along with Jetstream and the Livewire stack. No other changes
have been made to the project.

To run, clone the repo and then:

`$ composer update`

`$ npm install && npm run dev`

Then create and configure `.env` with some suitable database settings
and credentials.

Migrate:

`$ php artisan migrate:fresh`

Generate the application key:

`$ php artisan key:generate`

Run the development server, and the app will be available,
most probably on port 8000.

`$ php artisan serve`
