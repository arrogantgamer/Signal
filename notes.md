
Possibilities:
 - make all block pushable
 - make non arrow blocks pushable by arrow blocks
 ( now we can "pull out" a non arrow block from behind a mesh )
 - entity types: a purple entity that can pass mesh
 - ability to steal entity types, or swap?
 - entity type: a digging entity, one that can swap with grey cells

Bugs:
I have an object called "neutralized" for drones that are trapped
by neighbour cells. This shouldn't be necessary: I would like to
have rules such that the remote controller can send moves to all
the drones, but the trapped ones don't respond.

For some reason, at the moment, different moves will be sent to
different drones.
