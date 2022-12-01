# PHP-RestApi-sql
<img src="https://miro.medium.com/max/940/1*YW9N3wbkhZ7DoiJIxVGgZw.png" width="600" height="300">

## In this project I implemented Rest Api -
a server that connects to My Admin's sql database, 
and allows the client to do all kinds of things with the data-
View, create, edit and delete by http requests such as GET, POST, PUT, DELETE.

First I created some posts in database sql through My Admin,
And in order to communicate with the server I did it through Postman -
(Postman is an API platform for building and using APIs. )
## The actions that can be done-
- follow and see the posts that exist in the table: 
    1) Reading all posts
    2) Reading a single post
- create new posts,
- edit existing posts,
- Delete posts

Each post consists of some data that is inside a table and each data is a column:
id, category_id, title, body, author

## The posts that appear in the database: 
<img src="https://user-images.githubusercontent.com/57721728/205157211-ec59b47a-45bf-4521-b6f0-7b90b380e010.png" width="800" height="400">

## Reading all posts in a GET request:

<img src="https://user-images.githubusercontent.com/57721728/205159950-219fec36-eaf5-40f1-a618-ab4ed94aa332.png" width="800" height="400">

## Reading a single post - 
### in a GET request you can specify an ID number of that single post:
<img src="https://user-images.githubusercontent.com/57721728/205160030-1c250e8b-f5b9-40bf-bd71-276f261dce81.png" width="800" height="400">

## Create a new post:
### By writing in Jason the details and data that we would like to include in the post

<img src="https://user-images.githubusercontent.com/57721728/205160139-5eaf0453-0d4a-45bf-942b-505f2e8285dd.png" width="800" height="400">

## Post update:

<img src="https://user-images.githubusercontent.com/57721728/205160215-4ebb06c0-e7bb-41a9-bd12-a4aac1cf9fc4.png" width="800" height="400">

## Deleting a post:

<img src="https://user-images.githubusercontent.com/57721728/205160291-4b5154a9-9ac8-4349-b944-69f39912ad88.png" width="800" height="400">

