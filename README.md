= paypal-express

Handle PayPal Express Checkout.
Both Instance Payment and Recurring Payment are supported.
Express Checkout for Digital Goods is also supported.

[<img src="https://secure.travis-ci.org/justqyx/paypal-express.png" />](http://travis-ci.org/justqyx/paypal-express)

## Installation

    gem install paypal-express

## Usage

See Wiki on Github
https://github.com/nov/paypal-express/wiki

Play with Sample Rails App
https://github.com/nov/paypal-express-sample
https://paypal-express-sample.heroku.com

**Extra**

`Paypal::Express::Request` now support set environment for PayPal endpoint

```ruby
request = Paypal::Express::Request.new(
  :username    => SET_YOUR_OWN,
  :password    => SET_YOUR_OWN,
  :signature   => SET_YOUR_OWN,
  :environment => :sandbox # or `:production`
)
```

## Note on Patches/Pull Requests

1. Fork the project.
2. Make your feature addition or bug fix.
3. Add tests for it. This is important so I don't break it in a future version unintentionally.
4. Commit, do not mess with rakefile, version, or history. (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
5. Send me a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2011 nov matake. See LICENSE for details.
