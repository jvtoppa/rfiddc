              -x-

RFID Data Compiler

              -x-

Sorts CSV files created by RFID tech according to specific filters that can be set by the user.

INSTRUCTIONS:

To execute the program you need to run "RFIDDC.exe", which is located in the main folder.
1. Click on browse to choose the input and output folders. 
NOTE: 
*DO NOT PUT ANY EXTRA FILES ON THE INPUT FOLDER THAT ARE NOT TO BE ANALYZED (the .csv files generated from the RFID program)
*ALL INPUT FILES MUST BEGIN WITH THE DATE IN WHICH THE DATA WAS COLLECTED FOR THE PROGRAM TO WORK.

2. Click on Initial Date and End Date to choose the period that is to be analyzed.

3. Choose the filter to be applied over the data (the filter will only be applied over the data gathered from the period specified in the previous step).
There are 4 possible filters:

N/A: No filter (no file with filters applied will be generated in this case)
Frequency of Register: Returns how many times the SNs were registered during the specified period
Frequency of Register per Time of Day: Returns how many times the SNs were registered during the specified period in specifics times of day. The user must specify the time of day in a dropdown menu (default is morning).

MORNING - from 6:00 until 11:59
AFTERNOON - from 12:00 until 17:59
EVENING - from 18:00 until 23:59
DAWN - from 00:00 until 5:59

Frequency of Register per Hour: Returns how many times the SNs were registered during the specified period in any chosen hours.

4. Click OK
You will generate two files:
One of them, which is named after the specified time period in step 2, contains the original data (with some QOL improvements).
The other one is named after the chosen filter and contains the filtered data.

If you have any questions, you can send them over at jvtoppa@gmail.com.

Thanks!




