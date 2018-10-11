# HakxelPalindrome

`hakxel_palindrome` is a sample Ruby gem created in [*Learn Enough Ruby to Be Dangerous*](https://www.learnenough.com/ruby-tutorial) by Michael Hartl.

## Installation

Add this line to your application's Gemfile:

```
gem 'hakxel_palindrome'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install hakxel_palindrome

## Usage

`hakxel_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'hakxel_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba".palindrome?
=> true
>> phrase = "Madam, I'm Adam"
>> phrase.palindrome?
=> true
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Hakxel/hakxel_palindrome.
