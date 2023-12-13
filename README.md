Welcome to the Health Explorer App!

For some people, collecting health data can be difficult. To record heart rate, the user might have issues
with the heart monitor and needs to collect data for the doctor. 
These issues can include the device falling off or they might be allergic to the adhesive pads.
Various devices can be worn daily with no hassle that collect health data such as the Apple Watch.
A user can set up their Apple Watch to track almost any type of health data they want. 
This can include heart rate, workouts, the number of flights of stairs you climbed or how far you walked/ran. 
All of this information then gets stored into the Apple Health app to view. 
The biggest issue with the Apple Health app is that it is not very easy to read some of the data 
that is recorded.

In this app, it makes Apple Health data easier to read. 
It takes in imported Apple Health data from a device such as the Apple Watch, and analyzes and displays it. 
In this program, the user will be able to select different options. For instance, the user can check their heart rate by 
selecting heart rate and can select a given day. The program will display their heart rate as a line chart with the given times it was recorded.
The user will also be able to see their distance while wearing the Apple Watch. This shows all the number of miles that was recorded 
for that day. 
The user will also be able to see how many flights of stairs they climbed up. Sometimes it can be good to know if you are someone who goes up and down
stairs all day long. 


To get started, when you open the Apple Health app, click your profile in the top right.
A popup will show different options to choose from. Scroll down and click "Export All Health Data".
When you click it and click export on the popup that shows up to confirm, the user will be shown different ways to send it.
Click one of the choices you wish to send to such as email and email it to yourself. 

Unzip the folder and there will be different files. The main folder is the folder called "export.xml"
Move the export file to where you are going to have the project located. For this project to work, the user must 
go into the export.xml file, can open it via Notepad, and the user must delete the schema section. The schema section starts with:
<?xml version="1.0" encoding="UTF-8"?> and ends right before <HealthData local="en_US">. Save the file and the file can be accessed through the program.
Also, it is worth keeping in mind that the export.xml file may be slow depending on the amount of data that is recorded. 
If the user has not already, download the main file for this program and add it to the project.

To run this program, make sure the IDE allows Python and make sure that the imported libraries and APIs are downloaded as well. Once that is done
click run. The user will be given a command in the console to paste into the terminal. If the file path has any spaces, the user needs to enclose the 
file path in double quotation marks. If the user isn't already directed to their default browser with the program running, the user will be given a 
local host hyperlink to click that will then direct them. 

Do keep in mind technical issues alongside user issues. For example, the Apple Watch could be misreading data or the Apple Watch is reading information and the user takes it off, the 
results might be off. 


Sources:
Using xml.etree.ElementTree to parse through a XML file:
https://docs.python.org/3/library/xml.etree.elementtree.html

Using pandas merge to merge data frames:
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html

Using lambda: 
https://www.w3schools.com/python/python_lambda.asp
