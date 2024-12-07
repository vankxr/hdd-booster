# hdd-booster
This project consists of a simple PCB with two switching step-down regulators.
It aims to solve, or at least mitigate the low +5V rail current capacity of newer ATX consumer power supplies, which is a problem when trying to power lots of HDDs.
This problem is aggravated when adapters and splitters are used to expand the number of SATA/Molex power connectors.

## Short description
The board accepts power via a PCIe +12V aux power connector.
Since this board is best used on a NAS, typically there won't be any GPU installed, and thus there will be a +12V PCIe connector available.
The 12V from the PSU feeds both step-down regulators. Each regulator is capable of supplying about 5A, which should be enough for 4 power hungry HDDs.

## Authors

* **João Silva** - [vankxr](https://github.com/vankxr)

## License

The content of this repository is licensed under the [GNU General Public License v3.0](LICENSE).
