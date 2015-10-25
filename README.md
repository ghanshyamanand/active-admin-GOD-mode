## Development Setup

### Clone the repo
```
git clone https://github.com/ghanshyamanand/active-admin-GOD-mode.git
```

### Install dependencies (ensure bundler is installed)
```
cd active-admin-GOD-mode
bundle install
```

CREATE database config (sample config is in config/database_sample.yml)
```
cp config/database_sample.yml config/database.yml
# make the appropirate changes if necessary
```
Setup DB
```
rake db:create
rake db:migrate
rake db:seed
```

# Administration

You can access the admin console by visiting http://localhost:3000/admin. You can find out credentials in db/seed.rb file :)
