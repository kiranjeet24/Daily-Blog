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
## Creating Apps in Frappe
Any kind of applications can be created on frappe wich give more controll and flexible use. 
To create a new app  run command <br>
- bench new-app library_management

The app will create certains fille in the app folder the whole structure is 
- **library_management**: This directory will contain all the source code for your app
- **public**: Store static files that will be served from Nginx in production
- **templates**: Jinja templates used to render web views
- **www**: Web pages that are served based on their directory path
- **library_management**: Default Module bootstrapped with app
- **modules.txt**: List of modules defined in the app
- **patches.txt**: Patch entries for database migrations
- **hooks.py**: Hooks used to extend or intercept standard functionality provided by the framework
- **requirements.txt**: List of Python packages that will be installed when you install this a
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2022** 
## Introduction to DocTypes in Frappe:

A DocType is the core building block of any application based on the Frappe Framework. It describes the Model and the View of your data. It contains what fields are stored for your data, and how they behave with respect to each other. It contains information about how your data is named. It also enables rich Object Relational Mapper (ORM) pattern which we will discuss later in this guide. When you create a DocType, a JSON object is created which in turn creates a database table.

To enable rapid application development, Frappe Framework follows some standard conventions.

1. DocType is always singular. If you want to store a list of articles in the database, you should name the doctype Article.
2. Table names are prefixed with tab. So the table name for Article doctype is tabArticle.
3. The standard way to create a DocType is by typing new doctype in the search bar in the Desk.

A DocType not only stores fields, but also other information about how your data behaves in the system. We call this Meta. Since this meta-data is also stored in a database table, it makes it easy to change meta-data on the fly without writing much code.

Before we can create DocTypes, we need to enable developer mode on our bench. This will enable boilerplate creation when we create doctypes and we can track them into version control with our app.

##### bench set-config -g developer_mode true
##### bench start
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2022** 
### Creating Article DocType for LMS

Go To DocType list and here we can create a new doctype named article :
- Enter the Name for the docType
- Then We select a Module Named LMS which we have created earlier or we can create a new module.
- Now we require fileds for the doctype we created the required below fields in the doctype:
  - Article Name (type = data , and we set it as Mandatory )
  - Image (type = Attach Image )
  - Author ( Data )
  - Description(Text Editor)
  - ISBN(Data) 
  - Status(Select , here we can add a drodown with options Issued and Available )
  - Publisher( Data )
we can also set the naming series for our artcles( as deafult it will use title as series )

After adding the fields, click on Save.Our doctype is created and we can now Add data to our doctype.
Now We can go to the article list and create " Article ".
As we created new article the data wiil be pushed to the database in the form of tables and we can also check its data by giving command in the terminal 

- bench bench --site library.test mariadb

Here it will shoow all the database of a perticluar site.
And we can check and update  our data using differnet sql commands by selecting differnet databasea and tables.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-Feb-2022** 
### Adding functionality to the LMS

A small example in order to provide the full name of the user we defined the following code in the 
```
class LibraryMember(Document):
     #this method will run every time a document is saved
       def before_save(self):
          self.full_name = f'{self.first_name} {self.last_name or ""}'
````
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-Feb-2022** 
###  Creating Different Doctypes with required for the LMS :

### Library MemeberShip
It will have the following fileds 

- Library Member (Link, Mandatory)
- Full Name (Data, Read Only)
- From Date (Date)
- To Date (Date)
- Paid (Check)

We will enable the Submitable Part So after save the one must have to submit it and after submit one cant make any changes to the document.


Now for the functionality:

import frappe<br/>
from frappe.model.document import Document<br/>
from frappe.model.docstatus import DocStatus<br/>

```
class LibraryMembership(Document):<br/>
    # check before submitting this document<br/>
    def before_submit(self):<br/>
        exists = frappe.db.exists(
            "Library Membership",
            {
                "library_member": self.library_member,
                "docstatus": DocStatus.submitted(),
                # check if the membership's end date is later than this membership's start date 
                "to_date": (">", self.from_date),
            },
        )
        if exists:
            frappe.throw("There is an active membership for this member")
```
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2022** 
##  Installing ERPNext Powered by Frappe on our bench: 

- Pre requisite
 - Frappe FrameWork 
- For the perfect installation use this referance [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Feb-2022** 
##  Introduction to Docker, Virtual Machine and ERPNext

## Docker

Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up time.

## Virtual Machine

A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.

- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
## ErpNext

ERPNext is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ERPNext, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2022**
##  Introduction to Jinja Templating

A Jinja template is simply a text file. Jinja can generate any text-based format (HTML, XML, CSV, LaTeX, etc.). A Jinja template doesn’t need to have a specific extension: .html, .xml, or any other extension is just fine.

A template contains variables and/or expressions, which get replaced with values when a template is rendered; and tags, which control the logic of the template. The template syntax is heavily inspired by Django and Python.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Webpage</title>
</head>
<body>
    <ul id="navigation">
    {% for item in navigation %}
        <li><a href="{{ item.href }}">{{ item.caption }}</a></li>
    {% endfor %}
    </ul>

    <h1>My Webpage</h1>
    {{ a_variable }}

    {# a comment #}
</body>
</html>
```
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-March-2022**
## Education Domain in Erpnext

ERPNext is a free and open-source integrated Enterprise Resource Planning software developed by Frappe Technologies Pvt. Ltd. and is built on MariaDB database system using Frappe, a Python based server-side framework. ERPNext is a generic ERP software used by manufacturers, distributors and services companies.

The ERPNext Education Module helps to organizing your entire set-up. You can have your entire Student Database, Fee Structure, Staffing Information, Courses, Curriculum Which we used for the Project Nanakana Sahib Public School and Guru Nanak Dev Engineering College Ludhiana.

In this Domain We have 
- Basic Setup
- Student
- Admission
- Fees 
- Schedule
- Learning Management System
- Attendance 
- Assessment
- Tools

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-March-2022**
##  Setting Up ErpNext for School

First we setup the parent Company with all the details and under that parent company we setup our school which further related to courses, program , room, student category etc.
then our team divided the work for diferent modules.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 3-March-2022**
##  Fee Module

In the Fee module we have 

- Fee 
- Fee Structure 
- Fee Schedule
- Fee Components 
- Fee Category 

### Fee 

In the Fee section we can create a fee for an Individual student one by one
We have to enter the Student ,due date and we can aslo edit post time and date 
to create a fee we need some of its components which are described below:

- Prerequisites
  - Student 
  - Fee Structure
  - Fee Category


### Fee Structure

In the fee Structure we can define the type of fee like for which class and category of students what kind of fee should be there

In the fee structure we to provide program , student categor, acedamic year, acedamic term .
The important part we have to define the fee category components which includes the different kind of fee. 

### Fee Category

In the Fee Category we simply add the Different Fee components like Tution fee ,Bus fee,Books etc.

Fee Schedule

- Prerequisites
  - Fee Structure
  - Student group


**Fee schedule** is used to add bulk data for fee according to the Student groups and studnet category.
it will divide the grand_total with each group of students.
just go to fee schedule and click new fee schedule
after creating schedule just click create fee button on top that will create fee for the students

### Payment Entry 

To make a payment 
go to fee list  the select a unpaid status candidate 
Now on the top there is a Tab name Create in which we can select make payment and fill the parameters the then submit.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-March-2022**
##  Worked with website module in erpnext
Inside ERPNext! Using website module, we can:

- Create Web Pages
- Write Blogs
- Publish the Product Catalog using the Item master
- Allow users to buy your products using the Shopping Cart
- You need to use html\css to make better custom website designs. The good part is that once this is set up, you can add and edit content, blogs, and     products directly from your ERPNext account.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-March-2022**
##  Setting Up homepage
#### Hero Section in Homepage
There are three ways in which you can customize the way the Hero Section looks:
- Tag Line and Description (Default).
- Homepage Slideshow.
- Custom Hero Section.
#### Customizing Hero Section
Added bootstrap carousel in hero section using section based on custom HTML.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-March-2022**
##  Explored Website Settings
1. Landing Page - Configure the default landing page of your website by setting the Home Page field to the route of that page. You can put any route here including standard routes like home, about, contact, login, all-products, and blog.
2. Website Theme - We can also create custom website theme for web pages in erpnext.
3. Brand -
   - Brand Logo - We can set the brand logo for your website in this section. Upload the Brand Image first and then click on "Set Banner from Image"         button. It will generate a Banner HTML with your uploaded logo.  
   - Favicon - We can also set the favicon of your website in this section. It appears on the left side of the browser tab. 
4. Top Bar - We can customize the menu items in the navbar of your website from the Top Bar section.
5. Banner - We can add a persistent banner to the website which will be shown above the navbar on all web pages.
6. Footer - We can add address information and categorized links to your footer in the Footer section. 
7. HTML Header - We can use this section to set meta tags across all of web pages. A common use case is to add Google site verification tags.
8. Chat - We can enable website visitor chat on your website in the Chat section.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date :7-March-2022**
##  Adding web pages in erpnext
#### Creating webpage
1. Go to the Web Page list and click on New.
2. Enter a Title and add content in Main Section. The route will auto generated but you can change it.
3. Click on Save.
4. The web page will be published only when Published is ticked.
5. View the Web Page by clicking on See on Website in the side bar.
 
#### Added web pages in erpnext
Explored the navbar and created new webpages for navbar elements and also added new navbar elements as the requirement based on education website.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-March-2022**
##  Explored Web Themes
#### Creating a Website Theme
1. Go to the Website Theme list and click on New.
2. Enter a Theme Name.
3. Customize your theme.
4. Click on Save.

#### Features for Website theme
1.  Theme Configuration - The section "Theme Configuration" is there for bootstrapping a basic theme. Here you can choose your color scheme, font and       button styles.
2.  Stylesheet- Using SCSS and Bootstrap 4 theming, we can manually write custom SCSS.
3.  Custom JS - We can also write custom JavaScript that will run when your theme is applied.
 

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-March-2022**
##  Worked with webpage builder
#### Creating a page using Page Builder
1. Followed the steps to create a Web Page.
2. Enable full width by ticking the "Full Width" checkbox.
3. Select Content Type as Page Builder.
4. Click on Add Row in the Page Building Blocks Table.
5. Select a Web Template.
6. Click on the Edit Values button.
7. Enter values in the dialog and click on Submit.
8. Click on Save.
9. The web page will be published only when Published is ticked.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-March-2022**
##  Adding sections in webpage
More sections to the webpage by adding more rows in the Page Building Blocks table. 

#### Adding web templates in web page builder
Explored different web templates that can be used to create webpage more attractive and implemented it on webpages and added content according to the  requirments. For example I added section with collapsed content , cards , slider, hero slider,  hero with right image. There are many more web templates that can be used to build beautiful websites.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-March-2022**
##  Explored more features in website module
Added navbar elements like department, explore and then added dropdown option. Under department dropdown added college departments like applied science, computer science, information technology, mechnical and production engineering, electrical engineering, civil engineering. And under explore added courses explored created section with collapsed content. 

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-March-2022**
##  Understanding the structure of student module in erpnext
The Student document will hold all the data of any Student in your Academy like their Personal Information, Photo, Date of Birth, Address, etc.
In student module we have different doctypes like student group, student attendence, programs, classes. I added the data in these doctypes so that I can understand the structure of module properly.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-March-2022**
## Structure of student module in erpnext
For enrolling the student to a specific class we need to first enroll the student in the specific program using program enrollment tool then under program we can add the courses that come under the specific program. After adding the courses in the program we can further add topics under specific course. 
Once the course has been created, the following documents can be created from the course, which will later be linked to the course.
- Program
- Student Group
- Course Schedule
- Assessment Plan

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 15-March-2022**
##  Worked on SSH Shell
What is ssh?
SSH, also known as Secure Shell or Secure Socket Shell, is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.

Logined to Server,Trying to install ldap on server.
Apply different permission related queries on database for different user.


<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 16-March-2022**
##  Creating student groups in ERPnext
1. Go to Student Group List and click on New.
2. Group Based On: Select the basis on which you would like to create the student group. The three options available are:
   - Batch: List of all the students from within a specific batch will be fetched in this case.
   - Course: Lst of all the students who have enrolled for a specific course will be fetched in this case.
   - Activity: You can select this option when you want to create a group of students for certain activities happening in the school.
3. Student Group Name: Enter the name of the student group.
4. Save

Once the student group has been created and saved, the following can be created from the Student group: 
1. Attendance
2. Course Schedule
3. Assessment Plan
4. Update Email Group
5. Newsletter

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-March-2022**
## Learned Github

So being a part of a developer team one must need to Know Github in order to have a seamless conversation , information and code can be shared easily.
Give them about the introduction about github 
the basic github commands
- git init - to initialize a repository 
- git add . to add the whole files and folder 
- git add filename.extension to add the  specific file 
- git commit -m "Your Message" to commit the changes 
- git remote add origin git URL
- git push -u origin [branch name]
- git stash clear	 -to clear all stashed enteries
- git checkout branch_name  move across beanches of specifi reporsitory 
- git status to check the curent status of the files
- git pull origin [branch name] pull changes from the remote url
- form Documentation [Click here](https://github.com/joshnh/Git-Commands) 


<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-March-2022**
##  Understanding User permissions in Erpnext
#### Adding Users
There are two main types of users:
- Website users: Customers, Suppliers, Students, etc., who have access only to the portal and not to any modules. 
- System Users: People using ERPNext in the Company with access to modules, company data, etc.

Setting User Permissions are particularly useful when you want to restrict based on:
- Allowing user to access data belonging to one Company
- Allowing user to access data related to a specific Customer or Territory
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-March-2022**
## Adding New role and Give Permission to new Users

- When we got new user for allow them to create Library Management System we need to give them the access of doctype modules.
- For this we go to doctype list and create new role where new user create doctype by can't delete doctype.
- Similarly for Module we use select permission where user can select module but can't read module.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-March-2022**
##  Adding User Permission
- Go to the User Permissions list, click on New.
- Select the user for which the rule has to be applied.
- Select the type of document to be allowed (for example "Company").
- Under For Value, select the specific item that you want to allow (the name of the "Company).
- If you check 'Is Default', the value selected in 'For Value' will be used by default for any future transactions by this user. That is if company   'Gndec' is selected as 'For Value', this Company will be set as default for all future transactions by this user.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-March-2022**
## Learning about how to import data in erpnext from csv file

We can generate a csv template regarding ot a particular doctype and trhe we can add a particular data to ethe data type and then we can add the data in the abundace so it can save time.

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-March-2022**
## Arranging Student data

- As there are large data of students in school we need to make it correct.
- so we all divide work in team and understanding the concept of filter, concatinate etc. in excel.
- First we export the required format of csv file then we edit the csv file provided by the school according to our need and import thr data to the server.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 25-March-2022**
## Assessment Module
Assessment procedure to evaluate the students' curricular performance in a period.
Following are the Pre-requists required for the generation of assessment report.
- Assessment Criteria
- Assessment Group
- Grading Scale

**Date : 26-March-2022**
##  Assessment Criteria and Assessment Group

Marks earned are entered based on the ***Assessment Criteria***. For example, if the assessment was conducted for science subjects, then you can evaluate Student in Science on various criteria like Theory and Practical etc.
In ***Assessment Group*** if we wish to conduct an assessment for each Academic Term within an Academic Year e.g MST1,MST2 and ESE then these were the assessment groups.

**Date : 28-March-2022**
##  Assessment Plan and Assessment Result
An Assessment Plan is a schedule to conduct the examination/assessment of a particular course for a group of students studying that course in an on-going academic term.
Prerequisites:
- Student Group
- Course
- Program
- Assessment Group
- Grading Scale

***Assessment Result*** is a log of marks/grades earned by the student for specific Assessment.An Assessment Result is created in the backend based on the marks entered in the Assessment Result Tool.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-March-2022**

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-April-2022**
##  Worked with website module in erpnext

<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
