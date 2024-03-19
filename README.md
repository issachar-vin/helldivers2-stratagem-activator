# Stratagen Activator

## Prerequisites
- Windows
- Python 3.12
- pipenv
- Ability to run Makefiles on Windows (Recommend chocolatey to install make)

## How to use

### Compiling
Clone the repo locally and run make build

---

### Running app
There will be a `stratagems.exe` in the `dist/` folder. Store the exe and the config folder together where ever you like and add the parent folder to windows PATH. If you don't wanto to do that, you can use the absolute path to the exe. Run the exe with a parameter that is the name of the strategem you want activated. you can find the names for all strategemss in the `dist/codes.json` file or down below.

Example:
```
stratagen resupply
```
---
### Using with the Razer Stream Controller/Loupedeck

Setup a custom run action and use two pipe characters ( || ) between the app name and the stratagen name.

Example:
```
stratagems.exe || resupply
```
---
### Customizing keybindings
Change values for each key in `config/.env` file.

You can also change the delay between key presses.

---
## Strategems
| Engineering Bay          | Patriotic Administration Center| General Stratagems    | Robotics Workshop             | Orbital Cannons           | Hanger                   | Suits                     |
|--------------------------|----------------------|-----------------------|-------------------------|---------------------------|--------------------------|--------------------------|
| jump_pack                | machine_gun          | reinforce             | hmg_emplacement         | orbital_gatling_barrage   | eagle_strafing_run       | patriot_exosuit          |
| supply_pack              | antimaterial_rifle   | sos_beacon            | shield_generator        | orbital_airburst_strike   | eagle_airstrike          |                          |
| guard_dog_rover          | stalwart             | resupply              | tesla_tower             | orbital_120mm_barrage     | eagle_cluster_bomb       |                          |
| ballistic_shield         | expendable_anti_tank | hellbomb              | antipersonnel_minefield | orbital_380mm_barrage     | eagle_napalm_airstrike   |                          |
| shield_generator_pack    | recoilless_rifle     | sssd_delivery         | incendiary_mines        | orbital_walking_barrage   | eagle_smoke_strike       |                          |
| guard_dog                | flame_thrower        | seismic_probe         | machine_gun_sentry      | orbital_laser             | eagle_110mm_rocket_pods  |                          |
|                          | autocannon           | upload_data           | gatling_sentry          | orbital_railcannon_strike | eagle_500kg_bomb         |                          |
|                          | railgun              | illumination_flare    | mortar_sentry           | orbital_precision_strike  | eagle_rearm              |                          |
|                          | spear_launcher       |                       | autocannon_sentry       | orbital_gas_strike        |                          |                          |
|                          | grenade_launcher     |                       | rocket_sentry           | orbital_ems_strike        |                          |                          |
|                          | laser_cannon         |                       | ems_mortar_sentry       | orbital_smoke_strike      |                          |                          |


## DirectX Key Codes
| Hex | Dec | Label |
|-----|-----|--------|
| 0x01 | 1 | Escape |
| 0x02 | 2 | 1 |
| 0x03 | 3 | 2 |
| 0x04 | 4 | 3 |
| 0x05 | 5 | 4 |
| 0x06 | 6 | 5 |
| 0x07 | 7 | 6 |
| 0x08 | 8 | 7 |
| 0x09 | 9 | 8 |
| 0x0A | 10 | 9 |
| 0x0B | 11 | 0 |
| 0x0C | 12 | Dash(Minus) / Underscore |
| 0x0D | 13 | Equals / Plus |
| 0x0E | 14 | Backspace |
| 0x0F | 15 | Tab |
| 0x10 | 16 | Q |
| 0x11 | 17 | W |
| 0x12 | 18 | E |
| 0x13 | 19 | R |
| 0x14 | 20 | T |
| 0x15 | 21 | Y |
| 0x16 | 22 | U |
| 0x17 | 23 | I |
| 0x18 | 24 | O |
| 0x19 | 25 | P |
| 0x1A | 26 | Left Brace |
| 0x1B | 27 | Right Brace |
| 0x1C | 28 | Enter |
| 0x1D | 29 | Left Ctrl |
| 0x1E | 30 | A |
| 0x1F | 31 | S |
| 0x20 | 32 | D |
| 0x21 | 33 | F |
| 0x22 | 34 | G |
| 0x23 | 35 | H |
| 0x24 | 36 | J |
| 0x25 | 37 | K |
| 0x26 | 38 | L |
| 0x27 | 39 | Semicolon / Colon |
| 0x28 | 40 | Apostrophe / Doublequote |
| 0x29 | 41 | Backquote / Tilde |
| 0x2A | 42 | Left Shift |
| 0x2B | 43 | Backslash / Pipe |
| 0x2C | 44 | Z |
| 0x2D | 45 | X |
| 0x2E | 46 | C |
| 0x2F | 47 | V |
| 0x30 | 48 | B |
| 0x31 | 49 | N |
| 0x32 | 50 | M |
| 0x33 | 51 | Comma / Left Bracket |
| 0x34 | 52 | Period / Right Bracket |
| 0x35 | 53 | Slash / Question Mark |
| 0x36 | 54 | Right Shift |
| 0x37 | 55 | Keypad Asterisk |
| 0x38 | 56 | Left Alt |
| 0x39 | 57 | Spacebar |
| 0x3A | 58 | Caps Lock |
| 0x3B | 59 | F1 |
| 0x3C | 60 | F2 |
| 0x3D | 61 | F3 |
| 0x3E | 62 | F4 |
| 0x3F | 63 | F5 |
| 0x40 | 64 | F6 |
| 0x41 | 65 | F7 |
| 0x42 | 66 | F8 |
| 0x43 | 67 | F9 |
| 0x44 | 68 | F10 |
| 0x45 | 69 | Num Lock |
| 0x46 | 70 | Scroll Lock |
| 0x47 | 71 | Keypad 7 |
| 0x48 | 72 | Keypad 8 |
| 0x49 | 73 | Keypad 9 |
| 0x4A | 74 | Keypad Dash(Minus) |
| 0x4B | 75 | Keypad 4 |
| 0x4C | 76 | Keypad 5 |
| 0x4D | 77 | Keypad 6 |
| 0x4E | 78 | Keypad Plus |
| 0x4F | 79 | Keypad 1 |
| 0x50 | 80 | Keypad 2 |
| 0x51 | 81 | Keypad 3 |
| 0x52 | 82 | Keypad 0 |
| 0x53 | 83 | Keypad Dot(Period) |
| 0x57 | 87 | F11 |
| 0x58 | 88 | F12 |
| 0x9C | 156 | Keypad Enter |
| 0x9D | 157 | Right Control |
| 0xB5 | 181 | Keypad Slash(Divide) |
| 0xB8 | 184 | Right Alt |
| 0xC7 | 199 | Home |
| 0xC8 | 200 | Up Arrow |
| 0xC9 | 201 | PgUp |
| 0xCB | 203 | Left Arrow |
| 0xCD | 205 | Right Arrow |
| 0xCF | 207 | End |
| 0xD0 | 208 | Down Arrow |
| 0xD1 | 209 | PgDown |
| 0xD2 | 210 | Insert |
| 0xD3 | 211 | Delete |
