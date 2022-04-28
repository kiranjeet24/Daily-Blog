<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
## Introduction to Linux & Installing Ubuntu

Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Noraml Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Feb-2022** 
## Introduction to LAMP Stack

The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Feb-2022**
## Run Cgi Script

CGI stands for Common Gateway Interface. CGI defines a standard way in which information may be passed to and from the browser and server. Any program or script that can process information according to the CGI specification can, in theory, be used to code a CGI script.

- Create a cgi scirpt.
- Run it on Localhost using Apache Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Feb-2022**
## Image to video

- Create a python Script.
- install pip,Image-MagicK on your system.
- goto ---- /etc/ImageMagick-6/policy.xml file. 
- Comment out line "policy domain="path" rights="none" pattern="@*" 
- Run the script by using python3 filename.py.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Feb-2022**
## Introduction to frappe

Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.
#### Why Frappe?
The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Feb-2022**
## Creating App and Site & run on local server in Frappe

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2022**
## Introduction to Github Pages

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2022** 
## Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-Feb-2022** 
## Introduction to Ldap

#### What is Ldap?
- LDAP stands for Lightweight Directory Access Protocol. It is an industry standard application protocol (RFC here) that serves to define an interface or language with which client applications can talk to a directory service (such as OpenLDAP, Active Directory etc.) to query or modify the information in   the directory.
- An LDAP directory (or server) typically stores information about users, user credentials, groups, user memberships and so on. Since they act as a         central repository for user information, they are commonly used for user authentication and authorization.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
## Introduction to selenium
#### what is selenium?
- Selenium WebDriver is a web framework that permits you to execute cross-browser tests. This tool is used for automating web-based application testing to verify that   it performs expectedly. Selenium WebDriver allows you to choose a programming language to create test scripts.
- Selenium WebDriver supports most of the popular programming languages used by developers and testers, namely – Python, Java, C#, Ruby, and more. It supports popular   operating systems such as Windows, Mac OS, Linux, and Solaris. Mozilla Firefox is the default web browser of Selenium WebDriver.
- I opted for Python language for testing Selenium. It has far less verbose and easy to use than any other programming language. The Python APIs empower you to connect   with the browser through Selenium.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2022** 
## Installing and configuring to Ldap

#### Installing Ldap
- Open a terminal window.
- Update apt with the command sudo apt-get update.
- Once the update completes, install LDAP with the command
 ```
 sudo apt-get install slapd ldap-utils.
 ```
- Allow the installation to complete.

#### Configuring LDAP
To begin the process of configuring LDAP, issue the command sudo dpkg-reconfigure slapd. You’ll be presented with a number of options to configure. These options are:
- Omit OpenLDAP Server Configuration: Select No
- DNS Domain Name: This creates the base structure for your directory path (the configuration window, Figure A, explains this).
- Organization Name: The name to be used as the base DN for your LDAP directory.
- Administrator Password: The password to be used for your LDAP admin user.
- Database Backend: Select HDB
- Remove The Database When Slapd Is Purged: Select No
- Move Old Database: Select Yes
- Allow LDAPv2 Protocol: Select No

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-Feb-2022** 
## Introduction to Ldap Account Manager (LAM)

#### What is Ldap account manager?
- LDAP Account Manager (LAM) is a web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory. The LDAP Account Manager tool was designed to make LDAP management as easy as possible for the user.
- LAM ease administration of LDAP entries by abstracting the technical details of LDAP and allowing administrators and users without technical background to manage LDAP server. If needed, experienced users can directly edit LDAP entries via the integrated LDAP browser.

#### LDAP Account Manager Dependencies
LDAP Account Manager has a number of dependencies, namely:
- OpenLDAP server: Install and configure OpenLDAP on Ubuntu
- PHP and Apache web server
- A user account with sudo privileges

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2022** 
## Installing and configuring to Ldap Account Manager (LAM)

#### Installing Ldap account manager
- Open a terminal window.
- Update apt with the command sudo apt-get update.
- Install OpenLDAP Server
- Once the update completes, install LDAP with the command sudo apt-get install slapd ldap-utils.
- Install Apache Web server & PHP
- Install PHP and Apache web server by running the commands below on your terminal
```
   sudo apt -y install apache2 php php-cgi libapache2-mod-php php-mbstring php-common php-pear
```
- Then enable php-cgi PHP extension.
- Install LDAP Account Manager    
- LDAP Account Manager package is available on Ubuntu repositories, install it with the command:sudo apt -y install ldap-account-manager
- For futher installation or info go to (https://computingforgeeks.com/install-and-configure-ldap-account-manager-on-ubuntu/)

#### Configuring Ldap Account Manager(LAM)
- Access  LDAP Account Manager web interface from a trusted machine network on:http://(server’s hostname or IP address)/lam
- The LDAP Account Manager Login form will be shown. We need to set our LDAP server profile by clicking on[LAM configuration] at the upper right corner.
  Then click on,Edit server profiles
- This will ask you for LAM Profile name Password:
- The first thing to change is Profile Password, this is at the end of General Settings page.
- Next is to set LDAP Server address and Tree suffix. Mine looks like below, you need to use your Domain components as set in server hostname.
- You can also enable other available account types you wish to use. User and Group modules can be enabled and disabled on “Modules” page. 
- When done with the settings, click the Save button at the bottom of the page.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2022** 
## Adding Users and Groups in Ldap Account Manager(LAM)
- Login with the account admin to LAM dashboard to start managing user accounts and groups.
- Users and Groups links to manage user accounts and groups.
- To create a user entry
  - Access the Administration Server and choose the Users and Groups tab.
  - Click New User.
  - Select the LDAP directory service from the Select Directory Service drop-down list, and click Select.
  - Add the required information to the page that displays.
  - For more information see Directory Server User Entries.
  - Click Create User or Create and Edit User.
- Note that at a minimum, you must specify the following user information when creating a new user entry:
  - surname or last name
  - full name
  - user ID
   
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2022** 
## Automation with selenium in python
- The easiest way to install Selenium on a Python environment is through the installer pip.
  ```py
    pip install selenium
  ```
- Once you have completed the pre-requisites section, you are ready to start your first test in Selenium with the Python programming language!
  1. First import the webdriver from Selenium, the following import is for chrome browser. 
  ```py
     from selenium.webdriver.chrome.service import Service
  ```
  2. Next,create an instance of Chrome with the path of the driver that you downloaded through the websites of the respective browser. 
  ```py
     s = Service("/usr/bin/chromedriver")
     driver = webdriver.Chrome(service=s)
  ```
  3. Next, use the .get() method of the driver to load a website and for maximising the window use the maximize_window(). 
  ```py
     driver.get("https://www.python.org")
     driver.maximize_window()
  ```
 ## Locating elements in a webpage with selenium
- Selenium provides the following methods to locate elements in a page:
  - find_element
  - find_elements
    
- First import By class:
 ```
   from selenium.webdriver.common.by import By
 ```
- These are the attributes available for By class:
   ```py
   ID = "id"
   XPATH = "xpath"
   LINK_TEXT = "link text"
   PARTIAL_LINK_TEXT = "partial link text"
   NAME = "name"
   TAG_NAME = "tag name"
   CLASS_NAME = "class name"
   CSS_SELECTOR = "css selector"
   ```
 - Example code for finding element:-
 ```
  driver.find_element(By.XPATH, '//button[text()="Some text"]')
  driver.find_elements(By.XPATH, '//button')
 ```
 <br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-2022** 
#### Automation with selenium in python
## Using waits in selenium
   When a page is loaded by the browser, the elements within that page may load at different time intervals. This makes locating elements difficult: if an element is not yet present in the DOM, a locate function will raise an ElementNotVisibleException exception. Using waits, we can solve this issue. Waiting provides some slack between actions performed - mostly locating an element or any other operation with the element.
- Selenium Webdriver provides two types of waits:-
  - Explicit waits- An explicit wait makes WebDriver wait for a certain condition to occur before proceeding further with execution. 
  - Implicit waits- An implicit wait makes WebDriver poll the DOM for a certain amount of time when trying to locate an element.
## Various methods can used with an element in Selenium Python 
  - send_keys() - send_keys method is used to send text to any field, such as input field of a form or even to anchor tag paragraph, etc.
  - click() - click method is used to click on any element, such as an anchor tag, a link, etc.
  - submit() - submit method is used to submit a form after you have sent data to a form.
  - tag_name - tag_name method is used to get name of tag you are referring to.
- For more information refer to links-
  - https://www.geeksforgeeks.org/selenium-python-tutorial/
  - https://selenium-python.readthedocs.io/getting-started.html  
 
 <br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
*Date : 19-Feb-2022**  
