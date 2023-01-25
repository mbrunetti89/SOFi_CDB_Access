# SOFi_CDB_Access

SOFi_CDB_Access allows a direct access to the SOFiSTiK CDB from Grasshopper. Data as geometry, loads, forces, displacement and design results can be accessed from Grasshopper. This can be combined with the SOFiSTiK plug-in in order to send data back and forth between Grasshopper and SOFiSTiK.
It allows generating iterative processes and calculations in order to optimize structures. 
This plug-in has been developed for personal use, the author doesn't assume any liability. It is not an official SOFiSTiK plug-in

PREREQUISITES

The plug-in works with Rhino 6. It works for each SOFiSTiK version, but needs SOFiSTiK 2020 to be installed. 

INSTALLING

Install the components by dragging & dropping the assembly SOFi_CDB_Access.gha into the Grasshopper window. In some cases the Plug-in needs to be unblocked under properties.

EXAMPLES

Some examples are shown in the folder "Examples". Download the .cdb file and open the .3dm and the .gh files, more detailed instructions are given in Examples.gh file. Some visualization examples have been added in the latest update.

AUTHOR

Matteo Brunetti
ing.brunettimatteo@gmail.com

UPDATE 25/05/2021

1) GetSIR - bug fixed:  In the past the task returned correct SIRs only if each cut was generated with an unique number. With this update all SIRs are recognized, also with same beam number.

2) GetDisplacement - bug fixed:		With this update GetDisplacement works also in load cases where some groups are turned off.

3) GetBeamReinf - new task:   Returns the reinforcement results for the chosen design load case.

UPDATE 25/01/2022

1) New tasks

2) Bug fixes
