# install-Burpsuite-In-kali
Kali Linux does not use the BurpSuite installer,

rather it uses the Burp Suite JAR file.
The JAR file is kept in the /usr/bin folder.    
Navigate to /usr/bin  cd /usr/bin  
Rename burp suite to old sudo mv burpsuite burpsuite_old 
Copy the last burp suite jar file to /usr/bin sudo cp /root/Downloads/burpsuite_community_*.jar /usr/bin/  
Rename the new jar to burpsuite sudo mv burpsuite_community_*.jar burpsuite  
Give permissions to execute the file as program sudo chmod +x burpsuite  
Delete the old BurpSuite File sudo rm burp suite_old
