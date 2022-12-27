# xep-vibration-data

Each week, create a new folder for adding week's Vibration Data Files and Machine Status Files \
example:
#### Folder name:  week_20112022_26112022 
     vibrationdata_20112022_26112022.csv 
     machinestatus_20112022_26112022.csv  
                     
## Vibration Data Files
New data is pushed to GitHub every week <br>
File name format: example – vibrationdata_20112022_26112022.csv <br>
#### CSV file format:
     Timestamp, SensorID, other sensor data... 
     Timestamp - utc time epoch data received

## Machine Status Files
New data is pushed to GitHub every week <br>
File name format: example – machinestatus_20112022_26112022.csv <br>
#### CSV file format :
    Timestamp, UID, machine1, machine2...
    Timestamp - utc time epoch data received
    UID: Sensor ID
    machine1 - machine 1 running status
    Type of status
        1 - running
        0 - not running
       -1 - unknown
       ‘ ‘ - It is not a data related to machine

 

