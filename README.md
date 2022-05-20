# golang_bookstore

This a practice repo.an API which works mysql database.

setup a local database with the following credentials:

username:test <br /> 
password:test123 <br />
table:simplerest 


to add a book use the following variables:<br />
{<br />
&ensp;&ensp;"name":"",<br />
&ensp;&ensp;"author":"",<br />
&ensp;&ensp;"publication":""<br />
}<br />
***

**The routes to access the REST API:**
| Action | ROUTE  |METHOD |
| ------- | --- | --- |
| Get_ALL_books | /book/  | GET|
| ADD_A_BOOK	| /book/  | POST|
| GET_BOOK_BY_ID| /book/{bookID} | GET
| UPDATE_BY_ID  | /book/{bookID} | PUT
| DELETE_BY_ID  | /book/{bookID} | DELETE

 
