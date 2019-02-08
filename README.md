# [Aleph Labs](https://alephinsights.github.io/alephlabs/)

## About
A show case of some of the projects we've been working on.

# Adding Pages
Add .md (or .html) files to the /pages directory. Use the template file as a guide.


## Theme

Based on the [Cayman theme](https://github.com/jasonlong/cayman-theme) with some modifications.


## Setting up local Ruby & Jekyll dev environment

1. Setup [RVM](https://github.com/rvm/ubuntu_rvm)
    1. Don't `for get to add user to rvm group 'sudo usermod -a -G rvm USERNAME`
1. Setup ruby - `rvm install ruby` or `rvmsudo rvm install ruby` if you need to use root permissions
1. Install nodejs - `sudo apt install nodejs`
1. Setup bundle and jekyll - `gem install bundle && gem install jekyll`

# Prep site to run locally
- navigate to dir and run `bundle install`

## Running locally
Handy scripts
```
/script
```

run site with `script/server` site will be available at [localhost:4000](localhost:4000)

# Licence
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
