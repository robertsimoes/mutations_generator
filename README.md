# MutationsGenerator

Rails generator extension for the [mutations](https://github.com/cypriss/mutations) framework.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mutations_generator'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install mutations_generator

## Usage

```
 rails g mutation PumpTheJam technotronic:string:required space_jam:string:optional

 # created  app/mutations/pump_the_jam.rb
 ```
## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).


## License
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

