# digit.ml

### Run website locally
Install jekyll locally by following the instructions at
https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll

`
sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev
sudo apt-get install ruby-full
sudo gem update --system
sudo gem install bundler
sudo bundle update --bundler
`

Then run

`
bundle exec jekyll serve --port 8000
`

and in your browser open

`
http://127.0.0.1:8000/
`
