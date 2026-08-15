# WiFi TX power unlocker scripts

This repository contains the original WiFi region/txpower unlocker scripts for Arch Linux and Kali Linux.

## Included scripts

- `arch-linux-region-BO-wifi-txpower-unlocker.sh`
- `kali-linux-region-BO-wifi-txpower-unlocker.sh`

These scripts modify the regulatory database to raise the effective TX power for restricted regulatory domains, mainly targeting BO-region behavior.

## Notes

- These scripts are intended for Linux systems that use a regulatory database managed by `wireless-regdb` and `crda`.
- Use with caution; modifying regulatory data may affect Wi-Fi operation and compliance with local laws.
- Run the relevant script with `bash <script-name>.sh` on a supported system.

## Source

The scripts are adapted from the original `wifi-txpower-unlocker` project by Hiruna Wijesinghe.
