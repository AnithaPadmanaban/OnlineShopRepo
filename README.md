# OnlineShopRepo
## Tables
### Table 1:books_flipkart
|sno|book_name|book_price|popularity|
|--|--|--|--|
|1|Python|350|8|
|2|c++|400|4|
|3|Datastructure|200|7|
|4|Computer Architecture|270|9|

###List all books
select * from books_flipkart;

###List all books in lowest to hishest price order
select * from books_flipkart order by price ASC;

###List all books_flipkart in highest to lowest price order
select * from books_flipkart order by price DESC;

###List all books whose price is greater than 200
select * from books_flipkart where price>200;

###List book name using serial number
select book_name from books_flipkart where sno=2
