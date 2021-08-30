# python packages
We organize a large number of files in different folders and subfolders based on some criteria, so that we can find and manage them easily. In the same way, a package in Python takes the concept of the modular approach to next logical level. As you know, a module can contain multiple objects, such as classes, functions, etc. A package can contain one or more relevant modules. Physically, a package is actually a folder containing one or more module files.

Let's create a package named mypackage, using the following steps:

Create a new folder named D:\MyApp.
Inside MyApp, create a subfolder with the name 'mypackage'.
Create an empty __init__.py file in the mypackage folder.
Using a Python-aware editor like IDLE, create modules greet.py and functions.py with the following code:
greet.py Copy
def SayHello(name):
    print("Hello ", name)
    functions.py Copy
def sum(x,y):
    return x+y

def average(x,y):
    return (x+y)/2

def power(x,y):
    return x**y
That's it. We have created our package called mypackage. The following is a folder structure:

![Alt text](https://www.tutorialsteacher.com/Content/images/python/package.png "a title")