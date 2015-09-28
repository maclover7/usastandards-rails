# USA Web Standards, for Rails.

[![Build Status](https://travis-ci.org/moss-rb/usastandards-rails.svg)](https://travis-ci.org/moss-rb/usastandards-rails)

Please see the appropriate guide for your environment of choice:

* [Ruby on Rails](#a-ruby-on-rails).

### a. Ruby on Rails

`usastandards-rails` is easy to drop into Rails with the asset pipeline.

In your Gemfile you need to add the `usastandards-rails` gem.

```ruby
gem 'usastandards-rails', '~> 3.3.5'
```

`bundle install` and restart your server to make the files available through the pipeline.

Import Standards styles in `app/assets/stylesheets/application.css`:

```scss
// "usastandards-fonts" must be imported before "usastandards"
@import "usa-standards-fonts";
@import "usa-standards";

Require Standards Javascripts in `app/assets/javascripts/application.js`:

```js
//= require jquery
//= require usa-standards
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/moss-rb/usastandards-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
