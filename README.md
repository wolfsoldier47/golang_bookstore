# golang_bookstore

This a practice repo.an API which works mysql database.

setup a local database with the following credentials:
username:test
password:test123
table:simplerest


to add a book use the following variables:
{
	"name":"",
	"author":"",
	"publication":""
}
the routes to access the REST API:
Get_ALL_books --- /book/  ---------- GET
ADD_A_BOOK ------ /book/ ----------- POST
GET_BOOK_BY_ID -- /book/{bookId} --- GET
UPDATE_BY_ID  --- /book/{bookId} --- PUT
DELETE_BY_ID  --- /book/{bookId} --- DELETE
