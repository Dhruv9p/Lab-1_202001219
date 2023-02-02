# Lab-1_202001219

Q1. Identify Functional Requirements and Non-Functional Requirements-

Functional Requirements-
1. User should be able to determine whether or not the book is available.
2. A new record may be added to the system when a new book is purchased, and a record can be removed if a book is taken from the shelf by the librarian, who has to be given full administrative rights and control over the system.
3. If no other booking has been made for that particular book, the system also allows a member to prolong the date of his borrowing.
4. Only authorised users/members of the Library Information System may check out and return books; anybody else may only browse and search the collection.
5. If someone wants to become a LIS member, they must register with their institute email ID and be verified with it.
6. The system should notify the user and librarian about the overdue books and if the user fail to submit before due date then the system should calculate the fine for overdue books on their return.
7. It must have authentication whenever the user log in to the system
8. The system must be compatible with all the browser as it would be a web application.
9. The system would only run within the instistute LAN, accessing through other network won't run LIS.


Non-Functional Requirements-
1. Security- The system should not store personal information of users(eg. passwords) in plain text , the information must be stored in an encrypted manner.
2. The system must be easy to use ( user friendly ) and have good interface.
3. Scalability- The system must be usable for extended number of users if required.
4. Maintainability and Flexibility - It must be easy to maintain and make new changes without affecting the current system
5. Performance- It must be fast and ready to use. 
6. Accuracy is important. The data stored about the books and the fines calculated, user's information and status of issuing/returning books should be correct, consistent, and reliable.
7. It must be portable and accessable from anywhere inside the institute using its LAN.


Q2. Identify scope, features and non-functional aspects of the following problem.

Scope- 
Sound recognition application is used for deaf or hard of hearing people. 

Features-
1. It uses artificial intelligence to recognize key sound events of interest to this community, such as car horns and babies, where immediate alerts and continual logging are critical for the user.
2. User must be notified via text message , vibration , flashlight.
3. It should differentiate between harmful sound and normal sound. For eg. Something falling from the building , sound of bomb or cracker should be alerted with red colour.
4. User can set different type of notification for different sounds.
5. The app must sync with smart watches also so that user can be notified from there too.

Non-Functional aspects-
1. It must identify voices correctly with accuracy.
2. It must work fast and ensure that there is no delay in recognition.
3. It should work with multiple user accessing the application at same time.
4. This app is optimized for Android with low-latency so that it works in real-time for use. It should also work for IOS devices.
