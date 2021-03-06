# Minitest::PhilExample

<!-- MarkdownTOC autolink="true" -->

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Code of Conduct](#code-of-conduct)
- [Change Log](#change-log)
- [References](#references)

<!-- /MarkdownTOC -->


## Overview

This RubyGem is an example of how to make a Minitest Extension/Plugin for both 
Assertions/Expectations and Plugins.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'minitest-phil_example'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install minitest-phil_example

## Usage

```ruby
require 'minitest/autorun'
require 'minitest/phil_example'
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run 
`rake test` to run the tests. You can also run `bin/console` for an interactive 
prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To 
release a new version, update the version number in `version.rb`, and then run 
`bundle exec rake release`, which will create a git tag for the version, push 
git commits and tags, and push the `.gem` file to 
[rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at 
https://github.com/predatorian3/minitest-phil_example. This project is intended 
to be a safe, welcoming space for collaboration, and contributors are expected 
to adhere to the [Contributor Covenant](http://contributor-covenant.org) code 
of conduct.

## License

The gem is available as open source under the terms of the 
[MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Minitest::PhilExample project’s codebases, issue 
trackers, chat rooms and mailing lists is expected to follow the 
[code of conduct](https://github.com/predatorian3/minitest-phil_example/blob/master/CODE_OF_CONDUCT.md).

## Change Log

See the [Changelog](CHANGELOG) for historical information about the Gem.

## References

* [MiniTest RDoc Site](http://docs.seattlerb.org/minitest/)
* [GitHub: seattlerb/minitest Source](https://github.com/seattlerb/minitest)
* [GitHub Gist: How to write MiniTest Expectation](https://gist.github.com/ordinaryzelig/2032303)
