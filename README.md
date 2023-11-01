# OpenSourcePackagesCollector
Pre-build VI collecting packages names, version and licenses/copyright to feed this information into a About.vi (or any target VI)

This example is a pre-build VI to get all of the VIPM packages installed on the machine and extract open-source license copyright files.

## Requirements
- Any edition of VIPM 2023.3 or Pro edition of VIPM earlier than 2023.3

## Demonstration
[](https://github.com/NeosoftTechnologiesInc/OpenSourcePackagesCollector/assets/149504000/0b98dba9-40c4-4f43-a261-10d90820b914)

## Instructions
1. (#TODO1) In the block diagram, specify the target VI reference
2. (#TODO2) Specify the label name like this in the target VI
or change the string constant in the block diagram to make it the same as the constant label in the target VI
(Note: the constant must be 1D String Array)
3. (#TODO3) Replace the included control/indicator with your original control/indicator if you're using the pre-built VI template 
3. Set this VI as Pre Build in the project Build Specifications Properties (Pre/Post Build Actions -> Execute VI before build)

## NI Example
![ni example](https://github.com/NeosoftTechnologiesInc/OpenSourcePackagesCollector/assets/149504000/8a5cbe0b-e284-47e5-b76f-09be31b515a6)
