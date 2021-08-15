# find_all_the_books
cli tools and eventual Flask app for getting book info and searching Overdrive and local library

Book search: Check all my Overdrive libs, GoodReads, my Calibre libs, and $others

* Check Overdrive libs
  * Availability
    * "Where available to checkout, have I hit max checkouts?"
    * "Where available to put on hold, have I hit max holds?"
  * history of my checking it out
  * history of checking out anything else by the author

* Check Goodreads for:
  * on 'Read' or 'Want to Read' shelf?
  * Average review
  * Series information
  * If I’ve read anything else by the author  (TODO: import Read shelf into a SQLite db)

* Check local libraries
  * Availability
  * Search checkout history  (TODO: import checkout history of local libs into a SQLite db)

* Search my Calibre libraries
  * For exact title
  * For anything else by same author
