# HexaLeafs

## Description

We like hexagons and blinky lights.
So we thought, why not combine the two?

So we created a PCB in the shape of a hexagon with 6 LEDs on it.
The LEDs are controlled by wled, so you can control them via wifi.

## Design Records

There are many ways to design such a PCB.

We asked ourselves some questions and answered them with the following design decisions:

### Why hexagon?

Hexagons are bestagon ;)

### How To Connect The PCBs?

Here we had a lot discussions.

There were many ideas like pogo pins with magnets, spring loaded connectors, or even a custom connector with an extra PCB similar to Nanoleafs.

We asked ourselves what will be the typical use case for this PCB.
We came to the conclusion that the typical use case will be to put them on a wall or a ceiling and that the pattern of the connected PCBs will not change very often.

The connection should be easy to use and easy to connect and disconnect.

We also wanted to keep the cost low.
So we decided to use a simple 4-pin connector with a pitch of 2.54mm which are SMD soldered to the PCB.

