# Update: X Thermals Engine v3.1

* **Fixed fail-open thermal state** caused by missing/renamed core policy files.
* **Restored vendor thermal policy integrity** (`thermal.conf`, `thermal_policy_00-03`, `thermal_policy_08`, etc.).
* **Added charging safety daemon** (`charge_guard.sh`) for guaranteed thermal current limiting.
* **Boot-persistent enforcement** via module service startup.
* **Gaming path preserved** (no intentional nerf to game turbo policy flow).
