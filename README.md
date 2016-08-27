# SecretaryTool #

SecretaryTool admins a number of develop companies than look for a simulated certification. The levels of certification is represent by a KI.

![alt tag](https://github.com/oemunoz/secretarytool/raw/master/images/db_1.png)

----

## How my enterprise get certifications? ##

 - Instant Projects (**IP**).
 - Bidding Projects (**BP**).

The IP process dont have previus requeriments.

_
====

### Instant Projects (**IP**)

The team have to resolve problems by Rol.
 - Analist (**AN**).
 - Develop (**DV**).
 - Tester (**TT**).

_
====

### Bidding Projects (**BP**)

The team leader have to resolve a Pluzze problem and the rest of slaves have to work by rol like **IP**.
  - Analist (**AN**).
  - Develop (**DV**).
  - Tester (**TT**).

----

### General Funcional Requeriments

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	REQ00_00 	|	GENERAL OVERVIEW - SECRETARYTOOL	|
|	REQ01_00 	|	MANAGE USERS	|
|	REQ02_00 	|	MANAGE COMPANIES CERTIFICATIONS	|
|	REQ03_00 	|	MANAGE QUESTIONS	|
|	REQ04_00 	|	RUN TEST	|

_
====

### Manage Users

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	REQ01_01	|	Login	|
|	REQ01_02 	|	Import Responder Data	|
|	REQ01_03	|	Edit User Responder	|
|	REQ01_04 	|	Generate Password	|
|	REQ01_05 	|	Add User	|
|	REQ01_06 	|	Remove User	|
|	REQ01_07 	|	Report on User Account	|
|	REQ01_08 	|	Store User Account	|

_
====

### Manage Companies Certifications

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	REQ03_01 	|	Develop Test Pool	|
|	REQ03_02 	|	Add Question	|
|	REQ03_03 	|	Modify Question	|
|	REQ03_04 	|	Inactive Question	|
|	REQ03_05 	|	Aprove Question	|
|	REQ03_06 	|	Disable Question	|
|	REQ03_07 	|	Add Question Pool	|
|	REQ03_08 	|	Modify Question Pool	|
|	REQ03_09 	|	Remove a Question from Pool	|
|	REQ03_10 	|	Store Question	|
|	REQ03_11 	|	Validate Question	|

_
====

### Manage Questions

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	REQ04_01 	|	Store Test status	|
|	REQ04_02 	|	Determine Test settings	|
|	REQ04_03 	|	Present Question	|
|	REQ04_04 	|	Validate Answer	|
|	REQ04_05 	|	Store Answer	|
|	REQ04_06 	|	ValidateTest Status	|
|	REQ04_07 	|	Present Results 	|

_
====

### Busisnes Rules

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	REQBL_01 	|	Generate Report Any Time	|
|	REQBL_02 	|	Send Request Email	|
|	REQBL_03 	|	All Operations Users Must Be Traced	|
|	REQBL_04 	|	All Test Must be Generated Randomly	|
|	REQBL_05  	|	Reminder message for non-responders	|

----

## Case Uses

|	Name	|	Description	|
|	:-------------	|	:-------------	|
|	Case_01 	|	Manage Users	|
|	Case_02 	|	Manage Questions	|
|	Case_03 	|	Run Test	|

_
====

### Manage Users

![alt tag](https://github.com/oemunoz/secretarytool/raw/master/uml/ManageUsers.png)

_
====

### Manage Questions

![alt tag](https://github.com/oemunoz/secretarytool/raw/master/uml/ManageQuestions.png)

_
====

### Run Test

![alt tag](https://github.com/oemunoz/secretarytool/raw/master/uml/RunTest.png)

----

## CakePHP

[![Latest Stable Version](https://poser.pugx.org/cakephp/cakephp/v/stable.svg)](https://packagist.org/packages/cakephp/cakephp)
[![License](https://poser.pugx.org/cakephp/cakephp/license.svg)](https://packagist.org/packages/cakephp/cakephp)
[![Bake Status](https://secure.travis-ci.org/cakephp/cakephp.png?branch=master)](http://travis-ci.org/cakephp/cakephp)
[![Code consistency](http://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/grade.svg)](http://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/)

CakePHP is a rapid development framework for PHP which uses commonly known design patterns like Active Record, Association Data Mapping, Front Controller and MVC.
Our primary goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.

_
====

### Some Handy Links

[CakePHP](http://www.cakephp.org) - The rapid development PHP framework
[CookBook](http://book.cakephp.org) - THE CakePHP user documentation; start learning here!
[API](http://api.cakephp.org) - A reference to CakePHP's classes
[Plugins](http://plugins.cakephp.org/) - A repository of extensions to the framework
[The Bakery](http://bakery.cakephp.org) - Tips, tutorials and articles
[Community Center](http://community.cakephp.org) - A source for everything community related
[Training](http://training.cakephp.org) - Join a live session and get skilled with the framework
[CakeFest](http://cakefest.org) - Don't miss our annual CakePHP conference
[Cake Software Foundation](http://cakefoundation.org) - Promoting development related to CakePHP

_
====

### Get Support!

[#cakephp](http://webchat.freenode.net/?channels=#cakephp) on irc.freenode.net - Come chat with us, we have cake
[Google Group](https://groups.google.com/group/cake-php) - Community mailing list and forum
[GitHub Issues](https://github.com/cakephp/cakephp/issues) - Got issues? Please tell us!
[Roadmaps](https://github.com/cakephp/cakephp/wiki#roadmaps) - Want to contribute? Get involved!

_
====

### Contributing

[CONTRIBUTING.md](CONTRIBUTING.md) - Quick pointers for contributing to the CakePHP project
[CookBook "Contributing" Section (2.x)](http://book.cakephp.org/2.0/en/contributing.html) [(3.0)](http://book.cakephp.org/3.0/en/contributing.html) - Version-specific details about contributing to the project
