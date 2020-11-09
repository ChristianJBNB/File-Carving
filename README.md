# File Carving

File carving the process in which computer files are ressembled from fragments in the absence of metadata. File carving is able to recover files using the file structure and content of the file, without having to use the file system meta-data. File carving is used when trying to find files in an unallocated space in the system. This means that you will be looking for the file in a part of the system that no longer holds any data about the file. This is possible because file-systems do not fully get rid of the file, instead the system gets rid of the knowledge of where that file is located. File carving is the reconstruction of the file using raw bytes of the system and reassembling them so that the file can be recreated. 

## Christian Jackson
![Christian Jackson](https://user-images.githubusercontent.com/54372153/98284105-40401980-1f66-11eb-8d50-27906fdb3ffc.JPG)

Tool Needed for Example: [Winhex](https://www.x-ways.net/winhex/index-m.html)

You will also need the file named FileCarvingExample.docx

Video link: https://youtu.be/V01EZgPIuNo

Summary: In this video I go over a very simple file carving technique where I extract an image file from another file type. I was able to do this by using a hex editor tool, Winhex, which allowed for me to find and extract the image file from the word document. This technique, while not complicated, is useful to know if inside of a file there is a hiddden image that you would not have known about otherwise. After the extraction, I compare the image that was extracted to the image that is in the file and we see that the images are the exact same. This is also a way of validating that the images are actually the same and the image that is being displayed is not a different image.


## AJ Hagemann
![AJ Hagemann](https://user-images.githubusercontent.com/72477734/98379265-b5662a00-200c-11eb-9b48-1180d25c973a.jpg)

Tool Needed for my Example: [ProDiscover Basic 8.2](https://prodiscover-basic.software.informer.com/8.2/) 

For my example you will need the file Example.eve

Video Link: https://www.youtube.com/watch?v=CrwAbvQCEYk

Video Summary: In my video I went over one of the most basic ways of file carving. The method I showed was creating a drive image of the hard drive of another commputer or device. Then plugging the image file into ProDiscover Basic so I could view all the content on the computer or device. While looking at the data of the device, we are able to see all the documents and photes that were one it, even the recently deleted ones. While looking at the files we are able to see when they were created, last accessed and last edited. While inspecting some of the items on the device we are able to see the meta data and check for any hidden messages or other documents. This method may be one of the most basic forensic processes, but it should be where every case starts to find its first leads.


## Sources
https://resources.infosecinstitute.com/file-carving/

https://www.diva-portal.org/smash/get/diva2:613183/FULLTEXT01.pdf

https://www.x-ways.net/winhex/index-m.html

Sources for FileCarvingExample.docx

https://www.foodnetwork.com/content/dam/images/food/video/0/02/028/0281/0281639.jpg

https://en.wikipedia.org/wiki/Thanksgiving

https://23twentylincoln.com/content/turkey-when-it-all-began

Sources for Example.eve

Guide to Computer Forensics and Investigations (Our Class textbook)

https://www.researchgate.net/publication/224397415_The_evolution_of_file_carving
