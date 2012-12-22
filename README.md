# Act::Fluent::Logger::Rails

Fluent logger.

## Installation

Add this line to your application's Gemfile:

    gem 'act-fluent-logger-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install act-fluent-logger-rails

## Usage

in config/environments/production.rb

    config.log_level = :info
    config.logger = Actindi::Logger.new

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
