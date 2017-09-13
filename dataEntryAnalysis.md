## Data Entry Analysis
### Problem
* According to the background information, dataset should include three set of data from day to night, and it should specify in the table. But in those three files, they didn't specify which row collect from when.
* Some fields have highlight, some data shows red, but no introduction for those highlight and different text color.
* Wrong data analysis. Didn’t use reliable way to do data analysis. Under zoop-temp file, it shows Max Depth is 72m but in dataset max depth is 50, it should be calculated by using function in the excel instead of looking for it by eye. 
* Unstable data. Changing of * in field H23 in file zoop-temp-main H23 will cause change of other data.
* Confusing variable. Column name ‘z’ under file pond 2010
* No title or explanation for analysis graph under file zoop-temp-main .
* Missing dataset on both pond2010 and zoop-temp-main files
* Unit is not available for variables. For example, we don’t know the temperature is a Celsius number or Fahrenheit number.

## System Suggestion: 
I will suggest the organization to use a data collection system. It’s a computer application that facilitates the process of data collection, allowing specific, structured information to be gathered in a system fashion. It can solve the problem such as data missing, when data missing occur, system will pop up notification to users and stop users go to the next step until they enter data for required field. Also, data collection system containing detailed user input fields and data validations. In the potential template, Time is added to state the data collection time in a day. Unit is added to declare the variables. Pound file and zoop-temp file are combined to reduce data collection times.


| Date | Time | Depth(m) | Tempeture(°C) | Main Species | Main Species density per ml | Colony Diameter(ml) | Chippo #/L | Chippo ColonySize(mm) | Cuni #/L | Cuni ColonySize(mm) | Chlorophyll a |
|------|------|----------|---------------|--------------|-----------------------------|---------------------|------------|-----------------------|----------|---------------------|---------------|

