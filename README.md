# Textbook

## Setup

Install ruby and dependences

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

add ruby to path

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Install ruby package manager and jekyll

```bash
gem install jekyll bundler
```

Install ruby packages

```bash
bundle install
```

## run the server

bundle exec jekyll serve
