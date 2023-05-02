Download Link: https://assignmentchef.com/product/solved-comp93211-assignment-1
<br>
<a href="https://www.kaggle.com/rounakbanik/the-movies-dataset">The assignment data has been extracted from a Movie dataset on Kaggle (https://www.kaggle.com/rounakbanik/the-</a>

<a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/credits.csv">movies-dataset)</a> <a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/credits.csv">, with some minor modification to make things interesting. The dataset is split into two CSV files </a><a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/credits.csv"><strong>credits</strong></a>

<a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv"><strong>(https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/credits.csv)</strong></a> <a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv">and </a><a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv"><strong>movies</strong></a>

<a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv"><strong>(https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv)</strong></a> <a href="https://github.com/mysilver/COMP9321-Data-Services/raw/master/20t1/movies.csv">. Use the da</a>tasets to answer the following questions:

Join the two datasets based on the “id” columns in the datasets, keeping the rows as long as there is a match between the id columns of both dataset (do not concatenate the datasets).

<strong>Question 2: ( based on the dataframe created in Question-1 ) ( 0.5 Mark ) </strong>

Keep the following columns in the resultant dataframe (remove the rest of columns from the result dataset): <em>‘ ‘id’, title’, ‘popularity’, ‘cast’, ‘crew’, ‘budget’, ‘genres’, ‘original_language’, ‘production_companies’,</em>

<em>‘production_countries’, ‘release_date’, ‘revenue’, ‘runtime’, ‘spoken_languages’, ‘vote_average’, ‘vote_count’ </em>

<strong>Question 3: ( based on the dataframe created in Question-2 ) ( 0.5 Mark ) </strong>Set the index of the resultant dataframe as ‘id’.

Drop all rows where the budget is 0

<strong>Question 5: (based on the dataframe created in Question-4) (1 Mark) </strong>

Assume that there is a ranking scheme for movies defined by ” <em>(revenue – budget)/budget </em>“. Add a new column for the dataframe, and name it “success_impact”, and calculate it for each movie based on the given formula.

<strong>Question 6: (based on the dataframe created in Question-5) (1 Mark) </strong>

Normalize the ” <em>popularity </em>” column by scaling between 0 to 100. The least popular movie should be 0 and the most popular one must be 100. It is a float number.

<strong>Question 7: (based on the dataframe created in Question-6) ( 0.5 Mark ) </strong>Change the data type of the “popularity” column to (int16).

<strong>Question 8: (based on the dataframe created in Question-7) (1.5 Marks) </strong>

Clean the “cast” column by converting the complex value (JSONs) to a comma separated value. The cleaned “cast” column should be a comma-separated value of alphabetically sorted characters (e.g., Angela, Athena, Betty, Chester Rush ) . NOTE: keep unusual characters e.g., ‘(uncredited)’ as they are; no need for further cleansing.

<strong>Question 9: (based on the dataframe created in Question-8) (1.5 Marks) </strong>

Return a list, containing the names of the top 10 movies according to the number of movie characters (Harry Potter! is one character! do not count the letters in the title of movies!). The first element in the list should be the movie with the most number of characters.

<strong>UPDATE: You can assume that there is no COMMA in the characters. </strong>

<strong>Question 10 : (based on the dataframe created in Question-8) (1 Marks) </strong>

Sort the dataframe by the release date (the most recently released movie should be first row in the dataframe)

<strong>Question 11: (based on the dataframe created in Question-10) (2 Marks) </strong>

<ul>

 <li>( <strong>1 .5 Mark </strong>) Plot a pie chart, showing the distribution of genres in the dataset (e.g., Family, Drama).</li>

 <li>( <strong>5 Mark </strong>) Show the percentage of each genre in the pie chart. Please be noted that the following figure is just a sample and it does not reflect the real values or the list of all genres in the dataset.</li>

</ul>

<strong>UPDATE: You can add a legend to your chart if labels overlap.You can also merge the some of the infrequent labels (up to 4) and name them “other genres”. </strong>

<strong>Question 12 : (based on the dataframe created in Question-10) (2 Marks) </strong>

<ul>

 <li><strong>(1.5 Marks) </strong>Plot a bar chart of the countries in which movies have been produced. For each county you need to show the count of movies.</li>

 <li><strong>(0.5 Mark) </strong>Countries should be alphabetically sorted according to their names.</li>

</ul>

Please be noted that the following figure is just a sample and it does not reflect the real values or the list of all countries in the dataset.

<strong>Question 13: (based on the dataframe created in Question-10) (2.5 Marks) </strong>

<ul>

 <li><strong>(1.5 Marks) </strong>Plot a scatter chart with x axis being “vote_average” and y axis being “success_impact”.</li>

 <li><strong>(0.5 Marks) </strong>Ink bubbles based on the movie language (e.g, English, French); In case of having multiple languages for the same movie, you are free to pick any one as you wish.</li>

 <li><strong>(0.5 Marks) </strong>Add a legend showing the name of languages and their associated colors. <strong>UPDATE: You can use both “original_language” (e.g. “en”, “fr”) or “spoken_languages” . </strong></li>

</ul>




Please be noted that the following figure is just a sample and it does not reflect the real values or the list of all countries in the dataset. (also the x and y axis should be swapped in the figure)

What not to forget!

<strong>Due Date: </strong>Friday the 13th of March 2020 17:59

Submit your script named ” YOUR_ZID .py” (z2123232.py) which contains your code.

You are required to use the following code template ( <strong>it is not complete; please download the file </strong>) for your submission:

<strong> </strong><a href="https://raw.githubusercontent.com/mysilver/COMP9321-Data-Services/master/20t1/z1111111.py"><strong>You can download the code template from : https://raw.githubusercontent.com/mysilver/COMP9321-DataServices/master/20t1/z1111111.py (https://raw.githubusercontent.com/mysilver/COMP9321-DataServices/master/20t1/z1111111.py)</strong></a>

<strong>If you do not follow this structure, you will not be marked. </strong>

<strong>You can only add codes in the specified lines (do not edit the rest of the lines):</strong>

<table width="762">

 <tbody>

  <tr>

   <td width="762">import ast import jsonimport matplotlib.pyplot as plt import pandas as pd import sys import os studentid = os.path.basename(sys.modules[__name__].__file__) ################################################# # Your personal methods can be here … ################################################# def log(question, output_df, other):print(“————— {}—————-“.format(question))     if other is not None:print(question, other)     if output_df is not None:print(output_df.head(5).to_string()) def question_1(movies, credits):“””:param movies: the path for the movie.csv file:param credits: the path for the credits.csv file:return: df1Data Type: DataframePlease read the assignment specs to know how to create the output dataframe     “””################################################## Your code goes here …#################################################     log(“QUESTION 1”, output_df=df1, other=df1.shape)     return df1…  if __name__ == “__main__”:     df1 = question_1(“movies.csv”, “credits.csv”)     df2 = question_2(df1)     df3 = question_3(df2)     df4 = question_4(df3)     df5 = question_5(df4)     df6 = question_6(df5)     df7 = question_7(df6)     df8 = question_8(df7)     movies = question_9(df8)     df10 = question_10(df8)     question_11(df10)     question_12(df10)     question_13(df10)</td>

  </tr>

 </tbody>

</table>

#################################################

# Your code goes here …

#################################################

<strong> If your code does not run on CSE machines for any reasons (e.g., hard-coded file path such as C://Users/), you will be penalize at least by 5 marks. We assume that the two csv files are located in the same directory of your script, and the name is the same as the one in the template (movies.csv, and credits.csv)</strong>

<strong> Please look at the documentation for each question method; it describes the inputs (e.g., a dataframe) and output (e.g., dataframe, list of movies) of the method.</strong>

“””

:param df7: the dataframe created in question 7

:return: df8

Data Type: Dataframe

Please read the assignment specs to know how to create the output dataframe

“””

<strong>Please use the same variable names as mentioned in the comments (e.g., in question 8, you are supposed to create a dataframe and name it df8</strong>

<strong>In the last three questions, you need to plot charts; please do not use “plt.show()” function to pop up charts. The code template will automatically save the chart on the disk. What you need to do is to just call the plot functions of the dataframe (e.g., df.plot.pie()). We highly recommend you go through the lab activities to know how to plot charts.</strong>

FAQ:

<strong>Can I pass extra variables to functions? </strong>

No

<strong>Can we create our own functions besides the question functions (e.g., question_1)? </strong>

Yes

<strong>Can I call another function inside the question functions? e.g., calling question_1 inside question_2 </strong>Yes

<strong>What should I do if my charts are not shown automatically? </strong>

Look at the lab sample codes; if still need a help, ask your tutor during the labs. <strong>How should I print my dataframe? </strong>

print(df.to_string())

<strong>Is it okay that the graph for Q8 does not pop up until the graph for Q7 is closed or should they both pop up at the same time? </strong>

This is fine

<strong> Do the charts need to look the same (colors, legend position, grid) as the examples shown? or would it be fine to just use the default plotting from pandas? </strong>The default colours/fonts are fine

<strong>How are our submissions marked? </strong>

They are marked manually by tutors, by running the following command: python3 z{YOUR_ZID}.py <strong>What python packages can I use in my assignment? </strong>

You can only use packages imported in the template file to do the assignment. <strong>What version of python should I use? </strong>

Python 3


<strong>How I can submit my assignment? </strong>

Go to the assignment page click on the “Make Submission” tab; pick your files which must be named “YOUR_ZID.py”. Make sure that the files are not empty, and submit the files together.

<strong> Can I submit my file after deadline? </strong>

Yes, you can. But 25% of your assignment will be deducted as a late penalty per day. In other words, if you be late for more than 3 days, you will not be marked.