### cityhash [![TravisCI](https://secure.travis-ci.org/nashby/cityhash.png?branch=master)](http://travis-ci.org/nashby/cityhash)

Ruby wrapper for google's cityhash.

### Install

    gem install cityhash

### Usage

```ruby
require 'cityhash'

text = "test"
seed1 = 12345
seed2 = 54321

CityHash.hash64(text)               # => 17703940110308125106
CityHash.hash64(text, seed1)        # => 14900027982776226655
CityHash.hash64(text, seed1, seed2) # => 11136353178704814373
CityHash.hash128(text)              # => 1800071687761605184910580728449884026697
CityHash.hash128(text, seed1)       # => 6087407617808651818174120599816915369
```

### Contributing to cityhash

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

### Authors

#### [Contributors](http://github.com/nashby/cityhash/contributors)
 - [Johannes Holzfuß](http://github.com/DataWraith)
 - [Quin Hoxie](https://github.com/qhoxie)
 - [David Dai](https://github.com/newtonapple)

[Vasiliy Ermolovich](http://github.com/nashby/)<br/>

### Copyright

Copyright (c) 2012 Vasiliy Ermolovich. See LICENSE.txt for
further details.
