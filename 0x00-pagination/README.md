0. Simple helper function
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function named index_range that takes two integer arguments page and page_size.

The function should return a tuple of size two containing a start index and an end index corresponding to the range of indexes to return in a list for those particular pagination parameters.

Page numbers are 1-indexed, i.e. the first page is page 1.

1. Simple pagination
mandatory
Score: 0.0% (Checks completed: 0.0%)
Copy index_range from the previous task and the following class into your code

2. Hypermedia pagination
mandatory
Score: 0.0% (Checks completed: 0.0%)
Replicate code from the previous task.

Implement a get_hyper method that takes the same arguments (and defaults) as get_page and returns a dictionary containing the following key-value pairs:

page_size: the length of the returned dataset page
page: the current page number
data: the dataset page (equivalent to return from previous task)
next_page: number of the next page, None if no next page
prev_page: number of the previous page, None if no previous page
total_pages: the total number of pages in the dataset as an integer
Make sure to reuse get_page in your implementation.

You can use the math module if necessary.
