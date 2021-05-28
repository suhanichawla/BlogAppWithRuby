# SETUP

```
cd BlogAppWithRuby
bundle install
rails db:migrate
rails s
```
Go to localhost:300 to see the website in action

In case you run into the following error:
```
Rails: Webpacker::Manifest::MissingEntryError in Home#index
```
Run the following command:
```
bundle exec rake webpacker:install
```
