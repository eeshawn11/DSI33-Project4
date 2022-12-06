## Data Dictionary

| **Feature**            	| **Type** 	| **Dataset**              	| **Description**                                                                         	|
|------------------------	|----------	|--------------------------	|-----------------------------------------------------------------------------------------	|
| Id                     	| int      	| `train.csv` & `test.csv` 	| ID number of the record                                                                 	|
| Date                   	| object   	| `train.csv` & `test.csv` 	| Refers to the date the West Nile Virus test is performed                                	|
| Address                	| object   	| `train.csv` & `test.csv` 	| The approximate address of the location of trap; sent to GeoCoder                       	|
| Species                	| object   	| `train.csv` & `test.csv` 	| The mosquito species in trap                                                            	|
| Block                  	| int      	| `train.csv` & `test.csv` 	| Refers to block number of address                                                       	|
| Street                 	| object   	| `train.csv` & `test.csv` 	| Refers to street of address                                                             	|
| Trap                   	| object   	| `train.csv` & `test.csv` 	| ID number of the trap                                                                   	|
| AddressNumberAndStreet 	| object   	| `train.csv` & `test.csv` 	| The approximate address retrieved from GeoCoder                                         	|
| Latitude               	| float    	| `train.csv` & `test.csv` 	| The latitude retrieved from GeoCoder                                                    	|
| Longitude              	| float    	| `train.csv` & `test.csv` 	| The longitude retrieved from GeoCoder                                                   	|
| AddressAccuracy        	| int      	| `train.csv` & `test.csv` 	| The accuracy of information returned from GeoCoder                                      	|
| NumMosquitos           	| int      	| `train.csv` & `test.csv` 	| The number of mosquitoes in the trap                                                    	|
| WnvPresent             	| int      	| `train.csv` & `test.csv` 	| Whether or not West Nile Virus is present in these mosquitoes (1 = present; 0 = absent) 	|
| Date                   	| object   	| `spray.csv`              	| The date of spray                                                                       	|
| Time                   	| object   	| `spray.csv`              	| The time of spray                                                                       	|
| Latitude               	| float    	| `spray.csv`              	| Latitude of spray                                                                       	|
| Longitude              	| float    	| `spray.csv`              	| Longitude of spray                                                                      	|
| Station                	| int      	| `weather.csv`            	| Refers to the weather station (1 or 2)                                                  	|
| Date                   	| object   	| `weather.csv`            	| Refers to the date of measurement                                                       	|
| Tmax                   	| int      	| `weather.csv`            	| Maximum daily temperature (Degrees Fahrenheit)                                          	|
| Tmin                   	| int      	| `weather.csv`            	| Minimum daily temperature (Degrees Fahrenheit)                                          	|
| Tavg                   	| object   	| `weather.csv`            	| Average daily temperature (Degrees Fahrenheit)                                          	|
| Depart                 	| object   	| `weather.csv`            	| Departure from normal temperature (Degrees Fahrenheit)                                  	|
| Dewpoint               	| int      	| `weather.csv`            	| Average dew point (Degrees Fahrenheit)                                                  	|
| WetBulb                	| object   	| `weather.csv`            	| Average wet bulb (Degrees Fahrenheit)                                                   	|
| Heat                   	| object   	| `weather.csv`            	| Heating degree days                                                                     	|
| Cool                   	| object   	| `weather.csv`            	| Cooling degree days                                                                     	|
| Sunrise                	| object   	| `weather.csv`            	| Time of sunrise (calculated, not observed)                                              	|
| Sunset                 	| object   	| `weather.csv`            	| Time of sunset (calculated, not observed)                                               	|
| CodeSum                	| object   	| `weather.csv`            	| Code of weather phenomena                                                               	|
| Depth                  	| object   	| `weather.csv`            	| Depth of snow on the ground (M = Missing data)                                          	|
| Water1                 	| object   	| `weather.csv`            	| Water equivalent (M = Missing data)                                                     	|
| SnowFall               	| object   	| `weather.csv`            	| Snowfall (inch) (M = Missing data, T= Trace)                                            	|
| PrecipTotal            	| object   	| `weather.csv`            	| Total daily rainfall (inch)                                                             	|
| StnPressure            	| object   	| `weather.csv`            	| Average atmospheric pressure (inch Hg)                                                  	|
| SeaLevel               	| object   	| `weather.csv`            	| Average sea level pressure (inch Hg)                                                    	|
| ResultSpeed            	| float    	| `weather.csv`            	| Resultant wind speed (mph)                                                              	|
| ResultDir              	| int      	| `weather.csv`            	| Resultant wind direction (Degrees)                                                      	|
| AvgSpeed               	| object   	| `weather.csv`            	| Average wind speed (mph)                                                                	|
