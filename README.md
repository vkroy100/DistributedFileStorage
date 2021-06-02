# Distributed File Storage

This project is for storing large files on multiple servers. To store these files we shall divide the files
into the fixed sized chunks or blocks. In this project java socket programming is used to build the client
and server part along with the file management system of java, indexing system using hashmaps is
implemented to reconstitute the files from chunks from different server when the user tries to retrieve
the files. The system provides the user with CRUD (Create-Read-Update-Delete) operations. In such a
system, enormous chunks of data in the form of files would be provided by the user as input, which is
expected to be stored in various servers in the form of blocks. The user may then request to access,
update or delete a file. The corresponding operations would be successfully executed based on the
permission available to the user. The system ensures consistency and availability traits of a distributed
system. It provides access transparency that means the clients are unaware that their files are distributed
and can access them in the same way that their local files are accessed. It also provides concurrency
transparency, location transparency, failure transparency, heterogeneity ,scalability,Replication
transparency and Migration transparency.
