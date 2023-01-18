
# This is a timetracking app written entirely in bash

### Install
Run: `source install.sh`
This will create the functions in your .*rc-file.

### Uninstall
The functions can be removed again by calling `source uninstall.sh`.

### How it works

Calling `checkin` will create a new entry to the 





### Usage:
* Calling `checkin` will create a new entry to the table.

* Calling `checkout` will stamp the 'end' column with the current 
time.

* Calling `daily` will print the last 10 rows of the daily timetable.

* Calling `weekly` will generate a report with a summation of worked hours per 
week and an overview of surplus/deficit hours.
