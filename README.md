# Complexity-Analyzer
This project computes the code complexity using a JavaScript parser called [Esprima](https://esprima.org/).  

The following metrics can be calculated using this code:  
* Simple Cyclomatic Complexity  
* Maximum Nesting Depth of a function  
* Maximum number of conditions in a function  
* Number of Parameters passed to a function  
* Longest message chains in a function  
* Number of return statements in a function  

### Running Instructions
Clone this repository and perform ```npm install``` to install all the dependencies.  

Execute the ```analysis.js``` file using the command: ```node analysis.js```  
This command will pass the analysis.js folder itself to the analyzer and will return its complexity result.  

To calculate the complexity of ```mystery.js``` file, run the following command:  
```node analysis.js mystery.js```  

Screenshot of the result when code is tested on mystery.js:
![](/result.png)
