# Finance Tracker

#### This repo is for a social finance tracker app

### Quick Start
Clone the repo:
```
git clone https://github.com/ianagpawa/finance-tracker.git
```

### Installation of Dependencies
In order to run the app locally, `Ruby` and `Rails` must be installed on your system.  Then, while the terminal is in the project folder, execute the following command to install the necessary gems and perform necessary migrations:
```
bundle install --without production
bin/rake db:migrate RAILS_ENV=development
```

### Viewing the app locally
In order to view the app locally, with the terminal in the project folder, execute command `rails s`, then point your browser to `http://localhost:3000`



### What's included
Within the project folder, you will find the following files:

```
finance-tracker/
    ├───  app/
    |       ├── assets/
    |       |       ├── javascripts/
    |       |       |      ├── application.js
    |       |       |      ├── bootstrap.js.coffee
    |       |       |      ├── friends.js
    |       |       |      ├── stocks.js
    |       |       |      └── user_stocks.coffee
    |       |       |
    |       |       └── stylesheets/
    |       |               ├── application.css.scss
    |       |               ├── bootstrap_and_overrides.css
    |       |               ├── custom.css.scss
    |       |               ├── scaffolds.scss
    |       |               └── user_stocks.scss
    |       |
    |       ├─── controllers/
    |       |       ├── user/
    |       |       |       └── registrations_controller.rb
    |       |       |
    |       |       ├── application_controller.rb
    |       |       ├── friendships_controller.rb
    |       |       ├── stocks_controller.rb
    |       |       ├── user_stocks_controller.rb
    |       |       ├── user_controller.rb
    |       |       └── welcome_controller.rb
    |       |
    |       ├─── models/
    |       |       ├── friendship.rb
    |       |       ├── stock.rb
    |       |       ├── user_stock.rb
    |       |       └── user.rb
    |       |       
    |       └─── views/
    |               ├── common/
    |               |       └── _spinner.html.erb
    |               ├── devise/
    |               |       ├── confirmations/
    |               |       |       └── new.html.erb
    |               |       ├── mailer/
    |               |       |       ├── confirmation_instructions.html.erb
    |               |       |       ├── reset_password_instructions.html.erb
    |               |       |       └── unlock_instructions.html.erb
    |               |       ├── passwords/
    |               |       |       ├── edit.html.erb
    |               |       |       └── new.html.erb
    |               |       ├── registrations/
    |               |       |       ├── edit.html.erb
    |               |       |       └── new.html.erb
    |               |       ├── sessions/
    |               |       |       └── new.html.erb
    |               |       ├── shared/
    |               |       |       └── _links.html.erb
    |               |       └── unlocks/
    |               |               └── index.html.erb
    |               ├── friends/
    |               |       └── _lookup.html.erb
    |               ├── layouts/
    |               |       ├── _navigation.html.erb
    |               |       └── application.html.erb
    |               ├── stocks/
    |               |       ├── _list.html.erb
    |               |       └── _lookup.html.erb
    |               ├── user_stocks/
    |               |       ├── _form.html.erb
    |               |       ├── edit.html.erb
    |               |       ├── index.html.erb
    |               |       ├── index.json.jbuilder
    |               |       ├── new.html.erb
    |               |       ├── show.html.erb
    |               |       └── show.json.jbuilder
    |               ├── user/
    |               |       ├── my_friends.html.erb
    |               |       ├── my_portfolio.html.erb
    |               |       └── show.html.erb
    |               └── welcome
    |                       └── index.html.erb
    ├──  bin/
    |       ├── bundle
    |       ├── rails
    |       ├── rake
    |       ├── setup
    |       └── spring
    ├── config/
    |       ├── environments/
    |       |       ├── development.rb
    |       |       ├── production.rb
    |       |       └── test.rb
    |       ├─── initializers/
    |       |       ├── assets.rb
    |       |       ├── backtrace_silencers.rb
    |       |       ├── cookies_serializer.rb
    |       |       ├── filter_parameter_logging.rb
    |       |       ├── inflections.rb
    |       |       ├── mime_types.rb
    |       |       ├── session_store.rb
    |       |       └── wrap_parameters.rb
    |       ├─── locales/
    |       |       └── en.yml
    |       ├─── application.rb
    |       ├─── boot.rb
    |       ├─── database.yml
    |       ├─── environment.rb
    |       ├─── routes.rb
    |       └─── secrets.yml
    ├── public/
    |     ├── 404.html
    |     ├── 422.html
    |     ├── 500.html
    |     ├── favicon.ico
    |     └── robots.txt
    ├── .gitignore
    ├── config.ru
    ├── Gemfile
    ├── Gemfile.lock
    ├── Rakefile
    └── README.md
```

## Creator

**Ian Agpawa**


[Github](https://github.com/ianagpawa)

 agpawaji@gmail.com
