# Worktracker
WorkTracker is a set of GUI's used in a welding shop. Together these GUI's 
collect data, write that data to a .txt file, turn .txt file into a .xlsx
file, and finaly syncs between machines. I am sure to an experienced developer
this is crude and hacked together, it is. However it works and I am still
working on it. If you awould like to sugest any changes pleas feel free to 
contact me.


## VSM
The VSM GUI collects input from a welder out in a shop. That data is appended 
to a .txt file for use lator by txt2x. To use VSM you will need to change into
the directory where it is located `cd /Worktracker/WorkTracker/` then `./vsm`.


## TXT2X
TXT2X turns the .txt file into a .xlsx file. This will not turn any text
document into a spreadsheet. It is designed just to work with .txt files
produced by VSM. To use change into the directory where it is located
`cd /Worktracker/WorkTracker/` then enter `./txt2x`.

## Plasma
Plasma is for the plasma table operator. It takes input from the user and 
stores to a .txt file. To use change into the directory where it is located
`cd /Worktracker/WorkTracker/` then enter `./plasma`.

