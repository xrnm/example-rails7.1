# Rails 7.1 Example App with Devise-Two-Factor

Devise has a bunch of [example applications](https://github.com/heartcombo/devise/wiki/Example-Applications)
that provide examples of how Devise is used/installed.
Devise-Two-Factor was then adapted to the application.

## Getting Started

### Requirements

- Ruby 3.2.2
- Rails 7.1.1

### Install

```shell
bundle install
bin/rails db:create
bin/rails db:migrate
echo "aaecd7c87ddb047bdb5735529bcfea2fxrnm" > config/master.key
bin/rails server
```

## References

I took inspiration from [this project](https://github.com/timothyjamesmarias/rails_7_devise_example). If you are using Rails 7.0.X, be sure to check it out!
