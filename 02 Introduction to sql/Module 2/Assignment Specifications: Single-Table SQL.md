# Assignment Specifications: Single-Table SQL

### Example walkthrough for assignment

Perform the instructions below and enter the code you get into the following assignment. (Hint: starts with 493)

### Specifications

First, create a MySql database or use an existing database (make sure to use a UTF8 character set) and then create a table in the database called "Ages":

```
CREATE TABLE Ages ( 
  name VARCHAR(128), 
  age INTEGER
)

```

Then make sure the table is empty by deleting any rows that you previously inserted, and insert these rows and only these rows with the following commands:

### Sample Data
```
DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Zahra', 34);
INSERT INTO Ages (name, age) VALUES ('Olufunke', 23);
INSERT INTO Ages (name, age) VALUES ('Choire', 38);
INSERT INTO Ages (name, age) VALUES ('Makenna', 32);
INSERT INTO Ages (name, age) VALUES ('Ula', 16);
INSERT INTO Ages (name, age) VALUES ('Garren', 40);

```

For the assignment use the data on your individual autograder page, not the sample data above.

Once the inserts are done, run the following SQL command:

```
SELECT sha1(CONCAT(name,age)) AS X FROM Ages ORDER BY X

```

Find the first row in the resulting record set and enter the long string that looks like 254c6127cdbc4c38e065317667340e8b0950046f (this is just a sample string). Use the hint  as a guide. 

### Sample data output:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/4d01GBBaTj6dNRgQWn4-Aw_2007b1864ab3121b916d4c10057e3aa6_wa4e-c2-w2-sha1output-sample.JPG?expiry=1643241600000&hmac=DSAhxg9wRn240JXTQoVl5-sCQ27gNRH-7e9nmHOCFcU)

#### Note on Resources:
The 'Resources' section contains links to the book chapters, and the SQL code handout used in the lecture.  For this week the 'Resources' section can be found at: https://www.coursera.org/learn/intro-sql/resources/uSpSe  

