GVTools Website
===============

This website is written using [Octopress][octopress].

[octopress]: http://octopress.org/

If you would like to contribute and deploy, first follow the **Before You Begin** section in [Octopress Setup][octopress-setup]. *Do not* continue to **Setup Octopress** (we've done that already).

[octopress-setup]: http://octopress.org/docs/setup/

Now run the following:

```bash
# Clone repo
cd /path/to/better-banner-umbrella-dir
git clone git@github.com:gvsutools/gvsutools.github.io.git

# Install requisite Ruby dependencies
gem install bundler
rbenv rehash    # If you use rbenv, rehash to be able to run the bundle command
bundle install --binstubs

# Setup GitHub deployment
git clone --branch master git@github.com:gvsutools/gvsutools.github.io.git _deploy

# Generate and deploy
bin/rake gen_deploy
```
