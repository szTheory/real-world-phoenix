# Real World Phoenix

> Real World Phoenix apps and their open source codebases for developers to learn from

Learn from Phoenix apps written by experienced developers.

You'll find the source code for the Real World Phoenix apps in the [`apps/`](apps/) subdirectory.

Thank you to every developer who has worked on a project this repo links to, your work is helping developers learn Phoenix.

## How to install on your computer

```bash
# Clone this git repo:
git clone git@github.com:szTheory/real-world-phoenix.git

cd real-world-phoenix/

# The apps are linked to as git submodules.
# This will take some time... (see comment below for possible speedup)
git submodule update --init

# OR if you've got git 2.9+ installed try to run updates in parallel:
# git submodule update --init --jobs 4
```

## Information for Contributors

### How to add a Real World App

Given a GitHub repo for an app `githubuser/foo`:

```bash
# Inside the project root:
git submodule add -b master git@github.com:githubuser/foo.git apps/foo
```

### Updating the apps submodules to latest

The apps in `apps/` are git submodules. Git submodules are locked to a revision and don't stay in sync with the latest revision.

To update the revisions, run:

```bash
# This will take some time:
git submodule foreach git pull origin master
```

## Other Real World Codebase Collections

- [Real World Erlang Apps](https://github.com/szTheory/real-world-erlang-apps)
- [Real World Elixir Apps](https://github.com/szTheory/real-world-elixir-apps)
- [Real World Plug](https://github.com/szTheory/real-world-plug)
- [Real World Absinthe](https://github.com/szTheory/real-world-absinthe)
- [Real World Nerves](https://github.com/szTheory/real-world-nerves)
- [Real World Rails](https://github.com/eliotsykes/real-world-rails)
- [Real World Sinatra](https://github.com/jeromedalbert/real-world-sinatra)
- [Real World Ruby Apps](https://github.com/jeromedalbert/real-world-ruby-apps)
- [Real World React](https://github.com/jeromedalbert/real-world-react)
- [Real World Ember](https://github.com/eliotsykes/real-world-ember)
- Know any others? Please open a PR and add the link here

---

## Contributors

- Contributions are welcome, fork the GitHub repo, make your changes, then submit your pull request! Reach out if you'd like some help.
