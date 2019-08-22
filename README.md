# Dependencies
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Rails](https://guides.rubyonrails.org/index.html)
* [Postgresql](https://www.postgresql.org/)
* [Pusher account](https://dashboard.pusher.com/accounts/sign_up)

# Setup

## Figaro
Run
```
figaro install
```
Then put your pusher app keys in **config/application.yml**

Ex:
```
PUSHER_APP_ID: 'xxx'
PUSHER_KEY: 'xxxxxxxxxxxxxxxx'
PUSHER_SECRET: 'xxxxxxxxxxxxx'
PUSHER_CLUSTER: 'xxx'
```

## Database

```
rails db:setup
```

# Getting started

Start rails server
```
rails s
```

Then open your [browser](localhost:3000)
