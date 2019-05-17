# Trinity-Core
Just a Compiled version of Trinity for windows X64 
For those who can't figure out how to compile or don't have a computer powerful enough,
I will have the compiles here with the C++ Redistributables.

How To Use:

Step 1:

Download WinRAR http://rarlab.com  or 7zip http://www.7-zip.org

If you have 7 Zip or WinRAR installed, Skip to step 2.

Step 2: 

Install MySQL https://dev.mysql.com/downloads/mysql/5.6.html

if you already have MySQL installed proceed to step 3.

Step 3:

Install your favorite SQL Client and configure it to your sql server.

Step 4: 

Extract the archive to your hard drive

Step 5:

Load up HeidiSQL to your server and create 3 databases:
auth
characters
world 

Step 6:

Run auth.sql in the auth database, run the characters.sql in the characters database and run the world.sql in the world database. 

Step 7:

Rename "authserver.conf.dist" and "worldserver.conf.dist" to "authserver.conf" and "worldserver.conf"

Step 8:

Configure your server! 

In the authserver.conf and the worldserver.conf there will be lines in the beginning of the config files that look like this:

127.0.0.1;3306;trinity;trinity;auth

change that to your SQL server and databases.

step 9: 

(optional) 

Download a webpage from http://ac-web.com to have people sign up to your server.


Step 10:

(optional) 

Donations are not necessary but are appreciated I accept 

BTC: 1JhMw7E3iM1DDyVeJYKJ4ctarEmhTH9UzN
XLM: GDNHINFWTXLAMWNGE5DROZCR76TXGXQTMRHHR2T5EYB2TZTZA5ZLLMJ2
Paypal: btntourgasm@gmail.com
