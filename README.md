# SignalScope shared map

This repository holds the data behind SignalScope's shared map of detected
surveillance devices. The SignalScope app reads it; nothing here is meant to
be edited by hand.

- `index.json` lists the one-degree squares that have anything in them.
- `cells/` holds one file per square.

Each entry is a rounded position, the kind of device and its maker, how many
people reported it, and the first and last day it was reported. Nothing that
identifies who sent a report is published.

The files are rebuilt automatically, so changes made here are overwritten.
