# Add_Blank_Line

def show_read_books():
    read_books = store.get_books_by_read_value(True)
    print("\n") # adding blank line before list of books
    ui.show_books(read_books)
    print("\n") # adding blank line before list of books
