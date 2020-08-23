# Data Acquisition

## Feature
Display the gathered information in desired format and on desired media.

## Acceptance Criteria
Provided that acquired data is in sharable and manifest.

### Scenario: Display the required information

  Given : We have information from different sources in its supported format

  When : User wants to view data on desired media

  Then : Check whether the data format supports the desired media or not
         if True: Download and open the file
         else: Display message "Unsupportd Media"
                       OR
         else: Convert the data format to adapt the desired media(Use conversion methods like online web sevices)
                       
          

