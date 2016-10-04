<style>
img {
  width: 100%;
}
pre {
  font-size: 1em !important;
  line-height: 1em !important;
}
</style>
# CI/CD WORKSHOP

---

# Why CI/CD?

---

# lets face it!

---

# everybody makes mistakes!

Note: what can we do about that?

---

# Release more often

Note: is simply mean we deploy less code per deploy

---

# % > bugs released

---

# BUT ALSO

---

# quicker features

---

# small migrations all the time

---

# what you also get!

---

# easier recover

---

# no giant rollbacks

---

# lets get busy!

---

# today we all

---

# just hired as CTO

---

# a prototype
Note: it is not even on github

---

## first task 🚀
# get it on github
Note: email everybody the link

---

# luckily our developer did

---

# create a dockerfile

---

# 😅

---

# let's build it

---

# task: `docker build` 🚀
## give it a name!
## use `"--help"` for help

---

# let's try to run it

---

# look in the dockerfile to see port

---

# docker run -it -p 9000:9000 NAME

---

# but ...

---

# he hardcoded the database string

---

# we need to fix it

---

# task: change it to environment variable 🚀
## node.js: process.env.EXAMPLE

---

# let's share it

---

# a docker registry

---

# docker hub

---

# why use docker hub?
Note: it works, its cheap, is easy to get started

---

# 2 different types
Note: automated builds, normal repository

---

# sign up for docker hub 🚀
# create a repo 🚀

---

# push the image to docker hub 🚀

---

# bash commands

---

# doesn't really scale, right?

---

# docker-compose

---

# a project tool

---

```
version: '2'
services:
  web:
    ...
```

---

## task: create a docker-compose.yml 🚀
### find the docs for docker-compose

---

## docker-compose build
## docker-compose up -d

---

# continues service

---

# CircleCI

---

# why use that?

---

# task: create a account 🚀

---

# what to run on Circle CI?
Note: docker-compose up

---

# circle.yml

---

# task: create a circle.yml, commit it

---

# task: add your project 🚀

---

# we need to host it

---

# hyper.sh

---

## sign up for hyper.sh
# use promocode "kevinsimper"

---

task: run a container 🚀

---

# let's encrypt

---

# caddyserver

---

# task: create a local config 🚀

---

# how to differentiate prod vs dev

---

# default is prod

---

# task: create a remote config 🚀

---

# ELK STACK

---

# Elastic Search

---

# Logstash

---

# Kibana

---

# What did we learn?

---

# we learned how to setup github

---

# how circleci works

---

# how to deploy a container online

---

# how to setup tls/ssl

---

# how elk can be used
