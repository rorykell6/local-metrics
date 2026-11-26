# Systemd cheat sheet

- `journalctl -u service -f`
- `systemctl list-timers --all`
- `journalctl --vacuum-time=7d` to trim old logs
- `systemctl cat <unit>` to inspect drop-in overrides
