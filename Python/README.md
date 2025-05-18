## *Automate with Python*
### Purpose:
1. extract the glossary from the Google Data Analytics course 
2. automate the process of writing which Course and Week the term was first introduced (Ex: adding 'Course # Week #')
3. sort either by:
	- phrase alphabetically [(Result)](https://github.com/dalealberto/Case_Study_GDA/blob/main/GDA_Glossary_Sorted_By_Phrase.txt) ([Python Code](https://github.com/dalealberto/CaseStudy1-Bellabeat/blob/main/Python/GDA_Glossary_Sorted_Phrase.py))
 
	- course week [(Result)](https://github.com/dalealberto/Case_Study_GDA/blob/main/GDA_Glossary_Sorted_By_Course_Week.txt) ([Python Code](https://github.com/dalealberto/CaseStudy1-Bellabeat/blob/main/Python/GDA_Glossary_Sorted_Course_Week.py))

### Rationale:

Document 'GDA_Course_1_Week_3_Glossary' contains the list of all terminology learned "so far."
This means that there will be duplicate entries of phrases and definitions in every preceeding and subsequent document.In addition, there are duplicate phrases but the definitions are slightly tweaked for improvement.

Example:
Data analyst: Someone who collects, transforms, and organizes data in order to drive informed decision-making (Course 1 Week 1)
Data analyst: Someone who collects, transforms, and organizes data in order to draw conclusions, make predictions, and drive informed decision-making (Course 1 Week 2)

Therefore, I chose to update the old phrase's definition with the new definition while retaining the "Course # Week #" when the term was first introduced. 

Final Result:
Data analyst: Someone who collects, transforms, and organizes data in order to draw conclusions, make predictions, and drive informed decision-making (Course 1 Week 1)
