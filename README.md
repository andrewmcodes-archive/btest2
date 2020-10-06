# README

## [optional] Overmind

- [DarthSim/overmind: Process manager for Procfile-based applications and tmux](https://github.com/DarthSim/overmind)
- Instead of using `yarn start`, you can run Bridgetown inside of Overmind instead.
- Make changes to `.overmind.env` as needed.

### [wip] Recommended Workflow

- Run `overmind start`, which run's daemonized by default.
- Connect with `overmind connect [webpack,serve,sync]`, which puts you in a tmux session that allows you to switch to the other processes or create new ones.
- Restart specific parts with `overmind restart [webpack,serve,sync]`

Ex:

```sh
cd this-repo
overmind start
bundle add bridgetown-feed -g bridgetown_plugins
overmind restart bridgetown-serve
overmind connect
overmind kill
```

## Ruby 3

Note that this project is _currently_ using Ruby 3.0.0.preview-1
