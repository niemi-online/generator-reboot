# repo-bootstrapper
The standard yoeman generator for applications that I deploy to my personal infrastructure.

## Initial Setup
1. `npm install -g yo`
2. `npm install -g @niemi-online/generator-reboot`

## Common Usage
1. Create target directory: `mkdir target && cd target`
1. Boot up the repository: `yo reboot:<target>`
2. Answer the questions!

# Targets
These are the available generator targets

## Webapp
Created through `yo reboot:webapp`. This generates a base webapp project with:
1. Typescript, Sass, React, Redux
2. Lerna
3. Webpack & gulp for dev cycle
3. Dockerization for final deployment

## Python
Created through `yo reboot:python`. This generates a python project with:
1. A trivial python setup
2. Docker for local dev and deployment
TODO: allow for different types of python projects
