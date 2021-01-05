# Replication Package Standards

1. Cite everything that the replication package relies on.
	* Why: Citations in the manuscript and the README are the best way of directing readers to these resources and to give credit to the original authors.
	* How: All datasets, whether public or private, included or not, should be cited. It is good practice to cite software packages, but not required, unless the license terms specifically ask you to do so.
2. Include all exhibits and the code to produce them.
	* Why: The package should be self contained so that readers can verify that your analysis code produces the output you included.
	* How: Save all the output of the analysis in some standard format into the replication package. Tables can be saved as .csv, .xls or .tex files. It is also sufficient to save the Stata .log file. In this case, please report in the README the line numbers where the readers can find the table numbers. Figures can be saved in .eps, .pdf or .png.
3. For files not included, explain how to get them.
	* Why: The goal is to describe clearly the steps that readers have to take if they want to access the data and software you could not included. 
	* How: Include a formal Data Availability Statement for each of the datasets you are using. List all software packages, libraries, toolboxes that you use in the README with instructions on how to install them.
4. Guide the reader on how to get from the data to exhibits.
	* Why: Readers are expert empirical economists but need specific instructions on how to reproduce your analysis.
	* How: Create a list of exhibits and state which one is produced by which script. If possible, include a master script executing all the necessary steps. Explain if your code requires special hardware or runs for particularly long.
