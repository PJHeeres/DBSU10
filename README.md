# DBSU10
Technologies for Connectivity 
Eindhoven University of Technology [TU/e]

## Group 1 - BPM HEARTRATE MODULE
### Daan Heijsters (https://github.com/daanheijsters), Manisha Sethia (https://github.com/manishas97), Stijn van Geffen (https://github.com/StijnvGeffen), Pleun Heeres (https://github.com/PJHeeres)
This repository is meant for collaborators that want to use a heartbeat sensing module for connected products.

## MODULE CONCEPT
The module does not constantly sent heartbeat data. It makes more sense of data by sending useful data for different purposes. 
Following are some Input (BPM) related to some more useful ranges per topic. Also the relevance in our opinion to other groups is mapped.

|INPUT RANGE|OUTPUT USEFUL|Group 2 Caffee|tag|Group 3 Pizza|tag|Group 5 Bodytemp|tag| Group 7 Clock|tag| Other Groups | tag|
|------| ------|------ | ------|------|------|------|------|-------|------ | ------|------|
|<0    | Dead  | Coffee would not help  | - |Pizza will maybe cheer up loved ones| - | Heartrate  |...bpm | Dead, might schedule funeral| Heartrate |...bpm |
|0-30  | Critial health issue  | Call 112 instead of coffee  |- | Call 112 instead of pizza  | - | Heartrate |...bpm | Critial health issue   | Heartrate |...bpm  |
|30-50 | Sleeping  | Wait for a while, coffee needed soon   | sleeping  |Pizza as breakfast? | sleeping  |Heartrate  |...bpm | Sleeping | sleeping  |Heartrate  |...bpm  | 
|50-80 | Sad or Inactive   | Coffee needed | inactive   | Need some pizza to cheer you up?   | sad   |Heartrate   |...bpm | Passive  | passive   |  Heartrate |...bpm |
|80-100| Passive  | Coffee needed  | neutral |  Pizza time? | mad |Heartrate |...bpm | No Activity | no activity |Heartrate  |...bpm |          
|>100  | Physically active | Might skip that coffee | active   |Jeej pizzaparty  | happy |Heartrate |...bpm | Activity | activity|Heartrate |...bpm   |
