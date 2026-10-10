# Install-Java-and-Maven-on-Windows
This is a simple guide to install java and maven on Windows for new developers starting with Java.  

# Install Java Development Kit (JDK)  

The Java Development Kit (JDK) is the official software development environment used to build, compile, debug, and run Java applications.

  
Go to the oracle website ->  https://www.oracle.com/java/technologies/downloads/#jdk21-windows 
<img width="962" height="480" alt="image" src="https://github.com/user-attachments/assets/08759098-4acd-45ee-86b0-b1a21e66ed2a" />

Install Java and add the windows java path 

<img width="640" height="306" alt="image" src="https://github.com/user-attachments/assets/89577c42-81cf-473f-b8dd-57e502a43e75" />

Grab the Java Path  (Normally inside the program files)

<img width="946" height="297" alt="image" src="https://github.com/user-attachments/assets/33a4dcdd-855d-43ed-abc7-4316fede5c53" />

Click the java folder that you desire and grab the path until the bin  

  
In my case C:\Program Files\Java\jdk-25.0.4.1\bin

Then grab this path and place it in the Path env variables of your system  

<img width="473" height="425" alt="image" src="https://github.com/user-attachments/assets/85c263b0-b3da-4b3e-9d4f-8b9697b3450c" />

Also create or if you already have change the java home path (we need to create this variable) its a variable outside of the Path one  

<img width="557" height="618" alt="image" src="https://github.com/user-attachments/assets/553966ea-394b-4230-ae3a-065e455cdd00" />

Then you can confirm on the command line with java --version to confirm that java was properly installed  

<img width="1511" height="312" alt="image" src="https://github.com/user-attachments/assets/44984626-e78f-4840-bf1f-8090c703e0f7" />


# Install Maven

Go to the Maven website to download https://maven.apache.org/download.cgi  

Maven normally requires JDK to be able to execute make sure its installed.  
<img width="786" height="233" alt="image" src="https://github.com/user-attachments/assets/efdbd07c-d0f4-4bef-a54e-b8cf439ad7d0" />  

  
Select the binary zip archive  
<img width="762" height="500" alt="image" src="https://github.com/user-attachments/assets/a5235cec-38df-484e-9813-1583716649ea" />  

Then after the dowload go to the Maven folder where the zip is downloaded  
<img width="956" height="487" alt="image" src="https://github.com/user-attachments/assets/d224a9d1-244b-4669-b486-9c0e28e532bd" />

Extract the file to the program files sector, for example in my case C:\Program Files\apache-maven-3.10.0  
<img width="945" height="375" alt="image" src="https://github.com/user-attachments/assets/09b76201-f20d-446d-b9b1-a3cf51464228" />  

Click on the bin folder and copy the whole file path to then put in the env variables on the path variable  
<img width="595" height="657" alt="image" src="https://github.com/user-attachments/assets/d52d8260-f24c-4287-a6e3-989fe7eb9a93" />  

Now we need to set the MAVEN_HOME variable like the java one. (remove the \bin)  

<img width="547" height="251" alt="image" src="https://github.com/user-attachments/assets/4b11972b-a6cc-45d7-9af3-ef9d6309dafe" />

Verify maven is installed with mvn --version  
<img width="1476" height="727" alt="image" src="https://github.com/user-attachments/assets/d4e1d9a9-49fe-4cc7-83dc-e3e3f130a0b0" />












