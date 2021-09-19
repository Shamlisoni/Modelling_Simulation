This folder zipped folder contains multiple zipped folder inside it, Please unzipe every thing befor starting.


--------------------------------------------------Folder OD_Car----------------------------------------------------------------------------


Folder named as simulation contains all the simulation related file which includes simulation for 3 streets(Mörfelder Landstrasse, Kennedyallee and Darmstädter Landstrasse)
It contains Origin Destination SuMO readable files with type OD File.
Traffic assignment zone file with an extention .taz are also mentioned. 
These two files are mentioned in the configuration file starting with the name "od2trips_"
This configuration file includes the OD file and Taz file to create trip files.

To generate the trip files and route files the command used are mentioned in the file named as : List_of_command_for_OD2trips_Duarouter.txt


--------------------------------------OD_Car\Simulation\Darmstaedter   OD_Car\Simulation\Kennedyallee  OD_Car\Simulation\Morfelder--------------------------------

The trip files for the respective streets are stored in the folder named as Simulation\Darmstaedter,Simulation\Kennedyallee,Simulation\Moerfelder.
The trips files are with extension ".odtrips"
Configuration File: duarcfg_file.trips2routes.duarcfg used to create route files.
This route file are with the extension ".odtrips.rou".
This folders also inclued the output files starting with name "tripinfo_" and "vehicle_" these are used for data anlysis as it includes the 
behaviour of the traffic participants during the simulation with respect to different attribute such waiting time, timeloss etc.

--------------------------------------OD_Car\Simulation --------------------------------

In the folder Simulation:
Route files for each of the street are stored with extension ".odtrips.rou" with their respective street name.
Network_File named as "Sachsenhausen_network.net" is also stored in this folder
SuMO Configuration file. There are three configuration file for each of the streets. Configuration starts with the name "osm_" and file type is "SUMOCFG"
Files starting with the name "edge_count_" contains the edge related output information which is generated after the simulation has succesfully ended.
These files were used to create map based output. If we restart the simulation these files get overwritten.



