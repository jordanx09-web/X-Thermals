## v3.1
* Fixed fail-open thermal state caused by missing/renamed core policy files.
* Restored vendor thermal policy integrity (thermal.conf, thermal_policy_00-03, thermal_policy_08, etc.).
* Added charging safety daemon (charge_guard.sh) for guaranteed thermal current limiting based on battery temps (41°C+ cap).
* Boot-persistent enforcement via module service startup.
* Gaming path preserved (no intentional nerf to game turbo policy flow).

# X Thermals Engine - Full Changelog

## V3 (Latest)
* Enforced a strict 40°C thermal ceiling at the config level for sustained performance.
* Refined AI decision tree with priority override when battery drops below 30%.
* Redesigned glassmorphism WebUI with live indicators and boot-persistent profile restore.
* Resolved sysfs read errors and system execution bugs for improved stability.
