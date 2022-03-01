# Practice array functions with realistic data

Convert Northwind JSON files to JavaScript objects and practice querying and manipulating data with JavaScript array functions.

## Instructions

1. convert the **employees.json** file to a JavaScript object in a JavaScript file called `funcarrays.js`
2. display (with console.log) how many employees there are
3. display list of first names
4. display list of last names
5. display list of full names
6. display full name and notes of all employees that have the word `german` (upper or lower case) in their notes field
7. display `lastname, firstname` in alphabetical order by last name
8. display `lastname, firstname` in reverse alphabetical order by last name
9. display string of last names separated by pipe symbole, e.g. `Fuller|Buchanan|Davolio|...`
10. display string of last names with each name in parentheses and comma separated, e.g. `(Fuller), (Buchanan), (Davolio), ...`
11. display list of `lastname: city`
12. display list of `lastname: city` of each employee from the UK
13. make a function `reportCity(city)` which searches all employees returns "Some are from <city>", "None are from <city>" or "All are from <city>", e.g. `reportCity('London') --> "Some are from London"` and `reportCity('Berlin')` --> "None are from Berlin"

## Bonus :muscle:

1. convert the **customers.json** file to a JavaScript object and add it to the JavaScript file called `funcarrays.js`
2. display the sentence: `There are nnn employees and nnn customers.`
3. create a new array of customers from the UK with the following structure (use filter and map), e.g.
```
	{
		id : "AROUT",
		"company" : "Around the Horn",
		"contact" : "Thomas Hardy (Sales Representative)",
		"city" : "London"
	}
```

