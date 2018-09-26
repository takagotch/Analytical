### analytical
---

https://github.com/segmentio/analytics-ruby

```sh
gem 'analytics-ruby'
gem install 'analytics-ruby'
```

```ruby
analytics = Segment::Analytics.new(write_key: 'YOUR_WRITE_KEY')

analytics.identify(user_id: 42,
                   traits: {
                     email: 'name@ex.com',
                     first_name: 'Foo',
                     last_name: 'Bar'
                   })
                   
analytics.alias(user_id: 41)
analytics.track(user_id: 42, event: 'Created Account')

```
https://segment.com/docs/sources/server/ruby/

