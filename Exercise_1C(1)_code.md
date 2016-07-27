`$curl http://api.crossref.org/works/http://dx.doi.org/10.1103/PhysRevLett.116.061102 > cite1.txt`

`$less cite1.txt`

_Now use Content Negotation to specify a particular format for the citation._

`$curl -LH "Accept:text/bibliography; style=bibtex" http://dx.doi.org/10.1103/PhysRevLett.116.061102 > cite1.bib`

`$cat cite1.bib`

_Keep this citation for Lesson 2, where we add it to a publications list to include in a new research paper._
