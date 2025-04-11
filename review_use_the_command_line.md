# Review Use The Command-Line:

The command-line is used to tell your computer what to do. You can use it to access servers, directories, and write scripts. In this reading, you will learn how to write Python scripts at the command-line along with the Python GUI IDE. We will also cover the different ways you can access the command-line based on your operating system.

## Using the command line on Windows OS
In Windows, open the start menu. In the search box type cmd. Right-click on cmd and select Run as administrator. This will open up the command-line. Windows OS does not come with Python installed. Visit the official Python 
download page
 for Windows. Select the Windows installer (64-bit) or (32-bit). After the installer is downloaded, double–click the file. Select Install launcher for all users. Follow the prompts during installation. Make sure to select the Add python.exe PATH checkbox. This will allow you to launch Python from the command line. Once installation is complete, you can check for Python from the command line.

To check for Python, use the following command. The version of Python you installed will appear. 

python --version

I am using PowerShell on my Windows 11 laptop.

If you visit the images folder, you will see a few examples of how we can interact with Python using the command-line.

You can see the Python version we are currently using as well as few print statements that display different messages.

Example of Python

```
num1 = 1
num2 = 2
sum = num1 + num2

print("The sum is:" sum)

output
The sum is: 3
```