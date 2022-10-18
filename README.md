# peer-review-system

Created during my final year of college, I took a lot of the initiative in my group on this massive project for our computer professor.

Function: This program imports a given .txt file that is comma delimited and creates a table with the data. The first line is always the class name, the lines following are the students' names and their peer review points. Ex: Ruby Rose,3

Student names are broken up by spaces. Ex: Ruby Rose will fill the table with the first name Ruby, the last name Rose

Once the table is filled, using Javascript, the teacher can add or delete students within the table, and there is a dropdown feature to sort by first or last name. The sort will have to be reselected if a new student is added/deleted. They may also add or subtract peer review points.

A requested feature along with the sort was a leaderboard. When generated, the a table will show the top 5, 10, or 15 students. There is also a feature to copy and paste that table data into a separate site as requested by our professor.

The final touch and my proudest contribution is the save table feature. When clicked, the page will save the current table state as a comma delimited file once more that can be re-imported into the table later on. It took a decently lengthy time for me to find how to integrate this feature using solely javascript, but it will be saved in the same format as the .txt files that the program accepts.
