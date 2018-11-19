# Introduction
Jekyll is a static site generator. With jekyll, you can create a static website with your favorite language(html, sass, markdown, yml). This repository is a completion of [this tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/).

# Setup
Take ubuntu 16.04 as an example. For other operating system, please go [here](https://jekyllrb.com/docs/installation/).

## Install Ruby
`gem install jekyll bundler`

## Configure the gem installation path
```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME=$HOME/gems' >> ~/.bashrc
echo 'export PATH=$HOME/gems/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
```

## Install Jekyll
`gem install jekyll bundler`

# Build and Running
`jekyll build` will output a static site to a directory `_site`

`jekyll serve` does the same thing except it will watch your file change and rebuild at anytime and runs a local web server at `http://localhost:4000`.