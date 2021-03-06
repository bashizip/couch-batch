## couch-batch - a batch delete program for couchdb

Couch-batch can delete multiple documents from a couchdb. To select documents
to remove, couch-batch allows you to specify a regex.

### Usage

    java -jar couch-batch-0.1.0-SNAPSHOT-standalone.jar -r "^d+" -u USER -p localhost testdb

Options are:

    couch-batch [OPTIONS] <host> <db>
       -r             Regex to select a document by id
       -d             Delete selected documents
       -u <username>  Username
       -p             Prompt for a password
       -h             Show usage

### License
Copyright (C) 2010 David Soria Parra

This software may be used and distributed according to the terms of the
GNU General Public License version 2 or any later version.
