# CircleCI Orbs

A project to house our Orbs.

## Our Orbs

* [status_to_ms_teams_pure_bash](https://circleci.com/orbs/registry/orb/bluemarblepayroll/status_to_ms_teams_pure_bash) - publishes the status of a job to a Microsoft Teams channel. Note that Microsoft provides [this integration](https://appsource.microsoft.com/en-us/product/office/WA104381588?src=Office&tab=Overview), *but* it has not been updated to work with CircleCI version 2.

## Development

First, [install and configure the circleci command](https://circleci.com/docs/2.0/configuration-reference/).

Tests can be run by executing:

```bash
test/run
```

## Publishing

First validate the orb:

```bash
circleci orb validate src/orbs/my_orb.yml
```

Then publish (assumes that it has already been created):

```bash
circleci orb publish src/orbs/my_orb.yml bluemarblepayroll/my_orb@dev:0.0.1
```

More info on the publishing process is [available from CircleCI](https://circleci.com/docs/2.0/creating-orbs/)

## Contributing

Pull requests are welcome! Please ensure that the tests are passing before submission.

## License

This project is MIT Licensed. The actual Orb licencing is per the [CircleCI CI Code Sharing Terms of Service](https://circleci.com/legal/code-sharing-terms/).
