Download Link: https://assignmentchef.com/product/solved-itse-2309-database-programming-oracle-lab-11-views
<br>
To perform the following assignments, refer to the tables in the JustLee Books database.




<ol>

 <li>Create a view that lists the name and phone number of the contact person at each publisher. Don’t include the publisher’s ID in the view. Name the view CONTACT.</li>

</ol>




<ol start="2">

 <li>Change the CONTACT view so that no users can accidentally perform DML operations on the view.</li>

</ol>




<ol start="3">

 <li>Create a view called LAB11 that includes the columns named Col1 and Col2 from the FIRSTATTEMPT table. Make sure the view is created even if the FIRSTATTEMPT table doesn’t exist.</li>

</ol>




<ol start="4">

 <li>Attempt to view the structure of the LAB11 view.</li>

</ol>




<ol start="5">

 <li>Create a view that lists the ISBN and title for each book in inventory along with the name and phone number of the person to contact if the book needs to be reordered. Name the view REORDERINFO.</li>

</ol>




<ol start="6">

 <li>Try to change the name of a contact person in the REORDERINFO view to your name. Was an error message displayed when performing this step? If so, what was the cause of the error message?</li>

</ol>




<ol start="7">

 <li>Select one of the books in the REORDERINFO view and try to change its ISBN. Was an error message displayed when performing this step? If so, what was the cause of the error message?</li>

</ol>




<ol start="8">

 <li>Delete the record in the REORDERINFO view containing your name. (If you weren’t able to perform #6 successfully, delete one of the contacts already listed in the table.) Was an error message displayed when performing this step? If so, what was the cause of the error message?</li>

</ol>




<ol start="9">

 <li>Issue a rollback command to undo any changes made with the preceding DML operations.</li>

</ol>




<ol start="10">

 <li>Delete the REORDERINFO view.</li>

</ol>







Upload only the <strong>SQL Statements</strong> to Blackboard.


