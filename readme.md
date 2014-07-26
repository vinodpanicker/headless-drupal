Environment setup
    - Install Vagrant
    - Install Virtual Box
    - Provision using the given shell scripts
    - Install Node.js (Yo, Grunt, Bower, Angular Generator)
    - Install PHP55
    - Install Apache
    - Install MySQL
    - Install Ruby (Sass, Compass) use RVM

Setup VHOST
    - Create a VHost for Angular and Drupal servers
    - angular.dev & drupal.dev (Use Python for Client server)
    - Run both the servers

Use Drush/Git to pull down latest head of Drupal 8
    - drush dl drupal-8
    - git clone --branch 8.0.x http://git.drupal.org/project/drupal.git

Use Yo to generate Angular project scaffold
    - Use offical angular generator
    - Use generator scaffold toolds for creating test, controllers, routes
    - Add ng-animate, ng-resource


Fix CORS issue
    - Add the CORS support in either index.php or .htaccess
    - Mention Drupal Modules (CORS)

Enable REST modules
    - Enable all the REST modules in Drupal
    - Add instruction for drush en

Write API tests
    - Write Test using Superagent/Jasmine
    - Use Testem or Karma as runners
    - Use Curl/HTTPie

Create pages for About
    - Create a Basic page
    - Add a URL alias

Create views for Blog
    - Create a content-type
    - Create a View
    - Add content

Write client app
    - Setup up Angular app
    - Add support for hal-json
    - Add styles using bootstrap/Foundation

Write End-to-End test
    - Write test to check proper content is being rendered.
    - Use testem or Karma

Closing remarks
    - Mention the use cases
    - Future posts (POSTS, Forms, etc)


