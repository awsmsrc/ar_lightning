# ArLightning

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'ar_lightning'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ar_lightning

## Usage

Simply send the method 'lightning' to your AR class/query and get back plain old
hash objects. This skips initializing AR objects in the name of speed which
saves ALOT of time with large datasets.

This idea was stolen from this post: 
http://brainspec.com/blog/2012/09/28/lightning-json-in-rails/
by Sergey Nartimov

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
