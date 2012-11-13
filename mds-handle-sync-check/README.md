Scripts to get all minted DOIs from MDS and handle server.
Shell variable `DATACITE_MYSQL` shall contain the mysql connection parameter.

Usage:

    check-mds-handle-sync

or equivalent:

    get-dois-from-mds > dois.mds
    get-dois-from-handle > dois.handle
    diff dois.mds dois.handle

Notes: 
  
* Currently it only checks the handle from 0.SERV/10.TIB
* Due to lag of handle replica a few DOIs might be missing on the handle side

