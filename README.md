![image](https://user-images.githubusercontent.com/130363781/231080780-7a22529a-96ea-4505-a1f9-d4f469d426cd.png)

# MBaaS (Mobile Backend as a Service)
      MBaaS is a cloud-based data service that provides simple CRUD (Create, Read, Update, Delete) operations and search capabilities for mobile apps. It is written in Java and PHP and uses Symfony and Slim frameworks for development.

## Features
_CRUD operations (Create, Read, Update, Delete)
_Search and Get by ID
_Two parts: REST Server and REST Client
_Uses Symfony, Slim, Twig and Guzzle frameworks
_Can be hosted on a web server or locally
_Compatible with any device that can run Java applications
## Installation
     _Download and install XAMPP to provide the database
     _Make a new database called etripsdb 
     _put both restserver and restclient servers in the htdocs folder under xampp
    _run the restclient 
    
    
### Note:
   
    Locate your database in restserver/tripsdb.php.
    Update the following line with your database location:
    var $dsn = 'mysql:host=localhost;dbname=etripsdb';
    For web servers, listen on port 80 and remove indexes from options indexes followsymlinks to prevent indexing.
## Usage
    **REST Server**
    The REST server is the web service application responsible for database related operations, processing, and routing the data to the site and client. It uses the Slim 3 framework for PHP.

    **REST Client**
    The REST client is the client application that performs operations on the server. It can be used on mobile or any other device that can run Java applications. It uses the Guzzle and Twig frameworks.

Note: this is only simple CRUD you can add more features to it and about , services nav items dont work 
## Credits
  Misogare(Mesvak)
  thanks to Symphoni and Slim Framework Team
## License
Copyright (c) [2023] [Misogare]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
