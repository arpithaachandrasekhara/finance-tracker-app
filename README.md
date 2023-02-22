# README

"This is the finance tracker app"

Things you may want to cover:

* Ruby version
    5.2.8.1

* System dependencies
    yarn
    webpacker
    bootstrap

* Configuration
    dev env

* Database creation
    sqlite - rails db 

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

Design and add Stock model

- Attributes name, ticker_symbol and price
- Automate looking up stock (currently only possible through rails console using iex code with publishable key etc.)
- Automate API key insertion (instead of having to key it in everytime we look up a stock)
  - This will expose us to secure credentials in Rails apps:
    credentials.yml.enc (encrypted file)
    master.key (key to decrypt credentials file)