# Buildings

This document lists all the buildings available in the game, their
properties, perks and constraints.

## C&C - Command & Control

Must be present on the station. Destruction of this building
means that the station becomes inoperational, and directly fails
the game.

* Size: 3x2
* Required Personnel: 3
* Cost: 25.0 (high)
* Maintenance Costs: 5.0/month (medium)
* Health: 1000 (very high)
* Power Usage: 100 (high)

## Power Core

Provides electricity for the station. Can be built multiple times
for redundancy and to satisfy the station's energy consumption.

* Size: 3x3
* Required Personnel: 1
* Const: 60.0 (high)
* Maintenance Costs: 5.0/month (medium)
* Health: 500 (high)
* Power Usage: 0
* Power Production: 10000

## Cargo Bay

Allows cargo ships to dock at the station. Ships can refuel or get repairs
which generates money for the station. Customs tax may also generate income.

Only as many ships as there is personnel managing the building can dock at
the same time. Each ship docks for random amount of game-time.

* Size: 5x5
* Minimum Personnel: 1
* Max Personnel: 5
* Cost: 70.0 (high)
* Maintenance Costs: 7.0/month (high)
* Health: 500 (high)
* Power Usage: 700 (high)
* Income: random per ship

## Shuttle Bay

Allows shuttles with passangers to dock at the station. Ships can refuel or get
repais which generates money for the station. Passangers may embark on another
shuttle or stay on the station, if there's enough accommodation capacity. Staying
passengers/visitors tend to generate more money for the station form accommodation
costs and hazard tax.

Only as many shuttles as there is personnel managing the building can dock at
the same time. Each shuttle docks for a random amount of game-time.

* Size: 5x5
* Minimum Personnel: 1
* Max Personnel: 5
* Cost: 70.0 (high)
* Maintenance Costs: 7.0/month (high)
* Health: 500 (high)
* Power Usage: 700 (high)
* Income: random per ship

## Living Quarters (class C)

Basic living quarters. Allows personnel and visitors to live on the station. The quarters
can be designated to be for use by the station personnel. Such quarters do not generate
any income. No more personnel can be hired if there's not enough quarters designated for
personnel. No more guests can be accommodated if there are no free visitor quarters available.

* Size: 1x1
* Designation: personnel/visitors
* Max capacity: 1 person
* Cost: 20.0 (low)
* Maintenance Costs: 2.0/month (low)
* Health: 100 (low)
* Power Usage: 100 (low), only when used
* Income: personnel - none, visitors - player defined (default 2.0)
 

## Living Quarters (class B)

Medium-quality quarters. Same rules as for Class C apply.

* Size: 2x1
* Designation: personnel/visitors
* Max capacity: 2 persons
* Cost: 40.0 (low)
* Maintenance Costs: 3.0/month (low)
* Health: 200 (low)
* Power Usage: 200 (low), only when used
* Income: personnel - none, visitors - player defined (default 4.0)

## Living Quarters (class A)

High-quality quarters. Same rule as for Class C apply.

* Size: 2x2
* Designation: personnel/visitors
* Max capacity: 4 persons
* Cost: 60.0 (low)
* Maintenance Costs: 5.0/month (medium)
* Health: 300 (low)
* Power Usage: 300 (low), only when used
* Income: personnel - none, visitors - player defined (default 6.0)

## Station Security

Office for station security. Requires Chief of Security to be in the personnel.

* Size: 2x1
* Cost: 20.0 (medium)
* Maintenance Costs: 6.0/month (medium)
* Health: 300 (low)
* Power Usage: 600 (high)


