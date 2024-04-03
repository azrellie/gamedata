# notes for contributors of this repository

## cites.json
1. the **stateAbbrev** can also be the abbreviation of the province/territories and not just american states

## volcanoes.json
1. exclude things like "mt" and such from the names of volcanoes to keep names consistent and shorter
2. volcanoes with negative elevations (whether its underwater or not) are accepted for the **summitFeet** property

## faultLines.json
1. ***(TEMPORARY)*** fault lines can only be added by the owner of this repository since the owner is the only one who is able to edit the game and add colors for the fault lines for visualization purposes
2. when adding fault lines, remember to deeply inspect the landscape to find any geological remarks of a fault line being present so the points defined are accurate

## httpData.json
1. this file is updated by the game server and should not be touched unless necessary
