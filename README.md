Download Link: https://assignmentchef.com/product/solved-ism-4210-database-management-individual-project-4
<br>
<h1>INSTRUCTIONS</h1>

Please read the description and the requirements of Deliverable #4 carefully before responding. If you have any questions or clarifications, feel free to contact me via email (<u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="abcacfc2dfc2c6dec0c3ced9c1ceceeb">[email protected]</a> ufl.edu</u>), during my office hours, or by appointment <strong> </strong>

All submissions should be <u>individual work</u> only. Do not discuss your answers with your class mates or group members. Plagiarism will not be tolerated.




No late submissions will be accepted. If you have trouble submitting assignments to the e-learning system, please contact me <u>before</u> the submission deadline.

<strong><u>Page Limit:</u></strong>  There is no fixed page limit for this deliverable.

<strong><u>Format: </u></strong>  You will submit 8 SQL statements and the results of running the queries in the attached database. Copy and paste all the statements and the diagram into a Word document that you can save and submit as a PDF. Please note the number of the problem statement clearly above each query. See page 3 of this document for an example of how to present the statements.  The name of your file should be <strong>&lt;LastName&gt;_&lt;FirstName&gt;_IP4.pdf. </strong>Submissions that do not follow the formatting guidelines will not be graded.  <strong><u>Grading:</u></strong>  This deliverables will be graded out of 12 points.




<h1>SINGLE TABLE QUERIES</h1>

For this deliverable, you will be writing queries to use the data in the TheHipp database.




<strong>STEP 1:</strong> Download the SQL script (TheHipp.sql) file attached to assigment IP#4. Run the scripts into MySQL as follows:

<ul>

 <li>Open the SQL script file using CTRL+SHIFT+O.</li>

 <li>Run the entire script using CTRL+SHIFT+Enter.</li>

</ul>




<strong>STEP 2:</strong>  You must write queries for the problem statements on Page 2 as follows:

<ul>

 <li>Section 1: Write queries for all 4 problem satetemnts. Each query is worth 1 point.</li>

 <li>Section 2: Write queries for 2 problem statements. Each query is worth 2 points.         Section 3: Write queries for 2 problem statements. Each query is worth 2 points.</li>

</ul>

<strong>STEP 3:</strong>  Do the following for each of the problem statements you attempt:

<ol>

 <li>Write the SQL query that will achieve the desired result</li>

 <li>Run the query in the MySQL database.</li>

 <li>Copy and paste the results of the query below each SQL statement using the format on page 3 of this assignment.</li>

</ol>




Each query must satisfy the following criteria:

<ol>

 <li>They must not include any extra/unnecessary tables.</li>

 <li>The results must not include any extraneous columns.</li>

 <li>All column headings should be meaningful names. Please do not have columns with headings that contain expressions or aggregate functions.</li>

</ol>




<strong> </strong>

<h1>PROBLEM STATEMENTS</h1>




<strong><em><u>Section A: You must respond to ALL 4 of the following:</u></em></strong><strong><em>  </em></strong>

<ol>

 <li>List the LastName, FirstName, Email Address and DonorID for all the customers who are also donors. Sort the results by LastName.</li>

 <li>How many customers have been verified as students? Your query should return just one value.</li>

 <li>List the EventCode and the Year for all the shows that are scheduled in the month of December. Your query should display each event code only once.</li>

 <li>How many events have been scheduled for each venue? Your query should return two columns: the VenueID and the number of events.</li>

</ol>

<strong><em><u>Section B: You must respond to 2 of the following:</u></em></strong><strong><em>  </em></strong>

<ol start="5">

 <li>List the number of tickets sold during the month of November 2015. Group your results by show and only list those shows that have sold more than or equal to 10 tickets. Your query should have 4 columns: EventCode, ShowDate, ShowTime and the number of tickets sold.</li>

 <li>What is the maximum number of tickets that a single customer has bought in one day? You query should have 3 columns (HippCode, Date of Purchase and the number of tickets) and just 1 row in the results.</li>

 <li>For each of the event show, list the number of tickets that were made available, the number of tickets that were sold and the percentage of tickets that were sold. Your results should not include any rows where the shows were sold out (i.e. shows where all tickets were sold). Your results should look like the table below; but the numbers may differ.</li>

</ol>

<table width="453">

 <tbody>

  <tr>

   <td width="68"><strong>Event Code </strong></td>

   <td width="94"><strong>Show Date </strong></td>

   <td width="78"><strong>Show Time </strong></td>

   <td width="63"><strong>Total Tickets </strong></td>

   <td width="69"><strong>Tickets Sold </strong></td>

   <td width="82"><strong>Percentage Sold </strong></td>

  </tr>

  <tr>

   <td width="68">802</td>

   <td rowspan="2" width="94"> 2014-10-21</td>

   <td rowspan="2" width="78"> 07:00:00</td>

   <td width="63">50</td>

   <td width="69">34</td>

   <td width="82">68%</td>

  </tr>

  <tr>

   <td width="68">803</td>

   <td width="63">50</td>

   <td width="69">40</td>

   <td width="82">80%</td>

  </tr>

  <tr>

   <td width="68">804</td>

   <td width="94"> 2014-11-18</td>

   <td width="78"> 07:00:00</td>

   <td width="63">50</td>

   <td width="69">32</td>

   <td width="82">64%</td>

  </tr>

 </tbody>

</table>




<strong><em><u>Section C: You must respond to 2 of the following:</u></em></strong><strong><em>  </em></strong>

<ol start="8">

 <li>For each sponsor, list the sponsor name, the number of events and the total amount they have donated. Sort your results by donation amount in the ascending order.</li>

 <li>For the top 5 grossing events, list the event code, number of tickets sold, the date of the first show and the date of the last shows (these may be the same).</li>

 <li>Write a query that lists the number of tickets sold and the revenue earned for each day of the week. Group your results by year as well and sort them by year and day of the week.</li>

</ol>







For each query, you must present your results using the following template.

<table width="667">

 <tbody>

  <tr>

   <td width="667"><strong>Problem Statement Number</strong></td>

  </tr>

  <tr>

   <td width="667"><strong>Query: </strong> SELECT * FROM Customer;<strong>Results</strong>   </td>

  </tr>

 </tbody>

</table>





