# Jekyll and Docker Compose

## Summary

This project provides examples for building a Jekyll blog/site with Docker Compose. Using Docker you can easily
develop your jekyll site without installing Ruby and can develop it from computer to computer with a consistent
environment.  This is particularly helpful for Windows users.

## Why Use Docker

Docker containers provide a consistent environment accross different computers.  For the non-Ruby developer, it means you don't have to install Ruby on Rails to your system to make your site.  This is a great option for Windows users who don't want to deal with Ruby.

## Getting Started

#### Prerequisites
 You must have Docker and Compose installed to run your Jekyll project in Docker.

 [Instructions to install Docker Compose](https://docs.docker.com/compose/install/)

#### Using this sample

To start your project using this sample template begin by cloning this repository.

To serve up the project:
1) In project folder run (Linux users may need to use 'sudo'):
```
docker-compose up
```
2) View project at localhost:4000
3) Edit project and Jekyll will auto-regenerates the site
4) When you want to shut-down the site, ues Ctrl+C then run:
```
docker-compose down
```

When you are ready to publish, simply push your project to Github or whenever you choose you host your site.

#### Exisiting Project or Start from Scratch

Adding Docker Compose to an existing project or starting from scratch is easy.  Create a filed called 'docker-compose.yml' in the root.  See example file for the contents you sould add: [Sample docker-compose.yml](https://github.com/joelt11753/Jekyll-and-Docker-Compose/blob/master/docker-compose.yml)

After you have a docker-compose.yml file in your existing or new Jekyll project, simply follow the instructions above in the "Using this sample" section to serve up your project.  

#### Sample Theme

The theme that is used is from [portfolio-iro](https://github.com/Bloc/portfolio-iro/) and serves as an example theme
for this project.

A free and open-source [Jekyll](http://jekyllrb.com) theme. Great for blogs and easy to customize.

[Original Repo](https://github.com/Bloc/portfolio-iro/)

[Demo](https://rohanchandra.github.io/type-theme/)
