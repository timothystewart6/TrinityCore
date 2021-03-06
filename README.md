# Trinity Core 3.3.5a with NPC Bots and Extras

## New NPC Bots Source by thanosdk

For more informations please go here: [thesawolf New NPC Bots Readme](https://github.com/thesawolf/TrinityCore/blob/TrinityCoreLegacy/README_Bots.md)

## Trinity Core

This source is based on [TrinityCore Revision 330e5b0](https://github.com/TrinityCore/TrinityCore/commit/330e5b0ebcc6753a355afc3824121c5eba1bf5bc)

## New NPC Bots Source from martin26

 * NPC Bots
 * AH Bot

With [NewNPC Bots f7936eb9](https://github.com/martin26/NewNPCBots/commit/f7936eb9ea332c45146c59810f7d0d6bd3313308)

## Lord Psyan Patches
With [Lord Psyan Patches](https://bitbucket.org/technotim/lordpsyan-patches)

* Start Guild
* Auto Learn New Spells
* Annouce Login
* Account Mounts
* Login BoA
* Start Guild

## SQL Scripts

### world_db
You will need to use [TDB 335.61](https://github.com/TrinityCore/TrinityCore/releases/tag/TDB335.61)

Not sure this is necessary but here is the order in which to apply database scripts:

* create
* base
* world (full, above)
* updates
* custom

### custom
Included in `sql/custom`

* Portal Master [rochet2](http://rochet2.github.io/Portal-Master.html)
* Reforging NPC [rochet2](http://rochet2.github.io/Reforging.html)
* Transmogrification NPM [rochet2](http://rochet2.github.io/Transmogrification.html)

## Build
[Windows Requirements](https://trinitycore.atlassian.net/wiki/spaces/tc/pages/10977296/Windows+Requirements
)

* Visual Studio 2017 (x64)
* Boost 1.63.0 (x64)
* MySQL 5.6.37.0 (x64)
* CMake 3.9.1 (x64)
* OpenSSL 1.0.2L (x64)


