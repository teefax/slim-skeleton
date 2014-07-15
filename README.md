# Slim Framework Skeletop

This is my Slim framework skeleton with:

- Slim Framework 2.*
- Slim Views for Twig Templates
- SlimController
- Idiorm 1.5.*
- Swiftmailer
- slim-whoops
- phpref
- Compass and Bootstrap-Sass for CSS

## Usage:

Clone this repo, edit `app/config/app.php` and `app/config/db.php`, create models in `app/models/*` and controllers in `app/controllers/*`.

Define routes in `app/routes.php`

With ruby installed, run `bundle install` to get the required gems, and then run `bundle exec compass watch` to automatically compile your stylesheets when something changes in `app/asses/sass/`.
