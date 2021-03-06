# jQuery Textcomplete for Rails

[![Build Status](https://travis-ci.org/smolnar/jquery-textcomplete-rails.svg?branch=master)](https://travis-ci.org/smolnar/jquery-textcomplete-rails)

Provides integration of [jQuery Textcomplete](https://github.com/yuku-t/jquery-textcomplete) with Rails Asset Pipeline.

## Installation

Add this line to your application's Gemfile:

    gem 'jquery-textcomplete-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jquery-textcomplete-rails

## Usage

Include required javascripts in you `application.js` file:
```javascript
...
//= require jquery-textcomplete
...
```

Include required stylesheets into your `application.css` file:
```sass
...
//= require jquery-textcomplete
...
```

For more options and style customization, please, see [jQuery Textcomplete documentation](https://github.com/yuku-t/jquery-textcomplete).

## Testing

Go to `spec/dummy` and run `bundle`. After bundling, run specs with `bundle exec rspec`.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

Copyright &copy; 2014 Samuel Molnár

MIT License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
