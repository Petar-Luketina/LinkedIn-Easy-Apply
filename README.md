# LinkedIn-Easy-Apply

The notebook searches for only Easy Apply job postings. The search is specified in the first cell.

#### UPDATE:

A Lite version was added to soley apply for jobs after a desired search is inputted by the user. Lite circumvents automating the login, search, and filtering. This way, the user specifies the search then the program paginates through the postings. The max number of job application for one search is 1000 if the search is large enough (25 posting per page with a max of 40 pages).

#### INFO:

Note that LinkedIn job searches allow for minus signs, avoiding those terms during the query.
For example, "python developer -senior -manager" will remove all roles with "senior" or "manager" in the title.

The notebook can also be used after the search and filters are applied, as it applies generic filters now.
Find the ideal search terms and filters, then run the last cell (after the appropriate functions are instantiated).
