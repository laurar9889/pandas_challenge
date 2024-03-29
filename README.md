# pandas_challenge
Challenge_Week4_Laura_Roa
In this repository you will find 1 folder with a Jupyter notebook, which will walk you through the process followed to be able to manipulate, analyze and conclude from the data.
You will also find an analysis txt file, that summaries the dataframes with key highlighted findings. The conclusions will be drafted within Readme File.
As the assignment has multiple requests, I included numbers on each comment to facilitate the navigation on the file. Numbers of comments will be given in the conclusions as reference.

Background: 2 dataframes were given in csv format which contains a list of schools, relevant numbers such as number of students, budget amounts, math and reading scores, among others. The conclusions will be helping the school board and mayor to make strategic decision pertaining the future of school budgets.

Assumptions: 
1. Assumed that all the schools given in the database will cover 100% of the existing schools in the city
2. Assumed that grades go from 1 to 100 (1 being the lowest, 100 being the highest score)
3. Assumed "size" refers to total number of students per school
4. Assumed that passing a subject will be when the score is equal or greater than 70
5. Assumed high quality of school as schools with highest % of student that pass math and reading
6. Assumed Budget refers to total money spent per school(tuition fee, monthly payments)


Conclusions:
About 40,000 students results were evaluated by school. There are 3 main conclusions, focused on quality and budget per school.

  1. According to the size summary dataframe (#29.B in Jupyter notebook), schools that are consider small and medium have the best scores (between 89% and 90& overall passing score), compared to the large schools (58%   overall pass score). There is a direct relation between size of school versus overall passing score; the bigger the number of students, the lower their overall math and reading score.

  2. The budget per capita gap between the minimum and maximum value ($578 and $655) is not an extreme high number (see comment #14 per_school_capita). It does not seem to exist a relation between budget per capita and the quality of each school. In fact, the top number 1 school in quality, is Cabrera Highschool, with a budget per capita of $582. (see comment #27 spending ranges and #21.B top 5 schools)
     
  3. The relationship between quality and type of school will be shown in Data Frame #30.B "type summary" It is showing that the Charter School average is 67% higher than District School. Charter Schools perfom better than District Schools. The difference between them are unkonwn (location, instructors profile, among others). However, there is a clear difference in  their quality of scores.

As per conclusions, I encourage the school board to prioritize the quality of the schools by improving the District School scores. The mayority of them are large schools, which seems to be one of the variables that drive the quality. In addition, the top 3 schools seem to have a  good handle on budget per capita and quality. I recommend doing a benchmark, and working collaborately to standardize costing models, teaching methods, etc. 
