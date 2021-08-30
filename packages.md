# packages in python

A package is basically a directory with Python files and a file with the name __init__.py. This means that every directory inside of the Python path, which contains a file named __init__.py, will be treated as a package by Python. It's possible to put several modules into a Package.

![Alt text](https://www.python-course.eu/images/packages_script_350w.webp "a title")

Packages are a way of structuring Python’s module namespace by using "dotted module names". A.B stands for a submodule named B in a package named A. Two different packages like P1 and P2 can both have modules with the same name, let's say A, for example. The submodule A of the package P1 and the submodule A of the package P2 can be totally different. A package is imported like a "normal" module. We will start this chapter with a simple example.

![Alt text](https://www.python-course.eu/images/packages_300w.webp "a title")

"System focused programming" might be the better term than "System Programming". System programming or systems programming means often only the activity of "programming system software", programs which are often part of the operating system. Our topics in this section of our online course deal with Pipes, Threads and Forks and starting and using shell commands and scripts from a Python script.
 
![Alt text](https://cdn.programiz.com/sites/tutorial2program/files/PackageModuleStructure.jpg "a title")

__builtins__: Contains a listing of all the built-in attributes that are accessible from the package. Python adds these attributes automatically for you.
__cached__: Tells you the name and location of the cached file that is associated with the package. The location information (path) is relative to the current Python directory.
__doc__: Outputs help information for the package, assuming that you’ve actually filled it in. For example, if you type os.__doc__ and press Enter, Python will output the help information associated with the os library.
__file__: Tells you the name and location of the package. The location information (path) is relative to the current Python directory.
__initializing__: Determines whether the package is in the process of initializing itself. Normally this attribute returns a value of False. This attribute is useful when you need to wait until one package is done loading before you import another package that depends on it.
__loader__: Outputs the loader information for this package. The loader is a piece of software that gets the package and puts it into memory so that Python can use it. This is one attribute you rarely (if ever) use.
__name__: Tells you just the name of the package.
__package__: This attribute is used internally by the import system to make it easier to load and manage packages. You don’t need to worry about this particular attribute.

![Alt text](https://www.dummies.com/wp-content/uploads/beginning-programming-with-python-2e-attributes-.jpg "a title")