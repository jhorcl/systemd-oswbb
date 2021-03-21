# systemd-oswbb

Files to manage Oracle OSWatcher daemon with systemd.

## Installation

Create `oswbb.conf` in any directory you want, for example `/etc` and update
variables as described in the config.

Create `oswbb.service` in `/etc/systemd/system` and update `EnvironmentFile` to
reflect the path to `oswbb.conf`.

Then add the unit using `systemctl add oswbb.service` and start using
`systemctl start oswbb.service`
