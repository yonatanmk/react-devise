
Getting Started
``` ruby

# Clone down this template
$ git clone https://github.com/jennceng/react-rails-boilerplate.git <YOUR_APP_NAME>

# Move into your app's directory
$ cd <YOUR_APP_NAME>

# Install all the gems
$ bundle install

$ npm install

# Remove the old git history and start your own
$ rm -rf .git && git init && git add -A && git commit -m 'Initial commit'
```

---

Configuring Your Database

This template is set up for using a PostgreSQL database. You will need to create a config/database.yml. There is an example at config/database.example.yml.

Once you've created a config/database.yml, you can create your database

```ruby
$ rake db:create
$ rails s
```

open another tab and

```ruby
$ npm start
```
go to [http://localhost:3000](http://localhost:3000) and make sure you see `dope`, which is rendered via react

user authentication built following instruction at https://labs.chiedo.com/blog/authenticating-your-reactjs-app-with-devise-no-extra-gems-needed/
