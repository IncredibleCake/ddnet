ZMod
----

Z stands for Z as depth, along with X and Y 2D coordinates, and Zones, the initial big change.


CHANGELOG
---------
* Empty

PLANNED TASKS
-------------
* Make a clear map context
    * A map object - representing the file
    * A world object - representing the world. Map is used to built it, characters, projectiles, rules, etc, are used to animate it
    * Onto this world object will be attached everything that will be called on Tick(), and everything that can change its state, the idea being that this single object covers a Tee World
    * In clients : tees are nothing but tees with name, as the server intends to show them (?)
* Change the way map layers content is accessed (no more indexes, iterators)
* Make UI simpler, maybe with separate script : clear label, button classes, etc.
* Introduce zones - keeping everything compatible, see ZONES
* Adding simple map objects
* Introduce a new map format, with native zones support. Previous maps still being supported, see MAP
* Adding support for higher level protocol messages
    * Better time support : sometimes the clock shouldn't be seen
    * Better leaderboard, server is free to display what it wants

MAP & ZONES
-----------

TODO

