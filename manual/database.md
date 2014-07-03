---
title: Database
layout: manual
---


## Activation and Configuration

The framework is included as an optional module, that is not included in your
application by default.  To activate it, add the module to your app
configuration:

	module.db = github.com/revel/revel/modules/db

The [app.conf](appconf.html) needs setting with following as examples

	# postgres
	db.import = github.com/lib/pg
    db.driver = postgres
    db.spec = ?
    
    # mysql
	db.import = github.com/lib/pg
    db.driver = mysql
    db.spec = ?
    
    # sqlite
	db.import = github.com/mattn/go-sqlite3
	db.driver = sqlite3
	db.spec   = :memory:
    
    

## Initialising Connection

TODO

## Basic Usage

TODO

## ORM

ORM usage is beyond csope, but here is a goprp example and sqlx



## Multiple Connections 

TODO

