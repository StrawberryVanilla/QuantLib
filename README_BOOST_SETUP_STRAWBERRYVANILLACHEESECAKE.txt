1- download boost: https://boostorg.jfrog.io/artifactory/main/release/1.85.0/binaries/
2- install Boost, eg in C:\local\boost_1_85_0_vc141
3- open Quantlib.sln in visual studio
4- open "Property manager" (View -> Other windows ->Property Manager)
5- in "Property manager", on QuantLib Project (not solution) select all configuration and right click then "Create new Property sheet"
6- Expand all configurations and select the PropertySheet in each one
7- right click Properties
8- in VC++ Directories->General->Include Directories add: C:\local\boost_1_85_0_vc141
9- in VC++ Directories->General->Library Directories add: C:\local\boost_1_85_0_vc141\libs
10- in C/C++->General->Additional Include Directories add: C:\local\boost_1_85_0_vc141\boost
10- in Linker->General->Additional Library Directories add: C:\local\boost_1_85_0_vc141\libs