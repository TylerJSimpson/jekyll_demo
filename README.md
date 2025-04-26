# jekyll_demo

## Install Prerequisites

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

```bash
gem install jekyll bundler
```

Clone the theme of your choice:
```bash
git clone https://github.com/zerostaticthemes/jekyll-serif-theme.git
```

```bash
bundle install
```

```bash
bundle exec jekyll serve
```