# Punctuate

Converts Unicode or non-ASCII punctuation and symbols to nearest ASCII punctuation and symbols. It is based on [default symbols & punctuation mapping table](http://lexsrv3.nlm.nih.gov/LexSysGroup/Projects/lvg/current/docs/designDoc/UDF/unicode/DefaultTables/symbolTable.html) recommended by [Lexical Tools](http://lexsrv3.nlm.nih.gov/LexSysGroup/Projects/lvg/current/docs/designDoc/UDF/unicode/NormOperations/mapSymbolToAscii.html).

## Installation

Add this line to your application's Gemfile:

```ruby
gem "punctuate"
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install punctuate

## Usage

    irb(main):001:0> require "punctuate"
    => true
    irb(main):002:0> "Your résumé’s a 100٪ non–encyclopædia❢".punctuate
    => "Your résumé's a 100% non-encyclopædia!"

## Development

Git clone repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/qwuen/punctuate. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
