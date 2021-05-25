# CS569 Workshop 01
* Find in Sakai an intro to `HttpClientModule`, this module provide a service `HttpClient` that Angular uses to make `HTTP` requests. Read the documentation and get yourself familiar to use it for this workshop/
* Create a new Angular application, your application will use `RouterModule` and `HttpClientModule`.
* Create a service with two methods: (both methods will use `HttpClient` service)
  *  `getUsers()` will return an observable for a `GET` request to `https://jsonplaceholder.typicode.com/users`
  *  `getPosts(userId)` will return an observable for a `GET` request to `https://jsonplaceholder.typicode.com/posts/?userId=userId` (replace `userId`)
* Your application will display the list of users' `name`, when a certain user is clicked, in a new route, you will display the user details (email, full address, phone), all the posts that belong to the user, and a button to go back to the list of users. Use Rxjs pipes to customize the response.
