# File Carving

File carving the process in which computer files are ressembled from fragments in the absence of metadata. File carving is able to recover files using the file structure and content of the file, without having to use the file system meta-data. File carving is used when trying to find files in an unallocated space in the system. This means that you will be looking for the file in a part of the system that no longer holds any data about the file. This is possible because file-systems do not fully get rid of the file, instead the system gets rid of the knowledge of where that file is located. File carving is the reconstruction of the file using raw bytes of the system and reassembling them so that the file can be recreated. 







## Sources
https://resources.infosecinstitute.com/file-carving/
