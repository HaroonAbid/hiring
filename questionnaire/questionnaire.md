# Bluetel Candidate Exercise

Thanks for taking interest in a position at Bluetel! Answering this set of questions gives us a good idea about your technical and logical capabilities; as well as a couple of personal characteristics. You can be as brief or comprehensive as you wish in your answers. We don’t expect every candidate to know all the answers to these questions, so please don’t be discouraged if you don’t know the answer! Good luck!  

### Question 1
Create an algorithm  that prints  the integers from 17 to 53. However for multiples  of two print "Foo" instead  of the number and for the multiples of five print "Bar". For numbers which are multiples  of both two and five print "FooBar". 

### Question 2
In SQL database tables, why is redundant data (i.e. the same data stored in multiple tables) generally a bad thing?

Answer 
Disadvantages Of Data Redundancy:
1-Increases the size of the database unnecessarily.
2-Causes data inconsistency.
3-Decreases efficiency of database.
4-May cause data corruption.


### Question 3
In SQL database tables, why might redundant data be necessary in real world applications?

Answer
Data redundancy can also be used as a measure against silent data corruption; for example, file systems such as Btrfs and ZFS use data and metadata checksumming in combination with copies of stored data to detect silent data corruption and repair its effects.


### Question 4
Why won't the following Apache web server configuration work correctly? Can you suggest a solution to make it work?

```
Listen 33.33.33.33:443
<VirtualHost 33.33.33.33:443>
  ServerName www.example1.com
  DocumentRoot /var/html/www.example1.com
  SSLEngine on
  SSLCertificateFile /etc/apache2/ssl.crt/www.example1.com.crt
  SSLCertificateKeyFile /etc/apache2/ssl.key/www.example1.com.crt
</VirtualHost>

<VirtualHost 33.33.33.33:443>
  ServerName www.example2.com
  DocumentRoot /var/html/www.example2.com
  SSLEngine on
  SSLCertificateFile /etc/apache2/ssl.crt/www.example2.com.crt
  SSLCertificateKeyFile /etc/apache2/ssl.key/www.example2.com.crt
</VirtualHost>
```

### Question 5
In PHP, for what reasons might you initialise strings with single quotes ('')
instead  of double quotes (“”)?

Answer: 

The difference between using single quotes and double quotes in php is that if we use single quotes in echo statement then it is treated as a string. ... The simplest way to specify a string is to enclose it in single quotes. Single quote is generally faster, and everything quoted inside treated as plain string.

### Question 6
In development teams multiple people are often involved in building and maintaining applications, often including the same set of files. They may be working on a single task together, or multiple tasks, and changes made by one developer may conflict with those of another. What system would
you suggest to help manage this, and why would you choose your solution in particular?


Answer:

Continuous Integration


### Question 7
In an ecommerce web application you would typically have a series of prices for products stored in the system. The prices may be inclusive or exclusive of taxes, and may need to be combined for various reasons (such as producing a sum total at the end of an online checkout).

How would you programmatically manipulate those prices, and why?

### Question 8
In an ecommerce application, with discrete levels of stock, how would you manage a situation where two customers were interested in buying the last unit of stock for an item? How would your solution ensure the greatest possibility of the item being sold?

### Question 9
Modern websites often need to take into account the form of device a visitor is viewing the site on (e.g. desktop  computer, tablet, smartphone). What design pattern would you suggest to make the site work across each device?
Responsive design pattern
### Question 10
Explain what Object-oriented Programming is and the benefits of using an Object-oriented language.

Answer:
Object-oriented programming is a programming paradigm based on the concept of "objects", which can contain data, in the form of fields, and code, in the form of procedures. A feature of objects is an object's procedures that can access and often modify the data fields of the object with which they are associated.
It makes software easier to maintain. Since the design is modular, part of the system can be updated in case of issues without a need to make large-scale changes

### Question 11
Explain what procedural programming is and the benefits of using a procedural language.

Answer:
Procedural programming is a programming paradigm, derived from structured programming, based on the concept of the procedure call. Procedures, also known as routines, subroutines, or functions, simply contain a series of computational steps to be carried out.
Advantages of Procedural Programming: Its relative simplicity, and ease of implementation of compilers and interpreters. The ability to re-use the same code at different places in the program without copying it. An easier way to keep track of program flow. The ability to be strongly modular or structured.


### Question 12
Explain the benefits of using an MVC Framework.

MVC platform supports the development of SEO friendly applications. It provides ease to develop SEO friendly URL's in order to generate more visits on a specifies page. MVC is the talk of the IT industry at this moment of time. Thus, MVC design pattern is a surely the great approach towards developing applications.


