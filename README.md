# Compojure-Template

A Leiningen template for projects using [Compojure][1]. 

This template creates a project configured to run as a standalone, 
or compile to a WAR. The project is setup to automatically reload 
resources in development mode and correctly serve static resources.


[1]: http://compojure.org

## Installation

If you're using Leiningen 1, you'll need to install the following plugins:

    lein plugin install lein-newnew 0.2.6
    lein plugin install compojure/lein-template 0.2.3

If you're using Leiningen 2, you don't have to do anything; the template
will be automatically downloaded and installed when you first run the
command.

## Usage

Run the following command to create a new Compojure project:

    lein new compojure <your project name>

## License

Copyright © 2012 Yogthos

Distributed under the Eclipse Public License, the same as Clojure.