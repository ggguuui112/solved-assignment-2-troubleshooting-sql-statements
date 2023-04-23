Download Link: https://assignmentchef.com/product/solved-assignment-2-troubleshooting-sql-statements
<br>
In this assignment, you will delve deeply into Structured Query Language (SQL) statements. You will review existing SQL statements and troubleshoot them. You would need to determine why the given statements are not functioning properly. At the conclusion of this assignment, you should be able to examine and troubleshoot basic SQL statements.

<strong>Scenario:</strong>

A good friend of yours is starting a fantasy football league and has created a small database to track the team owners, teams, players, and games. Your friend knows that you are taking a database fundamentals class and has asked you to help. Your friend is not able to figure out why the database is not getting modified in any way. Your friend has given you a copy of the following:

<ul>

 <li>A database schema diagram. Click <a href="http://vizedhtmlcontent.next.ecollege.com/pub/content/7dfc7abf-d5e3-49ca-92ba-3af2939e9408/AU_IST351_Database_Schema_Diagram.pdf" target="_blank" rel="nofollow noopener"><ins>here</ins></a> to access the database schema diagram.</li>

 <li>A Microsoft Access database. Click <a href="http://vizedhtmlcontent.next.ecollege.com/pub/content/77d17d99-89f1-44c8-81e6-6291c94c294a/AU_IST351_Football_Team_Details.accdb" target="_blank" rel="nofollow noopener"><ins>here</ins></a> to access the Microsoft Access database.</li>

 <li>http://vizedhtmlcontent.next.ecollege.com/pub/content/77d17d99-89f1-44c8-81e6-6291c94c294a/AU_IST351_Football_Team_Details.accdb</li>

 <li>The following list of what he or she is trying to do:

  <ol>

   <li>Add a new owner named Alice Wonderland with an owner ID of 1205 and a contact e-mail of <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ff9e8890919b9a8d939e919bbf9b90929e9691d19c9092">[email protected]</a></li>

  </ol>INSERT INTO OwnerVALUES (1205, ‘Wonderland’, ‘Alice’, ‘<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b0d1c7dfded4d5c2dcd1ded4f0d4dfddd1d9de9ed3dfdd">[email protected]</a>’)

  <ol>

   <li>Update player 323’s salary to $1,800,000</li>

  </ol>UPDATE Playersalary = 1800000WHERE player_id = 323

  <ol>

   <li>Display all players whose salary is greater than $1,000,000</li>

  </ol>SELECT FROM PlayerWHERE salary &gt; 1000000

  <ol>

   <li>Delete owner Jerry Jones from the database</li>

  </ol>DELETE FROM Ownerlast_name = “Jones” AND first_name = “Jerry”

  <ol>

   <li>Update game 0105 with the final score</li>

  </ol>UPDATE GameSET home_score = 17,visitors_score = 23</li>

</ul>

<strong>Note</strong>: For this assignment, you will use Microsoft Access 2010 to open the database file provided. If you do not have Microsoft Access 2010, you may download a free trial version of Microsoft Office 2010, which includes Microsoft Access 2010, from the Microsoft website.

<strong>Tasks:</strong>

<ol>

 <li>Open the Microsoft Access file “Football.accdb” by double-clicking on it. You will see the small database created for the fantasy football league.</li>

 <li>Familiarize yourself with the database by opening and examining the data in each table.</li>

 <li>There are two queries included with the database that will display some of the information contained in the tables. Double-click each of these to see the results of the query.</li>

</ol>

Once you are familiar with the database, proceed to the next section.

<ol>

 <li><strong>Examine and Correct the Faulty SQL Statements</strong>

  <ol>

   <li>For each SQL statement listed above, identify the SQL statement errors.</li>

   <li>Once you have identified the errors, rewrite the SQL statements so that they will work.</li>

  </ol></li>

</ol>

<strong>Note</strong>: Take special precautions with <strong>Statement 5</strong> above. If you run the statement as it is written above, you will overwrite the scores of all of the existing games in the database.

<ol>

 <li><strong>Execute the Statements</strong>

  <ol>

   <li>On the <strong>Create</strong> tab, in the <strong>Queries</strong> group, click <strong>Query Design</strong>.</li>

   <li>When prompted to add tables, click the <strong>Close</strong> button.</li>

   <li>On the <strong>Query Tools Design</strong> tab, in the <strong>Results</strong> group, click on the down arrow below the word <strong>View</strong> and select <strong>SQL View</strong>. This is where you will compose your SQL statements. Feel free to type the statements above into the <strong>SQL View</strong> window and run them (see <strong>Step 4</strong>) to view the errors. (<strong>Note</strong>: Take special precautions with <strong>Statement 5</strong> above. If you run the statement as it is written above, you will overwrite the scores of all of the existing games in the database.)</li>

   <li>To run your SQL statements against the database, click the <strong>Run</strong>button in the <strong>Results</strong> group. You will be prompted to confirm that you want to modify data in your database. Click <strong>Yes</strong>. Close the query and save it as “Statement <em>n</em>“, where <em>n</em> is the statement number listed above. For example, you will save the first statement as “Statement 1”.</li>

   <li>Repeat this process for each SQL statement provided above.</li>

   <li>Once you have completed correcting the SQL statements, save and exit the database.</li>

  </ol>Save your database as M4_A2_Lastname_Firstname.accdb.</li>

 <li><strong>Explain the SQL Statement Errors</strong>

  <ol>

   <li>Create a Microsoft Word document explaining what was wrong with each of the five originally written SQL statements. Include any additional comments that you might have about the statements.Save your document as M4_A2_Lastname_Firstname.doc.</li>

  </ol></li>

</ol>

<strong>Submission Details:</strong>

<ul>

 <li>Save your deliverables as M4_A2_Lastname_Firstname.zip.</li>

 <li>By <strong>Week 4, Day 7</strong>, submit both the files to the <strong>M4 Assignment 2 Dropbox</strong>.</li>

</ul>

<strong>Assignment 2 Grading CriteriaMaximum Points</strong>Corrected the faulty SQL statements.40Explained the SQL statement errors.40Wrote in a clear, concise, and organized manner; demonstrated ethical scholarship in accurate representation and attribution of sources (i.e., APA); and displayed accurate spelling, grammar, and punctuation.20<strong>Total:100</strong>