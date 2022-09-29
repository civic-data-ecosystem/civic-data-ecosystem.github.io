# Civic Data Ecosystem website


## Development
### Prerequisites
The Jekyll Docs have guides on how to check that your environment meets  prerequisites and, if not, how to install them.
https://jekyllrb.com/docs/installation/



Once you have ruby and the other prerequisites installed,
you'll need to make sure you have the `jekyll` and `bundler` ruby gems installed
```shell
# install jekyll and bundler gems if you don't already have them
gem install jekyll bundler
```

### Installation
```shell
# clone repo
# ssh
git clone git@github.com:civic-data-ecosystem/website.git
# OR https
git clone https://github.com/civic-data-ecosystem/website.git

# change directory to where you cloned the project
cd website

# (maybe optional) add webrick to project if using ruby 3.0.0+
bundle add webrick

# build and deploy local version of site! 
# The livereload option  will have it refresh as you work on the site
bundle exec jekyll serve --livereload
```

