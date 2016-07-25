Fetch metadata associated with a CrossRef DOI:
`$curl -s -S http://api.crossref.org/works/http://dx.doi.org/10.2307/1578389 > ex1c.txt`

Now search for the author and title in the saved citation to see what work the DOI is assigned to:

`vim ex1c.txt`
`/family`
`/"title"`

You can see that using UNIX commands to query DOI metadata is no joke! 