# AI-Data-Warehouse-for-Students-Release-4

It is in interactive desktop based application, created using Python and PostgreSQL, OpenCV and Tesseract for text extraction, Speech_recognition for voice login.

## Release 4 features

  1. **Incremental Load**: Now, data is stored from source to target table by performing incremental load.
  2. UI enhancement: Display output table in a beautiful table structure.

## Release 3 features:
   
   1. Primary Key Integration: Now User table has primary key.
   2. Secured Login:           Now Password stored in database in a hashed form, provides more security.
   3. **Robust Login**:            Now login count is hard stored in the database. So someone must have to wait till 2 minutes for wrong credentials. Closing the Application and restoring session is not an option anymore.
   4. Timer Display:           CountDown Timer is now available to show session restore time after 3 incorrect attempts.
   5. Some logic enhancement.

## Release 3 Project Diagram (Revised):
[![Proj-diagram.png](https://i.postimg.cc/Kz9shHPH/Proj-diagram.png)](https://postimg.cc/0MwCpZHY)

## Release 2 features:
   
   1. **Text to Speech login**: Takes command from microphone, if matched with credential, login successful.
   2. Modular approach:     All operations kept in seperate files.
   3. Little UI enhancement: Shows red for unsuccessful login, green for successful login
   
## Release 1 features:

### Main features:

1. Takes input through Camera also from a Image file saved in Desktop/Laptop.

### Other features:

1. Login guard - After 3 incorrenct attemps, Session got Suspended for 2 minutes.                  
2. Desktop Notification - It can send desktop notification for certain operations.                  
3. Database Inheritance - Implemented the concept of RDBMS as well as ORDBMS.                  
4. Bulk Insertion - Transfer data from one table to another table using SQL Query.
