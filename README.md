# Monolith PHP Web Development Framework

**version: 5.91**

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
# Collections 3.6

some basic info about collections

# Component Bootstrapping 4.5

information

# Configuration 2.11

uses php dot env

# Dependency Injection 5.13

basic di container

# Error Handling 2.8

[![Build Status](https://travis-ci.org/monolith-php/error-handling.svg?branch=master)](https://travis-ci.org/monolith-php/error-handling)

# HTTP 8.1

[![Build Status](https://travis-ci.org/monolith-php/http.svg?branch=master)](https://travis-ci.org/monolith-php/http)
# Relational Database 5.3

[![Build Status](https://travis-ci.org/monolith-php/relational-database.svg?branch=master)](https://travis-ci.org/monolith-php/relational-database)
# Web Routing 15.0

[![Build Status](https://travis-ci.org/monolith-php/web-routing.svg?branch=master)](https://travis-ci.org/monolith-php/web-routing)

## Todo

Remove concept of "Controllers" and other hard-wiring from the Route definitions and replace with parameters. This will allow for vastly improved extensibility.
# Web Sessions 9.0

not yet secured, consider hazardous
# Twig HTML Templating 3.1


# Web Forms 0.8

form state management / validation model

