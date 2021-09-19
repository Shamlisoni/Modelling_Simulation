

---------------------------Folder Emergency_Vehicle -------------------------------------


It Contains three zipped folders Priority_withdynamicdistance,Priority_withFixeddistance,Withoutpriority. Please unzip all the folders.


Folder Withoutpriority : It contains folder named as Output: which contains all the output for the scenarios tested under the case scenario without priority and without priority with closed lane.
It also contains all the route files for all the three streets with an extension "odtrips.rou".
It also contains the trips files for ambulance whose behaviour are monitered od_file_ambulance.odtrips and od_file_ambulance1.odtrips. Due to the crashing of memory two ambulance files are prepared.
Network file with the name Sachsenhausen_network.net is also found.

induction_loop.det : Induction loop file which is not used here but used in other case scenarios.

osm_withoutpriority and osm_withoutpriority1 are the configuration files used analyze behaviour of EV present in the file od_file_ambulance.odtrips and od_file_ambulance1.odtrips respectively.
osm_withoutpriority1_closedlane,osm_withoutpriority1_closedlane and osm_withoutpriority_closedlane are the configuration files used analyze behaviour of EV present in the file 
od_file_ambulance.odtrips and od_file_ambulance1.odtrips respectively.


---------------------------------------------------Folder Priority_withFixeddistance-------------------------------------------

It contains folder named as Output: which contains all the output for the scenarios tested under the case scenario without priority and without priority with closed lane.
It also contains all the route files for all the three streets with an extension "odtrips.rou".
It also contains the trips files for ambulance whose behaviour are monitered od_file_ambulance.odtrips and od_file_ambulance1.odtrips.
Network file with the name Sachsenhausen_network.net is also found.

induction_loop.det : Induction loop file which is not used here but used in other case scenarios.

osm_fixeddistance is the configuration files used analyze behaviour of EV present in the file od_file_ambulance.odtrips.
osm_fixeddistance_CL is the configuration files used analyze behaviour of EV present in the file 
od_file_ambulance.odtrips.

To run the configuration file python script "Traci_Traffic_light_fixed_distance" is suppose to be run in command line. For all the simulation files python script is executed one by one
and the configuration filename
is suppose to be changed in the python script for every run.



---------------------------------------------------------------Folder Priority_withdynamicdistance-------------------------------------

It contains folder named as Output: which contains all the output for the scenarios tested under the case scenario without priority and without priority with closed lane.
It also contains all the route files for all the three streets with an extension "odtrips.rou".
It also contains the trips files for ambulance whose behaviour are monitered od_file_ambulance.odtrips and od_file_ambulance1.odtrips. Due to the crashing of memory two ambulance files are prepared.
Network file with the name Sachsenhausen_network.net is also found.

induction_loop.det : Induction loop file which is used here.

osm_trafficlight and osm_trafficlight1 are the configuration files used analyze behaviour of EV present in the file od_file_ambulance.odtrips and od_file_ambulance1.odtrips respectively.
osm_trafficlight_CL is the configuration files used analyze behaviour of EV present in the file 
od_file_ambulance.odtrips and od_file_ambulance1.odtrips respectively.

To run the configuration file python script "Traci_Traffic_light" is suppose to be run in command line. For all the simulation files python script is executed one by one
and the configuration filename
is suppose to be change in the python script.




