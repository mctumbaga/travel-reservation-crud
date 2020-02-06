#For this project, a user should be able to:

1. View a list of hotels
2. Log in to their dashboard
3. View all of their current reservations
4. Create a new reservation at a specific hotel
5. Edit an existing reservation
6. Delete an existing reservation
7. Log out of their dashboard

#GET Requests
```/``` — Show a homepage
```/hotels``` — Show a list of hotels
```/login``` — Lets a user login
```/logout``` — Lets a user logout
```/auth0/callback``` — Auth0 provided route to handle the login callback
```/dashboard``` — Show a user's dashboard homepage
```/dashboard/reservations``` — Show a user's reservations in their dashboard
```/dashboard/reservations/new``` — Show the page to create a reservation
```/dashboard/reservations/{id}``` — Show a single reservation
```/dashboard/reservations/{id}/edit``` — Show the page to edit a reservation

#POST Requests
```/dashboard/reservations``` — Creates a new reservation
#PUT Requests
```/dashboard/reservations/{id}``` — Update a specific reservation
#DELETE Requests
```/dashboard/reservations/{id}``` — Deletes a reservation
