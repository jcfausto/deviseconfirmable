# Devise Confirmable Example

This is a sample app with devise :confirmable activated.

### Installation

```sh
$ git clone https://github.com/jcfausto/deviseconfirmable.git
$ cd deviseconfirmable
$ bundle install
$ rails server
```
### Important

The ActionMailer is configured to use a GMail account. If you have one, just put your email and password at #config/environments/development.rb:
```ruby
  #At production I recommend to use environment variables.
  #i.e ENV[ACTION_MAILER_PASSWORD]
  config.action_mailer.smtp_settings = {
    address:              'smtp.gmail.com',
    port:                 587,
    domain:               'deviseconfirmable.com',
    user_name:            'your_email@gmail.com',
    password:             'your_password',
    authentication:       'plain',
    enable_starttls_auto: true  }
```

## Questions?
Just drop me a line:  [@jcfausto](http://twitter.com/jcfausto) at twitter or [hello@jcfausto.com](mailto:hello@jcfausto.com)

More info: Check here: [http://jcfausto.com](http://jcfausto.com)

License
----

MIT
