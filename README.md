# H2C (Heterogeneous Hyper Cloud)

This is a Conceptual architecture that has a sample implementation of the use cases, 
Scenarios, and Test Cases for the Heterogeneous Hyper Cloud (H2C). H2C allows people
to run HPC and Cloud workloads in the same cloud infrastructure. 

This repository contains the design and a simple interactive reference architecture of the design.
Which can be found on the [Read the Docs](http://h2c.readthedocs.io) document hub.

![image](docs/Solution/Deployment.png)

## Design

The design uses [plantuml](http://plantuml.com/) and [rst](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html)
to document the architecture.

Plantuml is a text based language that lets you describe UML diagrams. 
All of the plantuml graphic files are shown in the *.md (markdown language files). 
In order to see the graphical representation of the uml files you have to generate *.png files.
To generate the graphic files (*.png) for the plantuml files (*.puml) do the following:

```
# npm run-script design
```

## Implementations

An implementation of the reference architecture is written using [sailsjs](http://sailsjs.org/) a nodejs MVC framework.

