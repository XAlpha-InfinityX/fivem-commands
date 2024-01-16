# Add-On Resources

## Gameplay

### FivePD

[Link](https://fivem-mods.net/fivepd/)

FivePD adds a gamemode allowing players to immerse themselves in the world of law enforcement by roleplaying as a police officer. It draws inspiration from the popular single-player mod [LSPDFR](https://www.lcpdfr.com/lspdfr/index/).

With FivePD:
- You can conduct traffic stops
- Apprehend suspects
- Respond to 911 emergencies
- And much more

Additional plugins for FivePD can be found [here](https://github.com/topics/fivepd).

## Car Scripts

### Luxart Vehicle Control

[Link](https://docs.luxartengineering.com/)
[Github](https://github.com/TrevorBarns/luxart-vehicle-control)

Luxart Vehicle Control v3 is a police vehicle lighting system similar to ELS modeled after real siren controllers.

It includes:
- Small togglable HUD modeled after a real siren controller
- Siren assignments for cars so that different departments may have different siren setups
- ELS style hotkeys utilizing numrow
- Adjustable primary/secondary and auxiliary tones
- And more

Note: ELS vehicles DO NOT work with LVC.

### bmwg20uELS

[Link](https://www.lcpdfr.com/downloads/gta5mods/vehiclemodels/46162-unmarked-2020-bmw-3-series-g20-nonelselsfivem/)

A generic and fictional 2020 BMW 3 series G20 configured for FiveM.

## User Interface (UI)

### SimpleHUD

[Link](https://forum.cfx.re/t/updated-simplehud-dojrp-based-location-display-hud/4775936)
[Github](https://github.com/Andyyy7666/SimpleHUD)

A simple HUD featuring:
- Player location display
- Time display
- Speedometer
- AOP display
- Priority status
- Money display (you can add money from any framework if you know how)
- Fuel display (turns blue for electric vehicles)

### RageUI

[Link](https://forum.cfx.re/t/canceled-lua-rageui/931651)
[Github](https://github.com/ImBaphomettt/RageUI)

RageUI is a library giving developers the ability to create menus similar to the one of GTA Online. It is required for many other menu-based resources, such as vMenu.

### vMenu

[Link](https://docs.vespura.com/vmenu)
[Github](https://github.com/TomGrobbe/vMenu)

vMenu is a custom server-side trainer/menu. It gives server owners full permissions support.

Features include:
- Player options like god mode, heal, wanted level, etc.
- Advanced multiplayer character customization, saving, and spawning
- Vehicle options, including saving cars
- Miscellaneous features and settings including developer tools
- Full permissions and configuration support

## Development

### oxmysql

# Default Resources

### mapmanager

### chat

### spawnmanager

### sessionmanager

### basic-gamemode

### hardcap

### rconlog

# Personal Resources

# Others

## Databases

### MySQL/MariaDB

Our server uses a MySQL-forked database called MariaDB. 
- MySQL is a free relational database management system (RDBMS). As the name implies, it is a SQL-based database using tables to store relational and structured data.
- MariaDB is a fork of the MySQL database with the intention to remain open-sourced and free. It as developed after MySQL was acquired by Oracle Corp.

### SQLite

As mentioned above, our server also connects to a SQLite database separate from MariaDB in order to smoothly integrate the FivePD resource.
- SQLite is a small, fast, self-contained SQL database engine which requires zero-configuration and runs serverless. It's useful as an embedded database that may ship with a desktop application that only needs a simple abstraction around a file.