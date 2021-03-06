# Cycle ORM
[![Latest Stable Version](https://poser.pugx.org/cycle/orm/version)](https://packagist.org/packages/cycle/orm)
[![Build Status](https://github.com/cycle/orm/workflows/build/badge.svg)](https://github.com/cycle/orm/actions)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cycle/orm/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cycle/orm/?branch=master)
[![Codecov](https://codecov.io/gh/cycle/orm/graph/badge.svg)](https://codecov.io/gh/cycle/orm)
<a href="https://discord.gg/TFeEmCs"><img src="https://img.shields.io/badge/discord-chat-magenta.svg"></a>

<img src="https://cycle-orm.dev/cycle.png" height="135px" alt="Cycle ORM" align="left"/>

Cycle is a PHP DataMapper ORM and Data Modelling engine designed to safely work in classic and daemonized PHP applications (like [RoadRunner](https://github.com/spiral/roadrunner)). The ORM provides flexible configuration options to model datasets, a powerful query builder, and supports dynamic mapping schemas. The engine can work with plain PHP objects, support annotation declarations, and proxies via extensions.

<p align="center">
	<a href="https://github.com/cycle/docs"><b>Documentation</b></a> | <a href="https://github.com/cycle/docs/issues/3">Comparison with Eloquent and Doctrine</a>
</p>

Features
---------
- ORM with has-one, has-many, many-through-many and polymorphic relations
- Plain Old PHP objects, [AR](https://github.com/cycle/docs/blob/master/advanced/active-record.md), Custom objects or [same entity type for multiple repositories](https://github.com/cycle/orm/tree/master/tests/ORM/Classless)
- eager and lazy loading, query builder with multiple fetch strategies
- embedded entities, lazy/eager loaded embedded partials
- runtime configuration with/without code-generation
- column-to-field mapping, single table inheritance, value objects support
- hackable: persist strategies, mappers, relations, transactions
- works with directed graphs and cyclic graphs using command chains
- designed to work in long-running applications: immutable service core, disposable UoW
- supports MySQL, MariaDB, PostgresSQL, SQLServer, SQLite
- schema scaffolding, introspection, and migrations
- supports global query constraints, UUIDs as PK, soft deletes, auto timestamps
- custom column types, FKs to non-primary columns
- use with or without annotations, proxy classes, and auto-migrations
- compatible with Doctrine Collections, Doctrine Annotations, and Zend Hydrator

Extensions
---------
| Component | Current Status
| ---       | ---
cycle/schema-builder | [![Latest Stable Version](https://poser.pugx.org/cycle/schema-builder/version)](https://packagist.org/packages/cycle/schema-builder) [![Build Status](https://github.com/cycle/schema-builder/workflows/build/badge.svg)](https://github.com/cycle/schema-builder/actions) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cycle/schema-builder/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cycle/schema-builder/?branch=master) [![Codecov](https://codecov.io/gh/cycle/schema-builder/graph/badge.svg)](https://codecov.io/gh/cycle/schema-builder)
cycle/annotated | [![Latest Stable Version](https://poser.pugx.org/cycle/annotated/version)](https://packagist.org/packages/cycle/annotated) [![Build Status](https://github.com/cycle/annotated/workflows/build/badge.svg)](https://github.com/cycle/annotated/actions) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cycle/annotated/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cycle/annotated/?branch=master) [![Codecov](https://codecov.io/gh/cycle/annotated/graph/badge.svg)](https://codecov.io/gh/cycle/annotated)
cycle/proxy-factory | [![Latest Stable Version](https://poser.pugx.org/cycle/proxy-factory/version)](https://packagist.org/packages/cycle/proxy-factory) [![Build Status](https://github.com/cycle/proxy-factory/workflows/build/badge.svg)](https://github.com/cycle/proxy-factory/actions) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cycle/proxy-factory/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cycle/proxy-factory/?branch=master) [![Codecov](https://codecov.io/gh/cycle/proxy-factory/graph/badge.svg)](https://codecov.io/gh/cycle/proxy-factory)
cycle/migrations | [![Latest Stable Version](https://poser.pugx.org/cycle/migrations/version)](https://packagist.org/packages/cycle/migrations) [![Build Status](https://github.com/cycle/migrations/workflows/build/badge.svg)](https://github.com/cycle/migrations/actions) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cycle/migrations/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cycle/migrations/?branch=master) [![Codecov](https://codecov.io/gh/cycle/migrations/graph/badge.svg)](https://codecov.io/gh/cycle/migrations)

License
--------
The MIT License (MIT). Please see [`LICENSE`](../license.md) for more information. Maintained by [Spiral Scout](https://spiralscout.com).
