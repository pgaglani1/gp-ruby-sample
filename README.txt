# Ruby on Rails Starter Application

Bluemix provides a Ruby on Rails Starter Application as a template so that you can add your code and push the changes back to the Bluemix environment.


## Files

The default directory structure of a generated Ruby on Rails application. If you want more information about Ruby on Rails application, you can refer to RubyOnRails.rdoc file.

*   app
  Holds all the code that's specific to this particular application.

*   app/assets
  Contains subdirectories for images, stylesheets, and JavaScript files.

*   app/controllers
  Holds controllers that should be named like weblogs_controller.rb for
  automated URL mapping. All controllers should descend from
  ApplicationController which itself descends from ActionController::Base.

*   app/models
  Holds models that should be named like post.rb. Models descend from
  ActiveRecord::Base by default.

*   app/views
  Holds the template files for the view that should be named like
  weblogs/index.html.erb for the WeblogsController#index action. All views use
  eRuby syntax by default.

*   app/views/layouts
  Holds the template files for layouts to be used with views. This models the
  common header/footer method of wrapping views. In your views, define a layout
  using the <tt>layout :default</tt> and create a file named default.html.erb.
  Inside default.html.erb, call <% yield %> to render the view using this
  layout.

*   app/helpers
  Holds view helpers that should be named like weblogs_helper.rb. These are
  generated for you automatically when using generators for controllers.
  Helpers can be used to wrap functionality for your views into methods.

*   config
  Configuration files for the Rails environment, the routing map, the database,
  and other dependencies.

*   db
  Contains the database schema in schema.rb. db/migrate contains all the
  sequence of Migrations for your schema.

*   doc
  This directory is where your application documentation will be stored when
  generated using <tt>rake doc:app</tt>

*   lib
  Application specific libraries. Basically, any kind of custom code that
  doesn't belong under controllers, models, or helpers. This directory is in
  the load path.

*   public
  The directory available for the web server. Also contains the dispatchers and the
  default HTML files. This should be set as the DOCUMENT_ROOT of your web
  server.

*   script
  Helper scripts for automation and generation.

*   test
  Unit and functional tests along with fixtures. When using the rails generate
  command, template test files will be generated for you and placed in this
  directory.

*   vendor
  External libraries that the application depends on. Also includes the plugins
  subdirectory. If the app has frozen rails, those gems also go here, under
  vendor/rails/. This directory is in the load path. 
  
  
The Ruby on Rails starter application add example files as below: 


*   app/controllers/say_controller.rb

  The main source code that contains instructions to read cloud injected parameters and current information system environment.
    
*   app/views/say/hello.html.erb

  This file is example display page code.
  
*   app/views/layouts/application.html.erb

  This file is example project display page html head content code.

*   app/assets/stylesheets/style.css

  This file is example display page css code.

*   config/routes.rb

  This file browser access path settings.