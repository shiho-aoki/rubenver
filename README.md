# README

* Ruby version
ruby: 3.1.1p18 (2022-02-18 revision 53f5fc4236) [aarch64-linux]


* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## How to make the world
### rails install

```
echo "gem: --no-document" >> ~/.gemrc

gem install rails -v 6.0.4

gem install bundler -v 2.2.17
```

### nodejs install

```
curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -

apt -y install nodejs

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt update && sudo apt install -y yarn
```