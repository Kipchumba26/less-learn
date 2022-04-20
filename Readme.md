# Less LEarn
( *quick guide to working with less* )

## Table of Contents

- [Introduction](#introduction)
- [Installation](#install)




## Introduction 
Less is alot like css but more alike to sass and scss. It was build to help build styles in a more composable way allowing reusability and ease of maintainance.
It add better way of defining variables than css root feature, mixins which are simply function like structures that help generate styles.


## Installation
Less has to be compiled to regular css to be used. This means that a less compiler is required. Below command is still used to reference styles but this is the compiled css file not the source.

```
<link rel="stylesheet" href="index.css">
```

In a folder with below files i.e
```
    index.html
    index.less
```

Index.html still uses 

```
<link rel="stylesheet" href="index.css">
```
to reference the styles. 'index.css' can be generated in 2 ways.


### 1. Using less compiler
To install this compiler. Ensure you have installed NodeJS first. To verify Run below command on cmd


```
    node -v
    npm -v
```

Run below command to install less globally on the pc.
```
    npm i less -g
```

On mac remember to use 'sudo' before any of the terminal commands.


#### How to use the compiler
Open command line, navigate to the folder your project is in.

example
```
    cd C:\Users\user\Desktop\App\
```

Run 
```
    lessc less-filename.less
```

The command will generate a file with the same name but with .css as the file name extension. You should not edit the generated .css but rather the .less file then compile it.

'less-filename.less' was just an example of a filename, ensure you use the name of your less filename.



### 2. Using less extension on Visual Studio Code
If youre using VSCode, go to extensions, search 'Easy LESS' and click install on the less extension.



#### How to use this extension
Once you edit any .less file and save it, the extension will compile the less file generating a corresponding .css file. You can reference this .css file wherever you need to.


