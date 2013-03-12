# Real world example

Here is a "real world" examples of using the RESTful module.

Let's assume the application runs on it's own domain, e.g. `http://api.example.com/`,
and we're running a library where we can manage books stock.

[!!] **SECURITY NOTE**
For the sake of simplicity in this example we're not doing any input
validation. This is a serious security risk you should make sure you do it in
your applications.


## Files

### bootstrap.php


### classes/Controller/API/Books.php


### classes/Model/Book.php




## Request examples


### GET list of all books

We'll try to retreive a list of books.

#### Request


#### Response


### GET book's property

Now let's try and get a book's property to see if it is currently in stock.

#### Request


#### Response


### PUT new book

We're gonna add a new book to the library now.

#### Request


#### Response
