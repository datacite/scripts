scripts to count DOIs and get and format DOI milestones. 

Usage: 

    get-dois <mysql options> | grep-milestones | wiki-format-milestones
    count-dois <mysql options>

Notes: 
  
* `count-dois` counts the `HS_ADMIN` values in all handle server assuming there is exactly one per DOI.
* `get-dois` does a mixture of MDS and handle server query.
