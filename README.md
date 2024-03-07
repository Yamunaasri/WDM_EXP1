### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 10.02.2024
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name nominal 
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
John, 001, medium, 5, male, 123456
Alice, 002, high, 8, female, 987654
Bob, 003, low, 2, male, 456789
Emily, 004, high, 10, female, 789012
Michael, 005, medium, 6, male, 234567
Samantha, 006, low, 3, female, 901234
David, 007, medium, 7, male, 345678
Sophia, 008, high, 9, female, 678901
Daniel, 009, low, 4, male, 012345
Ella, 010, medium, 6, female, 890123



--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
#### Employee Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/9725d7ad-68f7-47c6-a511-39d98d896dc8)

#### Weather Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/585c7d8f-0e9a-4a77-a6a2-ea7fd449ce5e)

### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
#### Employee Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/dc1df5b9-dd0f-424e-b56f-0895066b1813)

#### Weather Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/36f60eb0-2f6a-42fb-9495-b555c8a6bc8a)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
#### Employee Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/c473f206-de6a-4d28-a69f-0e2779018235)

#### Weather Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/c7848088-3e76-41c2-819a-1c49874c2843)

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
#### Employee Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/b30c7b09-90ba-463d-b1fa-fb3cc42de812)

#### Weather Data
![image](https://github.com/Yamunaasri/WDM_EXP1/assets/115707860/10dc81fe-8c7d-48b8-a0aa-40383ea71f9f)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
