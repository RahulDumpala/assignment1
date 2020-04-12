# Project Title

JIO UI Assessment

## Getting Started

Download the source code from GITHUB URL supplied in email

### Prerequisites

* Internet enabled machine.
* Javascript enabled browser(preferably chrome)




### Installing

Unzip/explode the downloaded file.

## Running the tests

4 Pages were developed as part of this assignment which implements Implement UIs for least the `GET /posts`, `GET /posts/:id`, `POST /posts`, and `PUT
/posts/:id` endpoints.

Page 1 Post Listing Page (jio-posts.html) implemets `GET /posts`

Open this page in javascript enabled browser with valid/seamles internet connection to list of all posts pulled (via GET) from https://jsonplaceholder.typicode.com/posts

Each sku displays two fields ID (Hyperlinked to Post Details page) and Title

Page 2 Post Search  Page(jio-posts-search.html) implements `GET /posts/:id`

This page has one field to search on ID which accepts only numbers.

Operation 1
Upon hitting Search with empty ID value it pulls and gets all posts available.

Operation 2
Upon entering valid ID and hitting search will return post sku and display ID (Hyperlinked to details page) and title

Opertaion 3
Upon enterng an invalid/non-existent id value displays message of No Search Result Found


Page 3 Add/Create Posts (jio-new-post.html) implements `POST /posts`

This page has three fields all mandatory UserID(accepts only numbers), title(accepts aplhanumeric + space with limit of 100), body(accepts aplhanumeric + space with limit of 256).

Upon entering valid details in these three fields submit button appears. 
Operation 1: 
Upon hitting submit button a new post gets created in the backend 
(Note : As mentioned/claimed by https://jsonplaceholder.typicode.com/ everytime a new post is created/edited it only sends back an orchestarted json back but does not create an actual post in the backend which can be consumed later)


Page 4 Post Details & Edit/Update Posts (jio-post-details.html) implements `PUT /posts/:id`

This page consumes a valid id as request parameter and display Post details userID, Title,Body

an option to update this value is provided in this page. 

Operation 1 : User edits values appropriately and hits update button. 
Upon successful client level validation a PUT request is triggered to the backend and updates the posts based on ID.

Since content from https://jsonplaceholder.typicode.com is of foreign language there was dificulties in parsing content while updating posts. It is prescribed to clear body content and update it with plain english text/numbers before updating. 

(Note : As mentioned/claimed by https://jsonplaceholder.typicode.com/ everytime a new post is created/edited it only sends back an orchestarted json back but does not create an actual post in the backend which can be consumed later)
 

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```


## Built With

* Knockout JS
* [APIs](https://jsonplaceholder.typicode.com/) - API Management


## Contributing

Not available for contributions

## Versioning

I used local file storage for versioning. Only one version was created as part of this assignment

## Authors

* **Rahul Dumpala** - *Initial work* - 




