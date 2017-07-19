# Vagrant environment for doing data science with R, Python and PostgreSQL

Work in progess...

## Prerequisites

* Vagrant
* Virtual Box

## Getting started

To get the images up and running:
```
git clone https://github.com/mateiw/data-science-vagrant.git
cd data-science-vagrant
vagrant up
vagrant ssh
```

To connect to the database from the host machine:
```
psql -h localhost -p 15432 -U datascience datascience
```
or with a Java client (e.g. SQuirreL SQL): 
```
jdbc:postgresql://localhost:15432/datascience
```

