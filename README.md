# Errbit docker

1. Create a mongodb container

docker run -d -p 27017:27017 -v /var/errbit/mongodb:/data/db --name mongodb dockerfile/mongodb

TODO: copy files

-> add content for config.ym;. mongoid.yml, init.d , logrotate, nginx, secret token
-> make file so that they use global vars?