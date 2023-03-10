# NV5 Coding Exercise

This goal of this exercise is to give us insight into your coding process.  It's designed to hopefully take no more 
than a couple of hours.

## Instructions

Two CSVs are provided. buildings.csv contains the locations of the 30 tallest buildings in Portland, from Wikipedia. queries.csv contains a set of locations around Portland that were chosen at random. All dimensions are in feet.

Write a C# program that reads buildings.csv and queries.csv. For each location in queries, output the name of the building point that is closest in 2D. Create and use class definitions wherever appropriate. 

You may use any version of .NET you wish. Please provide source code for either a command line application which accepts the two file paths as arguments or a WinForms GUI.

## Bonus tasks

Although it's not required, feel free to add whatever additional functionality you wish.  Some ideas:

- Return additional information about the closest building
- Return all buildings within a user-specified distance from the query location, ordered from tallest to shortest
- Give the option to calculate distances in 3D
- Plot the heights of the buildings
