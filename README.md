# LinkedIn-Easy-Apply

The notebook searches for only Easy Apply job postings. The search is specified in the first cell.

Note that LinkedIn job searches allow for minus signs, avoiding those terms during the query.
For example, "python developer -senior -manager" will remove all roles with "senior" or "manager" in the title.

The notebook can also be used after the search and filters are applied, as it applies generic filters now.
Find the ideal search terms and filters, then run the last cell (after the appropriate functions are instantiated).

UPDATE: A Lite version was added to just apply to jobs after a pre-designated search. Lite circumvents automating the login, search, and filtering. This way, the user specifies the search then the program paginates through all the desired jobs. The max number of job application is 1000 (25 posting per page with a max of 40 pages).
