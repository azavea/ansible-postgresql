# ansible-postgresql

An Ansible role for installing PostgreSQL.

## Role Variables

- `postgresql_version` - PostgreSQL version (default: `9.3`)
- `postgresql_package_version` - PostgreSQL package version (default: `9.3.5-1.pgdg14.04+1`)
- `postgresql_listen_addresses` - Address for PostgreSQL to bind to (default: `localhost`)
- `postgresql_port` - Port for PostgreSQL to bind to (default: `5432`)
- `postgresql_data_directory` - Default data directory (default: `/var/lib/postgresql/{{ postgresql_version }}/main`)
- `postgresql_log_min_duration_statement` - Minimum duration for logging slow queries (default: `-1`)

## Example Playbook

See the [examples](./examples/) directory.
