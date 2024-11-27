# DBFoundations-Module7

Introduction: 
In this paper I will discuss when I would use a SQL UDF, and the differences between Scalar, Inline, and Multi-Statement Functions.
SQL UDF:
I would use a SQL UDF when I want to be able to change a variable or multiple within a table or when I want to create repeat calculations. The ability to pass in parameters into a UDF make it a very useful tool. If I want to change a value within a table to get different results, I would use a UDF because I can create a select statement then essentially add the interchangeable variable into the part of the SQL command that I want to be able to alter. Then to get the table it is as simple as calling upon the UDF and insert the variable value you want. For a simpler usage of a UDF such as a mathematical expression, you can create a UDF that returns a single value. For these scalar UDFs, I would put one into a table or a view to calculate a needed value without having to clutter up the table and create an expression I could use later on. 
Function Differences:
1.	Scalar: A Scalar Function differs from an Inline and Multi-Statement Function because unlike the other two, it just returns a singular value.  
2.	Inline: Unlike a Scalar Function, an Inline Function returns a table like a Multi-Statement Function. The difference between an Inline Function and a Multi-Statement Function is that an Inline uses a pre-structured table.
3.	Multi-Statement: The Multi-Statement Function has the ability to return a table like the Inline Function and unlike the Scalar Function. A unique feature about the Multi-Statement Function is that the structure of the table must be built into the function. The user is passing in the values for the table. 
Summary:
A UDF Function is a great tool to create different functionalities such as expressions, or altering table results with the usage of passed in parameters. The big differences between Scalar, Inline, and Multi-Statement Functions are that Scalar returns a singular value, Inline has a pre-built table, and Multi-Statement requires the table to built within the function, and the necessary values passed in. 
