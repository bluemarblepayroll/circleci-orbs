# CircleCI Orbs

A project to house our Orb.

## Publishing

First validate the orb:

```bash
circleci orb validate src/orbs/my_orb.yml
```

Then publish (assumes that it has already been created):

```bash
circleci orb publish src/orbs/my_orb.yml bluemarblepayroll/my_orb@dev:first
```

More info on the publishing process is [available from CircleCI](https://circleci.com/docs/2.0/creating-orbs/)
