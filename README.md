# Swatchh-Bharath
In order to start off the project in a systematic manner some part of the dev-ops features were used in the implementation of the project.
I initially started off with planning on exploring the different technologies that I’d be working on as I was unaware of them. 
After a lot of research on how to go about I finally made a plan on the requirements as well as on how I’d be implementing them.
  
  According to the specifications mentioned about the technologies which are supposed to be used the project was purely implemented using Eclipse as an IDE platform with maven as a project file and Java in order to write the code. 
 As there was no need to use any graphical user interface the code was written in java using command line arguments while the user is given the choice to enter his details and continue with selecting the type of waste he’d like to donate, brand etc.
But in order to store the data the user enters, we were asked to use either JSON or XML in order to read the details from the command line and store the details in the file. Started exploring on JSON using the Maven IDE project files. As I wasn’t familiar with JSON I sort of struggled on importing its packages. But due to the errors which were inevitable due to the packages of JSON, I took up on XML which I studied in my previous semester. Now, the process become slightly knowable. Using the DOM parser and the document builder class we can easily access the XML file which is able to read and write from the command prompt.
After that rechecking the entire code of the above I started resolving and a couple of errors. Moving on, generating coupon codes and displaying the points of the user. Using different string variables like numbers, alphabets, and special characters and concatenating them. They can be called by using the using the math.random() which generates random codes  that are displayed to the user along with the number of points that he’d earned.
## EXTENDED APPROACH
As storing the details of various users on files is a little hard and time consuming, an alternative approach can be formed where the user can use cloud services like AWS. This not only speeds up the process but also retrieves the data if the file is lost .

 
