# Build marketplace for freelancers like Fiverr with Rails 6 - Level 1

https://github.com/ingafter60/code4startup-freelancer

## Task 1 - Work with basic project

### 1.1.1 What is task 1 about? 0:39

      PASS

### 1.2.2 Create Rails project with Postgres 5:50

      >> rails new --database=postgresql
      >> sudo service postgresql start
      >> rails db:setup
      >> rails s
      >> create remote repository on github
      > https://github.com/ingafter60/code4startup-freelancer
      >> save project on local repository
      >> push the project to github repositoy

### 1.3.3 Source Control with Github 5:31

      PASS >> refer to 1.2.2
      modified:   README.md

### 1.4.4 Installing Bulma and jQuery 9:49

        modified:   Gemfile
        modified:   Gemfile.lock
        modified:   app/assets/stylesheets/application.css
        modified:   config/webpack/environment.js
        modified:   package.json
        modified:   yarn.lock

### 1.5.5 Create a static page with navbar 14:25

        modified:   Gemfile
        modified:   Gemfile.lock
        new file:   app/assets/images/logos/g-logo.jpg
        renamed:    app/assets/stylesheets/application.css -> app/assets/stylesheets/application-ori.css
        new file:   app/assets/stylesheets/application.scss
        new file:   app/assets/stylesheets/pages.scss
        new file:   app/controllers/pages_controller.rb
        new file:   app/helpers/pages_helper.rb
        modified:   app/views/layouts/application.html.erb
        new file:   app/views/pages/home.html.erb
        new file:   app/views/shared/_navbar.html.erb
        modified:   config/routes.rb
        modified:   package.json
        new file:   public/favicon-ori.ico
        modified:   public/favicon.ico
        new file:   test/controllers/pages_controller_test.rb
        modified:   yarn.lock

        DONE:) 15/12/2020 09:49

## Task 2 - Authentication with email

### 2.1.6 What is task 2 about? 0:56

      PASS

### 2.2.7.1 (Sing up and Log in) Create authentication with email and password 16:15

        modified:   Gemfile
        modified:   Gemfile.lock
        modified:   README.md
        new file:   app/models/user.rb
        new file:   app/views/devise/confirmations/new.html.erb
        new file:   app/views/devise/mailer/confirmation_instructions.html.erb
        new file:   app/views/devise/mailer/email_changed.html.erb
        new file:   app/views/devise/mailer/password_change.html.erb
        new file:   app/views/devise/mailer/reset_password_instructions.html.erb
        new file:   app/views/devise/mailer/unlock_instructions.html.erb
        new file:   app/views/devise/passwords/edit.html.erb
        new file:   app/views/devise/passwords/new.html.erb
        new file:   app/views/devise/registrations/edit.html.erb
        new file:   app/views/devise/registrations/new.html.erb
        new file:   app/views/devise/sessions/new.html.erb
        new file:   app/views/devise/shared/_error_messages.html.erb
        new file:   app/views/devise/shared/_links.html.erb
        new file:   app/views/devise/unlocks/new.html.erb
        modified:   app/views/layouts/application.html.erb
        modified:   config/environments/development.rb
        new file:   config/initializers/devise.rb
        new file:   config/locales/devise.en.yml
        modified:   config/routes.rb
        new file:   db/migrate/20201215034807_devise_create_users.rb
        new file:   db/schema.rb
        new file:   test/fixtures/users.yml
        new file:   test/models/user_test.rb
        > Sing Up and Log In are working

### 2.2.7.2 (Display logged in user) Create authentication with email and password 16:15

        modified:   README.md
        new file:   app/assets/images/logos/f-logo.jpg
        modified:   app/views/shared/_navbar.html.erb
        modified:   config/routes.rb
        new file:   public/favicon-g.ico
        modified:   public/favicon.ico

### 2.3.8 Add custom fields to User model 6:53

        modified:   app/controllers/application_controller.rb
        modified:   app/models/user.rb
        new file:   db/migrate/20201216022646_add_columns_to_user.rb
        modified:   db/schema.rb

### 2.4.9 Update authentication views 11:39

        new file:   app/assets/images/logos/f2-logo.jpg
        modified:   app/views/devise/confirmations/new.html.erb
        modified:   app/views/devise/passwords/edit.html.erb
        modified:   app/views/devise/passwords/new.html.erb
        modified:   app/views/devise/registrations/edit.html.erb
        modified:   app/views/devise/registrations/new.html.erb
        modified:   app/views/devise/sessions/new.html.erb
        modified:   app/views/devise/shared/_error_messages.html.erb
        modified:   app/views/devise/shared/_links.html.erb
        modified:   app/views/devise/unlocks/new.html.erb
        modified:   app/views/shared/_navbar.html.erb
        new file:   public/favicon--.ico
        modified:   public/favicon.ico

### 2.5.10 Update styles 8:28

## Task 3 - Authentication with Facebook

3.1.11 What is task 3 about? 0:49  
3.2.12 Notification 12:22  
3.3.13 Create Facebook app 1:55  
3.4.14 Create Facebook authentication 17:38  
3.5.15 Update User edit page 6:52

## Task 4 - Create User dashboard

4.1.16 What is task 4 about? 0:50  
4.2.17 Create dashboard controller 8:20  
4.3.18 Create User menu 9:39  
4.4.19 Update dashboard page - part 118:14  
4.5.20 Update dashboard page - part 28:05

## Task 5 - Create User profile

5.1.21 What is task 5 about? 1:22  
5.2.22 Upload User avatar 13:28  
5.3.23 Social verification with Facebook 8:02  
5.4.24 Create User profile page 12:14

## Task 6 - Create Gig

6.1.25 What is task 6 about? 1:22  
6.2.26 Create Gig model 11:24  
6.3.27 Gig controller - action New 12:15  
6.4.28 Gig View - action New 13:21  
6.5.29 Gig View - action Edit 27:39  
6.6.30 Gig controller - action Edit 21:18  
6.7.31 Gig upload photos 16:55

## Task 7 - Gig details

7.1.32 What is task 7 about? 1:42  
7.2.33 Update dashboard page 14:45  
7.3.34 Prepare Gig details 10:21  
7.4.35 Gig details page - part 111:02  
7.5.36 Gig details page - part 222:07

## Task 8 - Orders

8.1.37 What is task 8 about? 1:06  
8.2.38 Order model 11:28  
8.3.39 Create new order for Gig 13:39  
8.4.40 Selling and Buying orders 13:32  
8.5.41 Complete the order 6:44
