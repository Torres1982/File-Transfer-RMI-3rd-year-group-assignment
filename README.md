# File-Transfer-RMI-3rd-year-group-project

Technologies used: Java, UML.

The goal of this project is to design, develop and implement a distributed file server using java RMI, and facilitate
the user with a system that supports the following operations: file saving, file opening and file deletion.

The Server interface is used to declare necessary methods that must be implemented on the Server side 
(saving the file, opening the file, deleting the file and displaying all the files stored on the server). The interface extends 
‘Remote’ library, therefore any other classes that implements this interface can be used as a remote objects.

The client class incorporates most of the methods that are declared in the server class such as opening the file, 
saving the file or deleting the file. The client is provided with a simple GUI interface that facilitates navigation 
through the application. 
