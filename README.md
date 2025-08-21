# Gutenberg List

Automated archive of [Project Gutenberg](https://www.gutenberg.org/) books.  
This repository contains a complete list of books in `books.txt` and the actual book texts stored in organized folders (`books_001`, `books_002`, `…`).

## Features
- 📚 **Full index**: `books.txt` contains book ID, title, author(s), download count, and the original Project Gutenberg link.  
- 📂 **Organized storage**: Books are grouped into folders of max 900 files each for easier navigation (`books_001`, `books_002`, etc).  
- 🔄 **Automated updates**: The list and books are fetched and updated every 6 hours using GitHub Actions.  

## File Structure
```py
books.txt # Index of all fetched books
books_001/ # First 900 books
books_002/ # Next 900 books
```

## Usage
- Search `books.txt` to find a title or author.  
- Note the **Project Gutenberg ID** and link for more information.  
- Access the corresponding folder to read the plain text version of the book.  

## About
This project automatically keeps itself up to date with the latest entries from Project Gutenberg.

It’s meant as an accessible archive for exploration, searching, and reading.
