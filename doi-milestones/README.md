Scripts to count DOIs and get and format DOI milestones.
Shell variable `DATACITE_MYSQL` shall contain the mysql connection parameter.

Usage
-----

    count-dois [-v]
    get-dois | grep-milestones | wiki-format-milestones

Notes
-----
  
* `count-dois` counts the `HS_ADMIN` values in all handle server assuming there is exactly one per DOI.
* `get-dois` does a mixture of MDS and handle server query.
