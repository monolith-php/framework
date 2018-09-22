# Monolith PHP Web Development Framework

**version: $$VERSION$$**

This isn't a tool that should be adopted. It's a design project to experiment with ideas.

## Goals

1. idiomatic language usage
    1. allows static-analysis without IDE extension or helpers
2. no compromise for tradition
    1. integration of established tools / standards generally avoided
    2. standards and conventions are good for integration but they're not good for questioning what you know and questioning how things are usually done.
3. grown like a garden
    1. designed as a discovery process
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
