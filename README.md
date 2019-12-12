## Correlations between SAT Scores and Demographics
The SAT, or Scholastic Aptitude Test, is a test given to graduating high schoolers in the US every year. The SAT has 3 sections, each of which is worth a maximum of 800 points. The SAT is used by colleges to determine which students to admit. High average SAT scores are usually indicative of a good school.

New York City makes its data on __[high school SAT scores](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4)__ available online, as well as the __[demographics](https://data.cityofnewyork.us/Education/2014-2015-DOE-High-School-Directory/n3p6-zve2)__ for each high school.

One of the most controversial issues in the U.S. educational system is the efficacy of standardized tests, and whether they're unfair to certain groups. Given our prior knowledge of this topic, investigating the correlations between SAT scores and demographics might be an interesting angle to take. We could correlate SAT scores with factors like race, gender, income, and more.

### Summary of Results
1. Safety score ranges from 5. to 9.0. No school with a safety score lower than 6.5 has an average SAT score higher than 1500 or so. Upper Manhattan, west Queens and lower Bronx tend to have higher safety scores, whereas Brooklyn has low safety scores.
2. Higher SAT score is seen in schools with higher percentage of white or asian students and specialized science and technology schools whereas lower SAT scores are seen in schools having a higher percentage of black or hispanic students and international schools.
3. Each borough except Brooklyn has a school where hispanic student percentage is less than 10% and average SAT score of the school is greater than 1800.
4. There is a strong correlation between survey responded by parents, teachers and students in every field except communication. When it comes to communication score, there's a weak correlation between parents' response and teachers' response.
5. Bronx has more schools with 95% hispanic student popluation, it has the lowest average SAT score and many low performing schools. But few schools in are also amongst the highest 3% of SAT score schools.
6. Manhattan Area has selective liberal arts schools with with a female percentage greater than 60% and an average SAT score greater than 1700, schools with highest 3% of SAT score and many high performing schools. It has the 2nd highest mean SAT score.
7. Queens has a mix of high and low performing schools. Queens schools have an average SAT score.
8. Brooklyn has the 2nd lowest mean SAT score, it has a mix of high and low performing schools.
9. Staten Island has the highest averag SAT score.

To view the code and graphs accurately, please __[click on this link](https://nbviewer.jupyter.org/github/phtelang/Correlations-Between-SAT-Scores-and-Demographics/blob/master/Correlations%20Between%20SAT%20Scores%20and%20Demographics.ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the SAT folder and the text files on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
