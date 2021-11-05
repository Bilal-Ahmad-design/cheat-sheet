<!-- Importand commands in LINUX -->

1. Give a file/folder permission use:
   sudo chmod -R 777 /opt/lampp/htdocs

2. To Change directory use this format:
   cd opt/lammp

3. To view a list of the files and folders in a given directory.
   ls

4. To get the current path use:
   pwd

5. To open XAMPP control panel
   Go to the directory where XAMPP is placed and then run the command
   sudo ./manager-linux-x64.run
   6.  TO update Nodejs use the following command
   i) sudo npm cache clean -f
   ii) sudo npm install -g n
   iii) sudo n latest

6. TO create a folder/Directory
   mkdir node-project

7. And the to create a file in the same folder
   touch file.extension   or echo file.extension
   
8. When you are in the directory of the files you want to open in VS Code, type
    code .
    
9. To install a package globally 
    sudo apt install ...
    
10. Use either one of the below commands:

	.npx create-react-app my-app
	.npm init react-app my-app
	.yarn create react-app my-app
	if "npm uninstall -g create-react-app" stated above does not work. Type which 
	create-react-app to know where it is installed. Mine was installed in /usr/bin folder. 		Then do sudo rm -rf /usr/bin/create-react-app.
