# CRUD Operations for Book Model

## 1. CREATE
from bookshelf.models import Book
new_book = Book(title = "1984", author = "George Orwell", publication_year = 1949)
new_book.save()
new_book

# <Book: 1984>

# 2. RETRIEVE
Book.objects.all()

# Retrieve first book and display all attributes
book = Book.objects.first()
book.title, book.author, book.publication_year

# <QuerySet [<Book: 1984>]>
# ('1984', 'George Orwell', 1949)

# 3. UPDATE
new_book.title = "Nineteen Eighty-Four"
new_book.save()
new_book

# <Book: Nineteen Eighty-Four>

# 4. DELETE
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()

# (1, {'bookshelf.Book': 1})

Book.objects.all()

# <QuerySet []>


