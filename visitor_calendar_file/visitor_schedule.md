##Filename
visitor_schedule.csv

## Schema Summary
Contains history of visitor schedule and how the collected is being studied

|HUH Header  | Data Type | Emu Header |  Descriptor | Rule | Notes|
|:------------- |:------------- |:------------- |:------------- |:------------- |:------------- | 
| date_start | DATE | Waiting | Date arrived |
| date_end  | DATE | Waiting | Departure date |
| duration of visit (day)  | INT | Waiting | Departure date - date arrived = days of stay|
| name  | TEXT | Waiting | Visitor Name| |
| institution | TEXT | Waiting | Location of work or employer|
| acronym  | TINYTEXT| Waiting | Code for location of work or employer|
| areaofstudy | TEXT | Waiting | What group will be study|
| supervisor   | TINYTEXT | Waiting | Person looking over the visitor|
| destructive_sampling | Yes/No | Waiting | Asked to remove material|
| imaging_form  | Yes/No| Waiting | Asked to capture images|
| s/p | TINYTEXT | Waiting | Student and/or professional|
| notes  | TEXT | Waiting | Internal notes about the visitor|




