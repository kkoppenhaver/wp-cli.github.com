---
layout: default
title: 'wp db repair'
display_global_parameters: true
---

`wp db repair` - Repair the database in MySQL.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Adb-repair+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Runs `mysqlcheck` utility with `--repair=true` using `DB_HOST`,
`DB_NAME`, `DB_USER` and `DB_PASSWORD` database credentials
specified in wp-config.php.

[See docs](http://dev.mysql.com/doc/refman/5.7/en/repair-table.html) for
more details on the `REPAIR_TABLE` statement.



