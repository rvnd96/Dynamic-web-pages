# Dynamic-web-pages
This is a simple dynamic web pages projects to understand the GET method in PHP.

First I access for the folder 'Pages Folder' and store it in a variable.

Then using scandir() method, I accessed files inside the folder. 

Then I had to use unset() method to remove index 0 and 1 because they were blank.

After that, the $_GET() method is used.

Then, used in_array() function to search specific file type, in my case it is '.inc.php'.

When a user type a name of a file which is not there in the Pages Folder, the project will echo() and error message saying "Page Not Found".

It also have the Contact page which I earlier developed.

