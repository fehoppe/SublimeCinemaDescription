# Cinema 4D Description Syntax for SublimeText
A SublimeText syntax definition for Cinema 4D description resources. 

This definition has been designed for description resources and captures its *.res and *.str files. It can also be used for dialog resources, but will not capture all features of it. Some of the more exotic flags and types are also missing for resource files. This mostly serves as case of "good enough" and will render the vast majority of resource files correctly.

The definition captures:
* .res & *.str files
* container like directives, e.g., `CONTAINER` or `STRINGTABLE`
* parameters, e.g., `BOOL` or `VECTOR`
* flags, e.g., `NAME` or `MIN`
* numbers, strings and c-style single line comments

The syntax capturing will look like this (color scheme not included):

![A resource file using the syntax definition](img/pyro_res.png "A resource file using the syntax definition")
![A string file using the syntax definition](img/pyro_str.png "A string file using the syntax definition")