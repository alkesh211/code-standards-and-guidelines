# Purpose of Having Coding Standards:

- A coding standard gives a uniform appearance to the codes written by different engineers.
- It improves readability, and maintainability of the code and it reduces complexity also.
- It helps in code reuse and helps to detect error easily.
- It promotes sound programming practices and increases efficiency of the programmers.

# Some of the coding standards are given below:

> Use general guidelines for Naming and declaration rules for variables and functions such as All names start with a letter     and not use of hyphen,etc.

> Use ***appropriate variables/controllers/routes/hooks/methods name*** which can define the functioning of it. Avoid using random/inappropriate names such as test-hook,product1,color1,etc.

> Use ***camelCaseNotation*** for defining classes and components or file naming conventions to provide consistency in our     coding pattern.

> Follow linting rules, break up lines that are too long. Use ***linelength less than or equal to 100 characters***.For         readability, avoid lines longer than 100 characters.

> Minimize the use of ***Global variables*** as ***Global variables and functions*** can be overwritten by other scripts.

> Use **DRY [Don't Repeat Yourself]** strategy to avoid data/code duplication.
  If your component or controller code using some repeating patterns for error handling or file uploading or file               removing,etc please create generalize your code.

> Bigger components have to perform harder and may be difficult to maintain so,
  ***Keep components small and function-specific***.
  For example if your component or controller codelines longer than ***250 lines***,you need to create separate function or     component or modules.This strategy makes our code more clean, readable and With smaller components, it’s easier to           implement performance optimizations..

> Function-specific components can be ***standalone***, which makes testing and maintenance easier.

> Put comments ***only where its necessary***.

> Avoid using Styles in Your Components, Put all the ***styles in style specific files only***.

> Use Only neccessary ***Thirdparty packages*** for develop/integrate/manipulate internal functionalities.

> Follow the Directory structure to place your file according to component,pages,core,util,etc. If you are using any thirdparty javascript file to fullfill some requirement then ***use appropriate directory*** to place it such as assets or lib, etc.

> Avoid internal data logs and **keep DOM** clear as much as possible.

> **Refactoring** your developed code as much as you can.

> Only include one React component per file to make ***clean code***.

> ***Do not use underscore prefix*** for internal methods/variables of a React component.

> **Review your own code** before creating a pull request or pushing your changes.

> Don't push ***unneccessary changes*** and false commits over repository.

> **Check/Test** each & every features and module of whole application/project in your local system before push your changes to avoid code brokes.

That's all for now folks!! Hope you all follow some guidelines and keep your code Clean, Readable, Understandable & Maintainable.

:collision: :tada: **Happy Coding!!** :man_technologist: :trophy: :slightly_smiling_face:
