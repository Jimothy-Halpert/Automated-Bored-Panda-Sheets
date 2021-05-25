# Setting up googlesheets automated scripts for your computer

Firstly, we begin by downloading .exe and .rar from the [url provided](https://drive.google.com/drive/folders/1pBiYn5Z63lO3IkibCzZcv7rCen5pG_cl?usp=sharing), then we save those files to some directory in the computer and unzip .rar files.

When the previous step has been executed, we proceed to set up the task scheduler:

1. Type "Task Scheduler" in the search bar and press enter
2. Find "Create a new task" on the right and click on it
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/1.PNG?raw=true "open a new task")
3. In General settings write a name of the task, select "Run wheteher user is logged on or not", "Run with the highest privileges" and "Windows 10"
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/2.PNG?raw=true "open a new task")
4. In Triggers settings, create a new trigger, select "Daily" and "Stop the task if it runs longer than 30 minutes"
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/3.PNG?raw=true "open a new task")
5. In action section, click on "New.." -> "Browse..", find the .exe file and select it. **Important notice: for this to work properly you need to provide the path to the folder where the .exe file is saved and write it to "Start in (optional)"**
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/4.PNG?raw=true "open a new task")
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/5.PNG?raw=true "open a new task")
6. In Conditions section deselect "Start the task only if the computer is on AC power" and "Stop if the computer switches to battery power"
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/6.PNG?raw=true "open a new task")
7. In Settings select "Allow task to be run on demand", "Run task as soon as possible", "Stop the task if it runs longer than: 1hour" and "If the running task does not end when requested, force it to stop"
![image](https://github.com/Jimothy-Halpert/Automated-Bored-Panda-Sheets/blob/main/7.PNG?raw=true "open a new task")
