# Swipe Rails

## Installation

### Rails 4

**Step 1**

Load `swipe-rails` in your `Gemfile` as part of the `assets` group

    gem 'swipe-rails'

**Step 2**

Run 'bundle install'

**Step 3**

Require `swipe.js` in your Javascript manifest (e.g. `application.js`)

    //= require swipe

### Rails 3

The same as Rails 4 but put the gem into your `assets` group:

    group :assets do
      gem 'swipe-rails'
    end

## Usage

See [Swipe's Documentation](https://github.com/bradbirdsall/Swipe) for full
usage instructions.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
