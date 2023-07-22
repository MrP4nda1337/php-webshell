# PHP Webshell Tool

PHP Webshell Tool is a versatile and easy-to-use cybersecurity PHP webshell tool that allows for remote execution of system commands. Its customizable and lightweight design provides a clean and intuitive interface for performing a variety of pentesting commands. With PHP Webshell Tool, users can efficiently and securely navigate through the server file system, test for reverse shell connections,upload files, and much more.
<br><br><br>
<img width="681" alt="PHP Webshell Tool" src="https://github.com/MrP4nda1337/php-webshell/blob/main/php-webshell.png">
<br>

## Features

- Simple and easy-to-use interface
- execute commands in directory
- shows shell errors
- automatic reverse shell
- server information
- running application information
- file upload

<br>


## Installation

To install PHP Webshell Tool onto a server, simply copy the php file from [this link](https://github.com/MrP4nda1337/php-webshell/blob/main/cpwt.php) and upload it to the server's web directory.

Next, navigate to the webshell URL in your browser and you should see the PHP Webshell Tool interface.

<br>

## Usage

**Command Execution**
Using the terminal in PHP Webshell Tool is easy. Simply type in a command in the prompt and hit enter. If you want to execute the command inside of a specific directory, fill out the execute in directory box and hit enter.

**Reverse Shell Connection**
To test for a reverse shell connection, put in your ip and port and hit execute. The code should automatically try to execute many reverse shell [commands](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md) until one works. Make sure you have your listener set up properly.

**File Upload**
To upload a file, click the browse button and selected the desired file. Then hit upload. PHP Webshell Tool will attempt to upload your file into the current directory PHP Webshell Tool is running in.

<br>

## Contributing

If you find a bug or have a suggestion for PHP Webshell Tool, please submit email to me.


<br>

## Version
Beta version 1.0
