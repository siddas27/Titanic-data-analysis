# Titanic-data-analysis
This is a data analysis and data visualization on titanic data set.

### Programming Language: Python
### Libraries used: numpy, matplotlib, pandas<br>
## Data Dictionary
 <table style="width:100%">
  <tr>
    <th>Variable</th>
    <th>Definition</th>
    <th>Key</th>
  </tr>
  <tr>
    <td>survival</td>
    <td>Survival</td>
    <td>0 = No, 1 = Yes</td>
  </tr>
  <tr>
    <td>pclass</td>
    <td>Ticket class</td>
    <td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
  </tr>
	<tr>
    <td>sex</td>
    <td>Sex</td>
		<td></td>
  </tr>
	<tr>
    <td>Age</td>
    <td>Age in years</td>
    <td></td>
  </tr>
	<tr>
    <td>cabin</td>
    <td>Cabin number</td>
    <td></td>    
  </tr>
	<tr>
    <td>sibsp</td>
    <td># of siblings / spouses aboard the Titanic</td>
    <td></td>
  </tr>
		<tr>
    <td>parch</td>
    <td># of parents / children aboard the Titanic</td>
    <td></td>
  </tr>
	<tr>
    <td>ticket</td>
    <td>Ticket number</td>
    <td></td>
  </tr>
		<tr>
    <td>fare</td>
    <td>Passenger fare</td>
    <td></td>
  </tr>
	</tr>
		<tr>
    <td>embarked</td>
    <td>Port of Embarkation</td>
    <td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
  </tr>
</table> 

## Variable Notes

pclass: A proxy for socio-economic status (SES)<br>
1st = Upper<br>
2nd = Middle<br>
3rd = Lower<br>

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5<br>

sibsp: The dataset defines family relations in this way...<br>
Sibling = brother, sister, stepbrother, stepsister<br>
Spouse = husband, wife (mistresses and fiancés were ignored)<br>

parch: The dataset defines family relations in this way...<br>
Parent = mother, father<br>
Child = daughter, son, stepdaughter, stepson<br>
Some children travelled only with a nanny, therefore parch=0 for them.
