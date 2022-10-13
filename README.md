#Civic Data Ecosystem website
## Development
### Prerequisites
The Jekyll Docs have guides on how to check that your environment meets prerequisites and, if not, how to install them.
https://jekyllrb.com/docs/installation/

Once you have ruby and the other prerequisites installed, you'll need to make sure you have the `jekyll` and `bundler` ruby gems installed

Install jekyll and bundler gems if you don't already have them.
```shell
gem install jekyll bundler
```

### Installation
1. Clone the repo
```shell
# ssh
git clone git@github.com:civic-data-ecosystem/website.git

# OR https

git clone https://github.com/civic-data-ecosystem/website.git
```

2. Change directory to where you cloned the project
```shell
cd website
```

3. Add webrick to project if using ruby 3.0.0+
```shell
bundle add webrick
```

4. Build and deploy local version of site!  (The livereload option will have it refresh as you work on the site)
```shell
bundle exec jekyll serve --livereload
```

The webpage theme, "Forty", was initially created by <a href="https://html5up.net/forty">HTML5 UP</a> and was modified for jekyll by <a href="https://github.com/andrewbanchich/forty-jekyll-theme">Andrew Banchich</a> 
