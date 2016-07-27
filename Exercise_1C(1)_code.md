`$curl http://api.crossref.org/works/http://dx.doi.org/10.1103/PhysRevLett.116.061102 > cite1.txt`

`$less cite1.txt`

_Now use Content Negotation to specify a particular format for the citation._

`$curl -LH "Accept:text/bibliography; style=bibtex" http://dx.doi.org/10.1103/PhysRevLett.116.061102 > cite1.bib`

`$cat cite1.bib`

__Fetch another citation for a related dataset from DataCite:__

`$curl -LH "Accept:text/bibliography; style=bibtex" http://dx.doi.org/10.7935/K5MW2F23 > cite2.bib`
