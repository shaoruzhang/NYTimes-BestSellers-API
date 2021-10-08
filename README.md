# NYTimes-BestSellers-API

People can utilize this information to determine which best-seller books they may want to read during their free time. 

I chose to use the New York Times API to request **10 different query values**. For the query parameters, I chose different formats of books which includes ebook fiction, ebook nonfiction, hardcover fiction, hardcover nonfiction, trade fiction paperback, paperback nonfiction, manga, paperback graphic books, series books, and young adult. 

I also included a code for readers to see all the list of formats available and to choose their own. Then, for each format, I requested and parsed the top best-sellers list and converted it into a dataframe for easy readability. Within each format, I chose to look at **title, author, isbn13, weeks on list, ranks, ranks last week, book image height, and book image width of the book**. 
