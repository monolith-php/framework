# Monolith PHP Web Development Framework

**version: 7.0**

- PHP 8.1 mandatory 

**version: 6.1**

This isn't a tool that should be adopted. It's a design project to experiment with ideas.

## Goals

1. idiomatic language usage
    1. allows static-analysis without IDE extension or helpers
2. no compromise for tradition
    1. integration of established tools / standards generally avoided
    2. standards and conventions are good for integration but they're not good for questioning what you know and questioning how things are usually done.
3. grown like a garden, designed as a discovery process
    1. naive implementations are designed first
    2. algorithms become more complex only when pain points are experienced
    3. solve problems with the simplest implementation possible
4. can become feature-complete
    1. lack of ambition to solve all problems
    2. components are open for extension, closed for modification
5. smallest possible user-land api exposure
    1. final classes by default
    2. strong pressure to avoid inheritance

## Installation

1. extract [the application skeleton](https://github.com/monolith-php/application-skeleton/archive/master.zip) to a new folder
2. run composer install
# Collections 9.3

some basic info about collections, they're fancy

# Component Bootstrapping 8.0

information

# Configuration 7.1

goals:

- drop php dot env (uses global state so can't be used for multiple environments simultaneously in a runtime)
- add new configuration loader / reader
- keep env file conventions

warning:

config can be used in component boostrapping bind() methods but only within bound closures. the configuration tool needs the bootstrap bind() phase to set itself up.

# Dependency Injection 9.4

basic di container

# Error Handling 6.0

[![Build Status](https://travis-ci.org/monolith-php/error-handling.svg?branch=master)](https://travis-ci.org/monolith-php/error-handling)

# HTTP 12.1

[![Build Status](https://travis-ci.org/monolith-php/http.svg?branch=master)](https://travis-ci.org/monolith-php/http)
# Relational Database 8.1


# Messaging 0.1

[![Build Status](https://travis-ci.org/monolith-php/command-bus.svg?branch=master)](https://travis-ci.org/monolith-php/command-bus)
# Web Routing 23.2

[![Build Status](https://travis-ci.org/monolith-php/web-routing.svg?branch=master)](https://travis-ci.org/monolith-php/web-routing)

##

1. make collections final
2. fix these collections
3. move tests to phpunit

## Todo

under prefix('admin', get('/', ...)) the front-slash doesn't work
# Web Sessions 16.0

not verified secure, consider hazardous
# Twig HTML Templating 6.0


