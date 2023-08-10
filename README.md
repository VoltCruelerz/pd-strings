# Point Defense Strings

## Changes

- Point defense autocannons now fire in shorter, denser bursts to look more like real-life point defense weaponry and avoid the silliness of seeming to shoot down dead missiles.
- Point defense weapons have also been disambiguated in the UI based on whether or not they can attack things larger than a strikecraft.
  - `PD-A` (Point Defense - Attack): these turrets can be used offensively to attack other ships, such as on the _Garda_.
  - `PD-D` (Point Defense - Defense): these turrets _cannot_ be used offensively, such as those on the _Sova_.

## Installation

1. Download the latest release from [here](https://github.com/VoltCruelerz/pd-strings/releases)
2. Extract the zipped contents to `%APPDATA%/Local/sins2/mods/`, so that this file's path is `%APPDATA%/Local/sins2/mods/pd-strings/README.md`
3. Add/Update `enabled_mods.json`
    1. If you don't already have one, add an `enabled_mods.json` file to your `mods` directory. It should look like the below:
    2. If you do already have one, just add in the element to `mod_keys`.

### Example enabled_mods.json

```json
{
    "mod_keys": [
        {
            "name": "pd-strings",
            "version": 0
        }
    ]
}
```
