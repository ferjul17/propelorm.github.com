---
layout: documentation
title: Documentation
---

# Documentation #

 * [What's New in Propel 2.0](whats-new.html) Users of previous versions can check the changes here.
 * [Changelog](https://github.com/propelorm/Propel2/blob/master/UPDATE.md) Updates of the version 2.0.
 * [API Documentation](http://api.propelorm.org/) The generated API documentation.

## Project Setup ##

 * [Installing Propel](01-installation.html) Install Propel using Git, or a zipball/tarball.
 * [Building A Project](02-buildtime.html) Generate a PHP model based on a XML schema.

## Propel Basics ##

* [Basic CRUD](03-basic-crud.html) The basics of Propel C.R.U.D. (Create, Retrieve, Update, Delete) operations
* [Relationships](04-relationships.html) Searching and manipulating data from related tables.
* [Transactions](05-transactions.html) Where and when to use transactions.
* [Behaviors](06-behaviors.html) The behavior system allows to package and reuse common model features.
* [Logging And Debugging](07-logging.html) Propel can log a lot of information, including the SQL queries it executes.
* [Inheritance](08-inheritance.html) Single Table Inheritance, Class Table Inheritance, and Concrete Table Inheritance come free with Propel.
* [Migrations](09-migrations.html) Change the structure of the database without altering the data.

## Reference ##

* [XML Schema Format](../reference/schema.html) All the database, table, column and foreign key options explained
* [Active Record Classes](../reference/active-record.html) Complete list of the methods of Active Record classes.
* [Active Query Classes](../reference/model-criteria.html) Complete list of the methods of Propel Query classes.
* [Build Properties](../reference/buildtime-configuration.html) Reference for the `build.properties` file (`propel.ini` in symfony).
* [Runtime Configuration File](../reference/runtime-configuration.html) Reference for the `runtime-conf.xml` file.

## Behaviors Reference ##

* [`aggregate_column`](../behaviors/aggregate-column.html)
* [`alternative_coding_standards`](../behaviors/alternative-coding-standards.html)
* [`archivable`](../behaviors/archivable.html)
* [`auto_add_pk`](../behaviors/auto-add-pk.html)
* [`delegate`](../behaviors/delegate.html)
* [`i18n`](../behaviors/i18n.html)
* [`nested_set`](../behaviors/nested-set.html)
* [`query_cache`](../behaviors/query-cache.html)
* [`sluggable`](../behaviors/sluggable.html)
* [`timestampable`](../behaviors/timestampable.html)
* [`sortable`](../behaviors/sortable.html)
* [`validate`](../behaviors/validate.html)
* [`versionable`](../behaviors/versionable.html)
* And [`concrete_inheritance`](08-inheritance.html), documented in the Inheritance Chapter even if it's a behavior

You can also look at [user contributed behaviors](../cookbook/user-contributed-behaviors.html).

## Cookbook ##

### Common Tasks ###

* [Additional SQL Files](../cookbook/adding-additional-sql-files.html) How to execute custom SQL statements at buildtime
* [Advanced Column Types](../cookbook/working-with-advanced-column-types.html) How to work with BLOBs, serialized PHP objects, ENUM, and ARRAY column types.
* [Customizing build](../cookbook/customizing-build.html) How to customize the Phing build process.
* [How to Use PHP 5.3 Namespaces](../cookbook/namespaces.html) How to generate model classes with namespaces, and how to use them.
* [Model Introspection At Runtime](../cookbook/runtime-introspection.html) How to use the Map classes to discover table properties at runtime.
* [Multi-Component Data Model](../cookbook/multi-component-data-model.html) How to generate model classes in subdirectories, and organize your model into independent packages / modules.
* [Object Copy](../cookbook/copying-persisted-objects.html) How to clone and copy persisted objects.
* [Replication](../cookbook/replication.html) How to use Propel in a Master-Slave Replication Environment.
* [Using Propel With MSSQL Server](../cookbook/using-mssql-server.html) How to choose and configure Propel to persist data to a Microsoft SQL Server database.
* [Using SQL Schemas](../cookbook/using-sql-schemas.html) How to organize tables into SQL schemas (only for MySQL, PostgreSQL, and MSSQL).
* [Working With Existing Databases](../cookbook/working-with-existing-databases.html) How to build an XML schema from an existing db structure, how to dump data to XML, how to import it into a new database, etc.

### Contribute to Propel ###

* [Writing A Behavior](../cookbook/writing-behavior.html) How to write a custom behavior to reuse model code horizontally.
* [Testing Your Behaviors](../cookbook/testing-your-behaviors.html) How to unit test your behaviors.
* [Working with unit tests](../cookbook/working-with-unit-tests.html) How to setup propel's required environment and use PHPUnit.

### Working with Silex ###

* [Working with Silex](../cookbook/silex/working-with-silex.html)

>**Tip**<br />This is the up-to-date documentation for the last Propel version.
> To access the old documentation, please visit
[trac.propelorm.org](http://trac.propelorm.org) or
[propelorm.org/Propel](http://propelorm.org/Propel/).
