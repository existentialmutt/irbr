# irbr - Interactive RuBy Recorder

This gem is a workflow hack that helps you record the commands you type in a custom file.

There's not a lot of magic going on there.  IRB already saves your history to `~/.irbhistory` by default. This gem lets you easily specify a custom history file on the command line.

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add irbr

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install irbr

## Usage

`$ irbr output.rb`

You can also omit the filename.  It will write to `scratch.rb` by default.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/irbr. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/[USERNAME]/irbr/blob/master/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Irbr project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/irbr/blob/master/CODE_OF_CONDUCT.md).
