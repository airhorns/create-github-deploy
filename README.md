# `create-github-deploy`

Provides a binary, `create-github-deploy`, which will interact with the (Github Deployments API)[https://developer.github.com/v3/repos/deployments/] for you in deploy scripts.

You can use this to:
 - trigger deploys run by a different thing listening to Github Deployments
 - or, trigger a deploy, and then update it's status as you deploy from the same script. If you are running deploys in a simple way in one script or something like that, you can use this to create a deployment, and then update the status of it without needing to deploy multiple components.

## Installation

Add this line to your application's Gemfile:

```
$ gem install create-github-deploy
```

## Usage

TODO

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/hornairs/create-github-deploy. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Create::Github::Deploy project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/hornairs/create-github-deploy/blob/master/CODE_OF_CONDUCT.md).
