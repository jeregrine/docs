---
layout: documentation
title: Integrations
docs_active: frameworks-and-libraries
permalink: docs/frameworks-and-libraries/
---

{% infobox %}
__Add your library:__ Have you written a cool library related RethinkDB and want us to showcase it?
Shoot us an email at <a href="mailto:info@rethinkdb.com">info@rethinkdb.com</a>.
{% endinfobox %}

# Node.js libraries

## Drivers and extensions

- [rethinkdbdash](https://github.com/neumino/rethinkdbdash) by [@neumino](https://github.com/neumino)  
  An alternative Node.js driver with native promises and a connection pool.

- [RQL Promise](https://github.com/guillaumervls/rql-promise) by [@guillaumervls](https://github.com/guillaumervls)  
   Wraps the RethinkDB driver with [when](https://github.com/cujojs/when) to return promises.

- [rethinkdb-co](https://github.com/hden/rethinkdb-co) by [@hden](https://github.com/hden)  
  Allows using ECMAScript 6 generators with RethinkDB callbacks.

- [rdb-cursor-stream](https://github.com/guillaumervls/rdb-cursor-stream) by [@guillaumervls](https://github.com/guillaumervls)  
  Replaces cursors with streams.

- [connect-rethinkdb](https://github.com/guillaumervls/connect-rethinkdb) by [@guillaumervls](https://github.com/guillaumervls)  
  A RethinkDB session store for Connect, similar to connect-redis.

- [express-session-rethinkdb](https://www.npmjs.com/package/express-session-rethinkdb) by [@armenfilipetyan](https://github.com/armenfilipetyan)  
  Use RethinkDB as session store with Express 4.x framework. Adapted from connect-rethinkdb.

- [Rethinkdb-pool](https://github.com/hden/rethinkdb-pool) by [@hden](https://github.com/hden)  
  Connection pool for RethinkDB connections.

- [second-thought](https://github.com/robconery/second-thought) by [@robconery](https://github.com/robconery)  
  A light abstraction layer over RethinkDB adding methods you "wished you had."

## ORMs

- [reheat](https://github.com/jmdobry/reheat) by [@jmdobry](https://github.com/jmdobry)  
  JavaScript ORM for RethinkDB with promises.

- [Thinky][] by [@neumino](https://github.com/neumino)  
  JavaScript ORM for RethinkDB.

- [JugglingDB-RethinkDB](https://github.com/fuwaneko/jugglingdb-rethink) by [@fuwaneko](https://github.com/fuwaneko)  
  A RethinkDB adapter for [JugglingDB](https://github.com/1602/jugglingdb), a multi-database ORM for Node.js.

- [Osmos](https://github.com/mtabini/osmos) by [@mtabini](https://github.com/mtabini)  
  A store-agnostic object data mapper for Node.js with support for RethinkDB.

[Thinky]: https://github.com/neumino/thinky

## Integrations

- [rabbitMQ](/docs/rabbitmq/javascript)  
  Listen for changes in a RethinkDB table over RabbitMQ.

- [koa-rethinkdb](https://github.com/hden/koa-rethinkdb) by [@hden](https://github.com/hden)  
  Koa middleware that automatically manages connections via a connection pool.

- [sails-hook-thinky](https://github.com/mwielbut/sails-hook-thinky) by [@mwielbut](https://github.com/mwielbut)  
  A hook to use [Thinky][] with [Sails](http://sailsjs.org/).

# Python libraries


## ORMs

- [rwrapper](https://github.com/dparlevliet/rwrapper) by [@dparlevliet](https://github.com/dparlevliet)  
  An ORM designed to emulate the most common usages of Django's database abstraction.

- [pyRethinkORM](https://github.com/JoshAshby/pyRethinkORM) by [@JoshAshby](https://github.com/JoshAshby)  
  A Python ORM for RethinkDB.

- [rethink](https://github.com/caoimhghin/rethink) by [@caoimhghin](https://github.com/caoimhghin)  
  A Python object mapper in the style of [App Engine NDB](https://cloud.google.com/appengine/docs/python/ndb/).

- [remodel](https://github.com/linkyndy/remodel) by [@linkyndy](https://github.com/linkyndy)  
  A simple but powerful and extensible Object Document Mapper for RethinkDB. (Also see the [pip package](https://pypi.python.org/pypi/Remodel).)

## Integrations

- [rabbitMQ](/docs/rabbitmq/python)  
  Listen for changes in a RethinkDB table over RabbitMQ.

- [celery-backends-rethinkdb](https://github.com/pilwon/celery-backends-rethinkdb) by [@pilwon](https://github.com/pilwon)  
  [Celery](http://www.celeryproject.org/)'s custom result backend for RethinkDB.

- [flask-rethinkdb](https://github.com/linkyndy/flask-rethinkdb) by [@linkyndy](https://github.com/linkyndy)  
  A Flask extension that adds RethinkDB support (also see the [pip package](https://pypi.python.org/pypi/Flask-RethinkDB/)).

# Ruby libraries

## ORMs

- [NoBrainer](https://github.com/nviennot/nobrainer) by [@nviennot](https://github.com/nviennot)  
  A Ruby ORM designed for RethinkDB. (Read our [quickstart tutorial](/docs/rails).)

## Integrations

- [Epiphy](https://github.com/kureikain/epiphy) by [@kureikain](https://github.com/kureikain)   
  A light persistence framework for RethinkDB.

- [rabbitMQ](/docs/rabbitmq/ruby)  
  Listen for changes in a RethinkDB table over RabbitMQ.

- [lotus-rethinkdb](https://github.com/angeloashmore/lotus-rethinkdb) by [@angeloashmore](https://github.com/angeloashmore)  
  A RethinkDB adapter for [Lotus::Model](https://github.com/lotus/model), a persistence framework for Ruby.

# Tools and utilities

## Administration

- [Chateau](https://github.com/neumino/chateau) by [@neumino](https://github.com/neumino)  
  An administrative interface for your data (like phpMyAdmin for RethinkDB).

- [Methink](https://github.com/Calder/methink) by [@Calder](https://github.com/Calder)  
  A MySQL to RethinkDB migration script.

- [rethink-miner](https://github.com/baruch/rethink-miner) by [@baruch](https://github.com/baruch)  
  Stores queries and their results, and displays them from a web interface.

- [recli](https://github.com/stiang/recli)  
  CLI to run ReQL queries in JavaScript.

- [rethinkdb-cli](https://github.com/byterussian/rethinkdb-cli)  
  CLI to run ReQL queries in Ruby.

- [phpReAdmin](https://github.com/billbarsch/phpReAdmin) by [@billbarsch](https://github.com/billbarsch)  
  Web frontend written in PHP to create/rename/update/delete RethinkDB databases/tables/docs and run ReQL queries in PHP.

- [rethinkdb_nightly](https://github.com/robconery/rethinkdb_nightly) by [@robconery](https://github.com/robconery)  
  A node module that will execute a nightly backup and push it to S3.

## Logging tools

- [fluent-plugin-rethinkdb](https://github.com/kureikain/fluent-plugin-rethink)  
  [FluentD](https://github.com/fluent/fluentd) output plugins to ship logs to RethinkDB.

## For driver developers
- [rethinkdb-driver-development](https://github.com/neumino/rethinkdb-driver-development) by [@neumino](https://github.com/neumino)  
  A tool to retrieve the query objects, messages and responses.

## Deployment tools

- [Rethinkdb-vagrant](https://github.com/RyanAmos/rethinkdb-vagrant) by [@RyanAmos](https://github.com/RyanAmos)  
  Lets you install RethinkDB using Vagrant.

- [puppet-rethinkdb](https://github.com/tmont/puppet-rethinkdb) by [@tmont](https://github.com/tmont)  
  A Puppet module for RethinkDB.

- [chef-rethinkdb](https://github.com/AVVSDevelopment/chef-rethinkdb) by [@AVVSDevelopment](https://github.com/AVVSDevelopment)  
  A RethinkDB cookbook for Chef deployment.

- [box-rethinkdb](https://github.com/mies/box-rethinkdb)  
  Wercker box for RethinkDB, by [@mies](https://github.com/mies).

## Docker images

{% infobox %}
Docker provides an [official RethinkDB repository](https://registry.hub.docker.com/_/rethinkdb/) on the Docker Hub. (Read [Installing RethinkDB](/docs/install) for more details.) This list highlights community-provided Docker images and tools.
{% endinfobox %}

- [Docker-rethinkdb](https://github.com/grzesiek/docker-rethinkdb) by [@grzesiek](https://github.com/grzesiek)  
  A simple Docker image for RethinkDB.

- [Dockerfile/rethinkdb](http://dockerfile.github.io/#/rethinkdb) by [@pilwon](https://github.com/pilwon)  
  Trusted Docker build and instructions for deploying a RethinkDB cluster.

- [Dockerfiles-examples](https://github.com/kstaken/dockerfile-examples) by [@kstaken](https://github.com/kstaken)  
  Includes scripts for building an image for Docker with RethinkDB (and other things).

- [Docker-cookbooks](https://github.com/crosbymichael/docker-cookbooks) by [@crosbymichael](https://github.com/crosbymichael)  
  A collection of Dockerfiles and configurations to build images for RethinkDB.
