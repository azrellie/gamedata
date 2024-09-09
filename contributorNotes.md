# notes for contributors of this repository

## cites.json
1. the **stateAbbrev** can also be the abbreviation of the province/territories and not just american states
2. hdi for american cities (per county) can be found at this website: https://communityhdi.org/#3.97/39.9/-119.38

## volcanoes.json
1. exclude things like "mt" and such from the names of volcanoes to keep names consistent and shorter
2. volcanoes with negative elevations (whether its underwater or not) are accepted for the **summitFeet** property

## faultLines.json
1. fault lines can have the same color for visualization purposes, but they cannot next to each other
2. when adding fault lines, remember to deeply inspect the landscape to find any geological remarks of a fault line being present so the points defined are accurate
3. the currently registered fault types are strike slip, subduction zone, oblique normal, oblique reverse, oblique thrust, reverse, normal, rift, transform, continental convergent boundary

## httpData.json
1. this file is updated by the game server and should not be touched unless necessary

## contributorNotes.md
1. notes for each file mentioned should only be updated to serve as reminders for when updating the specified file
