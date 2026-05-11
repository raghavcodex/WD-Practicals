Running HTML and PHP Files

1. Running HTML Files (.html)

Key Points

HTML runs directly in a web browser
No server is required

Steps to Run
Right-click the .html file
Select Open with Browser

Optional Tools
Use VS Code Live Server for auto-refresh
Or open using a local address:
http://localhost/index.html

2. Running PHP Files (.php)

Key Points
PHP is a server-side language
A server is mandatory to execute PHP

Method 1: PHP Built-in Server
Open the project folder in VS Code
Start the server:
php -S localhost:8080
Open in browser:
http://localhost:8080/filename.php

Method 2: XAMPP Server
Start Apache from the XAMPP Control Panel
Place project files inside:
htdocs/
Open in browser:
http://localhost/filename.php

