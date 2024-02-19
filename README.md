# Functionalities
- Manage clients and movies. The user can add, remove, update, and list both clients and movies.
- Rent or return a movie. A client can rent a movie until a given date, as long as they have no rented movies that passed their due date for return. A client can return a rented movie at any time.
- Search for clients or movies using any one of their fields (e.g. movies can be searched for using id, title, description or genre). The search must work using case-insensitive, partial string matching, and must return all matching items.
- Create statistics:
  - Most rented movies. This will provide the list of movies, sorted in descending order of the number of days they were rented.
  - Most active clients. This will provide the list of clients, sorted in descending order of the number of movie rental days they have (e.g. having 2 rented movies for 3 days each counts as 2 x 3 = 6 days).
  - Late rentals. All the movies that are currently rented, for which the due date for return has passed, sorted in descending order of the number of days of delay.
- **PyUnit test cases** for all non-UI classes and methods for the first functionality

# Demo
