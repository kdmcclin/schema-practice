This is where your schema solutions should go.  If the SQL designer is working, save a screenshot of your schema in the img folder and use the following syntax for linking it in this file.  
	![Image Title](img/my_awesome_schema.png)
If the schema designer is not working or is causing you too much confusion (it can take some getting used to), try the empty tables below.


##One to One
Read the one-to-one section of the explanations if necessary.  
Create your own one-to-one database relationship.  You don't have to use the same number of fields as the empty skeleton below--adjust as necessary.  Make both a schema (using the designer or the skeleton below) and a few entries in each table.  **Note:** Make sure you're including the correct table_id (facebook_account_id in the explanation section) in the right place for the necessary entries.  Don't worry about actually drawing connecting arrows on the skeleton below unless that helps.

<pre>
+---------------------+        +-------------------+
| table_1		      |        | table_2		   |
+---------------------+        +-------------------+
| id                  |        | id                |
| field1	          |        | field1            |
| field2              |        | field2            |
| field3              |        | field3            |
| field4			  |        +-------------------+
+---------------------+
</pre>

**table_1**
| id | field1 | field2 | field3 | field4 |
|----|--------|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|

**table_2**
| id | field1 | field2 | field3 |
|----|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)|

##One to Many
Read the one-to-many section of the explanations if necessary.  
Create your own one-to-many database relationship.  You don't have to use the same number of fields as the empty skeleton below--adjust as necessary.  Make both a schema (using the designer or the skeleton below) and a few entries in each table.  **Note:** Make sure you're including the correct table_id (user_id in the explanation section) in the right place for the necessary entries.  Don't worry about actually drawing connecting arrows on the skeleton below unless that helps.

<pre>
+---------------------+        +-------------------+
| table_1		      |        | table_2		   |
+---------------------+        +-------------------+
| id                  |        | id                |
| field1	          |        | field1            |
| field2              |        | field2            |
| field3              |        | field3            |
| field4			  |        +-------------------+
+---------------------+
</pre>

**table_1**
| id | field1 | field2 | field3 | field4 |
|----|--------|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|

**table_2**
| id | field1 | field2 | field3 | 
|----|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)|

##Many to Many
Read the many-to-many section of the explanations if necessary.  
Create your own many-to-many database relationship.  You don't have to use the same number of fields as the empty skeleton below--adjust as necessary.  Make both a schema (using the designer or the skeleton below) and a few entries in each table.  **Note:** Make sure you're including the correct table_ids (author_id and book_id in the explanation section) in the right place for the necessary entries.  Don't worry about actually drawing connecting arrows on the skeleton below unless that helps.

<pre>
+------------+       +---------------+       +--------------+
| table1     |       | table1_table2 |       | table2       |
+------------+       +---------------+       +--------------+
| id         |	     | id            |   	 | id           |
| field1 	 |   	 | field1        |       | field1       |
| field2  	 |       | field2        |    	 | field2 		|
| field3 	 |       +---------------+       | field3   	|
| field4     |                            	 +--------------+
+------------+                               
</pre>

**table1**
| id | field1 | field2 | field3 | field4 |
|----|--------|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)| (insert entry here)|

**table2**
| id | field1 | field2 | field3 |
|----|--------|--------|--------|
| 1 | (insert entry here)| (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)| (insert entry here)|

**table1_table2**
| id | field1 | field2 |
|----|--------|--------|
| 1 | (insert entry here)| (insert entry here)|
| 2 | (insert entry here)| (insert entry here)|
| 3 | (insert entry here)| (insert entry here)|