# Chapter 9
## 1. What is a relative path relative to?
Relative to program's current working directory.
## 2. What does an absolute path start with?
It starts with os.path.abspath()
## 3. What does Path('C:/Users') / 'Al' evaluate to on Windows?
Path or Program Directory.
## 4. What does 'C:/Users' / 'Al' evaluate to on Windows?
Path or Program Directory.
## 5. What do the os.getcwd() and os.chdir() functions do?
os.chdir()- Current working directory as string value.

os.getcwd()- It returns current working directory of a process.
## 6. What are the . and .. folders?
Single dot represents absolute path
dot dot represent relative path to return to parent file.

## 7. In C:\bacon\eggs\spam.txt, which part is the dir name, and which part is the base name?
dir name-  C:\bacon\eggs
base name-\spam.txt
## 8. What are the three “mode” arguments that can be passed to the open() function?

>>> helloFile = open(Path.home() / 'hello.txt')

>>> helloFile = open('C:\\Users\\your_home_folder\\hello.txt')

>>> helloFile = open('/Users/your_home_folder/hello.txt')
## 9. What happens if an existing file is opened in write mode?

When we call write() on the opened file and passing the write() string rgument, it writes the string to the file and returns the number of characters(including newline) 
##  10. What is the difference between the read() and readlines() methods?

The read() method returns the string that is stored in the file.

The readlines() method gets a list of string values from the file, one string for each line.
##  11. What data structure does a shelf value resemble?
 A shelf value ressembles a dictionary value 
 



 
