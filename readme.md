# Parent (Project Parent)

parent library is used as parent in all PROVYS library and service projects. It holds reference to
used external libraries and plugins and enforces settings, common for PROVYS projects (e.g. plugins
that ensure projects follow PROVYS StyleGuide).

`parent` module holds all necessary dependencies.

`parent-tools` is used internally - it contains configuration of checkstyle plugin, that is included
in parent module.

## Development

Library is mostly modified to include new external libraries or update existing dependencies.
Before you do such change, please, see guidelines in
[Add / Update 3rd Party Libraries & Plugins](https://provys-wiki.dcit.cz/doku.php?id=development:java:tutorials:operations:update_parent).
