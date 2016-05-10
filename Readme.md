# Buildkite Static Site Deployment Example

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

This repository is an example of how to run a deploy agent which performs a simple deployment via `rsync`. It also contains an example of using a [branch configuration](https://buildkite.com/docs/guides/branch-configuration) to deploy non-master branches to separate folders.

It's recommended that deploy agents run under their own queue, such as `deploy`. See the [agent queue documentation](https://buildkite.com/docs/agent/queues) for how to do this.

Files to note:

* [.buildkite/project.json](.buildkite/project.json) - the two simple steps for deploying files using rsync
* [vhost.example.yml](vhost.example.yml) - an example Apache vhost configuration file

## License

See [Licence.md](Licence.md) (MIT)
