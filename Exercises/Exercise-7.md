# Exercise 7 – Choose your transformation objects in scope for the transition to SAP S/4HANA.
-	Step 7.1. – Launch the Select Transformation Objects app
    -	Click the header of the “**Transformation Object Selection**” card to access the scoping app for the transformation objects.
    -	Alternatively, select the “**Select Transformation Objects**” app from the “**Related Apps**” menu.
    -	Explore the app content by changing settings in the transformation object list view (e.g. setting filters or change grouping / sorting)

<code>Q10: Within application component “MM”, which transformation object has the highest total data count and what is the number of records?
</code>


- Step 7.2 – View details of a transformation object
    - Click on the “Sales Document – Order” transformation object to view its details page.
      
      <img width="488" height="231" alt="image" src="https://github.com/user-attachments/assets/6071a6a8-a21f-4f35-87ab-366402e41628" />
      
    - Examine the company codes where the transformation object is used, their scoping status, and the associated data count.
    - Compare the total data counts for all company codes marked as out of scope and the figure for “**Total Data Count**” and “**Relevant Data Count**” displayed at the top of the details page for the transformation object.
    - Optionally, click “**Go to Technical Details**” in the upper right corner of the detailed page of the selected transformation object to get insights on the table structure of the transformation object.
     
      <img width="488" height="231" alt="image" src="https://github.com/user-attachments/assets/9e4a83d6-5f02-4ef7-b017-f70bb92c90e9" />

<code>Q11: What is the Total Data Count for transformation object "Sales Document - Order" in company code Company 2000, Inc (2000)?
</code>


-	Step 7.3 – Mark transformation objects as out of scope.
    -	Filter the list to show transformation objects with “**Relevant Data Count**” of 0 for the application component “**Investment Management (IM)**”
    -	Use the “**Mass Edit**” button to set these transformation objects to “**Out of Scope**” and mark them as “**Confirmed**”.
    -	Add a comment stating that application components will not be used in the future SAP S/4HANA environment.

[Exercises](../README.md#exercises)
