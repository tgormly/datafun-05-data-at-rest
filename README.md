# datafun-05-data-at-rest
Repo for work in Module 5 of Data Analytics Fundamentals

In this repo, we will complete the following tasks:

## Task 3 - Titanic (from 9.12 above)
Follow the instructions in 9.12.3 (starting pg. 346).
Don't work in interactive mode!
Instead complete the exercise in a notebook. 
1-Load: Use pandas to read in the Titanic Disaster dataset csv file.
2-View: Set the precision to 2 decimal places. View the head and tail of the file.
3-Headings: customize the column headings.
4-Describe: Use the DataFrame describe() function to calculate basic descriptive statistics for all numeric columns. 
5-Survivors: Follow instructions to describe statistics for those who survived (titanic.survived == 'yes') - see the example. 
Notice that describe provides different results for non-numeric data (e.g., unique, top, freq)
Enable matplotlib. If it doesn't work (e.g., in a notebook), try 
%matplotlib inline
6-Histogram: Use the DataFrame's hist() function to create a histogram for each numerical column.
Required: Use Section headings in your Markdown to make it clear that each of these 6 sections are shown in your notebook. They should be numbered 1-6 and include the keyword shown above.
Required: Include the title of the notebook, and your name and date at the top.
Do these consistently. A heading and section titles is required in every notebook. 
 

### Task 3 Output
Document your results.

execute the completed notebook 
export to html
include the html in your repo
 
<hr>

## Task 4 - SQL (from 17.2 above)
Follow the instructions in 17.2.1 (starting pg 730) 
Don't work in interactive mode - use a notebook.
IMPORTANT: create the table using the books.sql script provided with the author files. 
If Windows, use Anaconda Prompt (generally for all commands we use in this course).
See Terminals: Database from Script (for more detailed discussion of how to run books.sql)
See Terminals: Running Python Scripts (for more about terminals and options)
In your Python code, import the sqlite3 module and use the connect function to create a connection to your database.
After running the script, there should be 3 tables: authors, author_ISBN, and titles. 
Import pandas as pd
Use pd options.display to set the max_columns to 10
Use pd read_sql fuction to select everything (*) from the authors table, then the titles table, then the author_ISBN table.
Complete 17.2.2 SELECT (1 query)
Complete 17.2.3 WHERE (3 queries)
Complete 17.2.4 ORDER BY (4 queries)
Complete 17.2.5 INNER JOIN (1 query)
Complete 17.2.6 INSERT INTO (2 queries)
Complete 17.2.7 UPDATE (2 queries)
Complete 17.2.8 DELETE FROM (2 queries)
Final Results, SELECT * from each table and display the final state of each of the 3 tables.
Required: Use Section headings in your Markdown to make it clear that each of these 8 sections are shown in your notebook. They should be numbered 1-8 and include the SQL keyword shown above. Use a heading before your the final results showing all 3 tables as well. 
Required: Include the title of the notebook, and your name and date at the top.
Do these consistently. A heading and section titles is required in every notebook. 
 

### Task 4 Output
Document your results.

execute the completed notebook 
export to html
include the html in your repo
Task 5. Push Repo to GitHub
Use VS Code to commit and sync (push) your repo to GitHub - or in Git Bash or terminal, do the following. 

git add .
git commit -m "added code"
git push origin main

<hr>

## Optional Task 6. Bonus
Start a new notebook.
Locate a unique csv dataset. 
Use pandas to import the csv dataset into a DataFrame.
Use the DataFrame commands to clean the data as needed and/or rename the columns.
Use the DataFrame describe() function to calculate basic descriptive statistics. 
Use the DataFrame hist() function to generate histograms for all numeric columns. 
Include the required heading at the top, and use section headings to tell your story with data. 
Execute the entire, professionally presented file and output to html. 
Git add, git commit, and git push the new content to your GitHub repo. 