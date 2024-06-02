To Start the server Use Nodemon server.js
and check all the Endpoints using Postman but I have specifically used ThunderClient For checking Endpoints.

# Create a new book
POST http://localhost:3000/api/books
{
    name: "Harry Potter and the Order of the Phoenix",
    img: "https://bit.ly/2IcnSwz",
    summary: "Harry Potter and Dumbledore's warning about the return of Lord Voldemort is not heeded by the wizard authorities who, in turn, look to undermine Dumbledore's authority at Hogwarts and discredit Harry.",
  }

# Get all books
GET http://localhost:3000/api/books

# Get a single book by ID
GET http://localhost:3000/api/books/<book_id>

# Update a book by ID
PUT http://localhost:3000/api/books/<book_id>
{
    name: "The Lord of the Rings: The Fellowship of the Ring",
    img: "https://bit.ly/2tC1Lcg",
    summary: "A young hobbit, Frodo, who has found the One Ring that belongs to the Dark Lord Sauron, begins his journey with eight companions to Mount Doom, the only place where it can be destroyed.",
  }

# Delete a book by ID
DELETE http://localhost:3000/api/books/<book_id>
