# Read: Class 06:  Game of Greed 1
### How to use Random Module
- usage of random module: is that it allows you to generate random numbers from a list.
- we use it when we want to pick a random number from a list
- code : 
	- import random
	 print random.randint(0, 5)
      this code will output either 1,2,3,4 or 5

	- a random number between 0 and 100:
		import random
		random.random() * 100

	- Choice
	Generate a random value from the sequence sequence.
	random.choice( ['red', 'black', 'green'] ).

	- from (https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)

- shuffle function shuffles the elements of the list in random places



### What is Risk Analysis
- The probability of any unwanted incident is defined as Risk. In Software Testing,
	risk analysis is the process of identifying the risks in applications or software
	that you built and prioritizing them to test. After that, the process of assigning 
	the level of risk is done. The categorization of the risks takes place, hence, 
	the impact of the risk is calculated.
	- from (https://www.edureka.co/blog/risk-analysis-in-software-testing/)


- possible risks you could encounter: 
	1. Use of new hardware
	2. Use of new technology
	3. Use of new automation tool
	4. The sequence of code
	5. Availability of test resources for the applicatio

- we need three steps to perform risk analysis
	1. Searching the risk
	2. Analyzing the impact of each individual risk
	3. Measures for the risk identified