# CA216 CPU Scheduling


This is the second assignment for the CA216 Operating Systems Module.

The video for the additional questions: https://www.youtube.com/watch?v=XqvWtJqCdak&ab_channel=ZubairAsif

## Files
This repo contains 5 main python files:

 - schedule_fcfs.py
 - schedule_sjf.py
 - schedule_priority.py
 - schedule_rr.py
 - functions .py

The schedule files contain the print formatting individual to each algorithm and file handling. Whilst, all sorting and list manipulation etc. is handled in the functions file.



## How to Run
In order to run an algorithm you would have to decided on which testfile you want to test with. For this example I will use schedule.txt.

You need to run python followed by the name of the python program followed by the test file.

> python3 pythonfile testfile

If you would want to run the FCFS algorithm, it would be as follows:

    python3 schedule_fcfs.py schedule.txt