# CS568 - Assignment 8 - React Router

The users:
- ```/users``` -> List users.
- ```/users/add``` -> Hide the list of users and show the add user page.
- ```/users/:userId``` -> Show user details in the input tags and be able to edit.

The courses:
- ```/courses``` -> List of courses. Keep the course object simple. Just name, code.
- ```/courses/add``` -> Add the course entered in the DB. There are 2 inputs name and code. This add and below detail routes are nested routes in the "courses" route. Use ```<Outlet>```. The list of courses is not hidden. Show (Swap) the add and details back and forth when click on the link. 
- ```/courses/:courseId``` -> Course details. No need to have edit funcitonality here. Just show.
