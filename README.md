# Ruby on Docker

This project is one way of programmer in [ruby](https://www.ruby-lang.org/) using [docker](http://docker.com/)

## To Run

`docker run --rm -v "$(pwd)":/app -w /app evild/alpine-ruby sh -c "bundle install --standalone && ruby hello.rb"`

### User Unix 

  if you are use unix, you could create an alias to run this project:
  
  `alias startApp='docker run --rm -v "$(pwd)":/app -w /app evild/alpine-ruby sh -c "bundle install --standalone && ruby hello.rb"'`
  
  **run** `startApp` **in your terminal**
