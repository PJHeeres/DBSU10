# DBSU10
Technologies for Connectivity 
Eindhoven University of Technology [TU/e]

## Group 1 - BPM HEARTRATE MODULE
### [Daan Heijsters] (https://github.com/daanheijsters), [Manisha Sethia] (https://github.com/manishas97), [Stijn van Geffen] (https://github.com/StijnvGeffen), [Pleun Heeres] (https://github.com/PJHeeres)
This repository is meant for collaborators that want to use a heartbeat sensing module for connected products.

## MODULE CONCEPT
The module does not only constantly sent heartbeat data. It makes more sense of data by sending useful data for different purposes.
Following are some Input (BPM) related to some more useful ranges per topic:

|INPUT RANGE|OUTPUT USEFUL||Group 2|Group 3|Group 4|Group 5|Group 6|Group 7|
|------|------|
|<0    | Dead | 
|0-30  | Critial health issue  | 
|30-50 | Sleeping  |
|50-80 | Sad or Inactive   | 
|80-100| Passive nuteral    |
|>100  | Physically active |
